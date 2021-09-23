# k8s-practice

## dev

start cluster

```
minikube start
```

create and deploy

```
kubectl apply -f ./deployment.yaml
```

show pods

```
kubectl get pods --show-labels
```

install argocd

```
kubectl create namespace argocd

kubectl apply -n argocd --force -f argocd-install.yaml
```

## memo
