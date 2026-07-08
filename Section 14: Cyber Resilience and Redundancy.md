# Cyber Resilience and Redundancy

## Objectives
- Understand how resilience supports availability
- Explain redundancy, backups, and recovery planning
- Know common recovery terms such as RTO and RPO

## Table of Contents

1. [Cyber Resilience](#cyber-resilience)
2. [Redundancy](#redundancy)
3. [Backups](#backups)
4. [Recovery Terms](#recovery-terms)
5. [Site Types](#site-types)
6. [Business Continuity and Disaster Recovery](#business-continuity-and-disaster-recovery)
7. [Testing and Validation](#testing-and-validation)
8. [Key Takeaways](#key-takeaways)

## Cyber Resilience

- **Cyber Resilience:** The ability to continue operating, respond to disruption, recover services, and improve after an incident.
- Resilience is closely connected to availability in the CIA triad.
- The goal is to reduce downtime and keep critical business services running.

## Redundancy

- **Redundancy:** Duplicate systems, components, or paths used to avoid a single point of failure.

Examples:
- Multiple power supplies
- UPS and generator
- RAID storage
- Load balancer
- Failover server
- Multiple network links
- Secondary DNS
- Replicated database
- Cloud availability zones

## Backups

- **Backup:** A copy of data that can be restored after deletion, corruption, ransomware, hardware failure, or disaster.

Backup best practices:
- Encrypt backups
- Protect backup credentials
- Monitor backup jobs
- Test restoration
- Keep offline or immutable copies where possible
- Store backups separately from production systems

Backup types:
- **Full Backup:** Copies all selected data.
- **Incremental Backup:** Copies changes since the last backup.
- **Differential Backup:** Copies changes since the last full backup.

## Recovery Terms

- **RTO:** Recovery Time Objective; how quickly a service must be restored.
- **RPO:** Recovery Point Objective; how much data loss is acceptable.
- **MTD:** Maximum Tolerable Downtime; longest acceptable outage.
- **MTTR:** Mean Time To Repair.
- **MTBF:** Mean Time Between Failures.

## Site Types

- **Hot Site:** Fully ready recovery site with systems and data available quickly.
- **Warm Site:** Partially ready site that needs some setup.
- **Cold Site:** Basic facility with little or no active equipment.

## Business Continuity and Disaster Recovery

- **Business Continuity:** Keeps essential business functions operating during disruption.
- **Disaster Recovery:** Restores technology systems after disruption.

Example:
- Business continuity may define how payroll continues.
- Disaster recovery may define how payroll servers are restored.

## Testing and Validation

- Plans must be tested before a real incident.
- Backup restore tests confirm that recovery is actually possible.
- Tabletop exercises help teams practice decisions and communication.

## Key Takeaways

- Redundancy helps prevent downtime.
- Backups help recover after failure or compromise.
- Recovery plans must be tested, not only documented.