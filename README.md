<img width="2560" height="1440" alt="Banner_logo" src="https://github.com/user-attachments/assets/1a4de613-24ec-4217-8e8e-b5b6608b7a46" />



#!/usr/bin/env python3
"""
# 🔍 Automated Vulnerability Scanner

This Python script automates several vulnerability and enumeration scans for a given target using popular tools like **Nmap**, **Nikto**, **SSLScan**, **BloodHound**, **BEEF**, and **Uniscan**.

## 🧰 Tools Used
- **Nmap** - Port scanning and service/version detection
- **Nikto** - Web server scanner
- **SSLScan** - SSL/TLS configuration testing
- **BloodHound** - AD enumeration (requires credentials)
- **BEEF (Browser Exploitation Framework)** - Client-side web exploits
- **Uniscan** - Web vulnerability scanner

> ⚠️ **Note:** Tools like BEEF and BloodHound must be installed and configured properly in your environment.

---

## 📦 Requirements

- Python 3.x
- Tools installed and available in PATH:
  - `nmap`
  - `nikto`
  - `sslscan`
  - `uniscan`
  - `bloodhound` (or relevant command interface)
  - `BEEF-XSS` (or your BEEF command path)

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/vuln-scanner.git
cd vuln-scanner
chmod +x scanner.py
./scanner.py <target> <username> <password> <beef_url>

## Notes & TODO
BEEF and BloodHound commands may need modification based on your environment.

Kerbrute section is commented out and can be enabled/configured as needed.

Consider sanitizing and securing credentials passed to the script.

⚠️ Disclaimer
This tool is intended only for authorized testing and educational purposes. Unauthorized use against systems you don't own or have explicit permission to scan is illegal and unethical.
