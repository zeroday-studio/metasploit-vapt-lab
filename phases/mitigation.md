# 🛡️ Phase 5: Mitigation

## 🎯 Objective
The objective of this phase is to provide security recommendations for all identified open ports and services to reduce the attack surface and improve system security.

---

## 🔍 Identified Open Ports & Services

- FTP (21)
- SSH (22)
- Telnet (23)
- SMTP (25)
- HTTP (80)
- SMB (139, 445)
- MySQL (3306)
- IRC (6667)
- Tomcat (8180)
- Java RMI (1099)
- NFS (2049)

---

## 🛠️ Mitigation Strategies

---

### 🔹 FTP (Port 21)

- Update vsftpd to a secure version  
- Disable anonymous login  
- Use SFTP instead of FTP  
- Restrict access using firewall rules  

---

### 🔹 SSH (Port 22)

- Disable root login  
- Use key-based authentication  
- Change default SSH port  
- Enable fail2ban for brute-force protection  

---

### 🔹 Telnet (Port 23)

- Disable Telnet service completely  
- Replace with SSH  

---

### 🔹 SMTP (Port 25)

- Disable VRFY and EXPN commands  
- Configure SMTP authentication  
- Restrict mail relay access  

---

### 🔹 HTTP (Port 80)

- Remove vulnerable web applications  
- Apply security patches  
- Implement HTTPS  
- Use Web Application Firewall (WAF)  

---

### 🔹 SMB (Ports 139/445)

- Update Samba service  
- Disable SMBv1 protocol  
- Restrict access to trusted IP addresses  
- Enforce strong authentication  

---

### 🔹 MySQL (Port 3306)

- Set strong passwords  
- Disable remote root login  
- Bind MySQL to localhost  
- Regularly update database  

---

### 🔹 IRC (Port 6667)

- Remove or update UnrealIRCd service  
- Block port if not required  
- Monitor network activity  

---

### 🔹 Tomcat (Port 8180)

- Change default credentials  
- Restrict access to manager interface  
- Apply security patches  
- Disable unnecessary applications  

---

### 🔹 Java RMI (Port 1099)

- Restrict access using firewall rules  
- Disable service if not required  
- Apply secure configurations  

---

### 🔹 NFS (Port 2049)

- Restrict NFS exports to trusted IPs  
- Avoid sharing root directory  
- Implement access controls  

---

## 🔐 General Security Recommendations

- Perform regular patch updates  
- Disable unused services and ports  
- Implement network segmentation  
- Deploy IDS/IPS systems  
- Monitor logs continuously  
- Enforce strong password policies  

---

## 🧠 Analysis

The system exposed multiple services with weak configurations and outdated software. By applying the above mitigation strategies, the overall attack surface can be significantly reduced and system security can be improved.

---
