# 🔐 Offensive Security VAPT using Metasploit Framework

## 📌 Overview
This project demonstrates a complete Vulnerability Assessment and Penetration Testing (VAPT) lifecycle on a vulnerable machine (Metasploitable2). The objective is to identify, enumerate, exploit, and analyze vulnerabilities in a controlled lab environment.

---

## ⚠️ Disclaimer
This project was conducted in a controlled lab environment using intentionally vulnerable systems. All activities were performed for educational and ethical learning purposes only. Unauthorized testing on real systems without permission is illegal and strictly prohibited.

---

## 🧪 Lab Setup

### 💻 Environment
- Kali Linux (Attacker Machine)
- Metasploitable2 (Target Machine)

### 🌐 Network Configuration
- Adapter 1: Internal Network (Lab Communication)
- Adapter 2: NAT (Internet Access)

### 📡 IP Addressing

| Machine | Interface | IP Address |
|--------|----------|-----------|
| Kali Linux | eth0 | 192.168.10.5 |
| Metasploitable2 | eth0 | 192.168.10.50 |

### 🔗 Connectivity
- Both machines are connected via Internal Network
- Connectivity verified using `ping`

---

## 🛠️ Tools Used

### 🔍 Reconnaissance
- Nmap

### 🔎 Enumeration
- Nmap
- Netcat
- smbclient
- ftp
- telnet
- mysql client

### 💣 Exploitation
- Metasploit Framework

### 🔥 Post-Exploitation
- Linux commands (whoami, id, ps, netstat)

### 🧠 Additional Tools (Knowledge)
- enum4linux (considered)
- Nikto (not used in this project)

---

## 🧭 Project Phases

| Phase | Description | Link |
|------|------------|------|
| 🔍 Phase 1 | Reconnaissance | [View](phases/phase1-reconnaissance.md) |
| 🔎 Phase 2 | Enumeration | [View](phases/phase2-enumeration.md) |
| 💣 Phase 3 | Exploitation | [View](phases/phase3-exploitation.md) |
| 🔥 Phase 4 | Post-Exploitation | [View](phases/phase4-post-exploitation.md) |
| 🛡️ Phase 5 | Mitigation | [View](phases/phase5-mitigation.md) |

---

## 📄 Report

A detailed report of this project is available here:  
👉 [View Report](VAPT-report.pdf)

---

## 📚 What I Did & Learned

### 🔧 What I Did
- Performed full network reconnaissance using Nmap  
- Enumerated multiple services (FTP, SMB, HTTP, etc.)  
- Exploited vulnerabilities using Metasploit Framework  
- Gained root access through multiple attack vectors  
- Conducted post-exploitation analysis  

### 📈 What I Learned
- Practical understanding of VAPT lifecycle  
- Identifying and exploiting real-world vulnerabilities  
- Importance of enumeration before exploitation  
- How attackers gain and maintain system access  
- Security measures to mitigate vulnerabilities  

---

## 🎯 Conclusion

This project demonstrated a complete VAPT lifecycle on a vulnerable system. Multiple services were exploited to achieve full system compromise. It highlights the importance of securing network services and reducing the attack surface.

---

## 👨‍💻 Author

Rakesh A R  
Aspiring Cybersecurity Analyst  
https://www.linkedin.com/in/rakesh-a-r-595517288
