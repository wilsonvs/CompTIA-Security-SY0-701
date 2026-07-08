# Investigating an Incident

## Objectives

- Understand how to investigate alerts and incidents using evidence.
- Build timelines from logs, user activity, network activity, and endpoint events.
- Connect investigation findings to containment and reporting.

## Investigation Workflow

1. Confirm the alert or report.
2. Identify affected users, hosts, IPs, and services.
3. Collect relevant logs and evidence.
4. Build a timeline.
5. Determine scope and impact.
6. Identify likely root cause.
7. Recommend containment and remediation.
8. Document findings clearly.

## Evidence Sources

- Authentication logs
- Endpoint process events
- File modification timestamps
- EDR alerts
- Firewall and proxy logs
- DNS queries
- Email headers
- VPN logs
- Cloud audit trails
- Web server logs
- Vulnerability and patch records

## Timeline Building

A timeline should show what happened before, during, and after the suspicious activity. It helps separate normal activity from attacker behavior.

Useful timeline fields:

- Timestamp
- Source
- User
- Host
- Event type
- Event detail
- Analyst note

## Scope Questions

- Is this one user or many users?
- Is this one host or many hosts?
- Did the activity originate internally or externally?
- Was privilege escalation attempted?
- Was data accessed, changed, or exfiltrated?
- Are there related alerts?

## What I Focus On

I connect investigation work to Windows log analysis, phishing triage, network traffic review, IOC analysis, and structured incident reporting.