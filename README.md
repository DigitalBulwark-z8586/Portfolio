# Zachary Hanselman – Portfolio  
**Cybersecurity | SOC Analyst | Blue Team Automation**

Welcome to my personal portfolio showcasing projects I’ve built to support security operations, incident response, and home-lab automation.  
With a background in business process analysis and risk management, and an active Secret clearance, I’m transitioning into SOC/Network Security with hands-on tooling, scripting, and threat-detection artifacts.

---

## 📋 Table of Contents  
1. [Suspicious Process Snapshot (PowerShell)](#1-suspicious-process-snapshot-powershell)  
2. [Home SOC Lab – Hybrid AD + SIEM Architecture](#2-home-soc-lab–hybrid-ad-+-siem-architecture)  
3. [Network Traffic Analyzer – Python Script](#3-network-traffic-analyzer–python-script)  
4. [Professional Background & Skills](#4-professional-background-&-skills)  
5. [Contact & LinkedIn](#5-contact-&-linkedin)

---

## 1️⃣ Suspicious Process Snapshot (PowerShell)  
**Windows Endpoint Triage Tool | SOC & Incident Response | PowerShell Automation**  
Developed a PowerShell-based triage utility designed to provide rapid situational awareness during SOC investigations. The script captures running processes, parent-child relationships, command-lines, and optional network connections — including built-in heuristics to flag suspicious behavior.

### ▶️ Key Features  
- Enumerates processes (Name, PID, ParentPID, Path, CmdLine)  
- Optional network connection mapping per process (IP:Port)  
- Flags suspicious activity like:
  - PowerShell/CMD using encoded or web-download commands  
  - Execution from Temp/Downloads or user cache folders  
  - Shell processes making outbound connections  
  - Missing executable path anomalies  
- Outputs include `IsSuspicious` + `SuspiciousReason`  
- Export to CSV or JSON for investigation/documentation  

### 💼 Use Cases  
Ideal for:
- Tier 1 triage of AV/EDR alerts  
- Endpoint investigations during incident response  
- Home-lab blue-team practice  
- Rapid host state capture before isolation  

### 🛠 Skills Leveraged  
PowerShell • Incident Response • Process & Network Triage • Threat Detection • Windows Internals • Automation  

### 🔗 Repository  
[GitHub – Suspicious_Process](https://github.com/DigitalBulwark-z8586/Suspicious_Process)

---

## 2️⃣ Home SOC Lab – Hybrid AD + SIEM Architecture  
**Hybrid Infrastructure • AWS EC2 • Windows Server 2022 • SIEM Integration**  
Built a home SOC lab combining on-premise infrastructure with cloud-based elements to simulate a realistic enterprise environment. Features include:

- A Windows Server 2022 Domain Controller on-prem  
- A cloud-hosted Domain Controller in AWS EC2  
- Integration with Splunk Enterprise for real-time log ingestion and security monitoring  
- Network traffic analyzer, Sysmon, and syslog forwarding  
- Visibility into DNS/ICMP, geolocation lookup, and live threat detection  

Prepared as a showcase for SOC Tier 1 Analyst roles and portfolio review.  
(*Details and scripts available in the lab’s GitHub section.*)

---

## 3️⃣ Network Traffic Analyzer – Python Script  
**Python • Pcap Parsing • DNS/ICMP Monitoring • GeoIP Lookup**  
Developed a Python tool to capture and analyze network traffic in a home lab environment. Key capabilities:

- Captures live network traffic (pcap) and parses DNS/ICMP flows  
- Logs output in JSON/CSV for ingest into SIEM (Splunk)  
- Includes GeoIP lookup to convert IP addresses into geographic locations  
- Configured for seamless integration with the home SOC lab stack  

Supports elevated learning in network-based detection and monitoring — core for SOC Tier 1 / Tier 2 roles.

---

## 4️⃣ Professional Background & Skills  
**Experience Highlights:**  
- Tier II Help Desk Support Specialist at Ka'ala Systems (U.S. Air Force contract) – network accounts, print-server troubleshooting, Trusted Agent Security Manager  
- Risk Management Analyst at USAA – enterprise risk workflows  
- Business Process Analyst at Wells Fargo – process redesign & automation  

**Certifications & Education:**  
- CompTIA Security+ (active)  
- Working toward: CCNA, CySA+ (Objective 1.2 in progress)  
- BBA Computer Information Systems – Information Security & Assurance (Texas A&M University San Antonio)  

**Core Technical Skills:**  
- PowerShell, Python, Splunk, AWS EC2, Windows Server 2022  
- SIEM log ingestion, network traffic analysis, process monitoring  
- Threat detection, incident response, SOC analyst tooling  

---

## 5️⃣ Contact & LinkedIn  
📧 Email – [your email]  
🔗 LinkedIn – [Your LinkedIn Profile]  

Thank you for reviewing my portfolio. I’m actively seeking SOC/Network Security roles and eager to bring automation and blue-team skills to a dynamic team.  

---

