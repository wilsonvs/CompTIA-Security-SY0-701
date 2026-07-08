# Automation and Orchestration

## Objectives
- Understand automation and orchestration concepts
- Explain common security automation use cases
- Identify benefits and risks of automated response

## Table of Contents

1. [Automation](#automation)
2. [Orchestration](#orchestration)
3. [SOAR](#soar)
4. [Automation Use Cases](#automation-use-cases)
5. [Benefits](#benefits)
6. [Risks](#risks)
7. [Key Takeaways](#key-takeaways)

## Automation

- **Automation:** Using technology to perform repeatable tasks with minimal manual work.
- Automation is useful for tasks that are common, predictable, and well-defined.

Examples:
- Parse logs
- Generate report
- Create ticket
- Run scan
- Send notification

## Orchestration

- **Orchestration:** Coordinating multiple automated tasks across tools, systems, and teams.

Example:
- A SIEM alert triggers enrichment.
- The IP is checked against threat intelligence.
- A ticket is created.
- An analyst is notified.
- A firewall block is prepared for approval.

## SOAR

- **SOAR:** Security Orchestration, Automation, and Response.
- SOAR platforms connect alerts, playbooks, tools, approvals, and response actions.

## Automation Use Cases

Common security automation uses:
- Enrich IP addresses and domains
- Disable compromised accounts
- Block malicious indicators
- Run vulnerability scans
- Create incident tickets
- Collect endpoint evidence
- Send incident notifications
- Generate compliance reports
- Deploy patches

## Benefits

- Faster response
- Fewer manual errors
- Consistent process
- Better evidence collection
- Reduced analyst workload
- Easier reporting

## Risks

- Wrong logic can cause wrong actions.
- Over-permissioned automation can create more damage.
- High-impact actions may need human approval.
- Automated actions should be logged, tested, and reviewed.

## Key Takeaways

- Automation is best for repeatable tasks.
- Orchestration connects multiple tools into a workflow.
- Automated response should be controlled and monitored.