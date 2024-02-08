# Fundamentals of Security

## Objectives
- 1.1 - Compare and contrast various security controls
- 1.2 - Summarize fundamental security concepts

## Fundamentals of Security
- **Information Security**: Protecting data and information from unauthorized access, modification, disruption, disclosure, and destruction
- **Information Systems Security**: Protecting the systems (e.g., computers, servers, network devices) that hold and process critical data

## CIA Triad
- **Confidentiality**: Ensures information is accessible only to authorized personnel (e.g., encryption)
- **Integrity**: Ensures data remains accurate and unaltered (e.g., checksums)
- **Availability**: Ensures information and resources are accessible when needed (e.g., redundancy measures)

## Non-Repudiation
- Guarantees that an action or event cannot be denied by the involved parties (e.g., digital signatures)

## CIANA Pentagon
- An extension of the CIA triad with the addition of non-repudiation and authentication

## Triple A’s of Security
- **Authentication**: Verifying the identity of a user or system (e.g., password checks)
- **Authorization**: Determining actions or resources an authenticated user can access (e.g., permissions)
- **Accounting**: Tracking user activities and resource usage for audit or billing purposes

## Security Control Categories
- Technical, Managerial, Operational, Physical

## Security Control Types
- Preventative, Deterrent, Detective, Corrective, Compensating, Directive

## Zero Trust Model
- Operates on the principle that no one should be trusted by default
- To achieve zero trust, we use the control plane and the data plane
  - **Control Plane**: Adaptive identity, threat scope reduction, policy-driven access control, and secured zones
  - **Data Plane**: Subject/system, policy engine, policy administrator, and establishing policy enforcement points

----------------

# Threats and Vulnerabilities

- **Threat**
  - Anything that could cause harm, loss, damage, or compromise to our information technology systems
    - Can come from the following:
      - Natural disasters
      - Cyber-attacks
      - Data integrity breaches
      - Disclosure of confidential information
  - **Vulnerability**
    - Any weakness in the system design or implementation
    - Come from internal factors like the following:
      - Software bugs
      - Misconfigured software
      - Improperly protected network devices
      - Missing security patches
      - Lack of physical security
- Where threats and vulnerabilities intersect, that is where the risk to your enterprise systems and networks lies
  - If you have a threat, but there is no matching vulnerability to it, then you have no risk
    - The same holds true that if you have a vulnerability but there’s no threat against it, there would be no risk
  - **Risk Management**
    - Finding different ways to minimize the likelihood of an outcome and achieve the desired outcome

## Confidentiality

- **Confidentiality**
  - Refers to the protection of information from unauthorized access and disclosure
    - Ensure that private or sensitive information is not available or disclosed to unauthorized individuals, entities, or processes
  - Confidentiality is important for 3 main reasons:
    - To protect personal privacy
    - To maintain a business advantage
    - To achieve regulatory compliance
  - To ensure confidentiality, we use five basic methods:
    - **Encryption**
      - Process of converting data into a code to prevent unauthorized access
    - **Access Controls**
      - By setting up strong user permissions, you ensure that only authorized personnel can access certain types of data
    - **Data Masking**
      - Method that involves obscuring specific data within a database to make it inaccessible for unauthorized users while retaining the real data's authenticity and use for authorized users
    - **Physical Security Measures**
      - Ensure confidentiality for both physical types of data, such as paper records stored in a filing cabinet, and for digital information contained on servers and workstations
    - **Training and Awareness**
      - Conduct regular training on the security awareness best practices that employees can use to protect their organization’s sensitive data

## Integrity

- **Integrity**
  - Helps ensure that information and data remain accurate and unchanged from its original state unless intentionally modified by an authorized individual
    - Verifies the accuracy and trustworthiness of data over the entire lifecycle
  - Integrity is important for three main reasons:
    - To ensure data accuracy
    - To maintain trust
    - To ensure system operability
  - To help us maintain the integrity of our data, systems, and networks, we usually utilize five methods:
    - **Hashing**
      - Process of converting data into a fixed-size value
    - **Digital Signatures**
      - Ensure both integrity and authenticity
    - **Checksums**
      - Method to verify the integrity of data during transmission
    - **Access Controls**
      - Ensure that only authorized individuals can modify data and this reduces the risk of unintentional or malicious alterations
    - **Regular Audits**
      - Involve systematically reviewing logs and operations to ensure that only authorized changes have been made, and any discrepancies are immediately addressed

