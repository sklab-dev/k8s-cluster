

#List all resources in a table
```
kubectl get po -o custom-columns="Name:metadata.name,CPU-limit:spec.containers[*].resources.limits.cpu, CPU-request:spec.containers[*].resources.requests.cpu, memory-limits:spec.containers[*].resources.limits.memory, memory-request:spec.containers[*].resources.requests.memory" --all-namespaces
```
Name                                                 CPU-limit    CPU-request                    memory-limits                       memory-request
cert-manager-659dbd9c7f-zprx5                        <none>      <none>                         <none>                              <none>
cert-manager-cainjector-c879b86d6-7vdzf              <none>      <none>                         <none>                              <none>
cert-manager-webhook-857864cb8c-kmlhl                <none>      <none>                         <none>                              <none>
cloudnative-pg-586475f9d5-5rdc6                      <none>      <none>                         <none>                              <none>
cloudnative-pg-586475f9d5-78mtz                      <none>      <none>                         <none>                              <none>
emqx-core-76b68874dc-0                               <none>      <none>                         <none>                              <none>
emqx-core-76b68874dc-1                               <none>      <none>                         <none>                              <none>
emqx-core-76b68874dc-2                               <none>      <none>                         <none>                              <none>
emqx-operator-controller-manager-5cbd66867d-5xn2q    500m        100m                           512Mi                               128Mi
emqx-operator-controller-manager-5cbd66867d-fvctm    500m        100m                           512Mi                               128Mi
...
```