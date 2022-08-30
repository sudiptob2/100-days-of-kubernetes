## Day 2 activity

Learned about **replicaset** and **replication controller**

Some notes on the commands I used.

```bash
kubectl create –f replicaset-definition.yml

kubectl get replicaset

kubectl delete replicaset myapp-replicaset # Also deletes all underlying PODs

kubectl replace -f replicaset-definition.yml

kubectl scale -–replicas=6 –f replicaset-definition.yml


```

Horizontal scaling of pods [here](https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/#replicaset-as-an-horizontal-pod-autoscaler-target)