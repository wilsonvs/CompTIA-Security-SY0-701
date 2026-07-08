# Investigating an Incident

## Objectives
- Understand how to investigate suspicious activity using evidence
- Identify useful logs and artifacts
- Build a timeline and determine scope

## Table of Contents

1. [Investigation](#investigation)
2. [Evidence Sources](#evidence-sources)
3. [Timeline](#timeline)
4. [Scope](#scope)
5. [Root Cause](#root-cause)
6. [Documentation](#documentation)
7. [Key Takeaways](#key-takeaways)

## Investigation

- **Investigation:** Process of collecting and analyzing evidence to understand what happened, how it happened, what was affected, and what action is needed.
- Investigations should be based on evidence, not assumptions.

## Evidence Sources

Common evidence sources:
- Authentication logs
- Endpoint logs
- Firewall logs
- DNS logs
- VPN logs
- Proxy logs
- Email headers
- Cloud audit logs
- EDR alerts
- File timestamps
- Process execution logs

## Timeline

- **Timeline:** Ordered list of events before, during, and after suspicious activity.

Timeline fields:
- Timestamp
- Source
- User
- Host
- IP address
- Event
- Analyst note

Example:
- 10:03 - Multiple failed logins from external IP
- 10:08 - Successful login
- 10:12 - New mailbox forwarding rule created

## Scope

- **Scope:** The full range of affected users, systems, data, and services.

Scope questions:
- Is one user affected or many?
- Is one host affected or many?
- Was sensitive data accessed?
- Was privilege escalation attempted?
- Is the attacker still active?
- Are there related alerts?

## Root Cause

- **Root Cause:** Main reason the incident happened.

Examples:
- Stolen credentials
- Missing patch
- Misconfigured cloud storage
- Phishing email
- Weak password
- Exposed remote access service

## Documentation

Incident notes should include:
- Summary
- Timeline
- Evidence
- Impact
- Scope
- Actions taken
- Recommendations
- Lessons learned

## Key Takeaways

- Good investigations identify what happened, how far it spread, and what must be fixed.
- Timelines make incident evidence easier to understand.