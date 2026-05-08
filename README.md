<div align="center">

# William Schnaith
### SOC Analyst · Blue Team · Threat Hunter

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0072b1?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/williamschnaith/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Site-39d353?style=for-the-badge&logo=githubpages&logoColor=white)](https://diveburien.github.io/WillsCorner/)
[![Security+](https://img.shields.io/badge/CompTIA-Security%2B-c8202f?style=for-the-badge&logo=comptia&logoColor=white)](certifications-and-education/artifacts/CompTIA-Security-Plus-certificate.pdf)
[![CPTE](https://img.shields.io/badge/Mile2-C%29PTE-1f3a93?style=for-the-badge)](certifications-and-education/artifacts/Mile2-CPTE-certificate.png)

</div>

---

> Cybersecurity professional with hands-on experience in **SIEM operations, threat hunting, incident response, and offensive security**. CompTIA Security+ and Mile2 C)PTE certified. Looking to bring detection-engineering and blue-team mindset to a SOC Analyst role.

## ⚡ At a Glance

| | |
|---|---|
| 🛡️ **Certifications** | CompTIA Security+ (SY0-701) · Mile2 C)PTE |
| 🔎 **SIEM Experience** | 33 active threat investigations on a live municipal network (Elastic + Suricata) |
| 🎯 **Detection** | CVE-2024-1709 exploitation tracking · 90-day persistence detection · geolocation threat hunting |
| 🔴 **Offensive** | Full enterprise pentest report · red/blue team exercise · MITRE ATT&CK-mapped findings |
| 🗄️ **Database Security** | MSSQL + MongoDB audit configuration, exploit testing, hardening |
| 🌐 **Networking** | CCNA I & II coursework — VLANs, STP, Layer 2 security, DHCP snooping |

---

## 🎯 SOC Core Competencies

<table>
<tr>
<td width="50%">

### 📊 SIEM & Log Analysis
- Alert triage in **Elastic SIEM** + **Suricata**
- Event correlation across logs, geo, and reputation feeds
- Suricata rule tuning to reduce false-positive load
- Investigation documentation and client-ready reporting

</td>
<td width="50%">

### 🔍 Threat Hunting & Detection
- IOC pivoting (IP reputation, geolocation, domain)
- CVE exploitation pattern recognition (e.g. CVE-2024-1709)
- Persistence detection across multi-month windows
- Threat-intel correlation against active campaigns

</td>
</tr>
<tr>
<td width="50%">

### 🚨 Incident Response & Reporting
- Investigation methodology: alert → triage → validate → document
- Severity classification and escalation
- Formal client-facing recommendations
- Post-incident hardening guidance

</td>
<td width="50%">

### 🔵 Network Security Monitoring
- **Snort IDS/IPS** deployment and live monitoring
- **Wireshark** packet capture and protocol analysis
- Firewall rule design and access control
- Pre-engagement vulnerability scanning with **OpenVAS**

</td>
</tr>
<tr>
<td width="50%">

### 🔴 Adversary Tradecraft (for Detection)
- Red-team experience informs detection engineering
- MITRE ATT&CK mapping of observed techniques
- Hands-on with **Metasploit, Responder, Mythic C2, BloodHound**
- LOLbin abuse, LLMNR poisoning, AD enumeration

</td>
<td width="50%">

### 🗄️ Endpoint & Database Security
- MSSQL server-level audit specifications
- MongoDB Atlas database triggers
- Hardening + re-test verification cycles
- Least-privilege access via stored procedures

</td>
</tr>
</table>

---

## 📁 Featured Projects

> Ordered by SOC relevance — start with **#1** for the work most representative of the day-to-day analyst role.

### ⭐ 1. [SIEM Threat Analysis — Burien Municipal Network](siem-threat-analysis/)
**The most SOC-representative project in this portfolio.** L1/L2 analyst work on a live municipal network using Elastic SIEM and Suricata. Conducted **33 comprehensive threat investigations** including:
- 🔴 **CVE-2024-1709** ConnectWise ScreenConnect auth-bypass exploitation tracking
- 🔴 90-day persistence detection from a malicious subnet (`78.153.140.0/24`)
- 🟡 Geolocation threat hunting (Uruguay, China)
- 🟡 Phishing simulation and IOC analysis
- 🟢 Suricata rule tuning to reduce false positives

`Elastic SIEM` `Suricata` `Threat Hunting` `IOC Analysis` `Incident Documentation`

### 2. [Red/Blue Team Exercise — Snort vs. Hashcat](redblue-team-exercise/)
Built and hardened a 6-host virtualized network from scratch, then attempted to penetrate the opposing team's infrastructure. **Defensive hardening blocked 100% of attacks.** Demonstrates blue-team mindset and understanding of how attacks fail when defenses are tuned.

`Snort IDS/IPS` `Wireshark` `OpenVAS` `Network Hardening` `Metasploit` `Armitage`

### 3. [Enterprise Penetration Test — Simulated Engagement](enterprise-pentest/)
Full-scope simulated pentest with two attack narratives (insider threat + assume breach). Findings mapped to **MITRE ATT&CK** to inform detection-engineering recommendations.

`Responder` `Nmap` `Mythic C2` `BloodHound` `Vulnserver` `LOLbins` `MITRE ATT&CK`

### 4. [Database Security & Audit Configuration](database-security-audit/)
Vulnerability scanning, exploit testing, audit configuration, and hardening across **MSSQL** and **MongoDB**. Includes pre/post hardening verification and a least-privilege stored-procedure implementation.

`MSSQL Audit` `MongoDB Triggers` `ApexSQL` `Metasploit` `AWS EMR` `Least Privilege`

---

## 🛠️ Toolbox

<table>
<tr>
<th>SIEM & Detection</th>
<th>Network Security</th>
<th>Offensive Security</th>
</tr>
<tr>
<td valign="top">

- Elastic SIEM
- Suricata
- ApexSQL Audit
- MSSQL Audit Specs
- MongoDB Atlas Triggers

</td>
<td valign="top">

- Snort IDS/IPS
- Wireshark
- Nmap / Zenmap
- OpenVAS
- pfSense

</td>
<td valign="top">

- Metasploit
- Responder
- Mythic C2 + Apollo
- BloodHound
- Armitage
- msfvenom
- Vulnserver
- LOLbins

</td>
</tr>
<tr>
<th>Identity & Endpoint</th>
<th>Cloud & Big Data</th>
<th>Networking</th>
</tr>
<tr>
<td valign="top">

- Active Directory enumeration
- LLMNR / NTLM analysis
- Windows Defender Firewall
- SSMS user/role management

</td>
<td valign="top">

- AWS S3
- AWS EMR
- PySpark
- MongoDB Atlas

</td>
<td valign="top">

- Cisco Packet Tracer
- VLANs, STP, EtherChannel
- DHCP snooping, DAI
- WPA2 / WPA3
- HSRP, static & default routing

</td>
</tr>
</table>

---

## 📜 Certifications & Education

<table>
<tr>
<td width="33%" align="center">

### 🛡️
**CompTIA Security+ (SY0-701)**
Certified Apr 30, 2026
Valid through Apr 30, 2029
[View Certificate →](certifications-and-education/artifacts/CompTIA-Security-Plus-certificate.pdf)

</td>
<td width="33%" align="center">

### 🎯
**Mile2 C)PTE**
Certified Penetration Testing Engineer
Issued Jun 14, 2023 · No expiration
[View Certificate →](certifications-and-education/artifacts/Mile2-CPTE-certificate.png)

</td>
<td width="33%" align="center">

### 📡
**CCNA I & II Coursework**
Cisco Networking Academy
Highline College (2022–2023)
[View Coursework →](certifications-and-education/)

</td>
</tr>
</table>

Full details and official transcript: [`certifications-and-education/`](certifications-and-education/)

---

## 📬 Contact

- **LinkedIn:** [linkedin.com/in/williamschnaith](https://www.linkedin.com/in/williamschnaith/)
- **GitHub:** [github.com/DiveBurien](https://github.com/DiveBurien)
- **Portfolio Site:** [diveburien.github.io/WillsCorner](https://diveburien.github.io/WillsCorner/)
