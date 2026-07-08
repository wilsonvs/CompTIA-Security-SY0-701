# Fundamentals of Security

## Objectives
- 1.1 - Compare and contrast various types of security controls
- 1.2 - Summarize fundamental security concepts
- Understand the CIA triad, AAA, non-repudiation, and Zero Trust

## Table of Contents

1. [Information Security](#information-security)
2. [CIA Triad](#cia-triad)
3. [Non-Repudiation](#non-repudiation)
4. [Authentication, Authorization, and Accounting](#authentication-authorization-and-accounting)
5. [Security Control Categories](#security-control-categories)
6. [Security Control Types](#security-control-types)
7. [Threats, Vulnerabilities, and Risk](#threats-vulnerabilities-and-risk)
8. [Gap Analysis](#gap-analysis)
9. [Zero Trust](#zero-trust)
10. [Key Takeaways](#key-takeaways)

## Information Security

- **Information Security:** Protecting data and information from unauthorized access, disclosure, modification, disruption, or destruction.
- **Information Systems Security:** Protecting systems that store, process, or transmit information.

Examples:
- Protecting customer records
- Securing servers and endpoints
- Restricting access to sensitive folders
- Monitoring logs for suspicious activity

## CIA Triad

- **Confidentiality:** Ensures information is only accessible to authorized users.
  - Example: Encryption, access control, data masking.

- **Integrity:** Ensures data remains accurate, complete, and unchanged unless modified by an authorized user.
  - Example: Hashing, checksums, digital signatures.

- **Availability:** Ensures systems and data are accessible when needed.
  - Example: Redundancy, backups, failover, disaster recovery.

## Non-Repudiation

- **Non-Repudiation:** Provides proof that an action or transaction cannot be denied later.
- Digital signatures are commonly used for non-repudiation.

Example:
- If a user digitally signs a document, the signature helps prove who signed it and that the document was not changed.

## Authentication, Authorization, and Accounting

- **Authentication:** Verifies identity.
- **Authorization:** Determines what access is allowed.
- **Accounting:** Tracks user actions for logs, audits, and investigations.

Example:
- Logging in with a password and MFA is authentication.
- Accessing only assigned folders is authorization.
- System logs showing file access are accounting.

## Security Control Categories

- **Technical Controls:** Technology-based controls.
  - Example: Firewall, encryption, MFA.

- **Managerial Controls:** Administrative or governance controls.
  - Example: Risk assessment, security policy, audit.

- **Operational Controls:** Day-to-day security processes.
  - Example: Security awareness, incident response, change management.

- **Physical Controls:** Controls that protect physical assets.
  - Example: Locks, cameras, guards, badges.

## Security Control Types

- **Preventive:** Stops an event before it happens.
- **Detective:** Identifies an event or suspicious activity.
- **Corrective:** Fixes or restores after an event.
- **Deterrent:** Discourages unwanted behavior.
- **Compensating:** Alternative control when the preferred control cannot be used.
- **Directive:** Tells users what is expected.

## Threats, Vulnerabilities, and Risk

- **Threat:** Anything that can cause harm.
- **Vulnerability:** A weakness that can be exploited.
- **Risk:** The possibility that a threat will exploit a vulnerability and cause impact.

Example:
- Threat: Attacker
- Vulnerability: Unpatched server
- Risk: Server compromise

## Gap Analysis

- **Gap Analysis:** Comparing current state to desired state.
- Used to identify what is missing or weak.

Example:
- Current state: No MFA on admin accounts.
- Desired state: MFA required for all admin accounts.
- Gap: Admin MFA is missing.

## Zero Trust

- **Zero Trust:** Security model based on never trusting by default and always verifying.

Core ideas:
- Verify identity
- Use least privilege
- Monitor continuously
- Segment access
- Assume breach

## Key Takeaways

- The CIA triad is the foundation of security.
- AAA explains identity and access activity.
- Security controls should be layered to prevent, detect, and correct security problems.