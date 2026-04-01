# 🛡️ Mini SOC (Security Operations Center) Home Lab

## 📌 Project Overview
This project demonstrates a **Mini SOC Home Lab** using Splunk.  
It simulates real-world cyber attacks, collects logs, detects threats, and performs incident analysis.

---

## 🎯 Objectives
- Build a real-world security monitoring environment
- Simulate cyber attacks (Brute Force, Enumeration, Exfiltration)
- Ingest and analyze logs using Splunk
- Create detection rules and alerts
- Visualize threats using dashboards
- Track attacker IPs with geolocation

---

## 🖥️ Lab Architecture
- **Attacker Machine:** Kali Linux
- **Target System:** Linux Log Generator
- **SIEM:** Splunk (Docker)
- **Host:** VirtualBox

---

## 🔍 Log Generation
Custom scripts simulate realistic logs:

```bash
bash ~/soc-logs/attack_sim.sh
