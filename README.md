# Hail Software LTD — Cybersecurity Risk Assessment

> **Independent GRC / Cybersecurity Portfolio Project**

##  Project Overview

This project presents a structured cybersecurity risk assessment of **Hail Software LTD**, a hypothetical technology/finance organisation operating a hybrid working environment.

The assessment was designed to evaluate the organisation's security posture, identify potential security weaknesses, assess business risk, and develop practical remediation recommendations aligned with **ISO/IEC 27001 information security principles**.

The assessment covers:

* Identity & Access Management
* Authentication & Credential Management
* Cloud Security
* Data Protection
* Incident Management
* Vulnerability Management
* Endpoint & BYOD Security
* Security Governance
* Security Awareness & Training

**Project date:** August 2026
**Project type:** Independent / hypothetical case study
**Focus:** Cybersecurity Risk, GRC & Compliance

---

##  Hypothetical Environment

| Area           | Environment          |
| -------------- | -------------------- |
| Industry       | Technology / Finance |
| Personnel      | 45                   |
| Working Model  | Hybrid               |
| Cloud Platform | AWS                  |
| Database       | PostgreSQL           |
| Productivity   | Google Workspace     |
| Source Code    | GitHub               |
| Communication  | Slack, Zoom & Teams  |
| Endpoints      | Corporate & BYOD     |

The hypothetical organisation develops financial reconciliation software, meaning confidentiality, access control and protection of sensitive information are important considerations.

---

##  Assessment Objectives

The assessment aimed to:

1. Identify cybersecurity weaknesses within the hypothetical environment.
2. Assess the likelihood and business impact of identified risks.
3. Prioritise risks according to their potential severity.
4. Map relevant controls and recommendations to ISO 27001.
5. Develop practical remediation recommendations.
6. Create a 30/60/90-day cybersecurity improvement roadmap.
7. Develop an incident-response tabletop exercise to test response procedures.

---

##  Key Findings

The assessment identified **9 security findings**.

| ID   | Finding                           | Likelihood | Impact | Risk     | Priority  |
| ---- | --------------------------------- | ---------- | ------ | -------- | --------- |
| F-01 | MFA not enforced                  | High       | High   | Critical | Immediate |
| F-02 | No centralised SSO                | Medium     | High   | High     | High      |
| F-03 | Sensitive data exposure           | High       | High   | Critical | Immediate |
| F-04 | No incident response plan         | Medium     | High   | High     | High      |
| F-05 | Lack of security policies         | Medium     | High   | High     | High      |
| F-06 | No routine vulnerability scanning | Medium     | High   | High     | High      |
| F-07 | BYOD weaknesses                   | High       | Medium | High     | High      |
| F-08 | No permission audits              | Medium     | Medium | Medium   | Medium    |
| F-09 | Limited security training         | Medium     | Medium | Medium   | Medium    |

The assessment identified six High-priority findings and three Medium-priority findings.

---

##  ISO 27001 Alignment

The assessment mapped identified risks and recommendations to relevant ISO 27001 control areas.

Examples include:

| Security Area            | ISO 27001 Alignment                 |
| ------------------------ | ----------------------------------- |
| MFA                      | Annex A 5.8 — Secure Authentication |
| Identity Management      | Annex A 5.16 — Identity Management  |
| Access Rights            | Annex A 5.18 — Access Rights        |
| Data Protection          | Annex A 8.11, 8.12, 8.24            |
| Incident Response        | Annex A 5.24, 5.28                  |
| Security Policies        | Clause 5.2 / Annex A 5.1            |
| Vulnerability Management | Annex A 8.8                         |
| Endpoint Security        | Annex A 7.13, 8.1, 8.20             |
| Security Awareness       | Annex A 6.3                         |

The project therefore demonstrates how identified technical and organisational risks can be connected to a broader information-security control framework.

---

##  Priority Recommendations

### 1. Enforce Multi-Factor Authentication

Implement MFA across corporate accounts, beginning with Slack and GitHub and prioritising privileged and high-risk accounts.

### 2. Implement Centralised Identity Management

Evaluate and implement an Identity Provider / SSO solution to improve identity management, authentication consistency, provisioning and deprovisioning.

### 3. Strengthen Sensitive Data Protection

Review Google Drive permissions, classify sensitive information, apply least-privilege access and restrict inappropriate external sharing.

