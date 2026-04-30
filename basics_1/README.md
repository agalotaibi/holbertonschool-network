## 0. Change your home IP

The /etc/hosts file acts as a local DNS map. By modifying it, we can force specific hostnames to resolve to specific IPs before the computer ever asks a DNS server.
File: 0-change_your_home_IP


## 1. Show attached IPs
We want to extract just the IPv4 addresses from the system. We can use the hostname -I command for a quick list, or parse ip addr for more detail.
File: 1-show_attached_IPs


## 2. Port listening on localhost
To listen on a specific port and display incoming data, netcat (nc) is the industry standard tool.
File: 2-port_listening_on_localhost
