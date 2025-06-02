```shell
talhelper genconfig --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --secret-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talsecret.sops.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig

# Runs it direct
talhelper gencommand apply --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig --extra-flags="--insecure"
talosctl apply-config --talosconfig=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/talosconfig --nodes=10.10.0.81 --file=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/k8s-sklab-talos-1.yaml --insecure;
talosctl apply-config --talosconfig=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/talosconfig --nodes=10.10.0.82 --file=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/k8s-sklab-talos-2.yaml --insecure;
talosctl apply-config --talosconfig=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/talosconfig --nodes=10.10.0.83 --file=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/k8s-sklab-talos-3.yaml --insecure;


talhelper gencommand apply --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig --extra-flags="--insecure" | bash

talhelper gencommand bootstrap --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig

talosctl reset --nodes 10.10.0.83 --graceful=false --reboot

############################
#   Brings node in Maint  #
############################

# create the cluster bootstrap coomand
talhelper genconfig --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --secret-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talsecret.sops.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig

# Creates command to apply the node configs
talhelper gencommand apply --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig --extra-flags="--insecure"
-> talosctl apply-config --talosconfig=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/talosconfig --nodes=10.10.0.81 --file=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/k8s-sklab-talos-1.yaml --insecure;
-> talosctl apply-config --talosconfig=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/talosconfig --nodes=10.10.0.82 --file=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/k8s-sklab-talos-2.yaml --insecure;
-> talosctl apply-config --talosconfig=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/talosconfig --nodes=10.10.0.83 --file=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/k8s-sklab-talos-3.yaml --insecure;

# Can be piplined with | bash for direct execution
talhelper gencommand apply --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig --extra-flags="--insecure" | bash

############################
#     Bootstrap Node       #  
############################

# create the cluster bootstrap commnad
talhelper gencommand bootstrap --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig
-> talosctl bootstrap --talosconfig=/workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig/talosconfig --nodes=10.10.0.81;

# Can be pipelined and awaited
until talhelper gencommand bootstrap --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig | bash; do sleep 10; done

############################
#   Bootstrap k8s Cluster  #
############################
# ROOT_DIR  The absolute path of the root Taskfile directory.

talhelper gencommand kubeconfig --config-file /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/talconfig.yaml --out-dir /workspaces/k8s.sklab.dev/kubernetes/bootstrap/talos/clusterconfig --extra-flags="{{.ROOT_DIR}} --force"

```
