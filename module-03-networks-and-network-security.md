# Module 3: Connect and Protect - Networks and Network Security

## How to Use This Module

Use this module to understand how systems communicate and how attackers target network communication. Network knowledge is essential for SOC work because many alerts, logs, and investigations involve IP addresses, ports, protocols, firewalls, DNS, VPNs, and unusual traffic.

Focus on understanding the purpose of each network concept. You do not need to become a network engineer immediately, but you should be able to read basic network evidence and ask the right investigation questions.

## Week 1: Networks, Devices, and Communication Basics

### What You Should Understand

A network connects devices so they can share data and services. Networks can be small, such as a home Wi-Fi network, or large, such as an enterprise network with cloud systems, branch offices, and remote users.

Security analysts need to know how devices communicate so they can recognize normal and suspicious activity.

### Key Concepts

- A network allows systems to communicate using agreed rules called protocols.
- Common network devices include routers, switches, firewalls, wireless access points, servers, and endpoints.
- LANs usually cover a smaller local area; WANs connect larger areas.
- Cloud networks use virtual networking concepts such as virtual private clouds, security groups, and routing rules.
- Network segmentation separates systems to reduce risk and limit attack spread.

### Important Terms

- LAN - Local Area Network.
- WAN - Wide Area Network.
- Router - Sends traffic between networks.
- Switch - Connects devices within a local network.
- Firewall - Filters traffic based on rules.
- Endpoint - A user device or system, such as a laptop, desktop, or server.
- Protocol - A rule set for communication.
- Packet - A small unit of network data.

### What To Practice

- Draw a simple network with laptop, switch, router, firewall, internet, and server.
- Identify which devices control traffic and which devices use services.
- Explain why segmentation protects important systems.

### Quick Check

1. What is the purpose of a network?
2. What is the difference between a router and a switch?
3. Why are firewalls important?
4. What is network segmentation?
5. Why does a security analyst need basic networking knowledge?

## Week 2: Protocols, Ports, and System Identification

### What You Should Understand

Protocols and ports help systems know how to communicate. When reviewing logs, analysts often look at source IP, destination IP, source port, destination port, protocol, timestamp, and action.

### Key Concepts

- IP addresses identify systems on a network.
- MAC addresses identify network interfaces at the local network level.
- DNS translates domain names into IP addresses.
- DHCP assigns IP addresses to devices.
- TCP is connection-oriented; UDP is faster but does not establish the same type of connection.
- Ports help identify the service being used.

### Common Ports To Know

| Port | Protocol | Common Use |
| --- | --- | --- |
| 20/21 | FTP | File transfer |
| 22 | SSH | Secure remote administration |
| 25 | SMTP | Email sending |
| 53 | DNS | Name resolution |
| 80 | HTTP | Web traffic |
| 443 | HTTPS | Secure web traffic |
| 3389 | RDP | Windows remote desktop |

### Important Terms

- IP address - Logical network address assigned to a device.
- MAC address - Physical address of a network interface.
- DNS - Domain Name System.
- DHCP - Dynamic Host Configuration Protocol.
- TCP - Transmission Control Protocol.
- UDP - User Datagram Protocol.
- Port - Number used to identify a network service.

### What To Practice

- Read a sample firewall log and identify source, destination, port, protocol, and action.
- Memorize the most common ports used in basic investigations.
- Use `ping`, `ipconfig`, `nslookup`, or equivalent commands in a safe lab environment.

### Quick Check

1. What does DNS do?
2. Why are ports useful in network analysis?
3. What is the difference between TCP and UDP?
4. What port is commonly used for HTTPS?
5. What information should you look for in a network log?

## Week 3: Network Attacks and Intrusion Tactics

### What You Should Understand

Attackers target networks to steal data, interrupt services, move laterally, capture credentials, or gain access to internal systems. Analysts must recognize common attack patterns and know what evidence to look for.

### Key Concepts

- DoS and DDoS attacks attempt to make services unavailable.
- Packet sniffing can capture network traffic when traffic is not properly protected.
- Spoofing hides or impersonates an identity such as IP, email, or domain.
- Man-in-the-middle attacks intercept communication between two parties.
- Lateral movement happens when attackers move from one compromised system to another.
- Unusual traffic volume, strange destinations, repeated failures, and unexpected ports can indicate suspicious activity.

### Important Terms

- DoS - Denial of Service.
- DDoS - Distributed Denial of Service.
- Spoofing - Pretending to be another system, user, or source.
- Packet sniffing - Capturing network packets.
- Man-in-the-middle - Intercepting communication between parties.
- Lateral movement - Moving through a network after initial access.
- Exfiltration - Unauthorized transfer of data out of an environment.

### What To Practice

- Identify possible signs of DDoS in logs or dashboards.
- List indicators that may suggest data exfiltration.
- Compare spoofing, sniffing, and man-in-the-middle attacks.

### Quick Check

1. What is the goal of a DDoS attack?
2. Why is encrypted traffic safer than plaintext traffic?
3. What is lateral movement?
4. What is data exfiltration?
5. What network evidence could indicate suspicious activity?

## Week 4: Network Hardening and Defense

### What You Should Understand

Network hardening reduces the attack surface by removing unnecessary access, applying secure configurations, monitoring activity, and enforcing layered controls.

### Key Concepts

- Defense in depth uses multiple layers of protection.
- Firewalls filter traffic based on rules.
- VPNs protect remote access by creating encrypted tunnels.
- IDS tools detect suspicious traffic; IPS tools can block it.
- Secure configuration includes disabling unused services, patching systems, and limiting exposed ports.
- Cloud network security includes security groups, network ACLs, IAM, logging, and private networking.

### Important Terms

- Attack surface - All possible points an attacker could target.
- Hardening - Reducing weaknesses through secure configuration.
- VPN - Virtual Private Network.
- IDS - Intrusion Detection System.
- IPS - Intrusion Prevention System.
- Allowlist - Approved traffic, users, or applications.
- Denylist - Blocked traffic, users, or applications.

### What To Practice

- Create a basic hardening checklist for a small network.
- Identify which ports should be open for a web server and which should be restricted.
- Explain how VPN, MFA, firewall rules, and logging work together.

### Quick Check

1. What does hardening mean?
2. Why should unused ports and services be disabled?
3. What is defense in depth?
4. How does a VPN support secure remote access?
5. What is the difference between IDS and IPS?

## Module Review Checklist

- I can explain LAN, WAN, routers, switches, firewalls, and endpoints.
- I can identify common protocols and ports.
- I understand DNS, DHCP, TCP, UDP, IP addresses, and MAC addresses.
- I can recognize common network attacks.
- I can describe basic network hardening steps.
- I can read simple network or firewall log fields.

## Quick Revision

Networks allow systems to communicate. Security analysts use network knowledge to understand logs, identify suspicious traffic, investigate alerts, and recommend hardening steps. Key topics include devices, protocols, ports, DNS, DHCP, TCP, UDP, firewalls, VPNs, IDS, IPS, attacks, and defense in depth.