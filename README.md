# Introduction to SIEM – TryHackMe

## Overview

This room introduced the fundamentals of Security Information and Event Management (SIEM) systems and their role in modern cybersecurity operations. The room covered how SIEM platforms collect, analyze, and correlate log data from multiple sources to help security teams detect and respond to threats.

---

## What is a SIEM?

A Security Information and Event Management (SIEM) platform is used to centralize and analyze security logs from different devices and systems across an organization.

SIEM solutions help security teams by:

* Aggregating logs from multiple sources
* Detecting suspicious activity
* Generating alerts
* Supporting incident investigations
* Providing visibility into network and endpoint activity

SIEM tools are commonly used in Security Operations Centers (SOCs).

---

## Core SIEM Functions

### Log Collection

SIEM platforms ingest logs from:

* Endpoints
* Firewalls
* Servers
* IDS/IPS systems
* Authentication systems
* Cloud environments

### Event Correlation

Correlation rules allow SIEM systems to identify suspicious patterns across multiple log sources.

Example:

* Multiple failed login attempts
* Followed by a successful login
* From the same IP address

This may indicate a brute-force attack.

### Alerting

When suspicious behavior is detected, the SIEM generates alerts for analysts to investigate.

### Dashboards & Monitoring

SIEM platforms provide dashboards that help analysts monitor:

* Failed logins
* Malware detections
* Network anomalies
* Privileged account activity

---

## Common Log Sources

| Source                  | Purpose                            |
| ----------------------- | ---------------------------------- |
| Windows Event Logs      | Authentication and system activity |
| Firewalls               | Network traffic monitoring         |
| IDS/IPS                 | Intrusion detection                |
| Endpoint Security Tools | Malware and endpoint activity      |
| Web Server Logs         | HTTP requests and web traffic      |
| Authentication Logs     | User login activity                |

---

## SIEM Workflow

1. Collect logs from multiple systems
2. Normalize and parse data
3. Correlate events using detection rules
4. Generate alerts for suspicious activity
5. Investigate and respond to incidents

---

## Detection Example

Example scenario:

* A user account experiences repeated failed logins
* A successful login occurs shortly after
* The login originates from an unusual location

A SIEM may flag this as suspicious authentication activity requiring investigation.

---

## Popular SIEM Platforms

Some widely used SIEM solutions include:

* Splunk
* Microsoft Sentinel
* IBM QRadar
* Elastic Stack (ELK)
* ArcSight

---

## Skills Demonstrated

* Log analysis fundamentals
* Security monitoring concepts
* Event correlation
* Threat detection basics
* Understanding SIEM architecture
* SOC workflow awareness

---

## Key Takeaways

This room helped build a foundational understanding of how SIEM platforms support security operations and incident detection. Understanding SIEM concepts is essential for SOC analyst, blue-team, and incident response roles.

The room also highlighted the importance of centralized logging and correlation in identifying malicious activity within enterprise environments.

---

## References

* MITRE ATT&CK Framework
* TryHackMe – Introduction to SIEM
* NIST Cybersecurity Framework
