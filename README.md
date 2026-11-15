# Hi, I'm Vishal Chirra 👋

### 🛡️ CEH v13 Certified | Aspiring SOC Analyst | Blue Team & Threat Detection

I'm a cybersecurity enthusiast focused on **Security Operations (SOC), Blue Teaming, Threat Detection, and Incident Response**. I enjoy analyzing security logs, investigating suspicious activity, identifying indicators of compromise (IOCs), and building practical cybersecurity projects.

I'm currently strengthening my SOC Analyst L1 skills through hands-on labs, security investigations, and project development.

---

## 🎯 Career Focus

- Security Operations Center (SOC) — L1
- Security Alert Triage & Incident Investigation
- Threat Detection & Log Analysis
- Network Traffic Analysis
- Phishing Investigation & IOC Analysis
- Incident Response & Threat Hunting

## 🧰 Technical Skills

- **SIEM:** Splunk fundamentals, security log analysis
- **Query Language:** KQL fundamentals
- **Network Analysis:** Wireshark, packet analysis
- **Endpoint Security:** EDR concepts, alert triage, containment
- **Threat Intelligence:** IOC analysis, AbuseIPDB, MITRE ATT&CK
- **Security Concepts:** SSH security, brute-force detection, incident response
- **Operating Systems:** Windows, Linux, Kali Linux, Ubuntu
- **Programming & Tools:** Python, Git, GitHub, VirtualBox
- **Backend & Database:** Flask, SQLite, REST APIs

## 📜 Certifications & Training

- **Certified Ethical Hacker (CEH v13)** — EC-Council
- **SOC Analyst Learning Path** — LetsDefend
- **Pre Security Learning Path** — TryHackMe
- Hands-on cybersecurity labs and security investigations

## 🚀 Featured Projects

### 🐝 HoneyShield — Intelligent Honeypot System for Cyberattack Analysis

A honeypot-based cybersecurity monitoring and analysis system that captures controlled SSH activity, analyzes suspicious behavior, and presents security alerts through a SOC-style dashboard.

**Key Features**
- Deployed Cowrie SSH honeypot in a VirtualBox laboratory using Kali Linux and Ubuntu
- Built a Python-based log parsing and rule-based detection pipeline
- Detects successful/failed SSH logins, suspicious commands, and possible brute-force activity
- Maps relevant behaviors to MITRE ATT&CK techniques
- Integrates AbuseIPDB for threat-intelligence enrichment
- Stores attack events and alerts in SQLite
- Provides Flask REST APIs and a SOC-style dashboard

**Tech Stack:** Python, Kali Linux, Ubuntu, Cowrie, Flask, SQLite, AbuseIPDB, MITRE ATT&CK, VirtualBox

🔗 **[Explore HoneyShield on GitHub →](https://github.com/VISHALCHIRRA/HoneyShield)**

---

### 🛡️ Home SOC Lab — Wazuh SIEM & Blue Team Monitoring

A hands-on SOC environment built to practice **security monitoring, alert detection, log analysis, and incident investigation** in an isolated virtual enterprise network.

**Key Features**
- Built a virtual SOC environment using **Wazuh, pfSense, Windows Server 2022, Windows 10, Kali Linux, Sysmon, CrowdSec, and VirtualBox**
- Configured **Windows Server 2022 Active Directory** with the `corp.soclab.test` domain
- Deployed **Wazuh SIEM** for centralized security monitoring and alert investigation
- Integrated **pfSense firewall logs with Wazuh over UDP/514**
- Developed a **custom pfSense decoder** and Wazuh detection rule `100100` for blocked network traffic
- Generated and investigated **4 simulated ICMP firewall-block events**, producing 4 Wazuh Level 5 alerts
- Investigated a **FodHelper UAC-bypass detection** using Wazuh and Sysmon telemetry
- Assessed the FodHelper activity as **likely benign / false positive** based on available endpoint evidence
- Documented SOC investigation methodology, evidence, findings, and verdicts

**SOC Cases**
- **Case 01:** pfSense Blocked ICMP Traffic — Wazuh Rule `100100`
- **Case 02:** FodHelper UAC Bypass Detection — Wazuh Rule `92055`, MITRE `T1548.002`

**Tech Stack:** Wazuh, pfSense, Sysmon, Windows Server, Active Directory, Windows 10, Kali Linux, CrowdSec, VirtualBox

🔗 **[Explore Home SOC Lab on GitHub →](https://github.com/VISHALCHIRRA/Home-SOC-Lab)**

**Tech Stack:** Wazuh, pfSense, Sysmon, Windows Server, Active Directory, Windows 10, Kali Linux, CrowdSec, VirtualBox

## 📚 Currently Learning

- KQL for security monitoring and threat hunting
- Windows Event Logs and Sysmon
- SIEM alert investigation and incident documentation
- Network traffic analysis
- Incident response and Blue Team workflows

## 🔎 My Approach

I believe effective cybersecurity investigation requires understanding **why an alert occurred, what evidence supports it, how to assess its risk, and what response actions are appropriate**.

I focus on hands-on learning, documenting technical work, and building projects that connect cybersecurity concepts with practical implementation.

## 🤝 Let's Connect

- **GitHub:** [VISHALCHIRRA](https://github.com/VISHALCHIRRA)
- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/chirravishal27)

---

⭐ Thanks for visiting my profile! I'm continuously learning, building, and preparing for entry-level cybersecurity opportunities.

