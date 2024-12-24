
Get the Status of the Network
```
⬢ [podman] ❯ kubectl -n kube-system exec -it cilium-87szs -- cilium status
Defaulted container "cilium-agent" out of: cilium-agent, config (init), mount-cgroup (init), apply-sysctl-overwrites (init), mount-bpf-fs (init), clean-cilium-state (init), install-cni-binaries (init)
KVStore:                 Ok   Disabled
Kubernetes:              Ok   1.32 (v1.32.0) [linux/amd64]
Kubernetes APIs:         ["EndpointSliceOrEndpoint", "cilium/v2::CiliumClusterwideNetworkPolicy", "cilium/v2::CiliumEndpoint", "cilium/v2::CiliumLocalRedirectPolicy", "cilium/v2::CiliumNetworkPolicy", "cilium/v2::CiliumNode", "cilium/v2alpha1::CiliumCIDRGroup", "core/v1::Namespace", "core/v1::Pods", "core/v1::Service", "networking.k8s.io/v1::NetworkPolicy"]
KubeProxyReplacement:    True   [eth0   10.10.0.83 fe80::be24:11ff:fe20:cc1f (Direct Routing)]
Host firewall:           Disabled
SRv6:                    Disabled
CNI Chaining:            none
CNI Config file:         successfully wrote CNI configuration file to /host/etc/cni/net.d/05-cilium.conflist
Cilium:                  Ok   1.16.5 (v1.16.5-ad688277)
NodeMonitor:             Listening for events on 10 CPUs with 64x4096 of shared memory
Cilium health daemon:    Ok   
IPAM:                    IPv4: 21/254 allocated from 10.69.3.0/24, 
ClusterMesh:             0/0 remote clusters ready, 0 global-services
IPv4 BIG TCP:            Disabled
IPv6 BIG TCP:            Disabled
BandwidthManager:        Disabled
Routing:                 Network: Native   Host: Legacy
Attach Mode:             TCX
Device Mode:             veth
Masquerading:            IPTables [IPv4: Enabled, IPv6: Disabled]
Controller Status:       130/130 healthy
Proxy Status:            OK, ip 10.69.3.39, 0 redirects active on ports 10000-20000, Envoy: embedded
Global Identity Range:   min 65536, max 131071
Hubble:                  Ok              Current/Max Flows: 4095/4095 (100.00%), Flows/s: 56.10   Metrics: Ok
Encryption:              Disabled        
Cluster health:          3/3 reachable   (2024-12-23T23:27:27Z)
Modules Health:          Stopped(0) Degraded(0) OK(105)
```