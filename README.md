# -dawnsmithcyber
# 🛡️ Dawn Smith | SOC Analyst • Threat Hunter • Cyber Fraud Investigator • CFE

**Investigating threats across endpoint, network, identity, and SIEM telemetry — from initial detection through root cause, containment, and remediation.**
---
# Hi there, I'm Dawn 👋

I’m a **Cybersecurity Analyst, Threat Hunter, Cyber Fraud Investigator, and Certified Fraud Examiner (CFE)** with experience bridging traditional fraud investigations with security operations, incident response, and behavioral threat detection.

My focus is understanding the full attack story:

> **How did they get in? What did they do once they were there? What evidence did they leave behind — and how do we stop the next one?**

I currently work across **threat detection, incident investigation, log analysis, SIEM, endpoint telemetry, network security monitoring, account takeover (ATO), identity-related fraud, and detection engineering.**

I also serve as a **Cybersecurity Community Moderator**, where I lead **CompTIA Security+ SY0-701 study groups**, create cybersecurity education content, and help developing analysts strengthen their SOC and investigative skills.

---

## 🛡️ Cybersecurity Focus

### 🔎 Threat Hunting & Detection
- Behavioral threat hunting
- Log and telemetry analysis
- Indicator and TTP analysis
- MITRE ATT&CK mapping
- Suspicious process analysis
- Living-off-the-land activity
- Endpoint and network correlation
- Threat intelligence enrichment
- IOC, IOA, and behavioral detection

### 🚨 Incident Response & SOC Operations
- Security alert triage
- Incident investigation
- Root cause analysis
- Incident timeline development
- Containment and remediation analysis
- SIEM investigations
- Endpoint investigation
- Phishing and email threat analysis
- Escalation and documentation
- SOC runbook development

### 🕵️ Cyber Fraud Investigations
- Account Takeover (ATO)
- Identity theft investigations
- Authentication abuse
- Suspicious account behavior
- Fraud pattern analysis
- Financial crime investigations
- Large-scale data analysis
- Behavioral analysis
- Evidence documentation
- Root cause investigation

---

# 🧰 Technical Arsenal

## SIEM & Security Monitoring

- **Microsoft Sentinel**
- **Splunk / Splunk Enterprise Security**
- Azure Log Analytics
- Kusto Query Language (**KQL**)
- Sysmon
- Windows Event Logs
- Linux system telemetry

## Endpoint & Cloud Security

- Microsoft Defender for Endpoint
- Microsoft Defender for Cloud
- EDR investigation
- Azure security monitoring
- Cloud Security Posture Management (**CSPM**)
- Cloud workload protection
- Identity and access monitoring
- IAM / MFA analysis

## Network Security Monitoring

- **Suricata**
- **Zeek**
- Wireshark
- IDS / IPS
- TCP/IP
- DNS
- HTTP / HTTPS
- Firewalls
- VPNs
- Network traffic analysis
- Packet analysis

## Threat Detection & Investigation

- MITRE ATT&CK
- Cyber Kill Chain
- Threat Intelligence
- Threat Hunting
- Malware Analysis
- Phishing Analysis
- Behavioral Detection
- Root Cause Analysis
- Indicators of Compromise (IOC)
- Indicators of Attack (IOA)
- TTP Analysis

## Investigation & Data

- SQL
- Python
- Pandas
- NumPy
- Snowflake
- Tableau
- Large-scale dataset analysis

## Security Operations

- ServiceNow
- Jira
- SOC documentation
- Incident runbooks
- Alert triage
- Investigation documentation
- Security escalation workflows

---

# 🔬 Featured Cybersecurity Projects

## 🎯 Full Adversary Lifecycle Detection Lab

Built an end-to-end attack-and-detection environment designed to generate realistic security telemetry across the attack lifecycle.

### ⚔️ Attack Simulation

- Exploited a vulnerable **DVWA** web application
- Used an insecure file upload vulnerability to deploy a **PHP web shell**
- Staged additional tooling using `curl`
- Modified file permissions and executed staged tooling
- Established a **Sliver C2 session**
- Performed reconnaissance and privilege-escalation activity

### 🛡️ Detection Engineering

Built a telemetry pipeline using:

```text
Suricata → Zeek → Sysmon → Splunk Universal Forwarder → Splunk
