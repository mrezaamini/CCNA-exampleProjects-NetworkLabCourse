# VLAN

Virtual LAN (VLAN) is a concept in which we can divide the devices logically on layer 2 (data link layer). Generally, layer 3 devices divide broadcast domain but broadcast domain can be divided by switches using the concept of VLAN.

A broadcast domain is a network segment in which if a device broadcast a packet then all the devices in the same broadcast domain will receive it. The devices in the same broadcast domain will receive all the broadcast packets but it is limited to switches only as routers don’t forward out the broadcast packet. To forward out the packets to different VLAN (from one VLAN to another) or broadcast domain, inter Vlan routing is needed. Through VLAN, different small-size sub-networks are created which are comparatively easy to handle.

In this project we first create our vlans. each vlan has a number that is the number that is assigned to its hosts. at first, only hosts in the same vlan can ping each other, but in second part we made a vlan to vlan connection. therefore each host can ping the other. So, in this directory we have two files:

- vlan topology
- network with vlan to vlan connection

you can test connections with pinging hosts or using tracert command in hosts.
