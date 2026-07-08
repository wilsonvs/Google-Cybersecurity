# Module 2: Play It Safe - Manage Security Risks

## How to Use This Module

Use this module to understand how organizations identify, measure, reduce, and monitor security risk. Risk management is one of the most important cybersecurity foundations because every security decision is connected to risk, cost, business impact, and priority.

Each week includes concepts, terms, practice tasks, and quick checks. Focus on explaining risk clearly, because strong analysts must communicate technical issues in practical language.

## Week 1: Security Domains, Threats, Risks, and Vulnerabilities

### What You Should Understand

Security risk exists when something valuable can be harmed by a threat exploiting a weakness. Risk management is the process of identifying what matters, understanding what can go wrong, deciding what to fix first, and tracking whether controls are working.

### Key Concepts

- A threat is a possible cause of harm.
- A vulnerability is a weakness that can be exploited.
- Risk combines likelihood and impact.
- Security domains help organize areas of responsibility.
- Risk decisions should be based on business impact, not fear alone.
- Not every risk can be removed; many risks are reduced, transferred, accepted, or avoided.

### Important Terms

- Likelihood - The chance that a risk event could happen.
- Impact - The damage that could occur if the risk happens.
- Risk rating - A way to prioritize risk, often using likelihood and impact.
- Risk appetite - The amount of risk an organization is willing to accept.
- Risk register - A document used to track risks, owners, ratings, and treatment plans.
- Control owner - The person or team responsible for a security control.

### What To Practice

- Create a small risk register with five risks for a home office or small company.
- Rate each risk as low, medium, or high based on likelihood and impact.
- Identify one possible control for each risk.

### Quick Check

1. What is the difference between a threat and a vulnerability?
2. Why should risk be prioritized?
3. What is risk appetite?
4. Why is a risk register useful?
5. What happens when a risk is accepted?

## Week 2: Frameworks, Controls, and Security Audits

### What You Should Understand

Frameworks provide structure for managing risk. Controls reduce risk. Audits check whether controls exist, are documented, and are operating effectively. A security audit is not just paperwork; it helps find gaps before an incident exposes them.

### Key Concepts

- The CIA triad helps evaluate confidentiality, integrity, and availability risk.
- Frameworks such as NIST CSF, CIS Controls, ISO 27001, and OWASP help organize security work.
- Controls can be administrative, technical, or physical.
- Security audits review policies, evidence, access, configurations, logs, and procedures.
- Audit results should lead to practical remediation steps.

### Important Terms

- Administrative control - A policy, standard, process, or training requirement.
- Technical control - A technology-based safeguard such as MFA, firewall rules, encryption, or logging.
- Physical control - A physical safeguard such as locks, cameras, badges, or secure rooms.
- Compliance - Meeting legal, regulatory, contractual, or policy requirements.
- Audit evidence - Proof used to show whether a control is working.
- Control gap - A missing or weak control.

### What To Practice

- List three administrative, three technical, and three physical controls.
- Review a sample access-control process and identify audit evidence.
- Map five controls to the CIA triad.

### Quick Check

1. What is the purpose of a security framework?
2. How is a control different from a policy?
3. What are the three categories of controls?
4. Why do audits require evidence?
5. How can audit findings improve security?

## Week 3: SIEM Tools and Security Monitoring

### What You Should Understand

Security monitoring depends on collecting and reviewing activity from many systems. SIEM tools centralize logs, correlate events, generate alerts, and help analysts investigate suspicious behavior.

### Key Concepts

- Logs provide evidence of activity.
- SIEM tools help analysts search, filter, correlate, and alert on logs.
- Dashboards summarize important security information.
- Alerts need triage to determine whether they are true positives or false positives.
- Good monitoring depends on good data sources and clear detection rules.

### Important Terms

- Event - A recorded action, such as login success, login failure, file access, or network connection.
- Correlation - Connecting related events to identify a larger pattern.
- Dashboard - A visual summary of security information.
- Query - A search used to find specific data in logs.
- Detection rule - Logic used to identify suspicious activity.
- Triage - The first review of an alert to decide priority and next action.

### What To Practice

- Identify useful log sources: authentication logs, firewall logs, endpoint logs, DNS logs, VPN logs, and cloud logs.
- Write example questions a SIEM query could answer, such as failed logins from one user or unusual access from a foreign location.
- Practice classifying alerts as true positive, false positive, or needs more evidence.

### Quick Check

1. What problem does a SIEM solve?
2. Why are logs important for risk management?
3. What is alert triage?
4. What makes a dashboard useful?
5. Why can poor log quality weaken detection?

## Week 4: Playbooks and Incident Response

### What You Should Understand

Playbooks provide repeatable steps for handling common security situations. They reduce confusion during incidents and help analysts respond consistently. Incident response connects risk management with real operational action.

### Key Concepts

- A playbook should define triggers, steps, owners, evidence, escalation points, and communication paths.
- Incident response usually includes preparation, detection, analysis, containment, eradication, recovery, and lessons learned.
- Escalation is important when the analyst cannot fully resolve an issue or when business impact is high.
- Clear documentation supports handoff, investigation, reporting, and improvement.

### Important Terms

- Incident - A confirmed or likely security event that can harm systems, data, or operations.
- Containment - Limiting the spread or impact of an incident.
- Eradication - Removing the cause of the incident.
- Recovery - Returning systems to normal operation.
- Lessons learned - Reviewing what happened and improving controls or processes.
- Escalation - Moving an issue to a higher-level team or authority.

### What To Practice

- Create a simple phishing email response playbook.
- Create a checklist for suspected malware on a workstation.
- Write incident notes with timestamp, evidence, action taken, and next step.

### Quick Check

1. Why are playbooks useful during incidents?
2. What is the difference between containment and eradication?
3. When should an analyst escalate an incident?
4. Why is documentation important?
5. How do lessons learned reduce future risk?

## Module Review Checklist

- I can explain risk using likelihood and impact.
- I can identify threats, vulnerabilities, and controls.
- I understand frameworks, audits, and control categories.
- I know why SIEM tools are used for monitoring.
- I can describe alert triage and detection rules.
- I can explain how playbooks support incident response.
- I can create a basic risk register or response checklist.

## Quick Revision

Risk management helps organizations decide what to protect, what can go wrong, how serious it is, and what action should be taken. Frameworks organize security work, controls reduce risk, audits verify control effectiveness, SIEM tools support monitoring, and playbooks guide incident response.