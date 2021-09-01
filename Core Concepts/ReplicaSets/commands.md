|Command|Description|
|:----|:------------|
|kubectl get resplicasets (or kubectl get rs)|list replicasets in default namespace|
|kubectl create -f new-replicaset.yaml|create a replicaset from yaml file|
|kubectl scale rs  new-replicaset --replicas=5|change the number of replicas in replicaset named new-replicaset to 5|
