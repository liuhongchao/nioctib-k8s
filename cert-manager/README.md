Followed https://docs.cert-manager.io/en/latest/getting-started/install/kubernetes.html

Specifically:
```
kubectl apply --validate=false -f https://github.com/jetstack/cert-manager/releases/download/v0.15.1/cert-manager.yaml
kubectl create -f cert-manager.yaml --validate=false
```
