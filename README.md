# PwnCrypt-Threat-Hunt

📌 Overview
A zero-day ransomware strain, PwnCrypt, has been reported in the wild, leveraging PowerShell-based execution to encrypt and exfiltrate sensitive files. This report details my threat hunting investigation on the affected system (win-10-25a), covering file modifications, process execution, network activity, and persistence attempts.

Key Findings: ✔ PowerShell execution of exfiltratedata.ps1, used to stage, compress, and exfiltrate sensitive data.
✔ Outbound RDP connections to malicious IP (113.201.68.228), flagged for phishing and criminal activity.
✔ No persistence mechanisms detected (no registry run keys or scheduled tasks).

📌 Objective: Identify and analyze the execution, impact, and potential mitigation of PwnCrypt ransomware.
