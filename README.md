# SIEM Home Lab using Wazuh and Sysmon

## Overview

Built a SOC home lab using Wazuh SIEM, Sysmon, and Windows/Ubuntu endpoints for centralized log collection, real-time security monitoring, MITRE ATT&CK mapped threat detection, custom detection engineering, attack simulation, alert triage, and incident investigation.

---

## Architecture

* Ubuntu 24.04 (Wazuh Manager)
* Windows 10 Endpoint
* Wazuh Agent 4.7.5
* Sysmon
* MITRE ATT&CK Mapping

---

## Features

* Real-time Security Monitoring
* Centralized Log Collection
* Sysmon Integration
* MITRE ATT&CK Mapping
* Alert Triage
* Detection Engineering
* PowerShell Monitoring
* Process Creation Monitoring
* Network Activity Monitoring
* File Creation Monitoring
* DNS Query Monitoring
* Custom Detection Rules
* Attack Simulation

---

## Custom Detection

Rule ID: 100500

Detection:

PowerShell ExecutionPolicy Bypass

MITRE Technique:

T1059.001 - PowerShell

---

## Attack Simulations

* Encoded PowerShell Commands
* PowerShell ExecutionPolicy Bypass
* Process Creation
* Command Execution
* Network Activity

---

## Technologies Used

* Wazuh 4.7.5
* Sysmon
* Windows 10
* Ubuntu 24.04
* PowerShell
* MITRE ATT&CK Framework

---

## Project Status

Current Completion: ~80%

Upcoming Enhancements:

* File Integrity Monitoring
* Brute Force Detection
* VirusTotal Integration
* URLHaus Threat Intelligence
* Suricata IDS Integration
* Incident Response Playbooks
* Advanced Dashboards
