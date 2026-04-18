# Ahmed Hassan
### Cybersecurity Specialist · Penetration Tester · Security Researcher

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-hassan-069b83379)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmedelfokery@gmail.com)
[![HTB](https://img.shields.io/badge/Hack%20The%20Box-Profile-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://www.hackthebox.com)
[![Medium](https://img.shields.io/badge/Medium-Articles-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@ahmedhassanf099)

</div>

---

## About Me

Offensive security professional with hands-on experience in VAPT,
Active Directory exploitation, and network penetration testing.
Background spans IT operations and Cybersecurity instruction —
I've both broken systems and taught others how to defend them.
Pursuing a Master's in Cybersecurity. Active in bug bounty and Security research.

---

## Security Research & Penetration Testing

> Real-world engagements and controlled-environment simulations demonstrating full attack chains — from reconnaissance to exploitation to reporting.

---

### 🔴 Internal Active Directory Penetration Test ( REPORT )

[![Repo](https://img.shields.io/badge/GitHub-View%20Report-181717?style=flat-square&logo=github)](https://github.com/Ahmedhassanelf/-Internal-Active-Directory-Penetration-Test-Report)

Full-scale enterprise AD compromise simulation — from zero access to full domain takeover, documented as a professional pentest report.

**Attack Chain:**
```
Initial Access          Privilege Escalation       Full Compromise
AS-REP Roasting   →    Kerberoasting          →   Domain Admin + DB Takeover
(No preauth users)      (Service ticket crack)      (Full lateral movement)
```

**Domains Covered:** Active Directory Security · Kerberos Exploitation · Post-Exploitation · Lateral Movement

---

### 🐛 Subdomain Takeover – Credit Karma (Bug Bounty) ( REPORT )

[![Repo](https://img.shields.io/badge/GitHub-View%20Report-181717?style=flat-square&logo=github)](https://github.com/Ahmedhassanelf/Subdomain-Takeover-Vulnerability-Report)

Identified a real-world subdomain takeover vulnerability via a dangling CNAME record pointing to an unclaimed third-party service — submitted as part of Credit Karma's bug bounty program.

**Impact:** Potential phishing infrastructure, credential harvesting, brand abuse

**Domains Covered:** DNS Security · Asset Enumeration · Bug Bounty Methodology · Web Security Impact Analysis

---

## Projects

---

### 🔐 Kerberoasting & AS-REP Roasting Lab (Active Directory)

[![Repo](https://img.shields.io/badge/GitHub-View%20Project-181717?style=flat-square&logo=github)](https://github.com/Ahmedhassanelf/my-projects-Kerberoasting-Attack)

Built a fully functional multi-machine AD lab environment (Domain Controller + Domain User + Attacker) and executed both Kerberoasting and AS-REP Roasting attacks end-to-end — including ticket extraction, offline cracking, and defense recommendations.

**Lab Components:** DC · Victim Machine · Kali Attacker  
**Key Skills:** AD Enumeration · Kerberos Ticket Abuse · Hashcat Cracking · Mitigation Techniques

---

### 🏦 AD-Integrated Banking Access Control System

[![Repo](https://img.shields.io/badge/GitHub-View%20Project-181717?style=flat-square&logo=github)](https://github.com/Ahmedhassanelf/AD-Banking-Access-Control)

Python application simulating enterprise IAM in a banking environment — integrating Active Directory authentication (Kerberos/GSSAPI), LDAP group queries, and role-based folder access control (RBAC).

**Architecture:**
```
User Login  →  Kerberos Auth (GSSAPI)  →  LDAP memberOf Query  →  Folder Access by Role
                                                                  ├── Admins   → C:\Banking\Administrator
                                                                  ├── Employees → C:\Banking\Employees
                                                                  └── Customers → C:\Banking\customers
```

**Key Concepts:** IAM · RBAC · Least Privilege · Defense in Depth · AD Tiering Model

---

## Writeups & Articles

---

### 📝 Breaking Firewall Trust – Bypassing IDS/IPS to Expose a Hidden Database Service

[![Medium](https://img.shields.io/badge/Read%20on-Medium-000000?style=flat-square&logo=medium)](https://medium.com/@ahmedhassanf099/breaking-firewall-trust-bypassing-ids-ips-to-expose-a-hidden-database-service-c3180aee074c)
[![Repo](https://img.shields.io/badge/GitHub-View%20Repo-181717?style=flat-square&logo=github)](https://github.com/Ahmedhassanelf/-Breaking-Firewall-Trust-Bypassing-IDS-IPS-to-Expose-a-Hidden-Database-Service)

Hack The Box writeup documenting a complete IDS/IPS bypass chain to enumerate and expose an internal database service that was hidden behind firewall rules.

**Skills:** Firewall Evasion · IDS/IPS Bypass · Internal Service Enumeration · Traffic Analysis

---

## Technical Skills

### Offensive Security

`Web Application Pentesting` `Active Directory Attacks` `Privilege Escalation` `Post-Exploitation`
`Vulnerability Assessment` `Reconnaissance & OSINT` `Authentication Security Testing` `OWASP Top 10`

### Network & Infrastructure

`Network Scanning & Enumeration` `TCP/IP` `Firewall & IDS/IPS Evasion` `Internal Pivoting`

### Tools

<div align="center">

| Category | Tools |
|---|---|
| **Web** | Burp Suite · OWASP ZAP · SQLmap · XSStrike · ffuf · Gobuster · dirsearch |
| **Recon** | Nmap · Amass · Subfinder · theHarvester |
| **AD / Windows** | BloodHound · CrackMapExec · Mimikatz · Impacket |
| **Cracking** | Hashcat · John the Ripper |
| **Frameworks** | Metasploit |
| **Analysis** | Wireshark |

</div>

### Scripting & Automation

`Python` — security automation, custom tooling  
`Bash` — Linux enumeration scripts, workflow automation

---
## Certifications

<div align="center">

| Certification | Issuer | Status |
|---|---|---|
| 🏅 **eWAPT** – Web Application Penetration Tester | INE Security | ✅ Certified — May 2026 |
| 🏅 **OSCP** – Offensive Security Certified Professional | OffSec | ✅ Completed |
| 🏅 **eJPTv2** – Junior Penetration Tester | INE Security | ✅ Completed |
| 🏅 **SOC Fundamentals** | NetRiders | ✅ Completed |
| 🔄 **CPTS** – Certified Penetration Tester Specialist | Hack The Box | 🔄 In Progress |
| 🔄 **CWES** – Certified Web Exploitation Specialist | Hack The Box | 🔄 In Progress |

</div>

<details>
<summary><b>📜 View Certificates</b></summary>

### OSCP – Certificate of Completion
<img width="1200" alt="OSCP Certificate" src="https://github.com/user-attachments/assets/5ce9d486-525e-45d7-824f-d836f5511b0d"/>

### eJPTv2 – Certificate of Completion
<img width="1200" alt="eJPTv2 Certificate" src="https://github.com/user-attachments/assets/ab0a9ca1-e84d-4696-9389-785f720e5769"/>

### SOC Fundamentals – NetRiders
<img width="1200" alt="SOC Certificate" src="https://github.com/user-attachments/assets/82fb735f-fb32-4eca-9d33-532d77d8230c"/>

</details>

---
---

## Contact

📧 [ahmedelfokery@gmail.com](mailto:ahmedelfokery@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/ahmed-hassan-069b83379)

---

<div align="center">
<sub>All security research and penetration testing documented here was conducted in controlled lab environments or authorized bug bounty programs.</sub>
</div>
