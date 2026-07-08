# Identity and Access Management (IAM) Solutions

## Objectives
- 4.6 - Given a scenario, implement identity and access management
- Understand authentication, authorization, and accounting
- Compare common access control models

## Table of Contents

1. [IAM](#iam)
2. [AAA](#aaa)
3. [Authentication Factors](#authentication-factors)
4. [MFA](#mfa)
5. [Access Control Models](#access-control-models)
6. [Identity Lifecycle](#identity-lifecycle)
7. [Privileged Access Management](#privileged-access-management)
8. [Key Takeaways](#key-takeaways)

## IAM

- **Identity and Access Management (IAM):** Processes and technologies used to manage identities and control access to systems and data.
- IAM answers two main questions:
  - Who are you?
  - What are you allowed to access?

## AAA

- **Authentication:** Verifies identity.
- **Authorization:** Determines what the identity can access.
- **Accounting:** Tracks activity for logs, audits, and investigations.

Example:
- A user logs in with a password and MFA. That is authentication.
- The user can access only the finance folder. That is authorization.
- The system logs file access. That is accounting.

## Authentication Factors

- **Something you know:** Password or PIN.
- **Something you have:** Token, smart card, authenticator app.
- **Something you are:** Biometric factor.
- **Somewhere you are:** Location-based factor.
- **Something you do:** Behavior-based factor.

## MFA

- **MFA:** Multi-Factor Authentication uses two or more different factor types.
- MFA reduces the risk of account compromise if a password is stolen.

Examples:
- Password + authenticator app
- Smart card + PIN
- Password + biometric

## Access Control Models

- **DAC:** Discretionary Access Control; owner decides who gets access.
- **MAC:** Mandatory Access Control; access is based on labels and classifications.
- **RBAC:** Role-Based Access Control; access is based on job role.
- **ABAC:** Attribute-Based Access Control; access is based on attributes such as user, device, time, location, or risk.
- **Rule-Based Access:** Access is controlled by defined rules.

## Identity Lifecycle

1. Create account after approval.
2. Assign least-privilege access.
3. Review access regularly.
4. Modify access when role changes.
5. Disable or remove access during offboarding.

## Privileged Access Management

- **PAM:** Privileged Access Management controls and monitors high-privilege accounts.
- Privileged accounts should have:
  - MFA
  - Strong logging
  - Approval workflow
  - Session recording when needed
  - Time-limited access

## Key Takeaways

- IAM is one of the most important security controls.
- Compromised accounts are common in real attacks, so identity must be protected carefully.