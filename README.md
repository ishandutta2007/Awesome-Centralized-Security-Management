# Awesome-Centralized-Security-Management
# Awesome-Centralized-Security-Management

# Awesome-Centralized-Security-Management

## Top Centralized Security Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SIEM, XDR, CSPM & Security Operations*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Centralized Security Management**. These tools aggregate, correlate, and analyze security telemetry from endpoints, networks, cloud workloads, and identities to detect threats, manage vulnerabilities, and automate incident response.



**Examples** include Salesforce Security Center, Microsoft Defender XDR, Palo Alto Cortex XSIAM, Splunk Cloud, SentinelOne Singularity, CrowdStrike Falcon, Datadog Cloud Security, Wiz, Orca Security, and IBM Security QRadar (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom detection engineering, and open security data pipelines — ideal for SOC teams, security researchers, and organizations building transparent, vendor-independent security operations.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Security Center](https://www.salesforce.com/)**  

  Centralized security monitoring for Salesforce environments. Provides threat detection, anomaly alerts, and compliance posture management for CRM data.



- **[Microsoft Defender XDR](https://www.microsoft.com/en-us/security/business/)**  

  Unified extended detection and response across endpoints, identities, email, and cloud apps. Native integration with Microsoft Sentinel for SIEM capabilities.



- **[Palo Alto Cortex XSIAM](https://www.paloaltonetworks.com/cortex)**  

  AI-driven security operations platform converging SIEM, SOAR, ASM, and XDR. Designed to automate the entire SOC lifecycle.



- **[Splunk Cloud](https://www.splunk.com/)**  

  Enterprise SIEM and data analytics platform for security monitoring, threat detection, and compliance reporting at scale.



- **[SentinelOne Singularity](https://www.sentinelone.com/)**  

  Autonomous AI-powered endpoint protection and XDR platform with real-time threat detection and automated response.



- **[CrowdStrike Falcon](https://www.crowdstrike.com/)**  

  Cloud-native endpoint protection and threat intelligence platform with behavioral detection and managed hunting.



- **[Datadog Cloud Security](https://www.datadoghq.com/)**  

  Cloud security posture management and workload protection integrated with observability data.



- **[Wiz](https://www.wiz.io/)**  

  Agentless cloud security platform providing CSPM, CWPP, CIEM, and DSPM with graph-based risk analysis.



- **[Orca Security](https://orca.security/)**  

  Agentless cloud security platform with unified visibility across cloud estates and prioritized risk remediation.



- **[IBM Security QRadar](https://www.ibm.com/security)**  

  Enterprise SIEM with log management, network flow analysis, and security analytics for hybrid cloud environments.



## Open-Source GitHub Projects



- **[Wazuh](https://github.com/wazuh/wazuh)**  

  The leading open-source XDR/SIEM platform (GPL-2.0). Provides host-based intrusion detection, file integrity monitoring, vulnerability detection, and security configuration assessment. Integrates with ELK Stack, MISP, and TheHive for a complete open SOC stack. 600+ stars on related rule repositories .



- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  

  Open-source fork of Elasticsearch and Kibana (Apache-2.0) led by AWS. Provides log storage, search, and visualization for SIEM use cases. Can be paired with Suricata, Zeek, and Wazuh for detection .



- **[Suricata](https://github.com/OISF/suricata)**  

  High-performance network IDS/IPS and network security monitoring engine (GPL-2.0). Deep packet inspection with protocol-aware detection, file extraction, and Lua scripting for custom rules .



- **[Zeek](https://github.com/zeek/zeek)**  

  Powerful network analysis framework (BSD license) that produces structured logs for security monitoring. Extracts metadata from network traffic without blocking, ideal for threat hunting and forensics .



- **[MISP](https://github.com/MISP/MISP)**  

  Malware Information Sharing Platform (AGPL) for threat intelligence sharing. Collects, stores, distributes, and correlates IOCs. Extensive ecosystem including PyMISP, misp-dashboard, and MISP-Grafana for real-time threat intel visualization .



- **[TheHive / Cortex](https://github.com/TheHive-Project/TheHive)**  

  TheHive (AGPL-3.0 for v4 and earlier) is a scalable incident response platform with case management, task assignment, and observables. Cortex (AGPL-3.0) analyzes observables at scale via a REST API. Together they form a SOC incident response backbone . Note: TheHive 5+ requires a StrangeBee license.



- **[StackStorm](https://github.com/StackStorm/st2)**  

  Event-driven automation platform (Apache-2.0) for SOAR workflows. Connects security tools and automates response actions. Integrates with Wazuh, Jira, and Slack for alert triage and remediation .



- **[Tracecat](https://github.com/TracecatHQ/tracecat)**  

  Open-source SOAR platform (AGPL-3.0) positioned as a self-hosted Tines/Splunk SOAR alternative. No-code and YAML dual-authoring, Temporal-based workflow engine, 100+ integrations, SSO, and audit logs in the free tier .



- **[CloudRec](https://github.com/antgroup/CloudRec)**  

  Multi-cloud CSPM platform (Apache-2.0) by Ant Group. Asset discovery across 30+ cloud services, OPA-based rule engine, and risk detection for network, identity, data, and logging misconfigurations .



- **[OWASP OpenShield](https://github.com/OWASP/openshield)**  

  Open-source CSPM for Azure (AGPL-3.0). Scans for misconfigurations and quantum-unsafe cryptography, maps findings to CIS/NIST/ISO27001/SOC2, and provides one-command remediation playbooks .



- **[IntelOwl](https://github.com/intelowlproject/IntelOwl)**  

  Threat intelligence management at scale (AGPL-3.0). Integrates 100+ analyzers (VirusTotal, AbuseIPDB, Yara, Shodan, MISP) and connectors to MISP/OpenCTI. Provides REST API, GUI, and Python/Go client libraries for SOC integration .



- **[Radegast EDR](https://github.com/radegast-edr/radegast-backend)**  

  Privacy-focused endpoint detection and response platform with end-to-end encryption (age). SQLite-backed, self-contained deployment. Includes eBPF sensor (Rustinel) for Linux and Windows agents .



- **[Warden](https://github.com/Spellskite-coding/Warden)**  

  Open-source EDR for Linux workstations written in Rust. Fanotify-based filesystem monitoring, YARA rule scanning, ransomware detection, quarantine management, and GTK4 GUI dashboard. Hardened through adversarial testing .



- **[AEGIS](https://github.com/alejadxr/AEGIS)**  

  Open-source autonomous cybersecurity platform with 11/11 detection score. Sub-300ms pipeline, honeypot deception, Sigma correlation engine (163 rules), auto-blocking, and Rust endpoint agent. Built to replace Wazuh for autonomous response .



### Additional Strong Open-Source Options



- **[OSSIEM by SOCFortress](https://github.com/socfortress/OSSIEM)** — Open Source SIEM Stack combining Wazuh, Grafana, and threat intelligence .

- **[UTMStack](https://github.com/utmstack/UTMStack)** — Customizable SIEM and XDR powered by real-time correlation and threat intelligence .

- **[OpenSIEM Framework](https://ieeexplore.ieee.org/document/11113996)** — Academic fusion of Wazuh, TheHive, Shuffle, Elasticsearch, MISP, and OpenCTI. Processes 10,000+ logs/sec, reduces false positives by 40% .

- **[Catalyst](https://github.com/mshehata-dev/catalyst)** — Open-source SOAR/incident response platform with ticket management, tasks, reactions (automation), and timelines .

- **[n8n](https://github.com/n8n-io/n8n)** — Workflow automation with security tool nodes for SOAR-like orchestration .

- **[Greenbone GVM](https://github.com/greenbone/gvmd)** — Open-source vulnerability management (OpenVAS) with scanning, reporting, and remediation tracking .

- **[PatrowlManager](https://github.com/Patrowl/PatrowlManager)** — Open-source security operations orchestration for vulnerability assessment and pentest automation .



**Frameworks for building custom systems**: Combine **Wazuh** for endpoint detection with **Suricata + Zeek** for network telemetry, **OpenSearch** for log storage and visualization, **MISP** for threat intelligence, **TheHive/Cortex** for incident response, and **StackStorm** or **Tracecat** for SOAR automation — creating a fully self-hosted enterprise-grade security operations stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Security telemetry and threat intelligence must comply with privacy and data protection regulations (GDPR, CCPA, etc.).

- Self-hosted open-source solutions require proper security hardening, network isolation, and ongoing maintenance.



---



**Made for SOC teams, security engineers, threat hunters, and developers building transparent security operations.**  

Let's make centralized security management more open, data-driven, and resilient.
