Create the Kubewarden namespace and install the kubewarden-crds helm chart inside it. 

Fun fact: `kubewarden-crds` will register the ClusterAdmissionPolicy and PolicyServer Custom Resource Definitions

```
helm install --wait -n kubewarden --create-namespace kubewarden-crds kubewarden/kubewarden-crds
```