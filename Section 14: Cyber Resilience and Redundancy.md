# Cyber Resilience and Redundancy

## Objectives

- Understand how redundancy, backup, disaster recovery, and business continuity support availability.
- Explain recovery objectives and resilience planning.
- Connect resilience to incident response and operational security.

## Key Concepts

Cyber resilience is the ability to continue operating, recover quickly, and adapt after disruption. Redundancy reduces single points of failure, while recovery planning defines how services are restored.

Important terms:

- **RTO:** Recovery Time Objective. Maximum acceptable time to restore a service.
- **RPO:** Recovery Point Objective. Maximum acceptable data loss measured in time.
- **MTTR:** Mean Time To Repair.
- **MTBF:** Mean Time Between Failures.
- **High availability:** Design that keeps services running through component failure.
- **Fault tolerance:** Ability to continue operating despite failure.

## Redundancy Examples

- Multiple power supplies
- UPS and generators
- RAID storage
- Load balancers
- Failover clusters
- Multiple network paths
- Secondary DNS
- Cloud availability zones
- Replicated databases
- Hot, warm, and cold sites

## Backup Considerations

Backups should be protected, tested, and monitored. A backup is only useful if it can be restored.

Good backup practices:

- Define backup frequency by data criticality.
- Encrypt backup data.
- Protect backup credentials.
- Keep offline or immutable copies where appropriate.
- Test restoration regularly.
- Monitor backup job failures.
- Document restore procedures.

## Business Continuity and Disaster Recovery

Business continuity keeps essential operations running. Disaster recovery restores technology services after disruption. Both require clear priorities, ownership, communication, and testing.

## What I Focus On

I connect resilience to incident response planning, backup validation, outage triage, system administration experience, and availability-focused security controls.