# Automation and Orchestration

## Objectives
- Understand the difference between automation and orchestration
- Identify common security automation use cases
- Explain benefits and risks of automated response

## Automation
- **Automation:** Using technology to perform repeatable tasks with minimal manual work
- Helps reduce mistakes, save time, and make processes consistent

## Orchestration
- **Orchestration:** Coordinating multiple automated tasks across tools, systems, or teams
- Example: SIEM alert creates a ticket, enriches an IP address, checks threat intelligence, and notifies an analyst

## Common Security Automation Uses
- Parse logs
- Enrich IP addresses or domains
- Create tickets from alerts
- Disable compromised accounts
- Block malicious indicators
- Run vulnerability scans
- Deploy patches
- Send incident notifications
- Generate reports

## SOAR
- **SOAR:** Security Orchestration, Automation, and Response
- SOAR platforms connect alerts, tools, playbooks, approvals, and response actions

## Benefits
- Faster response
- Fewer manual errors
- Repeatable process
- Better evidence collection
- Reduced analyst workload

## Risks
- Wrong logic can cause wrong action
- Over-permissioned automation can increase damage
- High-impact actions may need human approval
- Automated actions should be logged and tested

## Key Takeaway
- Automation is useful when the workflow is repeatable, tested, logged, and controlled.