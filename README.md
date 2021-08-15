# Combined
4 Individual Containers inside 1 pod

# To run the project locally after cloning and cd into dir:
``` 
       > minikube start
       
``` 
```
       > kubectl apply -f namespace.yaml
       > kubectl apply -f sidecar.yaml
       
```
```
      > kubectl service sidecar --namespace=dockube
```
