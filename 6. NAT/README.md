# Network Address Translation (NAT)

Network address translation (NAT) is a method of mapping an IP address space into another by modifying network address information in the IP header of packets while they are in transit across a traffic routing device.
In this project we implemented these 3 types of NAT:

- static NAT : In this, a single private IP address is mapped with a single Public IP address, i.e., a private IP address is translated to a public IP address. It is used in Web hosting.
- dynamic NAT : In this type of NAT, multiple private IP addresses are mapped to a pool of public IP addresses. It is used when we know the number of fixed users who want to access the Internet at a given point in time.
- overlapping NAT : This is also known as port address translation (PAT) overload. In this, many local (private) IP addresses can be translated to a single public IP address. Port numbers are used to distinguish the traffic, i.e., which traffic belongs to which IP address. This is most frequently used as it is cost-effective as thousands of users can be connected to the Internet by using only one real global (public) IP address.

you can test connections with pinging hosts or using tracert command in hosts.
