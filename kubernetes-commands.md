### kubectl cluster-info − It displays the cluster Info
```
$ kubectl cluster-info
```
### kubectl create − To create resource by filename of or stdin. To do this, JSON or YAML formats are accepted.
```
$ kubectl create –f <File Name>
ex - kubectl create -f pods.yml
```
### To collect information about how many pods are there
```
$ kubectl get pods
```
### To gather information ablut particular pod
```
$ kubectl describe pod/pod-name
```
### To login inside the particular pod
```
$ kubectl exec -it pod/pod-name bash 
```
### To see the log of particular pod
```
$ kubectl logs pod-name
```
### To expose the pod to Internet
```
$ kubectl expose pods/pod-name --type="NodePort" --port 8080
```
### 
