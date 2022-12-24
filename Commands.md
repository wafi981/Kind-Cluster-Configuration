# Commands:


## To access our cluster:
```
kubectl get pods -A  --kubeconfig /home/ubuntu/work/kind/.kind/config --context kind-kind 

```


In general: 
```
kubectl get pods -A  --kubeconfig /Path/to/kubeconfig --context kind-kind 

```


# For any other configuration command use:
```
kubectl cluster-info --context kind-kind

```

So just pass the context tag with the name of your cluster with any Kubectl command
