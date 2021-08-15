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

# To check Logs
``` 
       > kubectl logs <pod name> -c <container name> --namespace=dockube     
``` 
###example
``` 
       > kubectl logs sidecar-8444b7bb88-nb4fl -c kartik --namespace=dockube       
``` 
