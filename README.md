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

![image alt] https://github.com/charleskwesley/cybersecurity-lab-metasploitable/blob/81bc4469187cc92503aa50243af2eabec5afeb4b/Screenshot%202026-05-04%20232440.png

![image alt] https://github.com/charleskwesley/cybersecurity-lab-metasploitable/blob/3db47aefe7138c1951a377d577303dbc93cd4b78/Screenshot%202026-05-04%20232555.png

![image alt] https://github.com/charleskwesley/cybersecurity-lab-metasploitable/blob/98f06b46a7f4ed91bbbe4a7726b07d54209c2fbd/Screenshot%202026-05-04%20232749.png





## 🔍 Enumeration Phase (Nmap)

Performed network scanning to identify open ports and services on the target machine.

### Commands Used
```bash
nmap 192.168.80.130
nmap -sV 192.168.80.130
nmap -A 192.168.80.130


https://github.com/charleskwesley/cybersecurity-lab-metasploitable/blob/cf3da4ce7cb1ea06702bec0edb3ae1790d1164b4/Screenshot%202026-05-05%20232937.png



