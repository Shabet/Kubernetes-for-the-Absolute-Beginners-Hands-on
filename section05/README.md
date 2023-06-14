# Pod command
```
kubectl get pods

kubectl describe pod {name}


```

# ReplicaSet command

```
kubectl edit replicaset {name}

kubectl scale replicaset {name} --replicas={number}

kubectl explain replicaset

kubectl get rs

kubectl describe rs {name}

kubectl get rs {name} -o yaml

#kubectl create -f {filename.yaml}
kubectl apply -f {filename.yaml}

kubectl delete rs {name}
```

# Deployment command
```
kubectl get deployments

kubectl describe deployment {name}

kubectl create deployment {name} --image={image-name:tag} --replicas={number}

kubectl get deployment {name} -o yaml

kubectl edit deployment {name} --record

kubectl apply -f {filename.yaml} --record

kubectl set image deployment {name} {container-name}={image-name:tag}

kubectl delete deployment {name}

kubectl rollout status deployment {name}

kubectl rollout history deployment {name}

kubectl rollout undo deployemnt {name}
```

# common
```
kubectl get all
```