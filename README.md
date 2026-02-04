Enterprise Security Audit & Compliance Case Study

Author: Mba Nonna
Domain: Governance, Risk & Compliance (GRC)
Frameworks: NIST CSF, NIST SP 800-30, ISO/IEC 27001, SOC 2

Executive Summary

This repository documents an Enterprise Security Audit & Compliance Case Study conducted as part of formal Governance, Risk, and Compliance (GRC) training. The engagement assessed the security posture of two critical enterprise systems:

Microsoft Exchange Server

Cisco AnyConnect VPN

A risk-based audit methodology aligned with NIST SP 800-30 was applied, with findings mapped to NIST CSF, ISO/IEC 27001, and SOC 2 Trust Services Criteria.

The objective was to identify material risks, evaluate control effectiveness, assess compliance alignment, and provide actionable remediation recommendations reflective of real-world enterprise security and consulting practices.

Engagement Scope
In-Scope Systems

Microsoft Exchange Server (enterprise email infrastructure)

Cisco AnyConnect VPN (secure remote access)

Out of Scope

End-user devices

Physical security

Third-party SaaS platforms not directly integrated

Objectives

Identify threats and vulnerabilities affecting critical systems

Assess likelihood and business impact of identified risks

Evaluate control effectiveness

Map findings to recognized security frameworks

Recommend prioritized remediation actions

Business Context

The assessed environment represents a mid-sized organization operating a hybrid work model. Email communication and VPN access were classified as high-impact assets due to their role in:

Business operations

Secure communications

Remote workforce enablement

Access to internal resources

A security incident impacting these systems would materially affect confidentiality, availability, and organizational trust.

Audit Lifecycle

The engagement followed a structured enterprise audit lifecycle:

Planning and scoping

Asset identification and classification

Threat and vulnerability identification

Risk analysis and evaluation

Control assessment and gap analysis

Compliance mapping

Reporting and remediation planning

This lifecycle aligns with industry GRC and internal audit best practices.

Asset Identification and Classification
Asset	Description	Impact Level
Microsoft Exchange Server	Enterprise email system	High
VPN Infrastructure	Secure remote access gateway	High
User Credentials	Authentication assets	High
Email Data	Sensitive organizational communications	High
Threat Modeling Overview

Threat identification considered:

Credential theft (phishing, brute-force)

Unauthorized remote access

Exploitation of unpatched vulnerabilities

Insider misuse

Service disruption

Threats were mapped to assets and evaluated against existing controls.

Risk Assessment Methodology

Risks were evaluated using a qualitative model aligned with NIST SP 800-30.

Factor	Description
Likelihood	Probability of threat occurrence
Impact	Business and security impact
Risk Rating	Likelihood × Impact
Key Findings – Microsoft Exchange Server
EX-01: Weak Authentication Enforcement

Threat: Credential compromise

Vulnerability: Inconsistent MFA enforcement

Impact: Unauthorized email access

Likelihood: Medium

Risk Rating: High

EX-02: Patch Management Delays

Threat: Exploitation of known vulnerabilities

Vulnerability: Delayed patch deployment

Impact: System compromise

Likelihood: Medium

Risk Rating: Medium–High

Key Findings – Cisco AnyConnect VPN
VPN-01: Unauthorized Remote Access

Threat: Credential abuse

Vulnerability: Limited access review processes

Impact: Internal network exposure

Likelihood: Medium

Risk Rating: Medium

VPN-02: Insufficient Authentication Monitoring

Threat: Undetected credential attacks

Vulnerability: Limited logging and alerting

Impact: Delayed incident response

Likelihood: Medium

Risk Rating: Medium

Consolidated Risk Register
ID	System	Risk Description	Likelihood	Impact	Rating
EX-01	Exchange	MFA enforcement gaps	Medium	High	High
EX-02	Exchange	Patch management delays	Medium	High	Medium–High
VPN-01	VPN	Unauthorized remote access	Medium	Medium	Medium
VPN-02	VPN	Insufficient auth monitoring	Medium	Medium	Medium
Control Gap Summary

Identified gaps included:

Inconsistent MFA enforcement

Lack of formal access review schedules

Logging enabled but not actively monitored

Incident response procedures lacking authentication-specific workflows

Compliance Mapping Summary
NIST Cybersecurity Framework

ID.RA – Risk Assessment

PR.AC – Identity and Access Management

DE.CM – Continuous Monitoring

ISO/IEC 27001

A.5 – Information Security Policies

A.8 – Asset Management

A.9 – Access Control

A.12 – Operations Security

SOC 2 Trust Services Criteria

Security

Availability

Risk Treatment Overview

Recommended treatment actions included:

Enforce MFA across all users and administrators

Implement structured patch management cycles

Apply least-privilege access controls

Enhance centralized logging and monitoring

Formalize access reviews and incident response procedures

Deliverables

Enterprise risk assessment

Enterprise IT audit report

Risk register and prioritization

Compliance alignment documentation

Remediation roadmap

Lessons Learned

Credential-based attacks remain a primary enterprise threat

MFA significantly reduces attack surface

Compliance mapping improves stakeholder communication

Continuous monitoring is critical for early detection

Supporting Audit Artifacts

📄 Enterprise Risk Assessment – Exchange & VPN

📄 Enterprise IT Audit – Exchange & VPN

References

See references/standards-and-frameworks.md for the complete list of authoritative standards and sources.
