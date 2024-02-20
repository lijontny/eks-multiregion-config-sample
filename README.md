# eks-multiregion-config-sample
### Deployment
```
cd <region>
kubectl create configmap nginx-config --from-file=index.html
kubectl apply -f nginx.yaml
```
