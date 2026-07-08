# Alerting and Monitoring

## Objectives
- 4.4 - Explain security alerting and monitoring concepts and tools
- Understand important log sources
- Explain alert quality, tuning, and triage

## Table of Contents

1. [Monitoring](#monitoring)
2. [Alerting](#alerting)
3. [Log Sources](#log-sources)
4. [SIEM](#siem)
5. [Alert Examples](#alert-examples)
6. [Alert Tuning](#alert-tuning)
7. [Triage](#triage)
8. [Key Takeaways](#key-takeaways)

## Monitoring

- **Monitoring:** Collecting and reviewing activity from systems, networks, applications, cloud platforms, and security tools.
- Monitoring provides visibility into normal and abnormal behavior.

## Alerting

- **Alert:** A notification that specific activity may require investigation.
- Alerts may come from SIEM, EDR, IDS/IPS, firewalls, cloud tools, or email security systems.

A good alert should include:
- Alert name
- Severity
- User
- Host
- IP address
- Timestamp
- Source log
- Reason it triggered
- Suggested triage steps

## Log Sources

Important log sources:
- Authentication logs
- Firewall logs
- DNS logs
- VPN logs
- Proxy logs
- Endpoint logs
- Cloud audit logs
- Email security logs
- Web server logs

## SIEM

- **SIEM:** Security Information and Event Management.
- A SIEM collects, stores, searches, and correlates logs from multiple sources.
- SIEM tools help analysts investigate activity across systems.

## Alert Examples

- Multiple failed logons
- Successful login after repeated failures
- Impossible travel
- Malware detection
- Suspicious PowerShell command
- New administrator account
- Public cloud storage change
- Large outbound data transfer

## Alert Tuning

- **Tuning:** Adjusting alert logic to improve accuracy and reduce noise.

Tuning may include:
- Thresholds
- Allow lists
- Suppression windows
- Asset criticality
- User context
- Correlation with related alerts

## Triage

Basic triage questions:
- What triggered the alert?
- Is this expected activity?
- What user and system are involved?
- What happened before and after?
- Is containment needed?

## Key Takeaways

- Monitoring provides visibility.
- Alerting turns important activity into investigation work.
- Tuning helps reduce false positives and analyst fatigue.