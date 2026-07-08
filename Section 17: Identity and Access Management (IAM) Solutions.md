# Identity and Access Management (IAM) Solutions

## Objectives

- Understand authentication, authorization, accounting, and identity lifecycle management.
- Explain access control models and privileged access concepts.
- Connect IAM to zero trust, cloud security, and incident prevention.

## Key Concepts

IAM controls who can access systems, what they can do, and how that activity is recorded. Weak IAM is one of the most common causes of security incidents.

Core IAM concepts:

- Identification
- Authentication
- Authorization
- Accounting
- Provisioning
- Deprovisioning
- Federation
- Single sign-on
- Multi-factor authentication
- Conditional access
- Privileged access management

## Authentication Factors

- Something you know: password or PIN
- Something you have: token, smart card, authenticator app
- Something you are: biometric factor
- Somewhere you are: location-based factor
- Something you do: behavior-based factor

## Access Control Models

| Model | Description |
| --- | --- |
| DAC | Owner controls access to resources |
| MAC | System-enforced labels and classifications |
| RBAC | Access based on job role |
| ABAC | Access based on attributes such as user, device, time, and location |
| Rule-based | Access based on defined rules or conditions |

## Identity Lifecycle

1. Create identity after approval.
2. Assign least-privilege access.
3. Review access regularly.
4. Modify access when roles change.
5. Remove access immediately during offboarding.
6. Monitor privileged and unusual activity.

## Cloud IAM

Cloud IAM requires careful permission design. Overly broad roles, exposed access keys, public storage, and weak logging can create major risk. Least privilege, MFA, short-lived credentials, and regular access review are critical.

## What I Focus On

I connect IAM to user administration, permissions management, cloud access review, Windows/Linux administration, and SOC investigation of suspicious logons.