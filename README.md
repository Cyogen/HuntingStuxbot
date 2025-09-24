# HuntingStuxbot
THM/HTB malware hunt

## Objective

Find and trace a R.A.T. in the system.

This is a text only write up of the successful steps taken to identify and get to the root of the infection.  Stuxbot is a R.A.T with multiple C&C servers.

### Skills Learned

- Threat-hunting fundamentals: hypothesis-driven search for anomalous activity (follow the evidence from email → file → process → network).
- Event/log triage: using Sysmon/Windows event streams to find suspicious behavior (process creation, file creation/streams).
- IOC discovery & enrichment: extracting file paths, hashes, DNS queries and destination IPs to create indicators of compromise.

### Tools Used

- Sysmon
- Windows Event Viewer/Event Logs
- Splunk
- KQL/SPL queries
- Process Explorer/Task Manager
- DNS/IP/IOC

## Notes

