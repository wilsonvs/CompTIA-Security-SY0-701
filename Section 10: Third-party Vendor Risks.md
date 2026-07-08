# Third-party Vendor Risks

## Objectives
- 5.3 - Explain processes associated with third-party risk assessment and management
- Understand vendor, supplier, and supply-chain security risks
- Know what should be reviewed before granting third-party access

## Table of Contents

1. [Third-party Risk](#third-party-risk)
2. [Supply Chain Risk](#supply-chain-risk)
3. [Vendor Due Diligence](#vendor-due-diligence)
4. [Vendor Contracts and SLAs](#vendor-contracts-and-slas)
5. [Access Control for Vendors](#access-control-for-vendors)
6. [Ongoing Monitoring](#ongoing-monitoring)
7. [Vendor Offboarding](#vendor-offboarding)
8. [Key Takeaways](#key-takeaways)

## Third-party Risk

- **Third-party Risk:** Risk created when an external vendor, supplier, contractor, cloud provider, software provider, or managed service provider supports business operations.
- Vendors may need access to systems, data, networks, buildings, or cloud resources.
- This access can create security risk if the vendor has weak controls.

Examples of third parties:
- Cloud service provider
- Payroll provider
- Managed IT service provider
- Software vendor
- Data processing company
- Contractor or consultant
- Hardware supplier

## Supply Chain Risk

- **Supply Chain Risk:** Risk that comes from products, services, software, hardware, vendors, or subcontractors used by an organization.
- A supply-chain attack targets a trusted relationship instead of attacking the final organization directly.

Examples:
- Compromised software update
- Vulnerable third-party library
- Vendor account compromise
- Insecure API integration
- Malicious code inserted into software
- Cloud provider outage

## Vendor Due Diligence

- **Due Diligence:** Reviewing a vendor before using the product or service.
- The goal is to understand whether the vendor can protect data and systems properly.

Common review items:
- Security questionnaire
- SOC 2 report
- ISO 27001 certification
- PCI DSS, HIPAA, or other compliance reports when applicable
- Data handling practices
- Encryption methods
- Access control process
- Incident response process
- Business continuity and disaster recovery plan
- Vulnerability management process
- Subcontractor list

## Vendor Contracts and SLAs

- **SLA:** Service Level Agreement that defines expected service performance.
- Contracts should explain security responsibilities clearly.

Important contract items:
- Data ownership
- Breach notification timeframe
- Audit rights
- Encryption requirements
- Logging and monitoring expectations
- Availability requirements
- RTO and RPO
- Right to terminate
- Secure data return or destruction

## Access Control for Vendors

- Vendor access should follow least privilege.
- Access should be temporary when possible.
- Vendor accounts should be monitored and reviewed regularly.

Good practices:
- Require MFA
- Use named accounts instead of shared accounts
- Restrict access by time, IP, or role
- Log vendor activity
- Remove access when work is complete
- Review privileged access frequently

## Ongoing Monitoring

- Vendor risk management is not only a one-time review.
- Vendors should be monitored during the relationship.

Monitoring can include:
- Annual reassessment
- Access reviews
- Contract renewal review
- Incident notification review
- Compliance report review
- Security news or breach monitoring

## Vendor Offboarding

- Offboarding is important because old vendor access can become a security weakness.

Vendor offboarding steps:
- Disable accounts
- Revoke API keys and tokens
- Remove VPN or remote access
- Retrieve company assets
- Confirm data deletion or return
- Update documentation
- Review logs if needed

## Key Takeaways

- Third-party vendors can become an attack path into an organization.
- Vendor access should be reviewed, limited, monitored, and removed when no longer needed.
- Contracts should define security expectations before problems occur.