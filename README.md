# Holberton School Networking: Basics & "What Happens When" 🛜

This repository contains a series of projects focused on understanding the fundamentals of computer networking, from the conceptual OSI Model to the practical implementation of Bash scripts for network configuration and the deep dive into the Web Stack.

Table of Contents
	1.	Network Basics 0
	2.	Network Basics 1
	3.	What Happens When?

## Network Basics 0
Directory: basics_0
This section covers the foundational concepts of how computers communicate.

•	0-OSI_model: Definitions and organization of the OSI (Open Systems Interconnection) model.

•	1-types_of_network: Understanding the differences between LAN, WAN, and the Internet.

•	2-MAC_and_IP_address: Differentiating between physical hardware addresses and logical network addresses.

•	3-UDP_and_TCP: Comparing the reliability of TCP vs. the speed of UDP.

•	4-TCP_and_UDP_ports: A Bash script that displays active listening ports and their associated PIDs/Program names.

•	5-is_the_host_on_the_network: A Bash script that pings an IP address 5 times to check for connectivity using ICMP.

## Network Basics 1

Directory: basics_1
Practical application of network configuration on Ubuntu servers.

•	0-change_your_home_IP: A script that modifies /etc/hosts to redirect localhost to 127.0.0.2 and facebook.com to 8.8.8.8.

•	1-show_attached_IPs: A script that filters and displays only the active IPv4 addresses assigned to the host machine.

•	2-port_listening_on_localhost: A script that sets up a local listener on port 98 using nc (netcat) to receive and display incoming text data.

# What Happens When?
Directory: what_happens_when_your_type_google_com_in_your_browser_and_press_enter
A comprehensive technical deep dive into the web infrastructure.

The Blog Post
•	File: 0-blog_post

•	Content: A link to a published technical article on Medium/LinkedIn.

•	Topics Covered:

•	DNS Resolution

•	TCP/IP Handshakes

•	Firewall filtering

•	HTTPS/SSL Encryption (TLS Handshake)

•	Load Balancers (Traffic distribution)

•	Web, Application, and Database server interactions.

The Infrastructure Diagram
•	File: 1-what_happen_when_diagram

•	Content: A URL to a visual schema illustrating the end-to-end flow of a request from the client to the database and back.
