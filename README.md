## Port scanner
A port scanner is a software tool designed to examine network ports and determine their status, which can be categorized as either open, closed, or filtered.

Port scanners serve a dual purpose in the realm of computer networks. On one hand, they are valuable for diagnosing network and connectivity problems, aiding network administrators and engineers in pinpointing issues and ensuring the smooth operation of their systems. On the other hand, malicious actors can employ port scanners as a reconnaissance tool to identify potential entry points for unauthorized access and gather information about the devices and services running on a network, such as firewalls, proxy servers, or VPN servers.

**How Port Scanners Work**

A port scanner operates by sending network requests to connect to specific TCP or UDP ports on a target computer and recording the responses received.

The fundamental process involves sending packets of network data to the designated ports to assess their current status. For example, if you wanted to verify the functionality of a web server, you would check the status of port 80 on that server to confirm whether it is open and actively listening for incoming connections.

The status information obtained through port scanning can be crucial in various scenarios, serving as a valuable tool for network engineers and administrators to diagnose network issues or application connectivity problems. Simultaneously, it can be exploited by attackers to identify potential entry points for network infiltration.
## Installation
Refer to requirements.txt file to know the dependencies.

## Usage
` python3 portscanner.py {IP ADDR} `

-Example: ` python3 portscanner.py 192.168.25.1 `
