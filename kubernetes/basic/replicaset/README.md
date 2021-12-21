# Replica Set 

Replica set is the new form and old way is replication controller. 
Main difference between those two are replica set has selector and replication controller does not have the.

* CREATE: 
``` create -f <file name>```

* GET 
``` Kubectl get replicaset```

* Update 
``` Kubectl replace -f <file>```
``` Kubectl scale --replicas=3 -f <file>```
``` Kubectl scale --replicas=3  <type> <name>```
``` Kubectl scale --replicas=3 replicaset fe```
