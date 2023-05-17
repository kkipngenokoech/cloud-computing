# PODS

pods are equivalent to the bricks we use to build houses.

in K8 the smallest unit is a Pod - Atom

a pod is a way to represent a running process cluster

A pod encapsulates one or more containers. It provides a unique network IP, attaches storage resources and also decides how this containers should run

container -> pod -> cluster

## creating a cluster

`k3d cluster create nameofcluster`

## creating pod

we can create pods with a single command.

here we are going to create a pod with mongo database

`kubectl run db --image mongo`

to confirm if our pods are up: `kubectl get pods`

In the output, we can see:

1. The name of the Pod
2. Its readiness
3. The status
4. The number of times it restarted
5. For how long it has existed (its age)

N/B: containers live in pods and pods live in clusters.

```bash
kubectl run db --image mongo

kubectl get pods

docker exec -it k3d-mycluster-server-0 ctr container ls | grep mongo  #- search

kubectl delete pod db # delete pods
```

that's the dirty way of creating pods.


