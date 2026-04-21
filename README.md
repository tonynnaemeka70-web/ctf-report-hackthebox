Capture the Flag (CTF) Internship Report

This repository documents my cybersecurity internship assignment completed on HackTheBox. 

I successfully captured flags from three machines Meow, Fawn, and Dancing  each demonstrating common misconfigurations and vulnerabilities.  
The project showcases practical penetration testing methodology and clear documentation aimed at both technical and non‑technical audiences.



 Contents
- `Capture-the-Flag-Report.pdf`  Full internship report with methodology and findings  
- `/screenshots`  Supporting evidence of exploitation and flag retrieval  
- `/notes/methodology.md` → Step‑by‑step commands used during the assignment  



 Tools & Environment
- Operating System: Kali Linux (VMware Workstation)  
- Connection: HackTheBox VPN via OpenVPN  
- Tools Used:
  - Nmap → Port scanning & service enumeration  
  - FTP / SMBClient → Service exploitation  
  - Telnet → Direct shell access  
  - Standard Linux utilities → `ls`, `cat`, `get`  



 Key Findings
- Meow (Telnet)  No password required  Immediate root access  
- Fawn (FTP) Anonymous login enabled  Flag exposed  
- Dancing (SMB)  Misconfigured file shares → Sensitive data leaked  



 Lessons Learned
- Disable insecure services (Telnet, anonymous FTP)  
- Enforce strong authentication for all network services  
- Regularly audit file shares and permissions  
- Use vulnerability scanning tools to detect misconfigurations early  



 Why This Project Matters
 
This project demonstrates:
- Practical penetration testing methodology (reconnaissance, enumeration, exploitation, flag capture)  
- Ability to document findings clearly for both technical and non‑technical stakeholders  
- Awareness of real‑world risks from insecure defaults and misconfigurations  





This repository highlights my hands‑on cybersecurity skills and ability to communicate technical findings professionally.  
Pinned here to showcase my internship work and practical penetration testing experience.

