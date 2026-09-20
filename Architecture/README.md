# Homelab Architecture
 
## Current Environment
 
Internet
│
Home Network (192.168.0.0/24)
│
Ubuntu SIEM Server (192.168.0.35)
├── Wazuh Manager
├── Wazuh Dashboard
└── Wazuh Indexer
 
Virtual Security Network
 
pfSense Firewall (192.168.1.1)
 
Kali Linux (192.168.1.101)
└── Wazuh Agent
 
## Future Components
 
- Windows Server 2022
- Active Directory
- Sysmon
- Suricata
- Zeek
- Ollama Integration
