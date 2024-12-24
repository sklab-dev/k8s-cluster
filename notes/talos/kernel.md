
To get the Current Kernel parameter 

```
network/echo-server/app on  main via 🐍 v3.12.7 (.venv) 
⬢ [podman] ❯ talosctl get kpds -n Talos-1
NODE      NAMESPACE   TYPE                     ID                                             VERSION
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.fs.aio-max-nr                         1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.fs.inotify.max_user_instances         1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.kernel.dmesg_restrict                 1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.kernel.kptr_restrict                  1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.kernel.panic                          1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.kernel.perf_event_paranoid            1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.kernel.pid_max                        1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.kernel.unprivileged_bpf_disabled      1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.kernel.yama.ptrace_scope              1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.bridge.bridge-nf-call-ip6tables   1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.bridge.bridge-nf-call-iptables    1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.core.bpf_jit_harden               1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.ipv4.ip_forward                   1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.ipv4.tcp_keepalive_intvl          1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.ipv4.tcp_keepalive_time           1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.ipv6.conf.default.accept_ra       1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.net.ipv6.conf.default.forwarding      1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.user.max_user_namespaces              1
Talos-1   runtime     KernelParamDefaultSpec   proc.sys.vm.overcommit_memory                  1
```


```
network/echo-server/app on  main via 🐍 v3.12.7 (.venv) 
⬢ [podman] ❯ talosctl get kernelparameters -n Talos-1
NODE      NAMESPACE   TYPE                ID                                             VERSION   CURRENT   DEFAULT   UNSUPPORTED
Talos-1   runtime     KernelParamStatus   proc.sys.fs.aio-max-nr                         1         1048576   65536     false
Talos-1   runtime     KernelParamStatus   proc.sys.fs.inotify.max_user_instances         1         8192      128       false
Talos-1   runtime     KernelParamStatus   proc.sys.fs.inotify.max_user_watches           1         1048576   258784    false
Talos-1   runtime     KernelParamStatus   proc.sys.kernel.dmesg_restrict                 1         1         1         false
Talos-1   runtime     KernelParamStatus   proc.sys.kernel.kptr_restrict                  1         1         0         false
Talos-1   runtime     KernelParamStatus   proc.sys.kernel.panic                          1         10        -1        false
Talos-1   runtime     KernelParamStatus   proc.sys.kernel.perf_event_paranoid            1         3         2         false
Talos-1   runtime     KernelParamStatus   proc.sys.kernel.pid_max                        1         262144    32768     false
Talos-1   runtime     KernelParamStatus   proc.sys.kernel.unprivileged_bpf_disabled      1         1         2         false
Talos-1   runtime     KernelParamStatus   proc.sys.kernel.yama.ptrace_scope              1         1         1         false
Talos-1   runtime     KernelParamStatus   proc.sys.net.bridge.bridge-nf-call-ip6tables   1         1         1         false
Talos-1   runtime     KernelParamStatus   proc.sys.net.bridge.bridge-nf-call-iptables    1         1         1         false
Talos-1   runtime     KernelParamStatus   proc.sys.net.core.bpf_jit_harden               1         2         0         false
Talos-1   runtime     KernelParamStatus   proc.sys.net.core.rmem_max                     1         7500000   212992    false
Talos-1   runtime     KernelParamStatus   proc.sys.net.core.wmem_max                     1         7500000   212992    false
Talos-1   runtime     KernelParamStatus   proc.sys.net.ipv4.ip_forward                   1         1         0         false
Talos-1   runtime     KernelParamStatus   proc.sys.net.ipv4.tcp_keepalive_intvl          1         60        75        false
Talos-1   runtime     KernelParamStatus   proc.sys.net.ipv4.tcp_keepalive_time           1         600       7200      false
Talos-1   runtime     KernelParamStatus   proc.sys.net.ipv6.conf.default.accept_ra       1         2         1         false
Talos-1   runtime     KernelParamStatus   proc.sys.net.ipv6.conf.default.forwarding      1         1         0         false
Talos-1   runtime     KernelParamStatus   proc.sys.user.max_user_namespaces              1         0         127938    false
Talos-1   runtime     KernelParamStatus   proc.sys.vm.nr_hugepages                       1         1024      0         false
Talos-1   runtime     KernelParamStatus   proc.sys.vm.overcommit_memory                  1         1         0         false
```