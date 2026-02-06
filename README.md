# 🔍 TraceIntel

**TraceIntel** is a powerful, asynchronous OSINT tool designed to collect, correlate, and visualize intelligence related to IP addresses. Built for security researchers, penetration testers, SOC analysts, and OSINT enthusiasts, TraceIntel aggregates data from multiple trusted sources to deliver accurate, actionable insights — fast.

> ⚡ Minimal footprint. Maximum intelligence.


## 🚀 Overview

TraceIntel performs deep reconnaissance on a given IP address by querying multiple APIs and services in parallel. It then correlates the results to improve accuracy and confidence. The tool is designed with privacy in mind and **never uses your user agent** for external requests.

Whether you're investigating suspicious traffic, validating threat intelligence, or doing OSINT research, TraceIntel gives you a clean, professional CLI experience with reliable results.


## ✨ Key Features

* ⚡ **Fully Asynchronous Engine** – ultra-fast execution using async requests
* 🔄 **Multi‑Source Correlation** – better accuracy by comparing results
* 🧠 **Smart IP Validation** – detects invalid or malformed IPs
* 📡 **Network Intelligence**

  * Ping check
  * Open port detection (80, 443, 8080 — extensible)
* 🔐 **VPN Detection** – identifies ProtonVPN-associated IPs
* 🕵️ **Paste Exposure Check** – detects presence in Pastebin
* 🌍 **Geolocation Intelligence**

  * Continent, country, region, city
  * Latitude & longitude
  * Nearest probable locations (confidence-based)
* 🏢 **Infrastructure Details**

  * ISP
  * Organization
  * ASN (Autonomous System Number)
  * Hostname
* 🗺️ **Map Generation** – visual IP location mapping
* 🧩 **Modular Architecture** – easy to extend and customize
* 🖥️ **Clean CLI Menu System** – professional and intuitive


## 🧰 Data Sources & Modules

| Module              | Service      |
| ------------------- | ------------ |
| ProtonVPN Detection | proton.me    |
| Paste Exposure      | pastebin.com |
| IP Geolocation      | ip-api.com   |
| Advanced IP Intel   | ipinfo.io    |
| WHOIS Intelligence  | ipwhois.io   |

Each source is queried independently and results are compared to enhance precision.


## 🛠️ Requirements

* **Python 3.8+**
* Internet connection


## 📦 Installation

### 🪟 Windows

```bash
git clone https://github.com/karndeepbaror/traceintel.git
cd traceintel
cd TraceIntel
install.bat
```

### 🐧 Linux / macOS

```bash
git clone https://github.com/karndeepbaror/traceintel.git
cd traceintel
cd TraceIntel
pip3 install -r requirements.txt
```


## 📚 Usage

```bash
python traxosint.py <ip-address>
```

### Example

```bash
python traxosint.py 8.8.8.8
```

### Help Menu

```bash
python traxosint.py --help
```


## 🎯 Use Cases

* SOC & Blue Team investigations
* OSINT research and correlation
* Threat intelligence enrichment
* VPN & anonymization detection
* Academic and learning purposes


## 🔐 Privacy & Ethics

TraceIntel is built strictly for **educational, defensive security, and lawful OSINT purposes**.

* ❌ No user-agent leakage
* ❌ No unauthorized access attempts
* ✅ Passive intelligence gathering only

Users are responsible for complying with all applicable laws and regulations.


## 📜 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.


## ⚡ ARCHITECT & LEAD DEVELOPER

<div align="center">

| 👤 **Developer** | **Karndeep Baror** |
| :--- | :--- |
| 🛡️ **Role** | Cyber Security Researcher & Ethical Hacker |
| 💻 **Stack** | Python | OSINT | Network Intelligence |
| 🚀 **Project** | TraceIntel - IP Tracker Tool |
| 🌐 **Status** | Active Security Researcher |


## 🔗 CONNECT WITH ME

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/karndeepbaror)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/karndeepbaror)
[![Community](https://img.shields.io/badge/Community-FF5722?style=for-the-badge&logo=react&logoColor=white)](https://whatsapp.com/channel/0029Vb6plDSBKfi3qGz2fq0f)

**"In the world of zero-days, I build zero-trust."**

</div>

<p align="center">
  <img src="https://capsule-render.vercel.app/render?type=waving&color=gradient&height=120&section=footer&text=TRACE%20INTEL%20•%20OSINT%20RESEARCH&fontSize=22&fontColor=ffffff" />
</p>

## ⭐ Support

If you find this project useful:

* ⭐ Star the repository
* 🍴 Fork it
* 🧠 Contribute ideas or improvements

> *Trace smarter. Intel deeper.*
> 
