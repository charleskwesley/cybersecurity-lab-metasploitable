# Cybersecurity Lab: Kali Linux vs Metasploitable 2

## 📌 Overview
This project demonstrates a hands-on penetration testing lab using Kali Linux and Metasploitable 2 in VMware.

The goal was to simulate a real-world attack scenario by scanning, identifying vulnerabilities, and exploiting a target machine in a controlled environment.

---

## 🛠️ Tools Used
- Kali Linux
- Metasploitable 2
- Nmap
- Metasploit Framework
- VMware Workstation

---

## 🌐 Lab Setup
- Created two virtual machines (Kali Linux & Metasploitable 2)
- Configured both machines on the same network
- Verified connectivity using ping

---

## 🔍 Scanning Phase
Used Nmap to identify open ports and running services on the target machine.

### Key Findings:
- FTP (vsftpd 2.3.4)
- SSH
- MySQL
- Apache Tomcat
- IRC

---

## 💥 Exploitation Phase
Used Metasploit to exploit a known vulnerability:

*Exploit Used:*
vsftpd 2.3.4 backdoor

### Result:
- Successfully gained access to the target machine
- Achieved root-level access
- Verified using:
## 🎯 Skills Gained
- Network scanning & enumeration
- Vulnerability analysis
- Exploitation using Metasploit
- Understanding of penetration testing workflow

---

## ⚠️ Disclaimer
This project was conducted in a controlled lab environment for educational purposes only.


!{image alt} https://github.com/charleskwesley/cybersecurity-lab-metasploitable/blob/17e02089633c1e60adc25edd849260401926b340/Screenshot%202026-05-04%20232207.png
![image alt] https://github.com/charleskwesley/cybersecurity-lab-metasploitable/blob/81bc4469187cc92503aa50243af2eabec5afeb4b/Screenshot%202026-05-04%20232330.png
