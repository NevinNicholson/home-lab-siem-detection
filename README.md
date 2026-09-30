# home-lab-siem-detection

A collection of hands-on security home labs I've built to learn practical SOC and detection work. Each folder is a self-contained project with its own writeup, and the folders are meant to show how the work has grown over time.

## Projects

### [V1-SOC-lab](V1-SOC-lab/)
A simulated Windows enterprise network monitored by a Splunk SIEM. I built an Active Directory domain with Windows and Linux clients, forwarded logs into Splunk, ran common attacks (brute force, encoded PowerShell, PsExec lateral movement) mapped to MITRE ATT&CK, and wrote and validated detections for each. Full writeup, screenshots, and the detection queries are in the folder.

## Planned

- **V2**: advanced add-ons and expanded detection coverage building on V1
- **Help Desk Simulation Lab**: a separate lab focused on end-user support and troubleshooting workflows

More detail will land in each folder as I build it out.
