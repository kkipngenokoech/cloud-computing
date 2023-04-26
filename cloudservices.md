# common cloud services

there is an high level view of how cloud services work:
1. physical infrastructure layer - this represents the physical infrastructure like the physical servers, network equipments, storage devices, it includes the data centers and the racks of servers containing the cpu, memory and hard drives
2. virtual infrastructure layer - it represents the software environment and the capabilities that virtualize the physical infrastructure.
3. orchestration layer - scalability, level of resilience, orchestrator locates the servers in a data center and provides  the services requested by customer
4. services layer - they often provide a friendly portal, web application or mobile application where customers can interact with their services.
5. customer application layer
6. monitoring layer
7. security

## compute in cloud computing environment

a combination of the following resources:

1. processing power
2. memory
3. storage
4. network

these computing services are pretty much what cloud providers provide

## virtual machine

this is a piece of software that emulates a physical machine.

it acts as a physical computer with cpu, memory, storage and network but it is completely managed by a software.

to enable virtual machines we can use the hypervisor softwares.

hyperversor lays in between the parent os and the vrtual machines.

all major cloud vendors provide services to host virtual machines:

1. microsoft  azure calls them azure virtual machines
2. amazon calls them EC2
3. google calls them google compute engine.

## microservices

this is a software development approach where a software is developed as mini-apps that talk to each other via apis.

this mini-apps are independent services.

the opposite of microservices are called monolith apps - where all components and functionalities of applications are tied to a single instance.

## containers

this is a software package with all it needs to run in any environment such as code, runtime configuration and dependencies.

containerization helps us in moving the application from one platform to another.

containers virtualize the operating system  since they share a cpu, memory, storage and networking resources from the underlying operating system.

the difference between containers and virtual machines is that VMs create a completely new virtual machine with its own os, hardware and stuff while containers extends the underlying operating system and hardware.

### steps to containerization

1. create a container image - this defines our application and what it needs to run
2. it creates a container from the image in any environment we want it to run on.

## orchestration

as we build containers and container images, we need a way to keep them alive and manage them because at some point they will be cumbersome and many to manage traditionally.

here is where orchestrators like K8(Kubernetes) comes into play.

## HORIZONTAL SCALING AND VERTICAL SCALING

### vertical scaling

traditionally when we run out of memory and other resources we would always extend the services by adding more that is more memory more cpu and more disk space or more ram to a single machine. that is vertical scaling.

This can be achieved by upgrading the hardware components of the machine, such as replacing the processor with a faster one or adding more RAM. Vertical scaling is typically used for applications that have high resource requirements, such as databases or virtualization environments.


### horizontal scaling

Horizontal scaling, also known as scaling out, involves adding more machines to a system in order to increase its capacity. This can be achieved by adding more servers to a cluster or distributing the workload across multiple machines. Horizontal scaling is typically used for applications that need to handle large numbers of concurrent users, such as web applications or messaging systems.

the hack here is adding more machines not more resources

### EVENT-DRIVEN ARCHITECTURE

An event is a change in state triggered by some actions 

so for an event driven architecture, we use events to communicate between different services decoupled from each other.

this particular architecture is used to build microservices and serverless applications

Event producers and consumers are decoupled from each other and often don't have any knowledge of each other. It makes this approach highly scalable and suitable for creating highly distributed applications. Consumers can respond to events in almost real-time.

Event-driven architecture can be cost-effective since we don’t poll servers to determine if anything has changed. Instead, we are notified whenever any event of interest occurs and we can take the necessary action.

### serverless

this includes things like using firebase for backend - we don't normally need to write our own backend, we just need to use the already provided server

severless involves two things:

1. Backend as a service (BAAS)
2. Function as a service(FAAS)

FaaS works in an event-driven way where functions are triggered by events such as HTTP requests or timer-based triggers

N/B: In cloud computing, "compute" refers to the resources used to process data and run applications in the cloud. This typically includes virtual machines (VMs) or containers that provide computing power, storage, and networking capabilities
