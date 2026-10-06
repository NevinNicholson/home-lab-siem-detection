# Home Labs

A collection of hands-on IT and security labs I've built to learn practical help desk, SOC, and detection work. Each folder is a self-contained project with its own writeup and screenshots, and the folders are meant to show how the work has grown over time.

Both labs run on the same simulated enterprise network: a Windows Server 2022 Active Directory domain (corp.lab) with Windows 11 and Linux clients, all running in VirtualBox on an isolated internal network.

## Projects

### [V1-SOC-lab](./V1-SOC-lab)
A simulated Windows enterprise network monitored by a Splunk SIEM. I built an Active Directory domain with Windows and Linux clients, forwarded logs into Splunk, ran common attacks (brute force, encoded PowerShell, PsExec lateral movement) mapped to MITRE ATT&CK, and wrote and validated detections for each. Full writeup, screenshots, and the detection queries are in the folder.

### [Help-Desk-lab](./Help-Desk-lab)
A help desk simulation on the same Active Directory domain. I worked through 8 realistic support tickets: onboarding a new hire, unlocking a locked-out account, offboarding an employee, granting shared folder access, mapping a network drive through Group Policy, troubleshooting a DNS problem, fixing a GPO that stopped applying, and sorting out a share vs NTFS permissions conflict. I also wrote up 2 real issues I found and fixed in the lab along the way. Each ticket covers the issue, diagnosis, resolution, and screenshots.

## Planned

- **V2 SOC lab**: advanced add-ons and expanded detection coverage building on V1

More detail will land in each folder as I build it out.
