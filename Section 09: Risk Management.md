# Risk Management

## Objectives
- 5.2 - Explain elements of the risk management process
- 5.3 - Explain processes associated with third-party risk assessment and management
- 5.4 - Summarize elements of effective security compliance

## Table of Contents

1. [Risk Management](#risk-management)
2. [Threats, Vulnerabilities, and Risk](#threats-vulnerabilities-and-risk)
3. [Likelihood and Impact](#likelihood-and-impact)
4. [Types of Risk](#types-of-risk)
5. [Risk Response Strategies](#risk-response-strategies)
6. [Risk Register](#risk-register)
7. [Risk Analysis](#risk-analysis)
8. [Business Impact Analysis](#business-impact-analysis)
9. [Key Takeaways](#key-takeaways)

## Risk Management

- **Risk Management:** The process of identifying, analyzing, prioritizing, treating, and monitoring risk.
- The purpose of risk management is not to remove all risk. The purpose is to understand risk clearly and reduce it to an acceptable level.
- Security teams use risk management to decide what should be fixed first, what can wait, and what requires leadership approval.

## Threats, Vulnerabilities, and Risk

- **Asset:** Anything valuable that needs protection, such as data, servers, laptops, user accounts, cloud storage, applications, or business processes.
- **Threat:** Anything that can cause harm, loss, damage, disclosure, disruption, or compromise.
- **Vulnerability:** A weakness that can be exploited by a threat.
- **Risk:** The possibility that a threat will exploit a vulnerability and cause impact to an asset or organization.

Example:
- Asset: Payroll server
- Threat: External attacker
- Vulnerability: Missing security patch
- Risk: Attacker exploits the vulnerability and accesses payroll data

## Likelihood and Impact

- **Likelihood:** How probable it is that a risk event will happen.
- **Impact:** The amount of damage caused if the risk event happens.
- Impact can include:
  - Financial loss
  - Downtime
  - Data loss
  - Legal or regulatory consequences
  - Reputational damage
  - Safety impact

- A high likelihood and high impact event should usually be treated as high priority.
- A low likelihood and low impact event may be accepted or monitored.

## Types of Risk

- **Inherent Risk:** Risk that exists before security controls are applied.
- **Residual Risk:** Risk that remains after controls are applied.
- **Control Risk:** Risk that a control may fail or not operate correctly.
- **Risk Appetite:** The amount of risk an organization is willing to accept.
- **Risk Tolerance:** The acceptable variation from the defined risk appetite.

Example:
- If a company enables MFA, the risk of account compromise is reduced, but not eliminated. The remaining risk is residual risk.

## Risk Response Strategies

- **Accept:** Acknowledge the risk and take no additional action beyond monitoring.
  - Example: Accepting low-risk vulnerability on a non-critical internal system.

- **Avoid:** Stop the activity that creates the risk.
  - Example: Removing an unsupported public-facing service.

- **Transfer:** Move some responsibility or financial impact to another party.
  - Example: Cyber insurance or outsourcing a service with contractual security requirements.

- **Mitigate:** Reduce likelihood or impact using controls.
  - Example: Patching, MFA, encryption, monitoring, segmentation, or backups.

## Risk Register

- **Risk Register:** A document used to track identified risks, ownership, treatment, and status.
- A risk register helps security teams communicate risk clearly and track remediation.

Common risk register fields:
- Risk ID
- Asset or system affected
- Risk description
- Threat
- Vulnerability
- Likelihood
- Impact
- Risk rating
- Existing controls
- Recommended treatment
- Risk owner
- Due date
- Status

## Risk Analysis

- **Qualitative Risk Analysis:** Uses descriptive ratings such as low, medium, and high.
- **Quantitative Risk Analysis:** Uses numbers, currency, probabilities, and formulas to estimate risk.

Common risk formulas:
- **SLE:** Single Loss Expectancy
- **ARO:** Annualized Rate of Occurrence
- **ALE:** Annualized Loss Expectancy

Formula:
- ALE = SLE x ARO

Example:
- If one outage costs $10,000 and it is expected twice per year, ALE is $20,000.

## Business Impact Analysis

- **Business Impact Analysis (BIA):** Identifies critical business functions and the impact of disruption.
- BIA helps determine recovery priorities.

Important BIA terms:
- **RTO:** Recovery Time Objective; how quickly a system must be restored.
- **RPO:** Recovery Point Objective; how much data loss is acceptable.
- **MTD:** Maximum Tolerable Downtime; longest acceptable outage.

## Key Takeaways

- Risk exists when threats, vulnerabilities, and valuable assets intersect.
- Risk cannot always be eliminated, but it can be reduced, transferred, avoided, or accepted.
- Risk management supports better decisions because it connects technical problems to business impact.