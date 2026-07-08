# Malicious Activity

## Objectives
- Recognize indicators of malicious activity
- Identify useful logs for investigation
- Understand basic triage questions during suspicious activity review

## Malicious Activity
- **Malicious Activity:** Any action intended to steal data, damage systems, gain unauthorized access, disrupt operations, or avoid detection
- Malicious activity may appear in endpoint logs, authentication logs, network traffic, email, or cloud audit logs

## Indicators of Compromise
- **IOC:** Evidence that a system, account, or network may be compromised
- Examples:
  - Unknown process
  - Malware hash
  - Suspicious IP address
  - Malicious domain
  - Unexpected admin account
  - Disabled security tool
  - Unusual outbound traffic
  - Repeated failed logons
  - Login from unusual location

## Common Log Sources
- Windows Security logs
- Linux authentication logs
- Firewall logs
- DNS logs
- VPN logs
- Proxy logs
- EDR alerts
- Email security logs
- Cloud audit logs

## Triage Questions
- What triggered the alert?
- Which user, host, or IP is involved?
- Is this activity normal for the user or system?
- What happened before and after the event?
- Are other systems affected?
- Is containment needed?

## Common Response Actions
- Disable account
- Reset password
- Isolate endpoint
- Block malicious IP or domain
- Preserve evidence
- Review related logs
- Patch affected system

## Key Takeaway
- Malicious activity investigation depends on evidence, context, timeline, and scope.