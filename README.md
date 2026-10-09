# SOC Analyst Investigation Challenge — SIEM, Network Forensics & Threat Hunting

## 📌 Overview

This repository documents a cybersecurity investigation challenge focused on Security Information and Event Management (SIEM), network traffic analysis, web application attacks, and memory forensics.

The challenge contains 10 questions based on a locally deployed SIEM environment, a PCAPNG network capture, and a suspected memory dump. The main objective is to investigate security events, identify suspicious activities, and extract relevant Indicators of Compromise (IOCs) using defensive security tools.

## 🎯 Objectives

- Investigate security events in a locally deployed SIEM.
- Identify agents associated with monitored systems.
- Analyze network traffic using PCAPNG files.
- Detect Local File Inclusion (LFI) and Remote File Inclusion (RFI) activities.
- Investigate Cross-Site Scripting (XSS) and SQL Injection (SQLi).
- Understand Wazuh log storage and indexing.
- Identify suspicious web server activity.
- Perform memory forensics to investigate a suspected executable.

## 🧪 Investigation Challenges

### Q1. SIEM Agent Identification
Identify the agent associated with the locally deployed SIEM.

**Options:**
- Emp01
- Emp02
- Metasploitable✔️
- Ent-DC

### Q2. Network Traffic Analysis
Identify the source port associated with destination port `4444` in `external.pcapng`.

**Options:**
- 49816✔️
- 1890
- 6666
- 7843

### Q3. Local File Inclusion (LFI)
Determine the URL associated with the LFI activity observed in the locally deployed SIEM.

**Options:**
- `/prod/vulnerabilities/fi/?page=file/../../../../../../etc/passwd`✔️
- `/prod/vulnerabilities/fi/?page=file/../../../../etc/passwd`
- `/prod/vulnerabilities/fi/?page=file/../etc/passwd`
- `/prod/vulnerabilities/fi/?page=file/etc/passwd`

### Q4. Wazuh Log Index
Identify the index where Wazuh stores collected raw logs in the deployed SIEM.

**Options:**
- Wazuh-archives✔️
- Wazuh-alerts
- Data
- Wazuh-monitoring

### Q5. Cross-Site Scripting (XSS)
Identify the HTTP status code associated with the XSS activity.

**Options:**
- 200✔️
- 404
- 300
- 402

### Q6. Suspicious Network Communication
Identify the port associated with suspicious network communication during the Remote File Inclusion (RFI) investigation.

**Options:**
- 9001✔️
- 4444
- 3000
- 5555

### Q7. Web Server Identification
Identify the web server associated with the locally deployed SIEM environment.

**Options:**
- Tomcat
- Apache2✔️
- NGINX
- XAMPP

### Q8. SQL Injection Activity
Determine the total number of SQL Injection (SQLi) activities identified during the investigation.

**Options:**
- 10
- 2
- 9
- 6✔️

### Q9. File Inclusion Investigation
Identify the filename associated with the File Inclusion activity.

**Options:**
- `shell.php`
- `mal.php`
- `rev.php`✔️
- `test.php`

### Q10. Memory Forensics
Determine the Process ID (PID) associated with `shell.exe` in the suspected raw memory dump.

**Options:**
- 7396✔️
- 10
- 789
- 6675

## ⚠️ Disclaimer

This repository is intended for educational purposes and authorized cybersecurity lab environments only. All investigation activities should be performed on systems and artifacts for which you have permission.

## 👤 Author

**Md. Sibgatur Rahman Efti**

- GitHub: [@efti74](https://github.com/efti74)
- LinkedIn: [Profile](https://www.linkedin.com/in/md-sibgatur-rahman-efti-861b67207/)

---

*Document your findings, validate the evidence, and keep learning through hands-on security investigations.*
