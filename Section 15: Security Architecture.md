# Security Architecture

## Objectives
- 3.1 - Compare and contrast security implications of different architecture models
- Understand secure design principles
- Explain segmentation, zero trust, defense in depth, and least privilege

## Table of Contents

1. [Security Architecture](#security-architecture)
2. [Defense in Depth](#defense-in-depth)
3. [Zero Trust](#zero-trust)
4. [Segmentation](#segmentation)
5. [Least Privilege](#least-privilege)
6. [Cloud Architecture](#cloud-architecture)
7. [Application Architecture](#application-architecture)
8. [Key Takeaways](#key-takeaways)

## Security Architecture

- **Security Architecture:** The design of systems, networks, applications, cloud resources, and controls to protect confidentiality, integrity, and availability.
- Good architecture reduces attack paths and limits damage when one control fails.

## Defense in Depth

- **Defense in Depth:** Using multiple layers of security controls.
- If one control fails, another control may still reduce the attack.

Examples:
- Firewall
- MFA
- Endpoint protection
- Network segmentation
- Logging and monitoring
- Backups
- Security awareness

## Zero Trust

- **Zero Trust:** Security model based on never trusting by default and always verifying.
- Zero trust assumes threats may exist inside and outside the network.

Zero trust ideas:
- Verify identity
- Use least privilege
- Check device health
- Monitor activity
- Segment access
- Continuously evaluate risk

## Segmentation

- **Segmentation:** Dividing networks or systems into smaller isolated areas.
- Segmentation helps reduce lateral movement.

Examples:
- Separate guest Wi-Fi from internal network
- Separate servers from user workstations
- Separate payment systems from general systems
- Use VLANs, firewalls, and access control lists

## Least Privilege

- **Least Privilege:** Users and systems should only have access needed to perform required tasks.
- Reduces impact if an account or system is compromised.

## Cloud Architecture

Cloud architecture should consider:
- Shared responsibility model
- IAM roles and permissions
- Security groups
- Encryption
- Logging
- Key management
- Backup
- Public exposure

## Application Architecture

Secure applications should include:
- Authentication
- Authorization
- Input validation
- Secure session management
- Secure APIs
- Error handling
- Logging
- Secrets management

## Key Takeaways

- Security architecture is secure design before problems happen.
- Good design uses layers, least privilege, segmentation, and monitoring.