# K8

k8 is the most used and widely spread container scheduler 

## life before K8

to deploy, test and debug applications were hard since you had t physically go to places where ther are servers so that you could actually place your applications to test.

A long time ago, in a galaxy far away... but seriously, this is how life was before k8:

1. order servers
2. takes months to arrive
3. takes months to be installed
4. a few people could access the servers
5. nobody knew what was running on those servers.
6. there had to be proper manual to help with the entire process
7. sysadmins were highly depended upon

so this is the transition:

physical servers -> virtual machines -> k8

## Docker and containers

1. docker client
2. docker host
3. docker hub

containers in the current world is a way to package software and deploy services

they provide necessary isolation of processes, optimized resource  utilization and quite a few other benefits.

it is not enough to package software, we need to be able to scale them, make them fault tolerance, provide transparent communication across a cluster

how do we interface with the container? we do so using containers schedulers, tools that are on top of the containers. 

we don't directly interact with the containers, container schedulers does that for us.

K8 is part of our container schedulers


## node and cluster

node is a single machine in the network

cluster is a collection of nodes in the network. this collections does a resource pulling to form a powerful machine called a cluster.

these clusters have the opportunity to ochestrate alot of services and resources but not in an organized manner, and for this, we need a coach, someone who calls the shots.

we need a Scheduler

we need a k8

## why use schedulers?

1. it ensures that resources in the cluster are used efficiently and within constraints
2. it ensures that the services are almost always in constant running state
3. it provides fault tolerance and ensures that the there's high availability
4. it ensures that specific replicas are deployed
5. We can tell a scheduler what the desired state is, and it will do its best to ensure that our desire is (almost) always fulfilled.

## scheduler and a deployment script

a scheduler will constantly check the state of the cluster and ensure that these services are in constant running state and if it fails, it will always get it back to action unlike deployment script which won't get your resources back to action.

Think of schedulers as operators who are continually monitoring the system and fixing discrepancies between the desired and the actual state. The difference is that schedulers are infinitely faster and more accurate. They do not get tired, they do not need to go to the bathroom, and they do not require paychecks. They are machines or, to be more precise, software running on top of them.

## container schedulers

containers are our basic/basis deployment unit

container schedulers are deploying services packaged as container images

Think of schedulers as operators who are continually monitoring the system and fixing discrepancies between the desired and the actual state. 

The difference is that schedulers are infinitely faster and more accurate. They do not get tired, they do not need to go to the bathroom, and they do not require paychecks. They are machines or, to be more precise, software running on top of them.

## why do we need schedulers for containers?

containers by themselves are not fault tolerance

they can not be deployed easily to the optimum spot in a cluster  - it needs a coach

