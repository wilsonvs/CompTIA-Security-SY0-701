# Incident Response

## Objectives
- 4.8 - Explain appropriate incident response activities
- Understand the incident response lifecycle
- Know common containment, eradication, and recovery actions

## Table of Contents

1. [Incident Response](#incident-response)
2. [Preparation](#preparation)
3. [Detection and Analysis](#detection-and-analysis)
4. [Containment](#containment)
5. [Eradication](#eradication)
6. [Recovery](#recovery)
7. [Lessons Learned](#lessons-learned)
8. [Key Takeaways](#key-takeaways)

## Incident Response

- **Incident Response:** Process of preparing for, detecting, analyzing, containing, eradicating, recovering from, and learning from security incidents.
- A structured process reduces confusion during high-pressure events.

## Preparation

Preparation includes:
- Playbooks
- Contact lists
- Logging
- Tools
- Access permissions
- Backups
- Training
- Tabletop exercises

## Detection and Analysis

- Determine whether an alert is a real incident.
- Identify affected users, systems, IPs, files, and data.
- Build an initial timeline.

Questions:
- What happened?
- When did it happen?
- Which assets are affected?
- Is the threat still active?
- What evidence supports the conclusion?

## Containment

- **Containment:** Limiting damage and stopping spread.

Examples:
- Disable account
- Isolate endpoint
- Block IP or domain
- Remove system from network
- Disable compromised API key

## Eradication

- **Eradication:** Removing the cause of the incident.

Examples:
- Remove malware
- Patch exploited vulnerability
- Delete persistence mechanism
- Rebuild compromised system
- Remove unauthorized account

## Recovery

- **Recovery:** Restoring systems to normal operation.

Examples:
- Restore from backup
- Reconnect cleaned systems
- Reset credentials
- Monitor for recurrence
- Validate business service operation

## Lessons Learned

- Review what happened after the incident.
- Identify root cause, timeline, impact, response actions, and improvements.

## Key Takeaways

- Incident response controls damage and restores operations.
- Documentation and evidence are important throughout the process.