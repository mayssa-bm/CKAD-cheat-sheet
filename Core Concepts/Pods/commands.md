|command|Description|
|:-----|:----------|
|kubectl get pods|list existing pods in default namespace|
|kubectl run nginx --image=nginx --restart=Never -o yaml  |create a pod in yaml format  with the nginx image , don't restart it if it exits|
|kubectl run nginx --image=nginx --dry-run=client|use --dry-run in case you need to modify the yaml file before creating the pod|
|kubectl describe pod nginx|describe pod nginx|

