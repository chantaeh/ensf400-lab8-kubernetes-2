Run this command to start minikube:
```
minikube start --nodes 3 -p ensf400
```

First, apply the configmap:
```
kubectl apply -f nginx-configmap.yaml
```

Then, apply the deployment:
```
kubectl apply -f nginx-dep.yaml
```

TODO: test deployment, test configmap, test svc (clusterip service)
well.. pods are not running for some reason???



Resources used:
- https://kubernetes.io/docs/tasks/run-application/run-stateless-application-deployment/
- https://stackoverflow.com/questions/71058097/how-do-i-attach-a-configmap-to-a-deployment-in-kubernetes
- https://medium.com/the-programmer/working-with-clusterip-service-type-in-kubernetes-45f2c01a89c8
- 
