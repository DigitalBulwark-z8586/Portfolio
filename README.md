Zachary Hanselman – Portfolio

Cybersecurity | SOC Analyst | Blue Team Automation | Incident Response

Welcome to my portfolio showcasing hands-on cybersecurity projects built to strengthen SOC analysis, threat detection, and endpoint triage capabilities. This collection demonstrates practical PowerShell/Python scripting, SIEM integration, hybrid infrastructure design, and blue-team automation.

📋 Table of Contents
#	Project Name & Repository URL
1	Suspicious Process Snapshot (PowerShell)	https://github.com/DigitalBulwark-z8586/Suspicious_Process

2	Event Log Triage Tool (PowerShell)	https://github.com/DigitalBulwark-z8586/EventLog_Triage1

3	Phishing Email Analyzer (Python)	https://github.com/DigitalBulwark-z8586/Email_Analyzer

4	Home SOC Lab – Hybrid AD + SIEM Architecture	Under Construction
5	Network Traffic Analyzer – Python	Under Construction
6	Professional Background & Skills	See Section Below
7	Contact & LinkedIn	See Section Below

1️⃣ Suspicious Process Snapshot (PowerShell)

Windows Endpoint Triage Tool | SOC & IR | Blue Team Automation

A PowerShell-based process triage script designed to support Tier 1 SOC analysts during active investigations. The tool captures real-time process activity, parent-child relationships, command-line usage, and optional network connections. Built-in heuristics help identify suspicious behavior such as encoded PowerShell, execution from Temp/Downloads, or shell processes making outbound connections.

🔧 Key Features

Process enumeration: Name, PID, ParentPID, Path, CmdLine

Optional network mapping per process

Flags suspicious behavior

CSV/JSON export for IR case documentation

Useful for malware triage and endpoint investigations

🔗 Repository

https://github.com/DigitalBulwark-z8586/Suspicious_Process

2️⃣ Event Log Triage Tool (PowerShell)

Windows Security Log Analysis | Incident Response | Automation

A reusable PowerShell module designed to pull, parse, and enrich Windows Security Event Logs for SOC and Incident Response. Helps analysts quickly extract key details from authentication events, account changes, and security logs critical during an investigation.

🔍 What This Script Does

Parses key Windows Security log events (4624, 4625, 4648, and more)

Extracts:

Logon type

Logon process

Network source info (IP, Workstation Name)

Account and user details

Converts raw event logs into analyst-friendly CSV/JSON outputs

Includes reusable helper functions and consistent PowerShell structure

Supports rapid triage, brute-force detection, and authentication analysis

🔗 Repository

https://github.com/DigitalBulwark-z8586/EventLog_Triage1

3️⃣ Phishing Email Analyzer (Python)

SOC Triage Tool | Python Automation | Email Forensics

🔗 Repository

https://github.com/DigitalBulwark-z8586/Email_Analyzer

🔎 Overview

The Phishing Email Analyzer is a Python-based SOC tool designed to quickly triage suspicious emails by parsing .eml files and extracting forensic data. It automates the first-level analysis typically performed by Tier 1 SOC Analysts, including sender verification, SPF/DKIM/DMARC evaluation, and URL risk assessment.

🛠️ What This Tool Does

Extracts and analyzes key email headers

Evaluates sender authenticity

Parses SPF, DKIM, and DMARC results

Extracts URLs from the email body

Flags suspicious domains, TLDs, and raw IP URLs

Handles Windows console Unicode issues safely

🧠 Skills Demonstrated

Python automation & parsing

Email header forensics

SPF, DKIM, DMARC trust-model understanding

Phishing detection logic

SOC Tier 1 workflow automation

Safe handling of user data

🧪 Use Case

A user reports a suspicious email → You download the .eml file → Run it through the analyzer → Review sender and URL findings → Escalate or close based on risk.

📈 Future Enhancements

JSON/CSV export for SIEM ingestion

WHOIS domain age lookup

Integration with VirusTotal / AbuseIPDB

GUI interface

4️⃣ Home SOC Lab – Hybrid AD + SIEM Architecture

Hybrid Infra • Splunk SIEM • AWS EC2 • Windows Server 2022

Designed a full SOC home lab combining on-premises Active Directory with a cloud-based domain controller, tied into Splunk Enterprise for security log ingestion. This lab simulates enterprise SOC workflows and detection engineering practices.

🧩 Lab Components

Windows Server 2022 Domain Controller (on-prem)

AWS EC2 cloud-based DC (Hybrid AD)

Splunk Enterprise SIEM on AWS

Sysmon + Winlogbeat + Universal Forwarders

DNS/ICMP monitoring

Custom detection rules mapped to MITRE ATT&CK

🎓 Goals

Build a realistic SOC Analyst environment

Practice detection engineering

Deploy and test blue-team tools in a controlled environment

🔗 Repository

Under Construction

5️⃣ Network Traffic Analyzer – Python

PCAP Parsing | DNS/ICMP Logging | GeoIP Lookup | SIEM Integration

Python-based network traffic monitoring tool created to support the Home SOC Lab. Captures live network data and exports logs to JSON/CSV for ingestion into Splunk or other SIEM platforms.

🔧 Features

Live DNS & ICMP flow logging
GeoIP lookup for destination IPs
CSV/JSON export
Planned syslog forwarding

🔗 Repository

Under Construction

6️⃣ Professional Background & Skills
👨‍💻 Experience
Contact me below for experience

🎓 Certifications

CompTIA Security+
CompTIA CySA+
Studying: Microsoft AZ-500

🧰 Technical Skills

PowerShell • Python • Splunk • SIEM Engineering • Windows Internals • Network Analysis • Hybrid AD • Detection Engineering • Incident Response

7️⃣ Contact & LinkedIn

📧 Email: bulwarkdigital47@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/digitalbulwark-z
