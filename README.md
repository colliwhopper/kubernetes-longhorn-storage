# kubernetes-longhorn-storage
Installation for longhorn storage for kubernetes  

install
```
kubectl apply -f longhorn.yaml
```

monitor install
```
kubectl get pods \
--namespace longhorn-system \
--watch
```

check there's now a longhorn storage class
```
kubectl get sc
```
