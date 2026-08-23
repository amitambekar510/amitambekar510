<div align="center">

# 🛡️ Amit Ambekar — Cybersecurity Engineer & Threat Intelligence Researcher

[![GitHub](https://img.shields.io/badge/GitHub-amitambekar510-181717?style=for-the-badge&logo=github)](https://github.com/amitambekar510)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-amitmilindambekar-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/amitmilindambekar/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:amit.ambekar@protonmail.com)

</div>

---

<div align="center">

### 🔴 LIVE THREAT INTELLIGENCE FEEDS

| Feed | IOCs | Last Updated | Status | RAW Feed |
|------|------|--------------|--------|----------|
| 🌐 **Malicious IPs** | `149,000+` | ![Last Commit](https://img.shields.io/github/last-commit/amitambekar510/Malicious-IP-Threat-List?label=&color=00ff41) | ![Status](https://img.shields.io/badge/STATUS-ACTIVE-00ff41?style=flat) | [📥 Download](https://raw.githubusercontent.com/amitambekar510/Malicious-IP-Threat-List/main/Malicious-IP-Threat-List.txt) |
| 🔗 **Malicious Domains** | `138,700+` | ![Last Commit](https://img.shields.io/github/last-commit/amitambekar510/Malicious-Domain-Threat-List?label=&color=ff8c00) | ![Status](https://img.shields.io/badge/STATUS-ACTIVE-ff8c00?style=flat) | [📥 Download](https://raw.githubusercontent.com/amitambekar510/Malicious-Domain-Threat-List/main/Blacklisted_Malicious_Domain_Repo.txt) |
| 🔐 **Malicious Hashes** | `85,400+` | ![Last Commit](https://img.shields.io/github/last-commit/amitambekar510/Malicious-Hash-Threat-List?label=&color=9b59b6) | ![Status](https://img.shields.io/badge/STATUS-ACTIVE-9b59b6?style=flat) | [📥 Download](https://raw.githubusercontent.com/amitambekar510/Malicious-Hash-Threat-List/main/malicious_SHA256_hashes_aa.txt) |

**🔄 Auto-Updated every 12 hours via GitHub Actions** | **🚫 Zero duplicates guaranteed** | **✅ Validated against VT/AbuseIPDB**

</div>

---

## 🎯 Threat Intelligence Platform Overview

```mermaid
graph TB
    A[🔍 Threat Sources] --> B[🤖 Automated Collection]
    B --> C[✅ Validation Engine]
    C --> D[🚫 Deduplication]
    D --> E[📦 GitHub Repos]
    E --> F[🔥 Firewalls/SIEM/EDR]
    
    A1[AbuseIPDB] --> A
    A2[AlienVault OTX] --> A
    A3[FireHOL] --> A
    A4[Tor Project] --> A
    A5[URLhaus] --> A
    A6[MalwareBazaar] --> A
    A7[Custom Honeypots] --> A
    
    style A fill:#1a1a2e,stroke:#00ff41
    style E fill:#16213e,stroke:#ff8c00
    style F fill:#0f3460,stroke:#9b59b6
```

---

## 📊 Real-Time Feed Statistics

<div align="center">

![IP Stats](https://img.shields.io/badge/Total_IPs-149,000+-00ff41?style=for-the-badge&logo=databricks)
![Domain Stats](https://img.shields.io/badge/Total_Domains-138,700+-ff8c00?style=for-the-badge&logo=cloudflare)
![Hash Stats](https://img.shields.io/badge/Total_Hashes-85,400+-9b59b6?style=for-the-badge&logo=hashicorp)
![Auto Updates](https://img.shields.io/badge/Auto_Updates-Every_12h-1abc9c?style=for-the-badge&logo=githubactions)
![Uptime](https://img.shields.io/badge/Uptime-99.9%25-00ff41?style=for-the-badge&logo=uptimerobot)

</div>

### 📈 Feed Growth (Last 30 Days)
```
IPs:      ████████████████████ +2,847 new
Domains:  ██████████████████   +1,923 new
SHA256:   █████████████████████ +4,156 new
MD5:      ████████░░░░░░░░░░░░  +127 new
SHA1:     ██████░░░░░░░░░░░░░   +89 new
```

---

## 🛠️ Security Tool Integrations

<div align="center">

### Direct RAW Feed Integration — No Auth Required

| Platform | IP Feed | Domain Feed | Hash Feed | Config |
|----------|---------|-------------|-----------|--------|
| **Palo Alto EDL** | ✅ | ✅ | ✅ | [Guide](https://github.com/amitambekar510/Malicious-IP-Threat-List/wiki/Palo-Alto) |
| **FortiGate** | ✅ | ✅ | ✅ | [Guide](https://github.com/amitambekar510/Malicious-IP-Threat-List/wiki/FortiGate) |
| **Sophos XG/XGS** | ✅ | ✅ | ❌ | [Guide](https://github.com/amitambekar510/Malicious-Domain-Threat-List/wiki/Sophos) |
| **Microsoft Sentinel** | ✅ | ✅ | ✅ | [Guide](https://github.com/amitambekar510/Malicious-IP-Threat-List/wiki/Sentinel) |
| **Splunk ES** | ✅ | ✅ | ✅ | [Guide](https://github.com/amitambekar510/Malicious-IP-Threat-List/wiki/Splunk) |
| **IBM QRadar** | ✅ | ✅ | ✅ | [Guide](https://github.com/amitambekar510/Malicious-IP-Threat-List/wiki/QRadar) |
| **CrowdStrike Falcon** | ✅ | ✅ | ✅ | [Guide](https://github.com/amitambekar510/Malicious-Hash-Threat-List/wiki/CrowdStrike) |
| **ELK Stack** | ✅ | ✅ | ✅ | [Pipeline](https://github.com/amitambekar510/Malicious-IP-Threat-List/blob/main/elk-pipeline.conf) |
| **MISP** | ✅ | ✅ | ✅ | [Script](https://github.com/amitambekar510/Malicious-IP-Threat-List/blob/main/misp_import.py) |
| **SentinelOne** | ❌ | ❌ | ✅ | [Script](https://github.com/amitambekar510/Malicious-Hash-Threat-List/blob/main/sentinelone_import.py) |

</div>

---

## 🚀 Featured Projects

### 🔴 Threat Intelligence Feeds (Core)

| Repo | Description | Stars | Last Update |
|------|-------------|-------|-------------|
| **[Malicious-IP-Threat-List](https://github.com/amitambekar510/Malicious-IP-Threat-List)** | 149K+ malicious IPs from 7+ intel sources | ⭐ 0 | ![](https://img.shields.io/github/last-commit/amitambekar510/Malicious-IP-Threat-List?label=&color=00ff41) |
| **[Malicious-Domain-Threat-List](https://github.com/amitambekar510/Malicious-Domain-Threat-List)** | 138K+ malicious domains, phishing, C2 | ⭐ 8 | ![](https://img.shields.io/github/last-commit/amitambekar510/Malicious-Domain-Threat-List?label=&color=ff8c00) |
| **[Malicious-Hash-Threat-List](https://github.com/amitambekar510/Malicious-Hash-Threat-List)** | 85K+ malware hashes (MD5/SHA1/SHA256) | ⭐ 5 | ![](https://img.shields.io/github/last-commit/amitambekar510/Malicious-Hash-Threat-List?label=&color=9b59b6) |

### 🛡️ SOC & Automation Projects

| Repo | Description | Tech Stack |
|------|-------------|------------|
| **[sentinel-ioc-block](https://github.com/amitambekar510/sentinel-ioc-block)** | Automated Tor/AbuseIPDB/FireHOL ingestion → Firewall blocking | Python, GitHub Actions, iptables |
| **[SOC-DarkWatch](https://github.com/amitambekar510/SOC-DarkWatch)** | Dark web monitoring: SpiderFoot + TorBot + MISP + ELK + FortiGate | Python, Docker, ELK Stack |
| **[SOC-Nemotron-CLI](https://github.com/amitambekar510/SOC-Nemotron-CLI)** | Terminal-based AI-assisted cyber ops with NVIDIA Nemotron 3 Ultra | Python, OpenCode CLI |

---

## 🧠 Skills & Expertise

<div align="center">

### Threat Intelligence & SOC
![Threat Intel](https://img.shields.io/badge/Threat_Intelligence-Expert-00ff41?style=flat-square&logo=shield)
![IOC Management](https://img.shields.io/badge/IOC_Management-Expert-00ff41?style=flat-square&logo=database)
![SIEM Engineering](https://img.shields.io/badge/SIEM_Splunk/ELK/QRadar-Advanced-ff8c00?style=flat-square&logo=splunk)
![EDR/XDR](https://img.shields.io/badge/EDR-CrowdStrike/SentinelOne-9b59b6?style=flat-square&logo=datadog)
![SOAR](https://img.shields.io/badge/SOAR-Phantom/Cortex-1abc9c?style=flat-square&logo=github)

### Automation & Infrastructure
![Python](https://img.shields.io/badge/Python-Advanced-3776AB?style=flat-square&logo=python)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-Expert-2088FF?style=flat-square&logo=githubactions)
![Docker](https://img.shields.io/badge/Docker-Advanced-2496ED?style=flat-square&logo=docker)
![Linux](https://img.shields.io/badge/Linux_Hardening-Advanced-FCC624?style=flat-square&logo=linux)
![Terraform](https://img.shields.io/badge/Terraform-Intermediate-7B42BC?style=flat-square&logo=terraform)

### Security Platforms
![Palo Alto](https://img.shields.io/badge/Palo_Alto-NGFW/Panorama-0078D4?style=flat-square)
![FortiGate](https://img.shields.io/badge/FortiGate-FortiSIEM-EE3124?style=flat-square)
![Sophos](https://img.shields.io/badge/Sophos-XG/XGS/Central-0078D4?style=flat-square)
![Microsoft](https://img.shields.io/badge/Microsoft-Sentinel/Defender-0078D4?style=flat-square)

</div>

---

## 📡 Live Feed Health Monitor

<div align="center">

### Feed Availability (Last 24h)

| Feed | HTTP Status | Response Time | Last Check |
|------|-------------|---------------|------------|
| IPs (main) | ![](https://img.shields.io/website?url=https%3A%2F%2Fraw.githubusercontent.com%2Famitambekar510%2FMalicious-IP-Threat-List%2Fmain%2FMalicious-IP-Threat-List.txt&label=IPs&color=00ff41) | < 200ms | Auto |
| IPs (part_aa) | ![](https://img.shields.io/website?url=https%3A%2F%2Fraw.githubusercontent.com%2Famitambekar510%2FMalicious-IP-Threat-List%2Fmain%2FMalicious-IP-Threat-List_aa&label=IPs_aa&color=00ff41) | < 200ms | Auto |
| Domains (main) | ![](https://img.shields.io/website?url=https%3A%2F%2Fraw.githubusercontent.com%2Famitambekar510%2FMalicious-Domain-Threat-List%2Fmain%2FBlacklisted_Malicious_Domain_Repo.txt&label=Domains&color=ff8c00) | < 200ms | Auto |
| Domains (part_aa) | ![](https://img.shields.io/website?url=https%3A%2F%2Fraw.githubusercontent.com%2Famitambekar510%2FMalicious-Domain-Threat-List%2Fmain%2FBlacklisted_Malicious_Domain_Repo_aa.txt&label=Domains_aa&color=ff8c00) | < 200ms | Auto |
| SHA256 (aa) | ![](https://img.shields.io/website?url=https%3A%2F%2Fraw.githubusercontent.com%2Famitambekar510%2FMalicious-Hash-Threat-List%2Fmain%2Fmalicious_SHA256_hashes_aa.txt&label=SHA256_aa&color=9b59b6) | < 300ms | Auto |
| SHA256 (ab) | ![](https://img.shields.io/website?url=https%3A%2F%2Fraw.githubusercontent.com%2Famitambekar510%2FMalicious-Hash-Threat-List%2Fmain%2Fmalicious_SHA256_hashes_ab.txt&label=SHA256_ab&color=9b59b6) | < 300ms | Auto |

</div>

---

## 📜 Certifications & Learning

- 🎓 **CompTIA Security+** (Valid)
- 🎓 **eJPT / eCPPT** (In Progress)
- 🎓 **AWS Cloud Practitioner** (Planned)
- 📚 **Continuous Learning**: MITRE ATT&CK, Malware Analysis, Cloud Security

---

## 🤝 Connect & Collaborate

<div align="center">

[![GitHub Discussions](https://img.shields.io/badge/Discussions-Ask_Anything-181717?style=for-the-badge&logo=github)](https://github.com/amitambekar510/Malicious-IP-Threat-List/discussions)
[![Report False Positive](https://img.shields.io/badge/Report-False_Positive-FF4444?style=for-the-badge&logo=bug)](https://github.com/amitambekar510/Malicious-IP-Threat-List/issues/new?template=false_positive.yml)
[![Submit IOC](https://img.shields.io/badge/Submit-New_IOC-00ff41?style=for-the-badge&logo=plus)](https://github.com/amitambekar510/Malicious-IP-Threat-List/issues/new?template=ioc_submission.yml)
[![Request Integration](https://img.shields.io/badge/Request-Tool_Integration-ff8c00?style=for-the-badge&logo=wrench)](https://github.com/amitambekar510/Malicious-IP-Threat-List/issues/new?template=integration_request.yml)

</div>

---

<div align="center">

### ⚡ Powered by Automation
**GitHub Actions** • **Python** • **Multi-source Intelligence** • **Zero-deduplication** • **12-hour cycles**

> *"Defending networks, one indicator at a time."*

**© 2026 Amit Ambekar — Threat Intelligence Researcher**  
*Data provided for defensive security purposes. Validate before enforcement.*

</div>

---

<details>
<summary><b>🔧 Technical Implementation Details</b></summary>

### Automated Pipeline Architecture
```yaml
Schedule: "0 */12 * * *"  # Every 12 hours
Sources:
  - AbuseIPDB (API)
  - AlienVault OTX (API)
  - FireHOL (level1/2/3/4)
  - Tor Project (exit nodes)
  - URLhaus (malware URLs → domains)
  - MalwareBazaar (recent hashes)
  - Custom honeypot sensors
Validation:
  - VirusTotal API (min 3 detections)
  - AbuseIPDB confidence > 50%
  - Cisco Talos reputation check
Deduplication:
  - In-memory set per cycle
  - Cross-file Bloom filter
  - Git history diff check
Output:
  - Append to partitioned files (100K lines max)
  - Update CHANGELOG.md with stats
  - Commit with signed GPG key
  - Push to main branch
```

### Feed Format Standards
- **IPs**: One IPv4 per line, no CIDR, no private ranges
- **Domains**: FQDN only, lowercase, no wildcards/paths/protocols
- **Hashes**: Lowercase hex (MD5:32, SHA1:40, SHA256:64 chars)

</details>