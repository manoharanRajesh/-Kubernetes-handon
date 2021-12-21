# Secret
Note password are base64 encoded when it is Declarative.

## Imperative Way

`
Kubectl create secret generic <name-secret> --image=<image:version>
`

* Create yaml from imperative way

  ``` kubectl create secret generic my-secret --from-literal=key1=config1 --from-literal=key2=config2```

  ``` kubectl create secret generic my-secret --from-file=key1=/path/to/bar/file1.txt --from-file=key2=/path/to/bar/file2.txt```


## Declarative Way

``` kubectl create -f cm-definition.yaml ```

