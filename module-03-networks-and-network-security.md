# Module 3: Connect and Protect - Networks and Network Security

## Goal
Understand how networks communicate, how protocols and ports work, how attackers target networks, and how hardening protects systems, networks, and cloud environments.

## Week-by-Week Focus

| Week | Study Focus |
| --- | --- |
| Week 1 | Network basics, network communication, LANs, WANs, and cloud networks |
| Week 2 | Protocols, IP addresses, MAC addresses, ports, DNS, and system identification |
| Week 3 | Network intrusion tactics, DoS attacks, packet sniffing, and defenses |
| Week 4 | Security hardening for operating systems, networks, and cloud environments |

## Network Basics

- **Network:** Connected devices that communicate and share resources.
- **LAN:** Local area network, usually within one location.
- **WAN:** Wide area network that connects locations over larger distances.
- **Cloud network:** Virtual network resources hosted by a cloud provider.
- **Router:** Moves traffic between networks.
- **Switch:** Connects devices inside a local network.

## Network Communication

- **IP address:** Logical address used to identify a device on a network.
- **MAC address:** Hardware address assigned to a network interface.
- **Packet:** Small unit of network data.
- **Port:** Logical number used to identify a service.
- **Protocol:** Rules that define communication.

## Common Protocols and Services

| Protocol | Purpose |
| --- | --- |
| DNS | Translates domain names to IP addresses |
| HTTP | Unencrypted web traffic |
| HTTPS | Encrypted web traffic |
| TCP | Reliable connection-based communication |
| UDP | Faster connectionless communication |
| DHCP | Assigns IP addresses automatically |
| SSH | Secure remote command-line access |
| FTP/SFTP | File transfer; SFTP is secure |
| ICMP | Network testing and error messages |

## Network Attacks

- **Packet sniffing:** Capturing network traffic.
- **Man-in-the-middle:** Intercepting communication between systems.
- **DoS/DDoS:** Overwhelming a service to make it unavailable.
- **DNS attacks:** Manipulating name resolution or DNS traffic.
- **Port scanning:** Checking open services on a system.
- **Spoofing:** Pretending to be another device, user, or service.

## Network Defenses

- Firewalls
- Network segmentation
- VPNs
- IDS/IPS
- Secure Wi-Fi configuration
- Strong authentication
- DNS filtering
- Logging and monitoring

## Hardening

- **OS hardening:** Patch systems, remove unnecessary software, disable unused services, configure logging, and restrict admin access.
- **Network hardening:** Review firewall rules, disable unused ports, secure device management, segment networks, and update firmware.
- **Cloud hardening:** Use least privilege, private storage, encryption, logging, secure security groups, and configuration monitoring.

## Analyst Questions

- What source and destination are involved?
- Which protocol and port are used?
- Is the traffic expected?
- Is there unusual volume or timing?
- Is the destination known, trusted, or suspicious?

## Quick Review

- Networks rely on addresses, protocols, ports, and devices.
- Attackers often look for exposed services and weak configurations.
- Hardening reduces attack surface.
- Logs and packet data help analysts understand network activity.
