# Network Basics: OSI Model, Protocols, and Troubleshooting
This repository contains foundational exercises and scripts related to networking concepts, covering everything from the conceptual OSI model to practical Bash scripts for network monitoring.

## 0. OSI Model
The Open Systems Interconnection (OSI) model is a conceptual framework used to understand and standardize the functions of a telecommunication or computing system regardless of its underlying internal structure.

•	Organization: It is organized into 7 layers, from the Physical layer (Layer 1) to the Application layer (Layer 7).

•	Key Fact: The OSI model itself does not perform any functions; it is a tool for understanding complex interactions within a network.
Knowledge Check

•	What is the OSI model?

•	Answer: The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology.

•	How is the OSI model organized?

•	Answer: From the lowest to the highest level.

## 1. Types of Network
Networks are categorized by their scale and reach:

•	LAN (Local Area Network): Connects local devices (e.g., your home or office).

•	WAN (Wide Area Network): Connects multiple LANs across large distances.

•	Internet: The global system of interconnected computer networks.
Knowledge Check

•	Local computer connection? LAN

•	Connecting offices a few streets away? WAN

•	Smartphone browsing without Wi-Fi? Internet

## 2. MAC and IP Address
To communicate, devices need identifiers:

•	MAC Address: A unique hardware identifier assigned to a network interface controller (NIC). It is the "identity" of the device.

•	IP Address: A logical address used to locate a device on a network, similar to how a postal address locates a house.

## 3. UDP and TCP
These are the two primary transport layer protocols used to move data.

Feature	TCP (Transmission Control Protocol)	UDP (User Datagram Protocol)
Reliability	Guaranteed delivery (Slow but sure)	Best-effort delivery (Fast but may lose data)
Connection	Connection-oriented (Handshake)	Connectionless
Usage	Web browsing (HTTP), Email, SSH	Streaming, Gaming, VOIP

Knowledge Check
•	TCP Box: Transfers data in a slow way but surely.

•	UDP Box: Transfers data in a fast way and might lose data in the process.

•	TCP Worker: "Have you received boxes x, y, z?" (Verification).

## 4. TCP and UDP Ports
Ports act as "doors and windows" for specific services on a device. A Socket is the combination of an IP Address + Port.

Common Ports to Remember:

•	22: SSH (Secure Shell)

•	80: HTTP (Unencrypted web traffic)

•	443: HTTPS (Encrypted web traffic)

Task: List Listening Ports
File: 4-TCP_and_UDP_ports
A Bash script that displays active listening sockets, including the PID and the program name.

## 5. Is the host on the network

ICMP (Internet Control Message Protocol) is used to send error messages and operational information. The ping command uses ICMP to check if a host is reachable.

Task: Ping Script

File: 5-is_the_host_on_the_network
A Bash script that pings an IP address provided as an argument 5 times.
