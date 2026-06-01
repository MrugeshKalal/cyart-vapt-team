# Week 2 - Vulnerability Assessment and Penetration Testing (VAPT)

## 📌 Objective

The objective of this week is to understand and perform basic Vulnerability Assessment and Penetration Testing (VAPT) using industry-standard tools. The focus is on identifying open ports, services, and web application vulnerabilities in a controlled lab environment.

---

## 🧰 Tools Used

- Nmap (Network Scanning)
- Nikto (Web Server Scanning)
- Kali Linux (Testing Environment)
- Terminal / Command Line Interface

---

## 🎯 Target

- Local Lab Machine / Metasploitable / Test VM
- IP Address: 192.168.56.101

---

## 🔍 Activities Performed

### 1. Reconnaissance

- Identified target IP address
- Verified network connectivity using ping

---

### 2. Network Scanning (Nmap)

Performed service and version detection scan.

#### Command Used:
```bash
nmap -sV 192.168.56.101
