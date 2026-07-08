# Malicious Activity

## Objectives

- Recognize indicators of compromise and suspicious activity.
- Understand how malicious behavior appears in logs, endpoints, email, and networks.
- Connect malicious activity analysis to SOC triage and incident response.

## Indicators of Compromise

Indicators of compromise are evidence that a system, account, or network may have been affected by malicious activity.

Examples:

- Unknown processes
- Suspicious PowerShell usage
- Unusual outbound connections
- Repeated failed logons
- Successful login after many failures
- Login from impossible travel locations
- New unauthorized admin account
- Disabled security tools
- Suspicious scheduled tasks
- Unexpected file encryption
- Malicious domains or IP addresses
- Known malware hashes

## Log Sources

Useful sources for malicious activity investigation:

- Windows Security logs
- Sysmon logs
- Linux authentication logs
- Firewall logs
- DNS logs
- Proxy logs
- VPN logs
- EDR alerts
- Email security logs
- Cloud audit logs
- Web server logs

## Triage Questions

- What triggered the alert?
- Which user, host, IP address, or process is involved?
- Is the activity expected for this user or system?
- What happened before and after the event?
- Is there evidence of persistence, privilege escalation, or lateral movement?
- Are other systems affected?
- What containment action is needed?

## Common Response Actions

- Disable compromised accounts
- Reset credentials
- Isolate affected endpoints
- Block malicious indicators
- Preserve evidence
- Review logs for scope
- Patch exploited systems
- Restore from clean backups if needed

## What I Focus On

I connect malicious activity analysis to SIEM triage, incident timelines, Windows authentication events, phishing analysis, and IOC reporting.