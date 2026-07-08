# Vulnerabilities and Attacks

## Objectives
- 2.3 - Explain various types of vulnerabilities
- 2.4 - Given a scenario, analyze indicators of malicious activity
- Understand common attacks and mitigation methods

## Table of Contents

1. [Vulnerabilities](#vulnerabilities)
2. [Attack Surface](#attack-surface)
3. [Common Vulnerabilities](#common-vulnerabilities)
4. [Common Attacks](#common-attacks)
5. [Web Application Attacks](#web-application-attacks)
6. [Password Attacks](#password-attacks)
7. [Mitigations](#mitigations)
8. [Key Takeaways](#key-takeaways)

## Vulnerabilities

- **Vulnerability:** A weakness in software, hardware, configuration, process, or design.
- Vulnerabilities may allow unauthorized access, data theft, service disruption, privilege escalation, or malware execution.

## Attack Surface

- **Attack Surface:** All possible points where an attacker can try to enter, interact with, or affect a system.

Examples:
- Public website
- VPN login page
- Email inbox
- User accounts
- APIs
- Cloud storage
- Wireless network
- Remote desktop service
- Third-party integration

## Common Vulnerabilities

- Missing patches
- Weak passwords
- Default credentials
- Misconfigured firewall
- Public cloud storage
- Excessive permissions
- Unencrypted sensitive data
- Insecure APIs
- Poor input validation
- Unsupported software
- Open ports and services

## Common Attacks

- **Phishing:** Tricks users into revealing information or running malicious content.
- **Malware:** Software designed to harm systems or steal data.
- **Ransomware:** Malware that encrypts files and demands payment.
- **DoS/DDoS:** Attack that disrupts service availability.
- **Privilege Escalation:** Gaining higher permissions than originally assigned.
- **Man-in-the-Middle:** Intercepting or altering communication between two parties.

## Web Application Attacks

- **SQL Injection:** Injecting SQL commands into an application to access or modify database data.
- **XSS:** Cross-site scripting; running malicious scripts in a victim browser.
- **CSRF:** Cross-site request forgery; tricking a user browser into performing an unwanted action.
- **Directory Traversal:** Accessing files outside the intended directory.

## Password Attacks

- **Brute Force:** Trying many password combinations.
- **Password Spraying:** Trying one or a few common passwords across many accounts.
- **Credential Stuffing:** Using leaked usernames and passwords from another breach.
- **Dictionary Attack:** Trying passwords from a wordlist.

## Mitigations

- Patch systems
- Enforce MFA
- Use least privilege
- Validate input
- Segment networks
- Encrypt sensitive data
- Monitor logs
- Disable unused services
- Apply secure configuration baselines
- Train users to recognize phishing

## Key Takeaways

- Vulnerabilities create opportunities for attacks.
- Reducing attack surface and applying layered controls lowers risk.