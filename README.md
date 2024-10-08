# NetPractice

__________________________________________________________________________________________________________________

# what is tcp :
## Transmission Control Protocol

<img width="514" alt="Screen Shot 2023-11-21 at 5 19 10 PM" src="https://github.com/Unstablemental/NetPractice/assets/111853245/6fe48652-859a-423e-90a0-b9c351702136">

*TCP* : is a communications standard that enables application programs and computing devices to exchange messages over a network. It is designed to send packets across the internet and ensure the successful delivery of data and messages over networks

*TCP* provides several features, including:

Reliability: *TCP* guarantees that data sent by one device will be received correctly by the other device. It achieves this through mechanisms such as acknowledgement, retransmission of lost packets, and sequencing of segments.

Flow control: *TCP* regulates the flow of data between sender and receiver to prevent overwhelming the receiving device. It uses a sliding window mechanism to dynamically adjust the amount of data sent based on the receiver's capacity.

Congestion control: *TCP* helps prevent network congestion by monitoring the network's condition and adjusting the transmission rate accordingly. It uses congestion control algorithms to avoid overwhelming the network with excessive traffic.

Connection-oriented: *TCP* establishes a connection between the communicating devices before data transfer. This connection remains active until both devices agree to terminate it.

__________________________________________________________________________________________________________________

# what is ip adress :
## internet protocol address

In networking, an IP address (Internet Protocol address) is a unique numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. It serves two primary functions: identifying the host or network interface and providing the location of the device in the network.

An IP address consists of a series of numbers, typically written in decimal form separated by periods (e.g., 192.168.0.1). There are two versions of IP addresses in use today:

[1- IPv4.](https://github.com/Unstablemental/NetPractice/blob/master/README.md#ipv4)
[2- IPv6.](https://github.com/Unstablemental/NetPractice/blob/master/README.md#ipv6)

IP addresses are used for two main purposes:

Host or device identification:
Every device connected to a network, such as a computer, smartphone, server, or      router, requires a unique IP address to be identified within that network. It helps in distinguishing one     
device   from another.

Routing:
IP addresses play a crucial role in routing data across networks. Routers on the internet use IP addresses to determine the best path for data packets to reach their intended destination. Each device's IP address helps in directing the traffic to the correct destination.

## difference between IPv4 && IPv6

![ip_version](https://github.com/Unstablemental/NetPractice/assets/111853245/6c519743-5a66-45ea-8d97-b6444a78b711)

# IPv4

(Internet Protocol version 4):
This is the most commonly used version of IP addresses. It consists of a 32-bit number, divided into four octets (each octet representing 8 bits). IPv4 addresses are expressed in dotted-decimal notation, as mentioned earlier. For example, 192.168.0.1 is an IPv4 address.

# IPv6

(Internet Protocol version 6): 
With the growth of the Internet and the depletion of available IPv4 addresses, IPv6 was introduced. IPv6 addresses are 128-bit numbers, expressed in hexadecimal form, separated by colons. For example, 2001:0db8:85a3:0000:0000:8a2e:0370:7334 is an IPv6 address.

__________________________________________________________________________________________________________________

# Subnet Mask

![mask1](https://github.com/Unstablemental/NetPractice/assets/111853245/7b7f62e0-6261-4f4b-a82e-88f3ac6dda14)

A subnet mask is a 32 bits (4 bytes) address used to distinguish between a network address and a host address in the IP address. It defines the range of IP addresses that can be used within a network or a subnet.

__________________________________________________________________________________________________________________

# CIDR Notation

The mask can also be represented with the Classless Inter-Domain Routing (CIDR). This form represents the mask as a slash "/", followed by the number of bits that serve as the network address.

Therefore, the mask in the example above of 255.255.255.128, is equivalent to a mask of /25 using the CIDR notation, since 25 bits out of 32 bits represent the network address.

![cidr](https://github.com/Unstablemental/NetPractice/assets/111853245/47f52402-a46b-451a-956f-987df23c55c6)

__________________________________________________________________________________________________________________

# Switch

![switch1](https://github.com/Unstablemental/NetPractice/assets/111853245/c3979791-6b73-4dd2-af3b-5f3ad2f086b3)

A switch connects multiple devices together in a single network. Unlike a router, the switch does not have any interfaces since it only distributes packets to its local network, and cannot talk directly to a network outside of its own.

__________________________________________________________________________________________________________________

# Router

![route1](https://github.com/Unstablemental/NetPractice/assets/111853245/53b23be0-6296-44c2-895a-d11c13e98c7c)

A router is a device that connects two or more packet-switched networks or subnetworks. It serves two primary functions: managing traffic between these networks by forwarding data packets to their intended IP addresses, and allowing multiple devices to use the same Internet connection

__________________________________________________________________________________________________________________

# Routing Table


![routing_table1](https://github.com/Unstablemental/NetPractice/assets/111853245/babddf0d-a6d1-466a-90e9-ef8fdcb8c083)

A routing table is a set of rules, often viewed in table format, that's used to determine where data packets traveling over an Internet Protocol (IP) network will be directed. This table is usually stored inside the Random Access Memory of forwarding devices, such as routers and network switches.

Destination: The destination specifies a network address on which a host is the end target of the packets. The route of default or 0.0.0.0/0, is the route that takes effect when no other route is available for an IP destination address. The default route will use the next-hop address to send the packets on their way without giving a specific destination. The default route will match any network.

Next hop: The next hop refers to the next closest router a packet can go through. It is the IP address of the next router on the packet's way. Every single router maintains its routing table with a next hop address.

__________________________________________________________________________________________________________________

# cheat sheet

![chtsht](https://github.com/Unstablemental/NetPractice/assets/111853245/a723cf7f-6bab-4109-8dc7-a3f3b67cff94)

