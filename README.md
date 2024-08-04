# Network-Scanning

##**OBJECTIVE**


Discover devices and services running on local network and aslo identify potential targets and vulnerabilities within a network.

##**TOOLS**

-Kali linux

-Nmap

-local network

##**STEPS**

1. Open the terminal and verify or update nmap installation using:

   sudo apt-get update && sudo apt-get install nmap

2. Determine the local network ip address using:

   ip addr

3. Run basic scan on the network using ip address gotten.

   nmap 192.268.2.5/24
   
This scan listed the hosts on the network, their ip address and open ports.
