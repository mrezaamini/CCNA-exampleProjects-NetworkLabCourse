# EIGRP & OSPF routing

In this project we used EIGRP & OSPF algorithm for routing. first we make a topology file that contains our basic configurations and ip addresses. After that, based on our topology we used OSPF and EIGRP as our routing algorithm. So this directory contains 3 files:

- topology network
- network routing using OSPF : Open Shortest Path First (OSPF) is a link-state routing protocol that is used to find the best path between the source and the destination router using its own Shortest Path First). OSPF is developed by Internet Engineering Task Force (IETF) as one of the Interior Gateway Protocol (IGP), i.e, the protocol which aims at moving the packet within a large autonomous system or routing domain. It is a network layer protocol which works on protocol number 89 and uses AD value 110. OSPF uses multicast address 224.0.0.5 for normal communication and 224.0.0.6 for update to designated router(DR)/Backup Designated Router (BDR).
- network routing using EIGRP : Enhanced Interior Gateway Routing Protocol (EIGRP) is a dynamic routing protocol that is used to find the best path between any two-layer 3 devices to deliver the packet. EIGRP works on network layer Protocol of OSI model and uses protocol number 88. It uses metrics to find out the best path between two layer 3 devices (router or layer 3 switches) operating EIGRP.

you can test connections with pinging hosts or using tracert command in hosts and use specified commands for debugging and checking routing tables.
