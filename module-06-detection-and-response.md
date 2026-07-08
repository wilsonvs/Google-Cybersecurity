# Module 6: Sound the Alarm - Detection and Response

## How to Use This Module

Use this module to study how security teams detect, analyze, document, respond to, and learn from incidents. This is one of the most important areas for SOC analyst preparation because it connects alerts, logs, network traffic, tools, evidence, escalation, and incident handling.

Read each week as an investigation workflow: notice activity, collect evidence, decide whether it is suspicious, document what happened, and take the correct next step.

## Week 1: Incident Response Lifecycle and Security Operations

### What You Should Understand

Incident response is a structured process for handling security events that may harm systems, data, or operations. Security operations teams use tools, procedures, and communication paths to monitor activity and respond consistently.

### Key Concepts

- Not every event is an incident.
- An event is any observable activity.
- An alert is a notification that activity may need review.
- An incident is confirmed or likely harmful security activity.
- Incident response reduces damage and helps recovery.
- Preparation is important because incidents move quickly.

### Incident Response Phases

- Preparation - Build tools, plans, playbooks, training, and access.
- Detection and analysis - Identify suspicious activity and determine scope.
- Containment - Limit spread or damage.
- Eradication - Remove the root cause.
- Recovery - Restore normal operations safely.
- Post-incident activity - Review lessons learned and improve controls.

### Important Terms

- Event - Recorded activity.
- Alert - Notification requiring review.
- Incident - Security event that can cause harm.
- Triage - Initial review and prioritization.
- Severity - Measure of incident importance.
- Scope - Systems, users, data, or networks affected.
- Escalation - Moving an issue to the correct team or authority.

### What To Practice

- Classify examples as event, alert, or incident.
- Write an incident response checklist for suspected credential compromise.
- Practice identifying severity based on affected assets and business impact.

### Quick Check

1. What is the difference between an event and an incident?
2. Why is preparation part of incident response?
3. What does containment do?
4. Why is scope important?
5. When should an analyst escalate?

## Week 2: Network Traffic and Packet Analysis

### What You Should Understand

Network traffic contains evidence about communication between systems. Analysts may inspect traffic to identify suspicious connections, unusual protocols, large transfers, repeated failures, or signs of command-and-control activity.

### Key Concepts

- Packets contain headers and data.
- Packet headers show information such as source IP, destination IP, ports, protocol, and flags.
- Packet capture tools collect network traffic for analysis.
- Traffic patterns can reveal scanning, brute force attempts, malware communication, or data exfiltration.
- Encrypted traffic protects content but metadata can still be useful.

### Important Terms

- Packet - Unit of network data.
- Packet capture - Recorded network traffic.
- Header - Metadata used to route and manage traffic.
- Payload - Data carried by the packet.
- Protocol analyzer - Tool used to inspect traffic.
- Baseline - Understanding of normal activity used to detect abnormal behavior.

### What To Practice

- Review packet fields: source, destination, protocol, port, timestamp, and length.
- Compare normal web browsing traffic with suspicious repeated connection attempts.
- Identify what information remains visible when traffic is encrypted.

### Quick Check

1. What is a packet?
2. What is the difference between a header and payload?
3. Why is a traffic baseline useful?
4. What traffic pattern could suggest scanning?
5. Why can encrypted traffic still provide investigation clues?

## Week 3: Detection, Verification, Documentation, and Recovery

### What You Should Understand

Detection is only the beginning. Analysts must verify whether activity is actually suspicious, document evidence, take appropriate action, and support recovery. Good documentation allows other team members to understand the investigation without guessing.

### Key Concepts

- Alert investigation should be evidence-based.
- Analysts should avoid assumptions and record facts clearly.
- Verification may require checking multiple data sources.
- Recovery should happen only after containment and eradication are understood.
- Post-incident review improves future detection and response.

### Alert Triage Checklist

- What triggered the alert?
- Which user, host, IP address, application, or account is involved?
- When did it happen?
- Is the affected asset critical?
- Is the activity expected or unusual?
- Is there supporting evidence from other logs?
- Is immediate containment required?
- Who needs to be notified or escalated?

### Important Terms

- True positive - Alert correctly identifies suspicious or harmful activity.
- False positive - Alert appears suspicious but is benign.
- Indicator of compromise - Evidence that a system or account may be compromised.
- Root cause - Underlying reason the incident happened.
- Timeline - Ordered record of important incident events.
- Post-incident review - Review used to improve future security.

### What To Practice

- Write a short timeline from sample alert data.
- Document an investigation using only observed facts.
- Compare a true positive and false positive example.

### Quick Check

1. Why should analysts verify alerts?
2. What should be included in incident notes?
3. What is an indicator of compromise?
4. Why is timeline building useful?
5. What should happen after an incident is resolved?

## Week 4: Logs, IDS, and SIEM Analysis

### What You Should Understand

Logs are the main evidence source for many security investigations. IDS and SIEM tools help detect and analyze suspicious activity by collecting, filtering, correlating, and alerting on logs and events.

### Key Concepts

- Logs should include enough detail to support investigation.
- Common log sources include authentication, endpoint, firewall, DNS, proxy, email, VPN, cloud, and application logs.
- IDS tools inspect traffic or behavior for suspicious patterns.
- SIEM tools collect and correlate logs from many sources.
- Query languages help analysts search large log datasets.
- Detection quality depends on log quality, rule logic, tuning, and analyst review.

### Important Terms

- Authentication log - Record of login and access attempts.
- Firewall log - Record of allowed or blocked network connections.
- DNS log - Record of domain lookups.
- Endpoint log - Record of activity on a device.
- IDS signature - Pattern used to detect known suspicious behavior.
- SIEM correlation - Linking related events across sources.
- Log retention - How long logs are stored.

### What To Practice

- Identify which log source would help investigate a failed login spike.
- Identify which log source would help investigate suspicious outbound traffic.
- Write example SIEM search goals, such as failed logins by user, rare destination domains, or administrative actions outside business hours.

### Quick Check

1. Why are logs important for detection and response?
2. What types of logs are useful for account compromise investigations?
3. What does an IDS do?
4. How does a SIEM help analysts?
5. Why does detection require tuning?

## Module Review Checklist

- I can explain event, alert, and incident.
- I understand the incident response lifecycle.
- I can describe basic packet and traffic analysis.
- I can use an alert triage checklist.
- I can explain true positive, false positive, and indicator of compromise.
- I can identify useful log sources for investigations.
- I understand how IDS and SIEM tools support detection and response.

## Quick Revision

Detection and response is the process of identifying suspicious activity, verifying evidence, documenting facts, containing harm, recovering safely, and improving afterward. Analysts use logs, alerts, SIEM tools, IDS tools, packet data, playbooks, and communication skills to support security operations.