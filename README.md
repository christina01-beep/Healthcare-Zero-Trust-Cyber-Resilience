
# Building Cyber Resilience Through Zero Trust Architecture (ZTA) in Healthcare

**Author:** Joseph Christina Sagar  
**Institution:** Webster University  
**Research Area:** Healthcare Cybersecurity | Zero Trust Architecture | NIST SP 800-207 | Cyber Resilience

## Project Overview

This project explores how Zero Trust Architecture (ZTA) can strengthen cybersecurity resilience in healthcare organizations by protecting Electronic Health Records (EHR), connected medical devices (IoMT), and sensitive patient data.

It combines Master's-level cybersecurity research with conceptual security architecture, identity and access management, network segmentation, and security policy examples.

## Objectives

- Examine how Zero Trust principles support healthcare cyber resilience.
- Explore identity verification, least privilege, and continuous monitoring.
- Design a healthcare network micro-segmentation reference architecture.
- Illustrate adaptive access controls for EHR systems.
- Demonstrate conceptual IoMT network segmentation and firewall policies.
- Map selected NIST SP 800-207 principles to HIPAA Security Rule safeguards.

## Frameworks and Concepts

- NIST SP 800-207 — Zero Trust Architecture
- HIPAA Security Rule
- Identity and Access Management (IAM)
- Multi-Factor Authentication (MFA)
- Role-Based Access Control (RBAC)
- Network Micro-Segmentation
- Security Information and Event Management (SIEM)
- Defense in Depth

## Architecture Diagram

[View Healthcare Zero Trust Architecture](diagrams/Healthcare_ZTA_Architecture.md)

The conceptual architecture demonstrates identity verification, policy evaluation, enforcement points, isolated healthcare network zones, and monitored access to protected patient information.

## Technical Artifacts

| File | Description |
|---|---|
| [HIPAA and NIST Control Mapping](docs/HIPAA_NIST_800-207_Control_Mapping.md) | Illustrative mapping of Zero Trust concepts to HIPAA security safeguards |
| [Healthcare ZTA Architecture](diagrams/Healthcare_ZTA_Architecture.md) | Mermaid micro-segmentation architecture diagram |
| [EHR Conditional Access Policy](policies/ehr_conditional_access_policy.json) | Conceptual JSON example of identity- and device-aware access controls |
| [IoMT VLAN Firewall Rules](policies/iomt_vlan_firewall_rules.yaml) | Conceptual YAML example of medical-device network isolation |

## Security Approach

1. **Verify identity:** Authenticate and authorize users before granting access.
2. **Apply least privilege:** Restrict access to approved resources and roles.
3. **Segment networks:** Separate administrative, clinical, and IoMT environments.
4. **Protect sensitive data:** Limit direct access to EHR and patient information systems.
5. **Monitor continuously:** Collect and analyze security events for suspicious activity.

## Project Scope

This repository contains research-oriented reference designs and illustrative security policy examples. The configuration samples are not directly deployable, have not been validated in a production healthcare environment, and do not independently establish HIPAA compliance.

## Author

**Joseph Christina Sagar**  
Master's Research — Webster University

**Contact:** christinasagar4@gmail.com
  
