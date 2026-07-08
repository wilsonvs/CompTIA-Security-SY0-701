# Hardening

## Objectives
- 4.1 - Given a scenario, apply common security techniques to computing resources
- Understand how hardening reduces attack surface
- Identify hardening methods for systems, networks, cloud, and applications

## Table of Contents

1. [Hardening](#hardening)
2. [System Hardening](#system-hardening)
3. [Network Hardening](#network-hardening)
4. [Cloud Hardening](#cloud-hardening)
5. [Application Hardening](#application-hardening)
6. [Baseline Configuration](#baseline-configuration)
7. [Key Takeaways](#key-takeaways)

## Hardening

- **Hardening:** The process of securely configuring systems and removing unnecessary exposure.
- Hardening reduces the number of ways an attacker can compromise a system.

Common hardening steps:
- Remove unused software
- Disable unused services
- Apply patches
- Change default passwords
- Disable default accounts if possible
- Enable logging
- Enforce MFA
- Restrict administrator access
- Use encryption

## System Hardening

Examples:
- Patch operating systems
- Enable endpoint protection
- Configure host firewall
- Enforce account lockout
- Disable unnecessary ports
- Restrict local admin rights
- Enable audit logs

## Network Hardening

Examples:
- Review firewall rules
- Disable unused switch ports
- Use secure management protocols
- Segment networks
- Update firmware
- Secure wireless settings
- Disable insecure protocols

## Cloud Hardening

Examples:
- Use least-privilege IAM
- Keep storage private by default
- Restrict security groups
- Enable cloud audit logs
- Encrypt data
- Rotate access keys
- Monitor configuration changes

## Application Hardening

Examples:
- Validate input
- Protect secrets
- Use secure headers
- Patch dependencies
- Enforce authentication and authorization
- Log security events
- Avoid detailed error messages

## Baseline Configuration

- **Baseline:** Minimum approved configuration for a system.
- Baselines help keep systems consistent and secure.

Examples:
- Windows server baseline
- Linux server baseline
- Firewall baseline
- Cloud IAM baseline
- Browser security baseline

## Key Takeaways

- Hardening is preventive security.
- Secure baselines help make systems consistent, auditable, and easier to maintain.