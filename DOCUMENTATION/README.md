# TraceIntel – IP Tracker Tool

## 📌 Overview

`TraceIntel` is a professional OSINT-based IP intelligence and tracking tool designed for cyber security researchers, ethical hackers, SOC analysts, and OSINT practitioners. It aggregates data from multiple trusted sources to provide accurate, actionable intelligence about any IPv4/IPv6 address.

The tool is built with performance, privacy, and usability in mind and follows ethical OSINT standards.


## 🎯 Objectives

* Provide deep IP intelligence using open-source intelligence (OSINT)
* Assist security research, threat hunting, and investigation
* Maintain privacy-first architecture (no user-agent leakage)
* Deliver fast, reliable, and structured results


## 🧠 Use Cases

* Incident response & SOC analysis
* Threat intelligence enrichment
* Cybercrime investigation (legal & ethical)
* Academic & security research
* OSINT investigations


## ⚙️ Architecture Overview

TraceIntel uses an asynchronous Python-based architecture:

* CLI-driven interface
* Fully async HTTP requests
* Modular intelligence collectors
* Result correlation engine
* Optional map generation


## 🔥 Core Features

### IP Validation

* IPv4 / IPv6 format validation
* Public vs private IP detection

### Network Intelligence

* Ping status
* Common port checks (80, 443, 8080)
* Hostname resolution

### OSINT Enrichment

* ISP & Organization
* ASN (Autonomous System Number)
* Country, Region, City
* Continent
* Latitude & Longitude

### Privacy & Risk Checks

* VPN / ProtonVPN affiliation detection
* Pastebin exposure checks

### Intelligence Correlation

* Probability-based nearest location estimation
* Cross-API result comparison

### Visualization

* Automatic map generation from geo-coordinates


## 🧩 Integrated Data Sources

| Service      | Purpose            |
| ------------ | ------------------ |
| ip-api.com   | Geo & ISP data     |
| ipinfo.io    | Coordinates & ASN  |
| ipwhois.io   | ASN & ownership    |
| proton.me    | VPN affiliation    |
| pastebin.com | Data leak presence |


## 📂 Project Structure

```
TraceIntel/
│
├── lib/
│   ├── colors.py
│   ├── network.py
│   ├── osint.py
│   └── utils.py
│
├── traxintel.py
├── requirements.txt
├── LICENSE
└── README.md
```


## 🛠 Installation

### Requirements

* Python 3.8+
* Internet connection

### Linux / macOS

```bash
git clone https://github.com/karndeepbaror/traceintel.git
cd traceintel 
cd TraceIntel
pip3 install -r requirements.txt
```

### Windows

```bat
git clone https://github.com/karndeepbaror/traceintel.git
cd traceintel 
cd TraceIntel
install.bat
```


## 🚀 Usage

```bash
python3 traxintel.py 
```

## 📊 Output Details

* Structured CLI output
* Colored risk indicators
* Geo-map (if enabled)
* Aggregated intelligence summary


## 🔐 Security & Ethics

* No intrusive scanning
* No exploitation
* OSINT-only data collection
* User-agent protection

⚠️ This tool must only be used for legal and ethical purposes.


## 🧪 Testing

* Tested on Linux & Windows
* Handles invalid IPs gracefully
* API timeout handling


## 🧾 License

This project is licensed under the MIT License.

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

## 🤝 Contribution

* Fork the repository
* Create a feature branch
* Submit a pull request



