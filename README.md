# Wazuh-SOC-Lab
Built a local Wazuh SIEM lab to monitor a Windows endpoint and validate alert ingestion.
# Lab Steps
- Installed Wazuh all-in-one on Ubuntu VM
- Connected Windows host as an agent
- Verified agent active in Wazuh dashboard
- Generated failed Windows logon attempts
- Confirmed alert rule 60122 in Threat Hunting events
# Screenshots
## Windows Agent Connected
Windows agent succesfully connected to Wazuh server.
<img width="1280" height="800" alt="Screenshot 2026-10-05 225858" src="https://github.com/user-attachments/assets/5fd0d1e0-271a-4aa1-b220-ef938ed90729" />
## Failed Logon Events
Threat hunting events showing multiple failed Windows logon attempts detected by Wazuh
<img width="1278" height="801" alt="Screenshot 2026-10-05 232539" src="https://github.com/user-attachments/assets/ce31987d-21fd-4490-9aa5-295c6731aa7a" />
## Failed Logo Alert Details
Detailed view of a single failed logon alert, rule 60122
<img width="1284" height="799" alt="Screenshot 2026-10-05 232735" src="https://github.com/user-attachments/assets/b74c70c2-a889-446a-ac56-fc5e25cc89ec" />
# What I learned
- How to connect and monitor a Windows endpoint using Wazuh
- How to generate and identify failed logon alerts
- How to perform basic alert triage by reviewing rule descriptions, severity levels, timestamps, and event details
- How to navigate and use a SIEM dashboard to investigate security events
