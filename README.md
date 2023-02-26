# k8s-training

## Minikube

**Installation**

```
brew install minikube
```

**Start**

```
minikube start
```

**dashbord**

```
minikube dashbord
```

## Apply Pod

```
kubectl apply -f nginx.yaml
```

**list pods**

```
kubectl get pod -o wide
```

**detail pod**

```
kubectl describe pod ${POD_NAME}
```

**in container**

```
kubectl exec -it ${POD_NAME} -- bash
```
