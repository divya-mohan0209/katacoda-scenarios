To install the latest version of cert-manager using kubectl, execute the command below.

```
kubectl wait --for=condition=Available deployment --timeout=2m -n cert-manager --all
```