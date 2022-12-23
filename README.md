# Fork of Kube DOOM

## To run

```shell
kind create cluster --config kind-config.yaml
kubectl cluster-info --context kind-kind
kubectl apply -k manifest
kubectl apply -f pods
kubectl get po -o wide
```