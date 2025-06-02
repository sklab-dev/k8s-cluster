# Homelab Kubernetes Network Design (Talos + Cilium + BGP + UniFi)

## 🔧 Cluster Overview

- **Kubernetes** on **Talos OS** (3 nodes)
- Hosted on **Proxmox** VMs
- Cilium used as CNI with built-in BGP control plane
- BGP used to expose LoadBalancer services directly to the LAN via UDM SE

## 🖧 Core Networking

| Component      | IP Address   | ASN     |
|----------------|--------------|---------|
| UDM SE         | 10.10.0.1     | 64513   |
| Talos Node 1   | 10.10.0.11    | 64514   |
| Talos Node 2   | 10.10.0.12    | 64514   |
| Talos Node 3   | 10.10.0.13    | 64514   |

- **PodCIDR**: `10.42.0.0/16` (not exported)
- **ServiceCIDR**: `10.43.0.0/16` (not exported)
- **LoadBalancer IP Pool**: `192.168.42.0/24` (selectively exported via BGP)

## 📡 BGP Design

- eBGP is used between each Talos node and UDM SE (different ASNs)
- Only `LoadBalancerIP`s from a labeled IP pool are advertised
- `CiliumBGPClusterConfig`, `CiliumBGPPeerConfig`, and `CiliumBGPAdvertisement` used (v2 API)
- Graceful restart + fast timers enabled

## 🌐 VLAN Configuration (UDM SE)

| VLAN ID | Name               | CIDR               |
|---------|--------------------|--------------------|
| VLAN1   | Core-Network       | `10.0.1.0/24`      |
| VLAN2   | VPN-Germany        | `10.0.2.0/24`      |
| VLAN3   | Guest-Network      | `10.0.3.0/24`      |
| VLAN4   | Home-Network       | `10.0.4.0/24`      |
| VLAN5   | Security-Network   | `10.0.5.0/24`      |
| VLAN40  | IoT-Network        | `10.40.0.0/16`     |
| VLAN6   | Config_Network     | `192.168.10.0/23`  |
| VLAN1000| Server-Secure      | `10.10.0.0/24`     |
| VLAN4000| Vlan-Isolated      | `10.255.255.0/24`  |
| VLAN4040| Inter-Vlan Routing | `10.255.253.0/24`  |

- BGP peering happens inside **VLAN1000**
- Other VLANs may be used for Multus-attached pods (e.g., Home Assistant)

## 🎯 Future Goals

- Add IPv6 support
- Add prefix-list filtering
- Route reflection or iBGP mesh (if needed)
- Extend pool separation (internal vs external services)

