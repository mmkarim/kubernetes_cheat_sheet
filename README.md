# Kubernetes Cheat Sheet

#### mac-os installation
```
$ brew install kubectl
$ brew install minikube
```

#### minikube
```
$ minikube start
$ minikube ip
$eval $(minikube docker-env)
```

#### kubectl
```
$ kubectl cluster-info
$ kubectl apply -f client-pod.yaml
$ kubectl get pods / kubectl get services
$ kubectl describe pod client-pod
$ kubectl delete -f client-pod.yaml
$ kubectl set image deployment/client-deployment client=image_name
```
