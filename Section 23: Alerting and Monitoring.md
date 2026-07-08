# Alerting and Monitoring

## Objectives

- Understand how monitoring supports detection and response.
- Identify useful log sources and alert types.
- Connect SIEM alerting to triage, tuning, and escalation.

## Key Concepts

Monitoring collects security-relevant activity so unusual or malicious behavior can be detected. Alerting turns selected events into items that need investigation.

Important monitoring sources:

- Authentication logs
- Endpoint logs
- Firewall logs
- DNS logs
- VPN logs
- Proxy logs
- Email security logs
- Cloud audit logs
- Web server logs
- EDR telemetry
- IDS/IPS events

## Alert Quality

Good alerts are specific, explain why the activity matters, include useful context, and reduce unnecessary noise. Poor alerts create fatigue and slow response.

Alert fields should include:

- Alert name
- Severity
- Source log
- User
- Host
- IP address
- Timestamp
- Trigger logic
- Related events
- Recommended triage steps

## Common Alert Examples

- Multiple failed logons followed by success
- Impossible travel login
- New admin account created
- Malware detected
- Suspicious PowerShell command
- Unusual outbound traffic
- Large data transfer
- MFA denied repeatedly
- Cloud storage made public

## Tuning

Alert tuning improves signal quality. Tuning can include thresholds, allowlists, suppression windows, asset criticality, user context, and correlation with related events.

## What I Focus On

I connect alerting and monitoring to SOC triage, SIEM logic, Windows Event ID analysis, Python log triage, and incident timelines.