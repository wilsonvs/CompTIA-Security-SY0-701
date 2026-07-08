# Investigating an Incident

## Objectives
- Understand how to investigate suspicious activity
- Identify useful evidence sources
- Build a basic incident timeline

## Investigation
- **Investigation:** The process of collecting and analyzing evidence to understand what happened, how it happened, what was affected, and what should be done next

## Basic Workflow
1. Confirm the alert or report
2. Identify user, host, IP, or application involved
3. Collect logs and evidence
4. Build a timeline
5. Determine scope
6. Identify possible root cause
7. Recommend containment and remediation
8. Document findings

## Evidence Sources
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

## Timeline
- **Timeline:** Ordered list of events showing what happened before, during, and after the incident
- Timeline fields may include:
  - Time
  - Source
  - User
  - Host
  - Event
  - Analyst note

## Scope Questions
- Is one user affected or many?
- Is one host affected or many?
- Was sensitive data accessed?
- Was privilege escalation attempted?
- Is the threat still active?
- Are there related alerts?

## Key Takeaway
- A good investigation is evidence-based and focuses on timeline, scope, impact, and next action.