### 4. Establish Incident Response

Create a documented Incident Response Plan covering:

**Identify → Report → Contain → Investigate → Recover → Lessons Learned**

### 5. Formalise Security Policies

Develop an information security policy framework covering areas such as:

* Information Security
* Access Control
* Acceptable Use
* BYOD
* Incident Response
* Vulnerability Management

### 6. Establish Vulnerability Management

Introduce a repeatable process:

**Identify → Assess → Prioritise → Remediate → Verify**

### 7. Improve BYOD Security

Define minimum security requirements for personal devices accessing corporate systems and evaluate MDM/EDR solutions where appropriate.

### 8. Conduct Access Reviews

Introduce quarterly reviews of users, roles, applications, permissions and privileged access.

### 9. Improve Security Awareness

Introduce recurring training covering phishing, social engineering, passwords, MFA, data protection, BYOD and incident reporting.

---

##   90-Day Security Roadmap

###  30 Days — Immediate Risk Reduction

**Focus:**

* Implement MFA for Slack and GitHub
* Create an Incident Response Plan
* Begin information security policy development
* Review sensitive Google Drive data and permissions

**Outcome:** Reduce immediate exposure to account compromise, unauthorised access and data exposure.

---

###  31–60 Days — Build the Security Foundation

**Focus:**

* Evaluate centralised IdP/SSO
* Establish joiner/mover/leaver processes
* Introduce vulnerability scanning
* Create a vulnerability register
* Develop BYOD requirements
* Complete data classification and access reviews

**Outcome:** Establish repeatable security processes and strengthen the control framework.

---

###   61–90 Days — Improve Security Maturity

**Focus:**

* Launch mandatory security awareness training
* Conduct the first formal quarterly access review
* Run an incident-response tabletop exercise
* Conduct a follow-up vulnerability scan
* Verify remediation of identified weaknesses

**Outcome:** Move from one-off remediation towards continuous security improvement.

---

##  Incident Response Tabletop Exercise

A tabletop exercise was designed around the following scenario:

> **Scenario:** An employee's GitHub credentials have been compromised.

Participants would consider:

* Who identifies the incident?
* Who needs to be notified?
* How is the account contained?
* How are credentials reset?
* Who communicates with management?
* How is evidence preserved?
* How are lessons learned recorded?

This exercise is intended to test whether the proposed incident-response process is practical and understood by relevant personnel.

---

##  Skills Demonstrated

### Governance, Risk & Compliance

* Cybersecurity risk assessment
* Risk identification
* Risk prioritisation
* Control assessment
* ISO 27001 alignment
* Security governance
* Policy development
* Remediation planning

### Security

* Identity & Access Management
* MFA
* SSO / Identity Providers
* Data protection
* Incident response
* Vulnerability management
* Endpoint security
* BYOD security
* Security awareness

### Analytical & Professional

* Analytical thinking
* Documentation
* Risk analysis
* Business-impact assessment
* Structured reporting
* Security recommendations
* Project planning

---

##  Project Documentation

### Assessment

* [Full Cybersecurity Assessment](assessment/Hail-Software-Cybersecurity-Assessment.pdf)

### Risk & Compliance

* [Risk Register](findings/risk-register.md)
* [ISO 27001 Control Mapping](findings/iso-27001-mapping.md)

### Remediation

* [Remediation Plan](remediation/remediation-plan.md)
* [90-Day Security Roadmap](remediation/90-day-roadmap.md)

### Incident Response

* [Tabletop Exercise](incident-response/tabletop-exercise.md)

### Methodology

* [Assessment Methodology](documentation/assessment-methodology.md)
* [Scope & Assumptions](documentation/scope-and-assumptions.md)

---

##  Disclaimer

**Hail Software LTD is a hypothetical organisation created for this portfolio project.**

This assessment does not represent an actual security assessment, penetration test, audit or consultancy engagement performed for a real organisation.

The project is intended to demonstrate practical knowledge of cybersecurity risk assessment, GRC, security controls, ISO 27001 alignment and remediation planning.

---

##  Author

**Rodrigo da Silva**

Independent Cybersecurity / GRC Portfolio Project

**Focus areas:** Cybersecurity • Governance • Risk • Compliance • Information Security

Independent cybersecurity risk assessment and GRC case study aligned with ISO 27001.
Hail-Software-Cybersecurity-Assessment.pdf
