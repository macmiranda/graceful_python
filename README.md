# Python service with graceful shutdown

Original code by [msjaiswal](https://github.com/msjaiswal).

Docker scaffolding provided by VScode.

Kubernetes deployment using minikube:
```bash
minikube start
eval $(minikube docker-env)
docker build -t graceful_python
kubectl create -f deployment.yaml
```


