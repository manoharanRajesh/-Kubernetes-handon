# POD 

## Imperative Way 

`
Kubectl run <name-pod> --image=<image:version>
`

* Create yaml from imperative way 
  
  ``` Kubectl run <name-pod> --image=<image:version> -o yaml > <file-name.yaml>```
  
  ``` Kubectl run <name-pod> --image=<image:version> --dry-run=client -o yaml  > <file-name.yaml>```

* EDIT
  
  ```kubectl edit pod <pod-name>```

* Get from existing pod

``` kubectl get pod <pod-name> -o yaml > pod-definition.yaml```



## Declarative Way

`
kubectl create -f nginx-definition.yaml
`




