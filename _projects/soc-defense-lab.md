---
layout: post
title: "SOC Defense Lab"
date: 2024-09-15
description: "Built a comprehensive SOC defense lab for blue team training and threat detection"
technologies: [Splunk, ELK Stack, Suricata, Zeek]
status: "Completed"
mermaid: true
toc: true
---

# SOC Defense Lab Project

Built a comprehensive Security Operations Center defense lab for training and threat detection.

## Overview
This project involved setting up a complete SOC environment with log aggregation, threat detection, and incident response capabilities.

## Technologies Used
- **SIEM**: Splunk Enterprise
- **Log Management**: ELK Stack (Elasticsearch, Logstash, Kibana)
- **Network Security**: Suricata IDS, Zeek network monitor
- **Virtualization**: VMware vSphere

## Key Features
- Real-time log aggregation from multiple sources
- Custom detection rules for advanced threats
- Automated incident response workflows
- Threat intelligence integration

Your project details here...

```bash
# Example command to start Suricata
sudo suricata -c /etc/suricata/suricata.yaml -i eth0
```

```mermaid
flowchart LR
A[Log Sources] --> B[Logstash]
B --> C[Elasticsearch]
C --> D[Kibana]
B --> E[Splunk]
E --> F[Alerting & Reporting]
```
