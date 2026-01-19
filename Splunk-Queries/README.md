# Splunk Query Library

This folder contains reusable SPL (Search Processing Language) queries used throughout the project.

## Structure
Splunk-Queries/
├── authentication/ # Login-related queries
├── sysmon/ # Process & network monitoring
├── web-attacks/ # Web server attack detection
└── threat-hunting/ # Proactive hunting queries


## Usage
Copy queries from `.spl` files and paste into Splunk search bar.

## Query Categories

### Authentication Queries
- **failed-logins.spl** - Detect failed login attempts (EventCode 4625)
- **successful-logins.spl** - Track successful logins (EventCode 4624)
- **user-creation.spl** - Monitor new user accounts (EventCode 4720)

### Sysmon Queries
- **process-creation.spl** - Monitor processes (EventCode 1)
- **network-connections.spl** - Track network activity (EventCode 3)

---

**Week 1 Queries:** 3 files in `authentication/`
