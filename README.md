# Cybersecurity Project Portfolio

**Seerat Fatima** | [LinkedIn](https://www.linkedin.com/in/seerat-fatima-cyb/) | [Email](mailto:seeratfatima2104@gmail.com)

Welcome to my hands-on cybersecurity portfolio. This repository serves as an index for my practical labs and projects, demonstrating skills in penetration testing, vulnerability exploitation, and incident response.

---

## Overview

This portfolio contains analysis and documentation for simulations performed in controlled lab environments. Each project focuses on understanding attack methodologies to improve defensive strategies.

---

## Penetration Testing Labs

### [Lab 1: Samba Enumeration & Privilege Escalation](https://github.com/seerat-fatima21/Samba-Exp)
- **Objective:** Exploit a critical Samba vulnerability (CVE-2007-2447).
- **Key Steps:** Service enumeration with `enum4linux`, exploitation with `Metasploit`, post-exploitation activities, and password cracking.
- **Result:** Achieved remote code execution with root privileges.

### [Lab 2: SSH Access & Kernel Exploitation](https://github.com/seerat-fatima21/SSH-exp)
- **Objective:** Gain SSH access and perform local privilege escalation.
- **Key Steps:** SSH login with compromised credentials, kernel vulnerability (CVE-2009-1185) exploitation.
- **Result:** Successfully escalated privileges to root.

### [Lab 3: MySQL to Web Shell](https://github.com/seerat-fatima21/mysql-exp)
- **Objective:** Achieve remote code execution via a MySQL service.
- **Key Steps:** Brute-force with `Hydra`, hash cracking with `John the Ripper`, web shell upload.
- **Result:** Gained RCE and performed data exfiltration.

### [Lab 4: vsFTPd 2.3.4 Backdoor Exploitation](https://github.com/seerat-fatima21/ftp-exp)
- **Objective:** Exploit a backdoor in a vulnerable FTP service.
- **Key Steps:** Service discovery with `Nmap`, exploitation with `Metasploit`.
- **Result:** Obtained a reverse shell.

---

### [Lab 5: Telnet Access & Post-Exploitation](https://github.com/seerat-fatima21/Telnet-Exp)
- **Objective:** Gain initial access via Telnet and perform comprehensive post-exploitation.
- **Key Steps:** Gained access with default credentials (`msfadmin:msfadmin`), leveraged `sudo` rights for immediate privilege escalation to root, extracted and cracked password hashes with `John the Ripper`, and established persistence via a new privileged user.
- **Result:** Full root compromise, credential harvesting, and guaranteed backdoor access.
- **Vulnerabilities:** Default credentials, excessive sudo privileges.

---


## Incident Response & Digital Forensics

### [Lab 1: Incident Response Journal: DFIR Case Studies](https://github.com/seerat-fatima21/DFIR-Case-Studies)
- **Objective:** Analyze and document security incidents using the 5 W's framework.
- **Cases:** Ransomware Attack, Malware Infection, Data Breach.
- **Key Skills:** Root cause analysis, containment strategies, mitigation recommendations.

---


### [Lab 2: Internal Data Leak Case Study](https://github.com/seerat-fatima21/Internal-Data-Leak-Case-study)

- **Objective:** Simulate and analyze a data leak caused by misconfigured sharing permissions.
- **Incident Summary:** A sales representative accidentally shared an internal-only folder link with a business partner, exposing sensitive product and customer data publicly.
- **Key Steps:** Applied the 5 W's framework (What, When, Where, Who, Why); assessed misconfiguration against NIST SP 800-53 AC-6 (Least Privilege).
- **Result:** Identified excessive access, recommended access restrictions, RBAC implementation, external sharing prevention, and regular access audits.
- **Key Skills:** Access control analysis, incident response, NIST framework application, DFIR principles.

---


## Technical Skills

- **Tools:** Metasploit, Nmap, Wireshark, John the Ripper, Burp Suite, Splunk, enum4linux
- **Platforms:** Kali Linux, Metasploitable2
- **Concepts:** Penetration Testing, Vulnerability Assessment, Digital Forensics, Incident Response (DFIR)

---

## Contact

- **LinkedIn:** [Seerat Fatima](https://www.linkedin.com/in/seerat-fatima-cyb/)
- **Email:** seeratfatima2104@gmail.com
- **GitHub:** [seerat-fatima21](https://github.com/seerat-fatima21)

---
