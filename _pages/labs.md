---
permalink: /labs/
layout: single
author_profile: true
---

# 🔬 Lab Challenges

Below are some of the hands-on labs and challenges I’ve completed as part of my ongoing training and personal practice in cybersecurity, system administration, and networking.

---

## 🧪 Challenge 1: Active Directory Exploitation (Beginner)

**Problem:** Simulate a vulnerable Windows network and exploit misconfigurations in Active Directory.

**Approach:**  
- Built a virtual lab with Windows Server, client machines, and Kali Linux  
- Enumerated shares, users, and misconfigurations using `rpcclient`, `enum4linux`, and BloodHound  
- Gained privilege escalation using Kerberoasting  

**Tools Used:** Kali Linux, BloodHound, Mimikatz, Impacket  

**Lessons Learned:** Importance of secure service principal naming and patching known AD flaws.

---

## 🧪 Challenge 2: Web App Recon and Exploitation

**Problem:** Identify vulnerabilities in a mock CMS platform.

**Approach:**  
- Conducted information gathering using `whatweb`, `dirb`, and `nmap`  
- Found XSS and SQLi flaws  
- Exploited an admin login bypass and accessed user data  

**Tools Used:** Burp Suite, sqlmap, Firefox Dev Tools, OWASP ZAP  

**Lessons Learned:** Secure coding principles and importance of WAFs.

---

## 🧪 Challenge 3: Firewall Rule Misconfiguration

**Problem:** Test and validate firewall ACLs for common attack vectors.

**Approach:**  
- Configured Cisco ASA in GNS3 and tested default deny rules  
- Sent crafted packets to validate port exposure  
- Hardened rules for ICMP, SSH, and HTTP

**Tools Used:** GNS3, Wireshark, Cisco Packet Tracer, Nmap

**Lessons Learned:** Defense-in-depth starts with proper rule review and segmentation.

---

These are part of my journey to becoming a skilled security and network operations professional. More writeups coming soon!

