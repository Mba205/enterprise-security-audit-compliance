# Enterprise Security Audit & Compliance Case Study

## 1. Overview

This repository presents an **Enterprise Security Audit & Compliance Case Study** conducted as part of formal Governance, Risk, and Compliance (GRC) training. The engagement assessed the security posture of two critical enterprise systems:

- Microsoft Exchange Server
- Cisco AnyConnect VPN

A **risk-based audit methodology aligned with NIST SP 800-30** was applied, with findings mapped to **NIST Cybersecurity Framework (CSF)**, **ISO/IEC 27001**, and **SOC 2 Trust Services Criteria**.

## 2. Engagement Objectives

The objectives of the engagement were to:

- Identify threats and vulnerabilities affecting critical systems
- Assess risk likelihood and business impact
- Evaluate control effectiveness
- Identify compliance gaps
- Provide prioritized remediation recommendations

## 3. Scope Definition

### 3.1 In-Scope Systems

- Microsoft Exchange Server (enterprise email)
- Cisco AnyConnect VPN (secure remote access)

### 3.2 Out-of-Scope Items

- End-user devices
- Physical security controls
- Third-party SaaS platforms not directly integrated

## 4. Business Context

The organization operates a **hybrid work environment**, making email and VPN access **high-impact assets**. Compromise of these systems would directly affect:

- Business continuity
- Data confidentiality
- Organizational trust
- Regulatory posture

## 5. Audit Lifecycle

The audit followed a structured enterprise lifecycle:

1. Planning and scoping  
2. Asset identification and classification  
3. Threat and vulnerability identification  
4. Risk analysis and evaluation  
5. Control assessment and gap analysis  
6. Compliance mapping  
7. Reporting and remediation planning  

## 6. Asset Identification and Classification

| Asset | Classification |
|-----|---------------|
| Microsoft Exchange Server | High impact |
| VPN Infrastructure | High impact |
| User Credentials | High impact |
| Email Data | High impact |

## 7. Threat Identification

Threat modeling considered:

- Credential theft (phishing, brute-force)
- Unauthorized remote access
- Exploitation of known vulnerabilities
- Insider misuse
- Service availability disruptions

## 8. Risk Assessment Methodology

Risks were assessed using a qualitative model aligned with **NIST SP 800-30**.

| Factor | Description |
|------|------------|
| Likelihood | Probability of occurrence |
| Impact | Business and security impact |
| Risk Rating | Combined assessment |

## 9. Findings – Microsoft Exchange Server

### 9.1 EX-01: Weak Authentication Controls

- **Threat:** Credential compromise
- **Vulnerability:** Inconsistent MFA enforcement
- **Impact:** Unauthorized email access
- **Likelihood:** Medium
- **Risk Rating:** High

### 9.2 EX-02: Patch Management Gaps

- **Threat:** Exploitation of known vulnerabilities
- **Vulnerability:** Delayed patch deployment
- **Impact:** System compromise
- **Likelihood:** Medium
- **Risk Rating:** Medium–High

## 10. Findings – Cisco AnyConnect VPN

### 10.1 VPN-01: Unauthorized Remote Access

- **Threat:** Credential abuse
- **Vulnerability:** Inadequate access review processes
- **Impact:** Internal network exposure
- **Likelihood:** Medium
- **Risk Rating:** Medium

### 10.2 VPN-02: Insufficient Authentication Monitoring

- **Threat:** Undetected credential attacks
- **Vulnerability:** Limited logging and alerting
- **Impact:** Delayed detection and response
- **Likelihood:** Medium
- **Risk Rating:** Medium

## 11. Consolidated Risk Register

| Risk ID | System | Risk Rating |
|-------|-------|-------------|
| EX-01 | Exchange | High |
| EX-02 | Exchange | Medium–High |
| VPN-01 | VPN | Medium |
| VPN-02 | VPN | Medium |

## 12. Control Gaps

Identified control gaps included:

- Inconsistent MFA enforcement
- Lack of formal access reviews
- Authentication logs not actively monitored
- Limited incident response coverage for credential attacks

## 13. Compliance Alignment

### 13.1 NIST Cybersecurity Framework

- ID.RA – Risk Assessment
- PR.AC – Identity and Access Management
- DE.CM – Continuous Monitoring

### 13.2 ISO/IEC 27001

- A.5 – Information Security Policies
- A.8 – Asset Management
- A.9 – Access Control
- A.12 – Operations Security

### 13.3 SOC 2 Trust Services Criteria

- Security
- Availability

## 14. Risk Treatment Summary

Recommended actions included:

- Enforce MFA across all systems
- Implement structured patch management
- Apply least-privilege access
- Enhance centralized logging and monitoring
- Formalize access review and incident response processes

## 15. Deliverables

- Enterprise risk assessment
- Enterprise IT audit report
- Risk register
- Compliance mapping
- Remediation roadmap

## 16. Supporting Audit Artifacts

- 📄 [Enterprise Risk Assessment – Exchange & VPN](artifacts/enterprise-risk-assessment-exchange-vpn.pdf)
- 📄 [Enterprise IT Audit – Exchange & VPN](artifacts/enterprise-it-audit-exchange-vpn.pdf)

## 17. References

See `references/standards-and-frameworks.md` for the complete list of authoritative standards and sources.

