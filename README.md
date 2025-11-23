# Zachary Hanselman – Portfolio  
**Cybersecurity | SOC Analyst | Blue Team Automation | Incident Response**

Welcome to my portfolio showcasing hands-on cybersecurity projects built to strengthen SOC analysis, threat detection, and endpoint triage capabilities. This collection demonstrates practical PowerShell/Python scripting, SIEM integration, hybrid infrastructure design, and blue-team automation.

---

## 📋 Table of Contents  
1. [Suspicious Process Snapshot (PowerShell)](#1-suspicious-process-snapshot-powershell)  
2. [Event Log Triage Tool (PowerShell)](#2-event-log-triage-tool-powershell)  
3. [Home SOC Lab – Hybrid AD + SIEM Architecture](#3-home-soc-lab--hybrid-ad--siem-architecture)  
4. [Network Traffic Analyzer – Python](#4-network-traffic-analyzer--python)  
5. [Professional Background & Skills](#5-professional-background--skills)  
6. [Contact & LinkedIn](#6-contact--linkedin)

---

## 1️⃣ Suspicious Process Snapshot (PowerShell)  
**Windows Endpoint Triage Tool | SOC & IR | Blue Team Automation**

A PowerShell-based process triage script designed to support Tier 1 SOC analysts during active investigations. The tool captures real-time process activity, parent-child relationships, command-line usage, and optional network connections. Built-in heuristics help identify suspicious behavior such as encoded PowerShell, execution from Temp/Downloads, or shell processes making outbound connections.

### 🔧 Key Features  
- Process enumeration: Name, PID, ParentPID, Path, CmdLine  
- Optional network mapping per process  
- Flags suspicious behavior  
- CSV/JSON export for IR case documentation  
- Useful for malware triage and endpoint investigations  

### 🔗 Repository  
https://github.com/DigitalBulwark-z8586/Suspicious_Process

---

## 2️⃣ Event Log Triage Tool (PowerShell)  
**Windows Security Log Analysis | Incident Response | Automation**

A reusable PowerShell module designed to pull, parse, and enrich Windows Security Event Logs for SOC and Incident Response. Helps analysts quickly extract key details from authentication events, account changes, and security logs critical during an investigation.

### 🔍 What This Script Does  
- Parses key Windows Security log events (4624, 4625, 4648, and more)  
- Extracts:
  - Logon type  
  - Logon process  
  - Network source info (IP, Workstation Name)  
  - Account and user details  
- Converts raw event logs into analyst-friendly CSV/JSON outputs  
- Includes reusable helper functions and consistent PowerShell structure  
- Supports rapid triage, brute-force detection, and authentication analysis  

### 🛠 SOC Use Cases  
- Investigating failed logon attempts  
- Reviewing suspicious account activity  
- Analyzing remote authentication logs  
- Documenting findings for IR tickets  
- Feeding logs into Splunk or your home SIEM  

### 🔗 Repository  
https://github.com/DigitalBulwark-z8586/EventLog_Triage1

📧 Phishing Email Analyzer (Python)
Project Type: SOC Triage Tool • Python Automation • Email Forensics
Repository: https://github.com/DigitalBulwark-z8586/Email_Analyzer/blob/main/README.md
🔎 Overview

The Phishing Email Analyzer is a Python-based SOC tool designed to quickly triage suspicious emails by parsing .eml files and extracting forensic data. It automates the first-level analysis typically performed by Tier 1 SOC Analysts, including sender verification, SPF/DKIM/DMARC evaluation, and URL risk assessment.

This project demonstrates applied cybersecurity skills, Python scripting, and practical email forensics — all essential for SOC, ISSO, and Security Engineering roles.

🛠️ What This Tool Does

✔ Extracts and analyzes key email headers
✔ Evaluates sender authenticity (impersonation checks)
✔ Parses SPF, DKIM, and DMARC results
✔ Extracts URLs from the email body
✔ Flags suspicious domains, TLDs, and raw IP URLs
✔ Handles Windows console Unicode issues safely

🧠 Skills Demonstrated

Python automation & parsing
Email header forensics
SPF, DKIM, DMARC understanding
Malware/phishing URL triage
SOC Tier 1 investigation workflow
Safe handling of user data & PII redaction
Blue team analysis logic

🧪 Use Case
This tool replicates the real-world workflow of a Tier 1 Analyst validating whether an email should be escalated or closed.

Example SOC scenario:
A user reports a suspicious email → you download the .eml file → run it through this analyzer → gather sender and URL insights → decide whether to escalate to IR or block at the mail gateway.

📂 Repository Contents

email_analyzer.py – Main analyzer script
README.md – Full documentation and usage
Example .eml files (optional)
Safe-printing utility for Windows environments

📈 Future Enhancements

JSON/CSV export for SIEM ingestion
Domain age lookup (WHOIS)
VirusTotal / AbuseIPDB integration
GUI version for security analysts
Email attachment scanning (future module)

🧩 Project Impact

This project strengthens your cybersecurity portfolio by demonstrating:

Practical SOC automation
Real forensics concepts
Ability to build security tooling
Understanding of email authentication
Analytical problem-solving

It is a perfect highlight for roles including SOC Analyst, Cybersecurity Analyst, ISSO, and Detection Engineering positions.

---

## 3️⃣ Home SOC Lab – Hybrid AD + SIEM Architecture  
**Hybrid Infra • Splunk SIEM • AWS EC2 • Windows Server 2022**

Designed a full SOC home lab combining on-premises Active Directory with a cloud-based domain controller, tied into Splunk Enterprise for security log ingestion. This lab simulates enterprise SOC workflows and detection engineering practices.

### 🧩 Lab Components  
- Windows Server 2022 Domain Controller (on-prem)  
- AWS EC2 cloud-based DC (Hybrid AD)  
- Splunk Enterprise SIEM on AWS  
- Sysmon + Winlogbeat + Universal Forwarders  
- DNS/ICMP monitoring  
- Custom detection rules mapped to MITRE ATT&CK  

### 🎓 Goals  
- Build a realistic SOC Analyst environment  
- Practice detection engineering  
- Deploy and test Blue Team tools in a controlled environment  

---

### 🔗 Repository  
(Under Construction)

## 4️⃣ Network Traffic Analyzer – Python  
**PCAP Parsing | DNS/ICMP Logging | GeoIP Lookup | SIEM Integration**

Python-based network traffic monitoring tool created to support your Home SOC Lab. Captures live network data and exports logs to JSON/CSV for ingestion into Splunk or other SIEM platforms.

### 🔧 Features  
- Live DNS & ICMP flow logging  
- GeoIP lookup for destination IPs  
- CSV/JSON exports  
- Future support for syslog forwarding to SIEM  

### 🔗 Repository  
(Under Construction)

---

## 5️⃣ Professional Background & Skills  
**Experience:**  
- Cybersecurity Engineer (DHA Contract)  
- Risk Management Analyst – USAA
- Service Member - United States Army 
- Tier II Help Desk – Ka'ala Systems (USAF Contract)

**Certifications:**  
- CompTIA Security+
- CompTIA CYSA+
- Actively working toward:  Microsoft AZ-500  

**Technical Skills:**  
PowerShell • Python • Splunk • SIEM Engineering • Windows Internals • Network Analysis • Hybrid AD • Detection Engineering • Incident Response

---

## 6️⃣ Contact & LinkedIn  
📧 Email – bulwarkdigital47@gmail.com
🔗 LinkedIn – www.linkedin.com/in/digitalbulwark-z

Thank you for visiting my portfolio!  
I'm actively pursuing SOC Analyst / Security Operations / Cybersecurity Engineering/ISSO opportunities and continuously building tools to strengthen my defensive skill set.
