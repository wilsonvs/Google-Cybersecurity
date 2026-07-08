# Module 5: Assets, Threats, and Vulnerabilities

## How to Use This Module

Use this module to understand what needs protection, what can go wrong, how weaknesses are found, and how threats are analyzed. This module connects asset security, vulnerability management, threat analysis, and common attack methods.

Study it from a practical point of view: identify the asset, understand the weakness, think like an attacker, and recommend a control.

## Week 1: Assets and Asset Security

### What You Should Understand

An asset is anything valuable to an organization. Assets can be digital, physical, human, or informational. Security starts with knowing what assets exist, where they are, who owns them, how important they are, and what risks affect them.

### Key Concepts

- Asset inventory helps organizations track systems, devices, applications, data, and owners.
- Asset classification helps prioritize protection based on sensitivity and importance.
- Critical assets need stronger controls and monitoring.
- Shadow IT creates risk when systems or tools are used without approval or visibility.
- Asset lifecycle includes creation, use, maintenance, transfer, and disposal.

### Important Terms

- Asset - Anything valuable that needs protection.
- Asset inventory - A record of assets and important details.
- Classification - Grouping assets based on sensitivity or value.
- Critical asset - An asset that is essential to business operations.
- Shadow IT - Technology used without formal approval or visibility.
- Data owner - Person or role responsible for data decisions.

### What To Practice

- Create an asset inventory for a small office or home lab.
- Classify assets as public, internal, confidential, or restricted.
- Identify which assets would have the highest business impact if unavailable.

### Quick Check

1. Why is asset inventory important?
2. What makes an asset critical?
3. Why is shadow IT risky?
4. How does classification support security?
5. What information should be tracked in an asset inventory?

## Week 2: Data Protection, Encryption, and Access Control

### What You Should Understand

Data must be protected from unauthorized access, modification, loss, and exposure. Strong data security uses classification, encryption, access control, authentication, authorization, and accountability.

### Key Concepts

- Data can exist at rest, in transit, or in use.
- Encryption protects confidentiality by making data unreadable without the proper key.
- Hashing verifies integrity but is not the same as encryption.
- Authentication verifies identity.
- Authorization determines what an authenticated user can access.
- Accounting tracks activity for monitoring and investigation.
- Least privilege reduces unnecessary access.

### Important Terms

- Data at rest - Stored data.
- Data in transit - Data moving across a network.
- Encryption - Converting readable data into unreadable form using a key.
- Hashing - Creating a fixed value to verify integrity.
- Authentication - Proving identity.
- Authorization - Granting permission.
- Accounting - Tracking actions.
- AAA - Authentication, Authorization, and Accounting.

### What To Practice

- Compare encryption and hashing with examples.
- List controls for protecting confidential customer data.
- Review a user access scenario and decide whether least privilege is being followed.

### Quick Check

1. What is the difference between encryption and hashing?
2. What does authentication prove?
3. What does authorization control?
4. Why is accounting important?
5. How does least privilege reduce risk?

## Week 3: Vulnerabilities and the Attacker Mindset

### What You Should Understand

A vulnerability is a weakness that can be exploited. Vulnerability management is the process of finding, prioritizing, fixing, and verifying weaknesses. Analysts should understand how attackers think so they can better recognize risk and recommend defenses.

### Key Concepts

- Vulnerabilities can exist in software, systems, networks, cloud configurations, identities, and processes.
- Patching fixes known software weaknesses.
- Misconfigurations are common causes of security exposure.
- Vulnerability severity should be prioritized with business context.
- Attackers often look for exposed services, weak passwords, unpatched systems, excessive permissions, and poor monitoring.

### Important Terms

- Vulnerability - A weakness that can be exploited.
- Exploit - A method used to take advantage of a vulnerability.
- Patch - An update that fixes a weakness or bug.
- Misconfiguration - Incorrect or insecure setup.
- CVE - Common Vulnerabilities and Exposures identifier.
- CVSS - Common Vulnerability Scoring System.
- Attack vector - Path or method used to attack.

### What To Practice

- Review a sample vulnerability report and identify severity, affected asset, and remediation.
- Explain why a medium vulnerability on a critical internet-facing server may be urgent.
- Build a simple prioritization list using severity, exposure, asset value, and exploitability.

### Quick Check

1. What is a vulnerability?
2. What is an exploit?
3. Why are misconfigurations dangerous?
4. Why should vulnerability priority include business context?
5. What is the purpose of patch management?

## Week 4: Threats, Social Engineering, Malware, Web Attacks, and Threat Modeling

### What You Should Understand

Threats come in many forms. Some attacks target technology directly, while others target people. Threat modeling helps identify what can go wrong and what controls can reduce risk before an incident happens.

### Key Concepts

- Social engineering manipulates people into unsafe actions.
- Phishing attempts to steal credentials or deliver malware.
- Malware includes viruses, worms, trojans, ransomware, spyware, and rootkits.
- Web attacks may target authentication, input validation, sessions, or insecure configurations.
- Threat modeling asks what is being built, what can go wrong, what should be done, and whether controls are effective.

### Important Terms

- Phishing - Fraudulent message designed to trick users.
- Spear phishing - Targeted phishing against a specific person or group.
- Ransomware - Malware that encrypts or blocks access until payment is demanded.
- Trojan - Malware disguised as legitimate software.
- SQL injection - Attack that sends malicious SQL input to an application.
- XSS - Cross-site scripting; injecting malicious script into web pages.
- Threat model - Structured analysis of potential threats and controls.

### What To Practice

- Analyze a sample phishing email and identify warning signs.
- List possible controls for ransomware prevention and recovery.
- Create a simple threat model for a login page.
- Review OWASP-style web risks at a high level.

### Quick Check

1. Why is social engineering effective?
2. What is the difference between phishing and spear phishing?
3. Why is ransomware dangerous?
4. What is SQL injection?
5. How does threat modeling help before an incident?

## Module Review Checklist

- I can identify and classify assets.
- I understand asset inventory and lifecycle.
- I can explain data at rest, in transit, and in use.
- I understand encryption, hashing, and AAA.
- I can explain vulnerabilities, exploits, patches, and misconfigurations.
- I can recognize common threats such as phishing, malware, and web attacks.
- I can build a simple threat model.

## Quick Revision

Asset security starts with knowing what needs protection. Data protection uses classification, encryption, hashing, access control, and monitoring. Vulnerability management finds and fixes weaknesses. Threat analysis helps identify how attackers may cause harm. Threat modeling turns that understanding into better design and stronger controls.