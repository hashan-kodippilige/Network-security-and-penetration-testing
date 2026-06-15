# 🔐 Network Security & Penetration Testing

<p align="center">
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/MITRE%20ATT%26CK-E22C2C?style=for-the-badge&logo=target&logoColor=white" />
</p>

> 🎓 Graduate-level network security portfolio covering vulnerability assessment, penetration testing, Active Directory administration, DNS security, web application testing, and cyber incident investigation — all performed in authorized lab environments.

---

## 📌 Overview

This repository documents hands-on offensive and defensive security work completed during **graduate-level Network Security coursework** at Minnesota State University Moorhead. It covers the full penetration testing lifecycle from reconnaissance to post-exploitation, alongside enterprise administration, incident response, and traffic forensics.

**Environment:** Windows Server 2022 | Kali Linux | Metasploitable | Oracle VirtualBox | Azure Lab

---

## 📋 Contents at a Glance

| # | Type | Title | Key Tools |
|---|------|-------|-----------|
| Lab 1 | 🔬 Lab | Software Vulnerabilities & Real-World Exploitation | MITRE CWE, ATT&CK |
| Lab 2 | 🔬 Lab | DNS Analysis & DNS Poisoning | NSLookup, Dig |
| Lab 3 | 🔬 Lab | Payload Deployment & Persistence | Metasploit, Cron |
| Lab 4 | 🔬 Lab | Web Application Vulnerability Testing | Burp Suite, DVWA |
| Project 1 | 🚀 Project | Active Directory Deployment & Administration | Windows Server 2022 |
| Project 2 | 🚀 Project | Metasploitable Exploitation Using Kali Linux | Nmap, Metasploit |
| Project 3 | 🚀 Project | Cyber Incident Investigation via Traffic Analysis | Wireshark, FTP Forensics |

---

## 🔬 Labs

### Lab 1 — Software Vulnerabilities & Real-World Exploitation

**Objective:** Research and analyze real-world exploitation of MITRE CWE Top 25 vulnerabilities.

| Topic | Details |
|-------|---------|
| CWE-352 | Cross-Site Request Forgery (CSRF) analysis |
| CWE-863 | Incorrect Authorization exploitation |
| Framework | MITRE ATT&CK technique mapping |
| Output | Security impact analysis and mitigation report |

**Skills:** Vulnerability Research · Threat Analysis · MITRE ATT&CK Mapping

---

### Lab 2 — DNS Analysis & DNS Poisoning

**Objective:** Analyze DNS resolution processes and demonstrate DNS poisoning concepts.

| Topic | Details |
|-------|---------|
| Tools | NSLookup, Dig utility |
| Analysis | DNS record types, forward/reverse resolution |
| Attack | DNS poisoning demonstration and defense |
| Output | DNS security assessment report |

**Skills:** DNS Troubleshooting · Network Analysis · DNS Security

---

### Lab 3 — Payload Deployment & Persistence

**Objective:** Deploy payloads using Metasploit and establish Linux persistence mechanisms.

| Topic | Details |
|-------|---------|
| Exploit | VSFTPD backdoor exploitation |
| Persistence | Cron job-based persistence on Linux |
| Framework | Metasploit Framework |
| Techniques | Post-exploitation activities and cleanup |

**MITRE Techniques:** T1059 (Command Shell) · T1053.003 (Cron) · T1190 (Exploit Public-Facing App)

**Skills:** Exploitation · Persistence Techniques · Linux Security

---

### Lab 4 — Web Application Vulnerability Testing

**Objective:** Perform web application security testing using Burp Suite against DVWA.

| Topic | Details |
|-------|---------|
| Tool | Burp Suite (proxy, interceptor, repeater) |
| Target | DVWA (Damn Vulnerable Web Application) |
| Tests | Authentication bypass, brute force, HTTP interception |
| Output | Web vulnerability assessment report |

**Skills:** Web Security Testing · HTTP Analysis · Proxy Configuration

---

## 🚀 Projects

### Project 1 — Active Directory Deployment & Administration

**Objective:** Deploy and administer an enterprise Active Directory environment from scratch.

