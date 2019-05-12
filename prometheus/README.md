```bash
kubectl create configmap prometheus --from-file=./config/ -o yaml --dry-run | kubectl replace -f -
kubectl apply -f .
```
