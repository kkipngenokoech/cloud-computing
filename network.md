# Network

## conventional Networks

1. Broadcast and unicast
   1. unicast - one person talking to the other - information is sent between two nodes
   2. broadcast - one node to many
2. Router -  a hardware device that connects two or more networks,  It works as a gateway to read the address of each data packet and decide how to forward it.
3. Default Gateway - A gateway is a device that connects a subnet to an external network. When a device sends information to a host, a subnet mask determines whether the destination host is on the local subnet according to the destination address. If the host is on the local subnet, the device can directly send information to the host. If not, the device will first send the information to the default gateway or router, which then forwards the information to other networks to reach the host.
4. Virtual local area network (VLAN) - VLAN is a group of logical devices and users, which are organized based on functions, departments, and applications, regardless of their physical locations. Such devices and users communicate with each other as if they are on the same network segment. VLANs can be used to isolate different services.

## conventional network devices

1. Router
2. Layer 3 switch
3. Layer 2 switch
4. Network interface card (NIC)

### Router

provide internet to devices at home

routers can also be used to provide internet/ connect servers to the internet

A router is a gateway device that operates on the third layer  - Network interface

it stores and forwards packages between different networks and routes data from one subnet to aonther.

it can discover network addresses and select ip routes

## network switch

used to forward electrical signals and establish exclusive electrical signal routes for any two nodes connected to the switch i.e ethernet, telephone voices and fibre switches.


## virtual networks

VMs hosted on a physical machine may be in different IP address ranges

so these IP address ranges need to be isolated.

In addition, VMs need to share the same physical NIC to access external networks. Therefore, virtual switches are used on servers to construct virtual networks.

In network virtualization, the first problem to be solved is how to map virtual NICs of the VMs to the physical NICs of the physical server where the VMs are hosted. As shown in the figure, we can use network bridges, NAT and virtual switches to solve this problem.

