# Penetration Test Engagement – Internal Lab Environment

##  Engagement Overview
This repository contains a **sanitized summary and deliverables** from a penetration testing engagement conducted against a Linux-based web application server within a controlled internal network.

The assessment focused on identifying exploitable vulnerabilities, validating impact through controlled exploitation, and providing actionable remediation guidance.

---

##   Scope
- Target: Linux Web Application Server  
- Network: Internal Lab Segment (172.20.10.0/24)  
- Applications: WordPress, phpMyAdmin  

---

##   Methodology
Testing followed established practices aligned with:
- **PTES (Penetration Testing Execution Standard)**  
- **OWASP Testing Guide**

Phases:
- Reconnaissance  
- Enumeration  
- Vulnerability Analysis  
- Exploitation  
- Post-Exploitation  
- Reporting  

---

##   Tooling
- arp-scan  
- Nmap  
- FTP  
- SMBClient  
- DirBuster  
- WPScan  
- Hydra  
- ExploitDB (searchsploit)  
- Metasploit (msfconsole)  
- Meterpreter  
- phpMyAdmin  
- Web Browser  
- Linux CLI Tools  
- Kali Linux  

---

##   Key Risk Areas
- Weak authentication controls  
- Misconfigured network services (FTP/SMB)  
- Web application access control weaknesses  
- Exposure leading to Remote Code Execution (RCE)  
- Privilege escalation to root  

---

##  Risk Summary
| Severity | Count |
|----------|------|
| Critical | 5    |
| High     | 3    |

---

##   Ethics & Disclosure
All testing was performed in a **controlled lab environment** with authorization.  
Sensitive details have been **sanitized** for public sharing.

---

##   Disclaimer
This repository is intended for **educational and portfolio purposes only**.  
Do not replicate these techniques on systems without explicit permission.

---

##   Author
**Ayisha Minha**  
Cybersecurity Student
