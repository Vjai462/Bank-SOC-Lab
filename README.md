# Bank SOC Lab - Security Operations Center Simulation

![Status](https://img.shields.io/badge/Status-Active-green) ![Progress](https://img.shields.io/badge/Progress-Week%201%20Complete-blue) ![Platform](https://img.shields.io/badge/Platform-Splunk%20%7C%20VirtualBox-orange)

## 🎯 Project Overview

A hands-on **Security Operations Center (SOC)** lab simulating a bank's security monitoring infrastructure using Splunk SIEM, Windows Active Directory, and real attack simulations.

**Duration:** 30 Days | **Current Status:** Week 1 Complete ✅  
**Author:** Cybersecurity Graduate 2024 | Telangana, India

---

## 🏦 Why This Lab?

This project replicates a real bank's SOC environment to build job-ready skills for **SOC Analyst** and **Cyber Defense Analyst** roles.

### Target Skills
✅ SIEM monitoring (Splunk)  
✅ Log analysis & correlation  
✅ Threat detection & incident response  
✅ Attack simulation & defense  
✅ Windows Event Log analysis  
✅ Threat hunting methodology  

---

## 🏗️ Lab Architecture

### Virtual Machines (4 Total)

| Machine | OS | IP | Role |
|---------|----|----|------|
| **BANK-DC01** | Windows Server 2019 | 192.168.56.10 | Domain Controller |
| **BANK-EMP01** | Windows 10 | 192.168.56.11 | Employee Workstation |
| **BANK-WEB01** | Ubuntu 24 LTS | 192.168.56.12 | Web Server (Apache) |
| **ATTACKER-EXT01** | Kali Linux | 192.168.56.13 | External Hacker |

### Host Machine
- **OS:** Windows 11 (16GB RAM)
- **SIEM:** Splunk Enterprise (Free - 500MB/day)
- **Network:** VirtualBox Host-Only (192.168.56.0/24)

---

## 📂 Project Structure

Week 1 (Days 1-7): ✅ Environment Setup & Log Collection
Week 2 (Days 8-14): 🔄 IN PROGRESS
Week 3 (Days 15-21): ⏳ Planned
Week 4 (Days 22-30): ⏳ Planned


**Navigate:**
- [📘 Week 1: Foundation](./Week1-Foundation/) - VM setup, Splunk, Dashboard
- [📚 Documentation](./docs/) - SOC concepts & reference materials
- [🔍 Splunk Queries](./Splunk-Queries/) - Reusable SPL searches
- [📊 Dashboards](./Dashboards/) - Exported Splunk dashboards

---

## 🎓 Week 1 Achievements

### Technical Milestones
✅ VirtualBox Host-Only network configured (192.168.56.0/24)  
✅ 4 VMs built with static IPs  
✅ Active Directory domain `banklab.local` with 6 users  
✅ Splunk Universal Forwarders installed on 3 VMs  
✅ Sysmon deployed for deep Windows visibility  
✅ Ubuntu web server with Apache configured  
✅ Authentication dashboard with 4 panels created  

### Skills Learned
- **Networking:** Host-only adapter, static IPs, port forwarding
- **Windows Security:** EventCode 4624/4625/4720, Active Directory
- **Sysmon:** EventCode 1 (process), 3 (network), 11 (file)
- **Splunk SPL:** rex field extraction, stats, timechart
- **Troubleshooting:** Sysmon Error Code 5, dashboard debugging

---

## 🔧 Technologies Used

**SIEM & Monitoring:**
- Splunk Enterprise 9.x
- Splunk Universal Forwarder
- Sysmon (SwiftOnSecurity config)

**Infrastructure:**
- VirtualBox 7.x
- Windows Server 2019
- Windows 10 Enterprise
- Ubuntu 24.04 LTS
- Kali Linux 2024.x

---

## 🖼️ Lab Evidence

All screenshots include:
✅ Timestamps visible  
✅ VM hostnames in screenshots  
✅ Windows taskbar (proof of environment)  
✅ Actual Splunk queries with results  

**View:** Screenshots organized by day in `Week1-Foundation/screenshots/`

---

## 📖 Documentation

- [Week 1 Details](./Week1-Foundation/) - Days 1-7 complete documentation
- [SOC Concepts](./docs/01-SOC-Concepts.md) - Event, Log, Alert, Incident
- [EventCode Reference](./docs/02-EventCode-Reference.md) - Windows event codes

---

## 🎯 Next Steps

**Week 2 Focus:** Attack simulation, alert creation, incident response
- Day 8: RDP Brute Force simulation
- Day 9: First Splunk alert
- Day 12: First incident report

---

## 📧 Connect

**GitHub:** [This Repository]  
**Location:** Telangana, India  
**Goal:** SOC Analyst | Cyber Defense Analyst

---

## 📝 License

Educational project - All tools used are open-source or free licensed.

---

**Last Updated:** January 17, 2026  
**Status:** Week 1 Complete - Moving to Week 2
