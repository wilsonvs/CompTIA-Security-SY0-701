# Security Architecture

## Objectives
- Understand how secure design reduces risk
- Explain defense in depth, segmentation, zero trust, and least privilege
- Connect architecture choices to confidentiality, integrity, and availability

## Security Architecture
- **Security Architecture:** The design of systems, networks, applications, cloud environments, and controls to protect an organization
- Good architecture reduces attack paths and limits damage if one control fails

## Secure Design Principles
- **Defense in Depth:** Using multiple layers of security controls
- **Least Privilege:** Giving users and systems only the access they need
- **Zero Trust:** Never trust by default; always verify
- **Segmentation:** Separating networks or systems to reduce lateral movement
- **Fail Secure:** Systems should fail in a secure state when possible
- **Separation of Duties:** Dividing responsibilities to reduce misuse or fraud

## Network Architecture
- Firewalls control traffic between networks
- VLANs separate network segments
- VPNs protect remote access
- IDS/IPS tools detect or block suspicious traffic
- Proxies inspect and control web traffic

## Cloud Architecture
- Cloud security depends on shared responsibility
- Important cloud controls include:
  - IAM
  - Security groups
  - Encryption
  - Logging
  - Private storage
  - Backup
  - Key management

## Application Architecture
- Secure applications need authentication, authorization, input validation, secure APIs, logging, and secrets management

## Key Takeaway
- Security architecture is about designing systems so they are harder to attack, easier to monitor, and easier to recover.