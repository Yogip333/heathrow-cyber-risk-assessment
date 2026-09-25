# heathrow-cyber-risk-assessment
Information security, risk management and supplier security assessment for Heathrow Airport, aligned with ISO/IEC 27001, ISO/IEC 27005, UK GDPR and UK critical infrastructure requirements.
# Heathrow Airport Information Security & Risk Management Assessment

## Overview

This project presents an information security management and compliance
assessment for Heathrow Airport Holdings Limited (LHR), with a focus on
cybersecurity governance, risk management, supplier security and protection
of critical airport systems.

The assessment considers Heathrow Airport as part of the United Kingdom's
Critical National Infrastructure and examines the security requirements
necessary to protect operational systems, passenger information and
third-party services.

The project is aligned primarily with:

- ISO/IEC 27001
- ISO/IEC 27005
- UK GDPR
- Data Protection Act 2018
- UK aviation and critical infrastructure security requirements

---

## Project Objectives

The main objectives of the project are to:

- Define the information security context and scope of Heathrow Airport.
- Identify key information and technology assets supporting airport operations.
- Assess cybersecurity threats and associated risks.
- Evaluate likelihood and impact using a structured risk assessment approach.
- Establish appropriate risk acceptance criteria.
- Define organisational security responsibilities.
- Analyse third-party and supplier cybersecurity risks.
- Develop an Information Security in Supplier Agreements Policy.
- Recommend technical and administrative controls for protecting airport systems.

---

## Scope

The assessment focuses on systems, information and supplier services that
support Heathrow Airport operations in the United Kingdom.

The project considers areas including:

- Passenger processing systems
- Flight tracking services
- Baggage handling systems
- Server infrastructure
- Enterprise applications
- Payment systems
- Network infrastructure
- CCTV and surveillance systems
- Security gateways
- Identity and authentication systems
- Employee workstations
- Third-party suppliers and contractors

The primary security objective is to maintain the:

- Confidentiality
- Integrity
- Availability

of Heathrow Airport systems and information.

---

## Key Technology Assets Considered

The assessment examines a range of representative airport technologies,
including:

### Airport Operational Systems

- ARINC cMUSE
- FlightAware
- Vanderlande VIBES

### Enterprise Platforms

- Oracle Fusion Cloud ERP
- Oracle Fusion Cloud HCM
- Stripe Payment Gateway

### Infrastructure

- Red Hat Enterprise Linux
- Microsoft Windows Server
- Windows 11 Enterprise
- Cisco Catalyst switches
- Aruba wireless infrastructure

### Security Technologies

- Palo Alto Networks PAN-OS
- Cloudflare Web Application Firewall
- Fortinet FortiProxy
- Okta Multi-Factor Authentication
- CrowdStrike Falcon

### Physical Security

- CCTV and surveillance infrastructure

---

## Threat Landscape

The project evaluates several cybersecurity threats relevant to a major
international airport environment.

Key threats include:

- Supply-chain attacks
- Ransomware
- Insider threats
- Phishing
- Distributed Denial-of-Service attacks
- Privilege escalation
- Exploitation of unpatched systems
- Unauthorised network access
- Compromise of third-party systems
- Data breaches affecting passenger information

Particular attention is given to supplier risk because airport operations
depend heavily on interconnected third-party technologies and services.

---

## Risk Assessment Methodology

The project applies a structured information security risk-management process
aligned with ISO/IEC 27001 and ISO/IEC 27005.

Risk is evaluated using:

1. Asset identification
2. Threat identification
3. Vulnerability analysis
4. Likelihood assessment
5. Impact assessment
6. Risk evaluation
7. Risk treatment
8. Risk acceptance

A five-level likelihood and impact model is used together with a 5x5 risk
matrix to determine the severity of identified risks.

Risk decisions also consider:

- Business impact
- Legal and regulatory obligations
- Operational continuity
- Technical feasibility
- Financial considerations
- Passenger safety
- Organisational reputation

---

## Supplier Security Governance

A major part of this project focuses on cybersecurity risks introduced by
suppliers, contractors and third-party service providers.

The supplier security model addresses the complete supplier lifecycle,
including:

- Procurement
- Onboarding
- System access
- Operational delivery
- Security monitoring
- Incident reporting
- Auditing
- Subcontractor management
- Offboarding
- Data return or destruction

---

## Information Security in Supplier Agreements Policy

The project includes the development of an Information Security in Supplier
Agreements Policy.

The policy defines security requirements for suppliers that access airport
information, maintain IT or operational technology systems, or connect
services to airport infrastructure.

Key control areas include:

### Privileged Access

Privileged access must follow least privilege and role-based access control,
with regular reviews and immediate revocation when access is no longer
required.

### Patch and Vulnerability Management

Supplier-managed systems must be updated and patched to reduce the risk of
service disruption and exploitation.

### Input Validation

Application inputs must be validated and sanitised to reduce injection and
cross-site scripting risks.

### Secure Configuration

Weak or vulnerable components must be disabled, patched or securely
configured.

### Network Access Control

Firewall rules and access-control lists must restrict connectivity to required
systems and services.

### Administrative Access

Administrative interfaces must only be available through authorised
management networks and approved systems.

### Multi-Factor Authentication

Strong authentication and MFA must protect access to sensitive airport
systems.

### Segmentation

CCTV, surveillance and other sensitive systems must be isolated from public
or untrusted networks.

### Transaction Security

Sensitive API requests and transactions should use appropriate cryptographic
controls to reduce replay and manipulation risks.

### Monitoring

Security monitoring communications must be protected against interception
and unauthorised disclosure.

---

## Data Protection

Suppliers processing personal data must follow UK data-protection
requirements.

The project considers requirements including:

- Lawful processing
- Data minimisation
- Restricted access
- Data Processing Agreements
- Security logging
- Secure transfer
- Incident reporting
- Data-subject rights
- Data retention and destruction

---

## Security Governance

Security responsibility is distributed across several organisational
functions.

These include:

- Board and executive management
- CISO / Information Security leadership
- IT Security teams
- Procurement and Supplier Management
- Legal and Compliance
- Operations teams
- Business-unit owners

The governance model ensures that cybersecurity risks can be identified,
treated, monitored and escalated appropriately.

---

## Key Security Principles

The project is based on several core principles:

- Deny access by default.
- Apply least privilege.
- Maintain strong authentication.
- Segment critical infrastructure.
- Keep systems securely patched.
- Restrict supplier access.
- Monitor security events.
- Protect passenger information.
- Maintain auditability.
- Assess risk continuously.
- Preserve operational resilience.

---

## Repository Contents

```text
/
├── README.md
├── report/
│   └── Heathrow_Information_Security_Report.pdf
│
├── risk-assessment/
│   └── Risk_Assessment.xlsx
│
├── policy/
│   └── Supplier_Security_Policy.pdf
│
└── supporting-material/
    └── references.md
