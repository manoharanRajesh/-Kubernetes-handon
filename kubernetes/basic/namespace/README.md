# Namespace

## Imperative Way

`
Kubectl create namespace <name-namespace> --image=<image:version>
`

* Create yaml from imperative way

  ``` Kubectl create namespace <name-namespace> -o yaml > <file-name.yaml>```

  ``` Kubectl create namespace <name-namespace> --dry-run=client -o yaml  > <file-name.yaml>```


## Declarative Way

``` kubectl create -f ns-definition.yaml ```

