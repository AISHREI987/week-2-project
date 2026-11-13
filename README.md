# 🛡️ Footprinting, Reconnaissance & Network Scanning

<p align="center">
  <strong>Cybersecurity Practical Project | Week 2</strong>
  <br>
  Hands-on experience with Kali Linux tools, reconnaissance techniques, and network scanning using Zenmap.
</p>

---

## 📌 Project Overview

This repository contains two cybersecurity practicals focused on **Footprinting, Reconnaissance, and Network Scanning**.

The project demonstrates how to gather publicly available information about a website and identify active devices on an authorized local network using commonly used cybersecurity tools.

## 🎯 Objectives

- Understand the basics of footprinting and reconnaissance.
- Explore website information using multiple Kali Linux tools.
- Identify DNS records and web server information.
- Perform host discovery on a local network.
- Identify live hosts and their MAC addresses.
- Generate and document network scan results.

## 🧪 Practical Modules

### 1. Footprinting & Reconnaissance with Multiple Kali Tools

Tools used:

| Tool | Purpose |
|---|---|
| WHOIS | Retrieve domain registration information |
| WhatWeb | Identify website technologies |
| Nslookup | Perform DNS lookups |
| cURL | Inspect HTTP response headers |
| WAFW00F | Identify web application firewall information |
| DNSRecon | Gather DNS-related information |

**Target:** `networkwalks.com`

**Key learning outcomes:**
- Domain information gathering
- Website technology identification
- DNS enumeration
- HTTP header inspection
- Basic WAF detection

> Note: Findings should be verified using your own command outputs and screenshots before being presented as actual results.

### 2. Network Scanning with Zenmap

**Tool:** Zenmap (Nmap GUI)

**Network Configuration:**

| Parameter | Value |
|---|---|
| Local IPv4 Address | `192.168.100.8` |
| Subnet Mask | `255.255.255.0` |
| Default Gateway | `192.168.100.1` |
| Target Network | `192.168.100.0/24` |
| Scan Type | Ping Scan |

**Scan Results:**

- Total IP addresses scanned: **256**
- Live hosts discovered: **6**
- Scan duration: **37.65 seconds**

**Discovered Hosts:**

| IP Address | MAC Address | Vendor |
|---|---|---|
| 192.168.100.1 | 28:9E:97:5C:38:80 | Huawei Technologies |
| 192.168.100.3 | 92:19:F2:37:CB:91 | Unknown |
| 192.168.100.4 | CE:BA:B1:10:32:1E | Unknown |
| 192.168.100.5 | A6:3D:BF:74:5D:8E | Unknown |
| 192.168.100.6 | FA:A3:CF:81:9D:78 | Unknown |
| 192.168.100.8 | Not shown in scan output | Not identified |

## 🧰 Tools & Technologies

- Kali Linux
- WHOIS
- WhatWeb
- Nslookup
- cURL
- WAFW00F
- DNSRecon
- Nmap
- Zenmap
- Windows Command Prompt

## 📂 Project Structure

```text
Cybersecurity-Week2/
│
├── README.md
│
├── PM1-Footprinting-Reconnaissance/
│   ├── Screenshots/
│   └── Output-Files/
│
├── PM5-Network-Scanning-Zenmap/
│   ├── Screenshots/
│   ├── Scan-Results/
│   └── Network-Topology.pdf
│
└── Penetration-Testing-Report/
    └── Week2-Complete-Report.docx
```

*Folder names can be adjusted according to the files uploaded in this repository.*

## 📸 Screenshots & Evidence

Screenshots and output files should be added to their respective practical folders to demonstrate the commands executed and results obtained.

Recommended evidence:

- WHOIS and WhatWeb outputs
- Nslookup and DNSRecon results
- cURL and WAFW00F outputs
- Zenmap Ping Scan results
- Discovered live hosts
- Network topology PDF

## 📚 Learning Outcomes

Through these practicals, I gained hands-on experience in:

- Website footprinting and information gathering.
- Understanding DNS and HTTP information.
- Using reconnaissance tools in Kali Linux.
- Discovering active devices on a local network.
- Interpreting Nmap scan results.
- Documenting cybersecurity findings professionally.

## ⚠️ Disclaimer

This project is created strictly for **educational and learning purposes**.

All network scanning activities should only be performed on networks you own or have explicit permission to test. Never use these techniques against unauthorized systems.

## 👨‍💻 Author

**Name:** Ayesha Ramzan
**Course:** Cybersecurity / Penetration Testing  
**Project:** Week 2 – Practical Modules PM1 & PM5

---

<p align="center">
  ⭐ If you find this project useful, consider giving this repository a star!
  <br>
  <strong>Learn • Practice • Secure</strong>
</p>
