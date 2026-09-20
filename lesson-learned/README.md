# Lessons Learned
 
## Lesson #001 - Read Before Pressing "Y"
 
### Situation
 
While attempting to install a Wazuh Agent, Linux displayed:
 
Installing:
- wazuh-agent
 
Removing:
- wazuh-manager
 
### Risk
 
Proceeding would have removed the Wazuh Manager from the SIEM server.
 
### Resolution
 
The installation was stopped and reviewed before any changes were made.
 
### Takeaway
 
Always review package manager actions before confirming installations.
 
### Commands Used
 
apt install
 
dpkg
 
systemctl