| Component | Details |
|-----------|---------|
| Platform | Windows Server 2022 |
| Domain | academia.local |
| Structure | Domain Controller → OUs → Users & Groups |
| Tasks | AD DS installation, OU design, user provisioning, access control |

**Skills:** Identity Management · Enterprise Administration · Access Control · Domain Controller Promotion

---

### Project 2 — Metasploitable Exploitation Using Kali Linux

**Objective:** Conduct a full penetration test against Metasploitable from reconnaissance to exploitation.

#### Attack Chain

```
Reconnaissance        →   Nmap port & service scan
Service Enumeration   →   VSFTPD 2.3.4 identified
Exploitation          →   Metasploit VSFTPD backdoor module
Post-Exploitation     →   Shell access & system discovery
```

#### MITRE ATT&CK Mapping

| Tactic | Technique ID | Technique |
|--------|-------------|-----------|
| Discovery | T1046 | Network Service Scanning |
| Initial Access | T1190 | Exploit Public-Facing Application |
| Execution | T1059 | Command and Scripting Interpreter |
| Discovery | T1082 | System Information Discovery |

**Skills:** Penetration Testing · Nmap · Metasploit · Threat Emulation · Report Writing

---

### Project 3 — Cyber Incident Investigation via Network Traffic Analysis

**Objective:** Investigate a simulated cyber incident using packet capture analysis and reconstruct the attack timeline.

| Phase | Activity |
|-------|---------|
| Collection | FTP log and PCAP file acquisition |
| Analysis | Wireshark deep packet inspection |
| Reconstruction | Attack timeline mapping |
| Reporting | Executive summary + technical findings + recommendations |

**Investigation Findings:**
- Identified unauthorized network reconnaissance activity
- Reconstructed attacker's lateral movement via service enumeration
- Mapped attack stages to MITRE ATT&CK framework
- Produced executive summary and full incident report

**Skills:** Digital Forensics · Incident Response · Wireshark · Timeline Reconstruction · Executive Reporting

---

## 📁 Repository Contents

```
📦 Network-security-and-penetration-testing
├── 📄 README.md
├── 📋 Network Security - Lab 1 - Hashan Kodippilige.pdf
├── 📋 Network Security - Lab 2 - Hashan Kodippilige.pdf
├── 📋 Network Security - Lab 3 - Hashan Kodippilige.pdf
├── 📋 Network Security - Lab 4 - Hashan Kodippilige.pdf
├── 📋 Network Security - Project 1 - Hashan Kodippilige.pdf
├── 📋 Network Security_Project 1 ppt_Hashan Kodippilige.pdf
├── 📋 Network Security - Project 2 - Hashan Kodippilige.pdf
├── 📋 Network Security_Project 2 ppt_Hashan Kodippilige.pdf
├── 📋 Executive Summary_Project 3 - Hashan Kodippilige.pdf
└── 📋 Network Security_project 3 ppt_Hashan Kodippilige.pdf
```

---

## 🧠 Skills Demonstrated

`Penetration Testing` `Metasploit Framework` `Nmap` `Burp Suite` `Wireshark` `Active Directory` `DNS Security` `DNS Poisoning` `MITRE ATT&CK` `MITRE CWE` `Incident Response` `Digital Forensics` `Web Application Security` `DVWA` `Kali Linux` `Windows Server 2022` `Network Reconnaissance` `Vulnerability Assessment` `Security Reporting`

---

## 💡 Real-World Relevance

This portfolio maps directly to industry roles including:
- **SOC Analyst** — incident investigation, traffic analysis, threat mapping
- **Penetration Tester** — full pentest lifecycle from recon to reporting
- **Security Engineer** — AD administration, DNS hardening, web security
- **PhD Research** — offensive/defensive security methodology, empirical lab-based research

---

## ⚠️ Disclaimer

All activities were conducted in **authorized, isolated educational lab environments** for academic cybersecurity training and research purposes only. No real systems were targeted.

---

## 👤 Author

**Hashan Kodippilige**  
M.S. Cybersecurity — Minnesota State University Moorhead  
📧 hashansharindu@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hashankodippilige/)  
🐙 [GitHub](https://github.com/hashan-kodippilige)
