# Config Map

## Imperative Way

`
Kubectl create namespace <name-namespace> --image=<image:version>
`

* Create yaml from imperative way

  ``` kubectl create configmap my-config --from-literal=key1=config1 --from-literal=key2=config2```

  ``` kubectl create configmap my-config --from-file=key1=/path/to/bar/file1.txt --from-file=key2=/path/to/bar/file2.txt```


## Declarative Way

``` kubectl create -f cm-definition.yaml ```

