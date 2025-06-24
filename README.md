# 🔍 Cybersecurity Internship - Task 1

## 🎯 Task: Scan Your Local Network for Open Ports

### ✅ Objective:
To discover open ports on devices within the local network and understand exposure to potential security risks.

---

## 🛠 Tools Used:
- Nmap (`v7.94`)

---

## 🔄 Steps Performed:

1. Identified local IP range: `192.168.1.0/24`
2. Performed TCP SYN scan using:
   ```bash
   nmap -sS 192.168.1.0/24 -oN local_scan_report.txt
