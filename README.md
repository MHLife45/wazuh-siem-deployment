# Wazuh SIEM Deployment
 
## Project Overview
 
This project documents the deployment of a Wazuh Security Information and Event Management (SIEM) environment within a cybersecurity homelab.
 
The objective is to gain practical experience with security monitoring, endpoint telemetry, compliance reporting, log analysis, and threat detection workflows.
 
## Environment
 
### Security Infrastructure
 
- Wazuh Manager
- Wazuh Dashboard
- Wazuh Indexer
- Kali Linux Endpoint
- pfSense Firewall
- Ubuntu Linux Server
 
## Current Architecture
 
```text
Internet
│
Home Network
│
Ubuntu SIEM Server
├── Wazuh Manager
├── Wazuh Dashboard
└── Wazuh Indexer
 
pfSense Firewall
 
Kali Linux
└── Wazuh Agent
```
 
## Accomplishments
 
### Wazuh Deployment
- Installed Wazuh Manager
- Installed Wazuh Dashboard
- Installed Wazuh Indexer
- Verified service functionality
 
### Endpoint Monitoring
- Enrolled Kali Linux as the first active endpoint
- Validated agent communications
- Generated compliance and monitoring reports
 
### Troubleshooting
- Resolved repository signing issues
- Corrected package installation conflicts
- Verified agent service operation
- Validated network connectivity
 
## Skills Demonstrated
 
- Linux Administration
- SIEM Deployment
- Security Monitoring
- Endpoint Security
- Network Troubleshooting
- Security Operations
 
## Lessons Learned
 
- Read package installation summaries before approval
- Verify package installation before troubleshooting services
- Confirm connectivity before troubleshooting applications
- Telemetry is required before meaningful monitoring can occur
 
## Future Enhancements
 
- Integrate pfSense logs
- Deploy Windows Server 2022
- Install Sysmon
- Integrate Suricata
- Integrate Zeek
- Explore AI-assisted log analysis using Ollama
