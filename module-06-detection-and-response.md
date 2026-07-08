# Module 6: Sound the Alarm - Detection and Response

## Goal
Understand how analysts detect incidents, inspect network traffic, document findings, respond to incidents, and use IDS/SIEM tools.

## Week-by-Week Focus

| Week | Study Focus |
| --- | --- |
| Week 1 | Incident response lifecycle, operations, and response tools |
| Week 2 | Network traffic, packet capture, packet inspection, and protocol analysis |
| Week 3 | Incident detection, verification, documentation, recovery, and post-incident actions |
| Week 4 | Logs, IDS, SIEM tools, log formats, and detection rules |

## Incident Response Lifecycle

1. **Preparation:** Build tools, procedures, contacts, and playbooks.
2. **Detection and analysis:** Identify and validate suspicious activity.
3. **Containment:** Limit damage and prevent spread.
4. **Eradication:** Remove the cause of the incident.
5. **Recovery:** Restore normal operations.
6. **Post-incident activity:** Document lessons learned and improve controls.

## Network Traffic Review

Analysts may inspect traffic to understand:

- Source and destination IP addresses
- Ports and protocols
- Packet size and timing
- DNS requests
- HTTP requests
- Unusual connections
- Repeated failed communication

Tools and concepts:

- Packet capture
- Protocol analyzer
- Network metadata
- TCP/IP headers
- DNS and HTTP logs
- Network telemetry

## Incident Documentation

Good documentation should include:

- Alert name or event summary
- Date and time
- User, host, IP, or asset involved
- Evidence reviewed
- Timeline of events
- Impact estimate
- Actions taken
- Next steps

## Logs

- **Log:** Record of activity from a system, application, network device, or security tool.
- **Security logs:** Events related to access, alerts, authentication, or suspicious activity.
- **System logs:** Operating system and service events.
- **Network logs:** Traffic and connection records.

Common formats:

- Syslog
- JSON
- XML
- CSV
- Key-value pairs

## IDS and SIEM

- **IDS:** Detects suspicious activity and creates alerts.
- **NIDS:** Network-based IDS.
- **HIDS:** Host-based IDS.
- **SIEM:** Collects, searches, and correlates logs.
- **Rule/signature:** Detection logic that identifies known patterns.

## Search and Detection

Analysts may use:

- Raw log search
- Field search
- SPL-style queries
- UDM-style searches
- YARA-L style detection logic
- Filters by user, host, IP, time, or event type

## Quick Review

- Detection starts with logs, traffic, alerts, and context.
- Verification decides whether activity is benign, suspicious, or malicious.
- Documentation supports escalation and lessons learned.
- SIEM and IDS tools help analysts search and detect security events.
