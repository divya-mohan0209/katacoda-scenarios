Using Kubectl, let's install cert-manager

```
kubectl wait --for=condition=Available deployment --timeout=2m -n cert-manager --all
```