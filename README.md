# 🛡️ Mini SOC Home Lab (Splunk)

[![Splunk](https://img.shields.io/badge/Splunk-FF5733?style=flat&logo=splunk)](https://www.splunk.com/)
[![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=flat&logo=kali-linux)](https://www.kali.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python)](https://www.python.org/)

Welcome to my **Security Operations Center (SOC) Home Lab**! This project simulates a real-world SOC environment, helping me practice detecting, analyzing, and responding to cyber threats using **Splunk**, **Kali Linux**, **Wireshark**, and Python automation.

---

## 🚀 Project Overview

This lab allows me to:

- Collect and analyze security logs from multiple sources.
- Create alerts and detection rules in **Splunk SIEM**.
- Simulate attacks to understand threat behavior.
- Visualize security events with dashboards and IP maps.

**Goal:** Gain hands-on experience similar to a professional SOC analyst role.

---

## 🛠️ Tools & Technologies

- **Splunk** – Log aggregation and threat detection.
- **Kali Linux** – Penetration testing and attack simulations.
- **Wireshark** – Network traffic capture and analysis.
- **Python** – Automation and log parsing scripts.
- **Docker** – Containerized lab environment.
- **Bash** – Attack simulation scripts.

---

## 📂 Project Structure

---

## 🖼️ Lab Screenshots

### 1️⃣ Dashboard Overview
![Dashboard Overview](projects/soc/dashboard_overview.png)  
> Splunk dashboard showing real-time security alerts and system metrics.

### 2️⃣ IP Map Visualization
![IP Map](projects/soc/ip_map_1.png)  
> Interactive map displaying network activity by IP address.

### 3️⃣ Threat Logs
![Threat Logs](projects/soc/threat_logs.png)  
> Example of collected logs and detected anomalies.

### 4️⃣ Python Automation Script
![Python Script](projects/soc/python_script.png)  
> Script automating log parsing and basic threat detection.

---

## 🎬 Demo

Watch the lab in action:

<video controls width="600">
  <source src="projects/soc/demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## 💡 How to Run the Lab

1. **Clone the repository:**

```bash
git clone https://github.com/labansoita/mini-soc-home-lab.git
cd mini-soc-home-lab

---

### ✅ Notes:

1. Make sure all **image files exist** in `public/projects/soc/` (dashboard_overview.png, ip_map_1.png, threat_logs.png, python_script.png).  
   - If you don’t have `threat_logs.png` or `python_script.png`, take screenshots of your logs or Python scripts and save them there.
2. The **demo video** should also exist in `public/projects/soc/demo.mp4`.
3. After adding images, **commit and push**:

```bash
git add README.md projects/soc/*
git commit -m "Add professional README with screenshots and video"
git push origin main
