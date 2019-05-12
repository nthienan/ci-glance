```bash
kubectl create configmap grafana --from-file=./config/ -o yaml --dry-run | kubectl replace -f -
```
