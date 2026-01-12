
# Mini SOC Project – Suricata & Splunk

This project demonstrates the design and implementation of a mini Security Operations Center (SOC) using Suricata for intrusion detection and Splunk for log analysis and visualization.

## Overview
- IDS: Suricata
- SIEM: Splunk Enterprise
- Attack Simulation: Nmap
- Analyst Workflow: Detection, Analysis, Response Classification

- PROJECT ARCHITECTURE
Attacker Activity (Nmap Scan)
        ↓
Suricata IDS (Kali Linux)
        ↓
Suricata Logs (JSON / Alerts)
        ↓
Splunk Universal Forwarder
        ↓
Splunk Enterprise (Windows Host)
        ↓
Detection, Analysis, Dashboards, Response Classification


## What This Project Covers
- Network intrusion detection
- Log forwarding and SIEM ingestion
- Dashboard creation
- Incident response decision-making

## Documentation
Detailed project documentation is available in the /docs folder.

