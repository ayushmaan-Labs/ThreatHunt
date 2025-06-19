# ThreatHunt
A practical project for collecting, analyzing, and hunting cyber threats using open-source intelligence and proactive detection techniques. Designed for SOC analysts to enhance threat visibility and response.
# 🔍 Threat Intelligence & Hunting Project

A cybersecurity project focused on gathering, enriching, and utilizing open-source threat intelligence to proactively hunt malicious indicators such as IPs, domains, and file hashes across network logs.

> *Built for SOC Analyst portfolios, this project simulates real-world hunting operations using Python, ELK Stack, and open threat intelligence feeds.*

---

## 📌 Objective

To create a proactive Threat Hunting framework that:
- Ingests Indicators of Compromise (IOCs) from public threat feeds.
- Stores and normalizes IOCs into Elasticsearch.
- Performs automated hunts in log data.
- Triggers alerts on matches.
- Documents actionable intelligence for incident response.

---

## 🛠️ Tech Stack

| Tool         | Purpose                            |
|--------------|-------------------------------------|
| Python       | Scripting and automation            |
| Elasticsearch| IOC storage and log searching       |
| Kibana       | Visualizing and querying logs       |
| OTX/MISP     | Threat Intel (OSINT Feeds)          |
| Logstash     | (Optional) Log parsing and ingestion|

---
