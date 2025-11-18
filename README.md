# 🚀 Zachary Hanselman's Cybersecurity & Automation Portfolio

Welcome to my cybersecurity, automation, and homelab engineering portfolio.  
I specialize in **SOC operations, detection engineering, Windows security monitoring, PowerShell automation, cloud security, and DoD-aligned cyber practices.**

This portfolio contains hands-on projects designed to demonstrate the technical skills I use daily as a **Cybersecurity Engineer** supporting the Defense Health Agency (DHA), as well as the blue-team and automation capabilities I continue to refine through my home SOC lab.

---

## 🛡️ Suspicious Process Snapshot (PowerShell)
**Windows Endpoint Triage Tool | SOC & Incident Response | PowerShell Automation**


This project is a PowerShell-based triage utility designed to provide quick situational awareness during SOC investigations and Incident Response. The script performs a real-time snapshot of running processes, parent-child relationships, command-line arguments, and optional network connections — all essential data points for quickly validating suspicious activity on a Windows host.

Repo: https://github.com/DigitalBulwark-z8586/Suspicious_Process

---

### 🎯 Objective
Modern SOC environments frequently deal with:
- AV alerts  
- Suspicious user activity  
- Potential malware execution  
- Irregular PowerShell/CMD behavior  
- Unknown outbound connections  

Tier 1 analysts must rapidly answer questions such as:
- *Is PowerShell running encoded commands?*  
- *Is something executing from Temp or Downloads?*  
- *Is a process unexpectedly making network connections?*  

This tool streamlines those checks without requiring an EDR platform, making it ideal for home labs, real-world SOC work, and blue-team training.

---

### 🔧 Key Features
- **Process Enumeration**
  - Process name, PID, Parent PID
  - Full command line
  - Executable path
  - Timestamp of capture

- **Network Connection Mapping** *(optional)*
  - Per-process remote IP:Port
  - Flags outbound activity

- **Suspicion-Based Heuristics**
  - PowerShell/CMD using encoded or web-download commands
  - Execution from user Temp, Downloads, or cache locations
  - Shell processes establishing outbound connections
  - Missing executable paths (non-system binaries)

- **Analyst-Friendly Outputs**
  - `IsSuspicious` flag
  - `SuspiciousReason` explanation
  - Export results to:
    - CSV (case documentation, Excel review)
    - JSON (automation/SIEM ingestion)

---

### 📦 Use Cases (SOC / IR Focus)
- Triage suspicious login or behavior alerts  
- Validate potential malware execution paths  
- Investigate PowerShell misuse / encoded commands  
- Rapid pre-isolation host review  
- Forensics-style host state capture  
- Home SOC lab simulations and training  

---

### 🚀 Example Usage

**Basic Run:**
```powershell
.\Get-SuspiciousProcessSnapshot.ps1 -IncludeNetConnections -ShowOnlySuspicious `
    -OutputCsv "C:\Logs\ProcessSnapshot.csv"

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
