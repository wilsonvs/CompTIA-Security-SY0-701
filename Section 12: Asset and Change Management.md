# Asset and Change Management

## Objectives
- Understand why asset inventory is important for security
- Explain asset lifecycle management
- Understand how change management reduces operational and security risk

## Table of Contents

1. [Asset Management](#asset-management)
2. [Asset Inventory](#asset-inventory)
3. [Asset Classification](#asset-classification)
4. [Asset Lifecycle](#asset-lifecycle)
5. [Change Management](#change-management)
6. [Change Records](#change-records)
7. [Security Impact of Poor Change Management](#security-impact-of-poor-change-management)
8. [Key Takeaways](#key-takeaways)

## Asset Management

- **Asset Management:** The process of tracking, protecting, maintaining, and retiring organizational assets.
- Assets include hardware, software, data, cloud services, accounts, licenses, network devices, and business processes.
- Security teams cannot protect systems they do not know exist.

## Asset Inventory

- **Asset Inventory:** A list of assets and their important details.
- Asset inventory supports patching, vulnerability management, incident response, audits, and lifecycle planning.

Common inventory fields:
- Asset name
- Asset ID
- Owner
- Department
- Location
- IP address
- Hostname
- Operating system
- Software installed
- Business function
- Criticality
- Data classification
- Patch status
- Warranty or support status

## Asset Classification

- **Classification:** Labeling assets based on importance, sensitivity, or business impact.
- Classification helps decide how strongly an asset should be protected.

Examples:
- Public
- Internal
- Confidential
- Restricted
- Critical

Example:
- A public website and payroll database should not have the same level of access control because the payroll database contains more sensitive data.

## Asset Lifecycle

Asset lifecycle stages:
1. **Procurement:** Asset is purchased or approved.
2. **Deployment:** Asset is configured and placed into service.
3. **Maintenance:** Asset is patched, monitored, and supported.
4. **Review:** Ownership, access, and configuration are checked.
5. **Decommissioning:** Asset is removed from active use.
6. **Disposal:** Asset is securely wiped, destroyed, recycled, or returned.

## Change Management

- **Change Management:** A formal process for requesting, reviewing, approving, implementing, and documenting changes.
- Change management reduces downtime, misconfiguration, and unauthorized changes.
- Changes can include software updates, firewall rule changes, system upgrades, cloud configuration changes, and access control changes.

## Change Records

A good change record includes:
- Change description
- Business reason
- Systems affected
- Risk and impact
- Approval
- Implementation steps
- Testing plan
- Backout plan
- Scheduled window
- Post-change validation

## Security Impact of Poor Change Management

Poor change management can cause:
- Outages
- Exposed services
- Broken logging
- Weak firewall rules
- Lost data
- Privilege mistakes
- Failed backups
- Security tool misconfiguration

## Key Takeaways

- Asset management gives visibility into what must be protected.
- Change management controls how systems are modified.
- Both processes support security, audit readiness, and incident response.