# Cybersecurity Vulnerability Assessment & Penetration Testing Project

## Project Title
Cybersecurity Practical Assessment using Kali Linux, Nessus Essentials, and Metasploitable 2

---

## Student Information

- Name: Md Fardin Hossain
- Student ID: 2023100000569
- Batch: 14
- Instructor: Rashadul Islam

---

## Project Overview

This project demonstrates practical Vulnerability Assessment (VA) and Penetration Testing (PT) techniques using Kali Linux and Metasploitable 2 in a controlled lab environment.

The main objective of this project was to identify security vulnerabilities using Nessus Essentials and exploit selected vulnerabilities using Metasploit Framework.

---

## Lab Environment

### Attacker Machine
- Kali Linux

### Target Machine
- Metasploitable 2

### Network Setup
- Host-Only Network

### Tools Used
- Nessus Essentials
- Metasploit Framework
- Nmap
- Linux Terminal Commands

---

## Target Information

- Target IP: 192.168.242.129
- Kali Linux IP: 192.168.242.128

---

## Tasks Completed

### Section A — Vulnerability Assessment
- Configured and executed Nessus scan
- Analyzed Critical and Medium vulnerabilities
- Identified open ports and services
- Documented vulnerability findings

### Section B — Penetration Testing
- Exploited vsftpd 2.3.4 backdoor vulnerability
- Gained remote shell access using Metasploit
- Executed post-exploitation commands
- Prepared penetration testing report

---

## Important Vulnerabilities Identified

### Critical Vulnerability
- Bind Shell Backdoor Detection
- CVSS Score: 9.8
- Port: 1524/tcp

### Medium Vulnerability
- Unencrypted Telnet Server
- CVSS Score: 6.5
- Port: 23/tcp

---

## Exploitation Summary

The vsftpd 2.3.4 backdoor vulnerability was successfully exploited using Metasploit Framework.

Successful shell access was obtained on the target system with root privileges.

Commands executed:
- whoami
- uname -a
- id

---

## Screenshots Included

- va1_scan_config.png
- va1_scan_summary.png
- va2_critical_finding.png
- va2_medium_finding.png
- pt1_exploit_result.png
- pt1_post_commands.png

---

## Learning Outcomes

Through this project, practical experience was gained in:
- Vulnerability scanning
- Risk analysis
- Exploitation techniques
- Linux command usage
- Penetration testing methodology
- Security reporting

---

## Repository Structure

screenshots/
├── va1_scan_config.png
├── va1_scan_summary.png
├── va2_critical_finding.png
├── va2_medium_finding.png
├── pt1_exploit_result.png
└── pt1_post_commands.png

CyberSec_VA_PT_Assessment_v2.docx
README.md

---

## Conclusion

This project successfully demonstrated the process of identifying and exploiting vulnerabilities in a controlled cybersecurity lab environment. Proper patching, service hardening, and secure configurations are necessary to prevent such attacks in real-world systems.
