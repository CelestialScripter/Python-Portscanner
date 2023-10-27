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
`` python3 portscanner.py {IP ADDR} ``

Eg.: ` python3 portscanner.py 192.168.25.1 `
## Usage and Liability Disclaimer

**Usage Agreement:** The code contained in this repository should only be used with proper consent and in strict compliance with all applicable local, state, and federal laws. Users of this code are solely responsible for ensuring their activities adhere to legal regulations and obligations.

**No Liability:** The developers of this code assume no liability and shall not be held responsible for any misuse, damage, or harm resulting from the use of this code by unauthorized individuals or malicious actors, whether intentional or accidental. This includes any actions that compromise the security, privacy, integrity, or availability of computer systems and associated resources. In this context, "compromise" refers to the exploitation of known or unknown vulnerabilities within these systems, which may involve circumventing security measures, whether through human actions or electronic means.

**Endorsement for Specific Scenarios:** The use of this code is explicitly endorsed by the developers in particular contexts, such as educational environments and authorized penetration testing engagements. These engagements should have a clearly defined objective: the identification and mitigation of vulnerabilities in systems, with the goal of enhancing their resistance to exploitation and attacks by malicious actors. These objectives should align with the defined threat models relevant to the specific scenario.


