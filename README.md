# 🚀 Zachary Hanselman's Cybersecurity & Automation Portfolio

Welcome to my cybersecurity, automation, and homelab engineering portfolio.  
I specialize in **SOC operations, detection engineering, Windows security monitoring, PowerShell automation, cloud security, and DoD-aligned cyber practices.**

This portfolio contains hands-on projects designed to demonstrate the technical skills I use daily as a **Cybersecurity Engineer** supporting the Defense Health Agency (DHA), as well as the blue-team and automation capabilities I continue to refine through my home SOC lab.

---

# 🛡️ Featured Project: EventLog_Triage1  
**Windows Security Event Log Triage Tool (PowerShell)**  
📂 Repo: https://github.com/DigitalBulwark-z8586/EventLog_Triage1

A PowerShell-based tool that automates triage of Windows Security event logs for Tier 1 SOC workflows.  
It collects critical authentication, account activity, and process creation events — parses XML event data, extracts actionable security fields, sorts events by relevance, and exports results for analyst review or SIEM ingestion.

### 🔍 Key Features
- Pulls Tier-1 SOC Security events: 4624, 4625, 4688, 4720–4726, 4768–4776, etc.
- Parses XML event data to extract:
  - Target/Subject User  
  - Domain  
  - IP Address and Port  
  - Logon Type  
  - Workstation  
  - Authentication Package  
  - Process Executed  
  - Status & SubStatus  
  - ✔ FailureReason for 4625 (Failed Logon)
- Groups & sorts events by **EventId + TimeCreated**
- Supports **CSV export** for SIEM, Excel, or forensic review
- Ideal for:
  - SOC Analyst training  
  - IR triage  
  - Home SOC lab data ingestion  
  - Account misuse investigation  
  - Authentication failure pattern analysis

---

# 📚 Additional Portfolio Projects

## 🔹 Home SOC Lab (Hybrid Cloud + On-Prem)
A multi-cloud SOC architecture integrating AWS, on-prem Windows Server 2022 AD, Linux endpoints, Splunk Enterprise, Wazuh, and Elastic Stack.

**Highlights**  
- Windows log forwarding with Splunk UF  
- Linux auditd + syslog forwarding  
- Malware simulation & detection testing  
- Network segmentation, VLANs, and firewall rules  
- MITRE ATT&CK mapping for custom detections  
- Cloud-hosted identity (Hybrid AD) investigations

---

## 🔹 Python Security Tools & Scripts
**Suspicious Process Snapshot Script**
- Process → network connection mapping  
- Flags suspicious command-line arguments  
- Detects execution from user temp/download folders  
- CSV + JSON output for IR triage

**Network Traffic Analyzer**
- Live packet capture  
- DNS & ICMP logging  
- GeoIP enrichment  
- Syslog export to SIEM stack

---

## 🔹 PowerShell Security & Automation
- Windows Event Log automation  
- Automated ACAS/Vulnerability compliance checks  
- Endpoint baseline compliance scripts  
- User provisioning & AD lifecycle automation  
- PKI Token auditing and privileged access reviews

---

# 💼 Professional Background

**Cybersecurity Engineer – Ka’ala Systems / DHA  
Security Clearance: Secret (Active)**

Key responsibilities:
- Privileged access management (PAM/PAA)  
- PKI token issuance & alternate token operations  
- ACAS/STIG vulnerability and compliance remediation  
- Incident response support (DLP, account misuse, access anomalies)  
- DoD 8570 / 8140–aligned security engineering tasks  
- RMF, audit evidence capture, and control validation

---

# 🧰 Skills & Technologies

### **Security**
- SIEM (Splunk, Elastic, Wazuh)  
- Windows Security / Kerberos / NTLM  
- Incident Response & Triage  
- Vulnerability Management (ACAS/Tenable)  
- STIG compliance / RMF  
- Identity & Access Management (IAM)

### **Tools & Languages**
- PowerShell  
- Python  
- Bash  
- Wireshark  
- Nmap  
- Sysmon  
- Git/GitHub  
- AWS / Azure (Foundational Security)

---

# 🎯 Current Goals
- Microsoft **AZ-500** (in progress)  
- Expand SOC automation scripts (Python + PowerShell)  
- Build and publish additional detection engineering lab content  
- Prepare for long-term achievement of **CISSP**  

---

# 📫 Contact  
If you're a recruiter, SOC manager, or security leader and would like to connect:

**LinkedIn:** https://www.linkedin.com/in/zachary-hanselman/  
**GitHub:** https://github.com/DigitalBulwark-z8586

---

Thank you for viewing my portfolio!
