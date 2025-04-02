# Networking

![image](https://github.com/user-attachments/assets/24c12cc3-635a-401b-979a-072909b01344)

# The TCP/IP Model: Layers & Protocol

The TCP/IP model is a 4-layer conceptual model that provides a set of rules and communication protocols that are used in computer networks and over the internet. It offers a glimpse of how the transmission of data takes place in a computer

# The four layers are as shown:

Application Layer
Transport Layer
Internet Layer
Network Layer
To get a better visual, below is the TCP/IP layer model.

![image](https://github.com/user-attachments/assets/4c5e2586-d114-4137-a69c-b9fcf7b3be80)

# 1. Network Layer

This is the most basic or rudimentary layer in the TCP/IP model. It determines how data is physically sent across the network. It defines how the transmission of data occurs between two network devices. This layer is dependent on the hardware used.

Here, you will find data transmission cables such as Ethernet / Twisted pair cables and Fiber.

# 2. Internet Layer

The second layer is the Internet Layer. It is responsible for the logical transmission of data packets over the network. Additionally, it determines how data is sent and received over the internet. In the internet layer, you find 3 main protocols:

# IP 
As you might have guessed, this stands for Internet Protocol. It delivers data packets from the source to the destination host by leveraging the IP addresses. As we discussed earlier, IP has two versions – IPv4 and Ipv6.

# ICMP 
This is an acronym for Internet Control Message Protocol. It is used to probe and diagnose network problems. A good example is when you ping a remote host to check whether it is reachable. When you run the ping command, you send an ICMP echo request to the host to check whether it is up.

# ARP 

This is short for address resolution protocol. It probes for a hardware address of a host from a given ip address.

# 3. Transport Layer

This layer is responsible for end-to-end communication and delivery of error-free data packets from one host to another. The transport layer comprises two key protocols.

# TCP – Short for Transmission Control Protocol

TCP provides reliable and seamless communication between hosts. It segments and performs sequencing of data packets. It also performs error detection and subsequently retransforms damaged frames.

# UDP 

This is the User Datagram Protocol. It is a connectionless protocol and doesn’t provide as much reliability and flawless connection as the TCP protocol. It is mainly used by applications that don’t need a reliable transmission.

# 4. Application Layer
Finally, we have the Application layer. This is the top-most layer that provides protocols that software applications use to interact with. There are a myriad of protocols on this layer, however, we have listed the most commonly used protocols and corresponding port numbers.

![image](https://github.com/user-attachments/assets/9c76aa13-a107-4387-9bbd-de8539d7174a)

![image](https://github.com/user-attachments/assets/2b475178-198c-4742-8acc-b4165ca76198)

# What is 127.0.0.1?

In basic terms, 127.0.0.1 is the loopback IP address, which is a special IP address that always refers to your own machine, just like localhost. In fact, localhost is essentially a name that points to 127.0.0.1.

127.0.0.1: A specific IP address is reserved for the loopback network interface.

Loopback: Refers to the process of sending network traffic from your system to itself.



