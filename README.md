# Enterprise Cyber Risk Remediation

A sanitized GRC/security portfolio case study focused on enterprise cyber risk assessment, critical infrastructure dependency analysis, control mapping, and POA&M-driven remediation planning.

> **Disclaimer:** This is an academic/portfolio case study. It does not represent Nike, Inc., does not contain internal Nike data, and does not use confidential organizational information. Raw coursework files, personal identifiers, internal-looking IP addresses, and template documents are intentionally excluded.

## What This Project Demonstrates

- Enterprise cyber risk assessment and prioritization
- Critical manufacturing and supply-chain dependency analysis
- NIST/FedRAMP-aligned control mapping
- POA&M planning with owners, milestones, risk ratings, and remediation actions
- Executive-level communication of cyber risk and business impact
- Public-safe documentation practices for a security portfolio

## Repository Structure

```text
.
├── README.md
├── docs/
│   ├── executive-summary.md
│   ├── risk-register.md
│   ├── poam-summary.md
│   ├── control-mapping.md
│   ├── critical-infrastructure.md
│   ├── screenshot-guide.md
│   └── redaction-and-publication-checklist.md
├── data/
│   ├── poam-sanitized.csv
│   └── risk-register-sanitized.csv
└── assets/
    └── screenshots/
        └── README.md
```

## Quick Portfolio Narrative

This project models how a large global sportswear enterprise could identify, prioritize, and remediate cyber risks affecting supply chain operations, manufacturing dependencies, third-party vendor exposure, access control, audit logging, incident response, and business continuity.

The project converts academic risk documentation into a recruiter-friendly GRC artifact: executive brief, risk register, control map, POA&M summary, and publication/redaction guidance.

## Portfolio Artifacts

| Artifact | Purpose |
|---|---|
| [`docs/executive-summary.md`](docs/executive-summary.md) | Business-facing summary of risk themes, scope, findings, and remediation strategy. |
| [`docs/risk-register.md`](docs/risk-register.md) | Sanitized risk register with likelihood, impact, priority, and treatment approach. |
| [`docs/poam-summary.md`](docs/poam-summary.md) | POA&M-style remediation tracker summarized without sensitive identifiers. |
| [`docs/control-mapping.md`](docs/control-mapping.md) | Maps risk themes to NIST/FedRAMP-style control families and evidence. |
| [`docs/critical-infrastructure.md`](docs/critical-infrastructure.md) | Explains manufacturing and supply-chain dependency risk. |
| [`docs/screenshot-guide.md`](docs/screenshot-guide.md) | Tells exactly where to place safe screenshots and what to redact first. |
| [`docs/redaction-and-publication-checklist.md`](docs/redaction-and-publication-checklist.md) | Public-release checklist to avoid leaking personal, academic, or sensitive information. |

## Risk-to-Remediation Workflow

```mermaid
flowchart LR
    A[Business Process] --> B[Risk Identification]
    B --> C[Risk Rating]
    C --> D[Control Mapping]
    D --> E[POA&M Item]
    E --> F[Owner + Milestone]
    F --> G[Remediation Tracking]
    G --> H[Executive Reporting]
```

## Main Risk Themes

| Theme | Business Concern | Example Control Direction |
|---|---|---|
| Supply chain disruption | Product delays, vendor concentration, operational dependency | Supplier assessments, SCRM processes, contractual security expectations |
| Manufacturing resilience | OT/ICS disruption, production downtime, quality impact | Network segmentation, monitoring, recovery planning |
| Access control | Privilege creep, weak account lifecycle controls, unmanaged mobile access | Account management, least privilege, MFA, mobile device encryption |
| Audit and monitoring | Incomplete event records, delayed investigation, weak accountability | Event logging, audit record content, weekly review/escalation |
| Vulnerability and integrity management | Delayed patching, unauthorized software/firmware changes | Vulnerability scanning, flaw remediation, integrity verification |
| Incident response and continuity | Slow containment, unclear ownership, business interruption | Incident playbooks, tabletop testing, backups, contingency planning |

## Suggested Screenshots / Images

Do **not** upload raw assignment screenshots. Add only sanitized visuals under `assets/screenshots/`.

| Image File | Place It In | What It Should Show |
|---|---|---|
| `01-risk-workflow.png` | README and `docs/executive-summary.md` | A clean workflow from risk identification to POA&M closure. |
| `02-risk-register.png` | `docs/risk-register.md` | A cropped risk register table with no personal/course details. |
| `03-poam-dashboard.png` | `docs/poam-summary.md` | A sanitized POA&M tracker/dashboard with no IPs, CVEs, or names. |
| `04-control-map.png` | `docs/control-mapping.md` | A control-family map showing AC, AU, SI, IR, CP, RA, and SR controls. |
| `05-critical-infrastructure-map.png` | `docs/critical-infrastructure.md` | A simple manufacturing/supplier/transportation dependency diagram. |

## What Was Intentionally Not Published

- Raw PDFs, DOCX files, and XLSX workbook
- Personal identifiers such as UIN, phone number, email, or professor/course cover-page details
- Full FedRAMP template pages or screenshots
- Nike logos, brand imagery, or anything implying affiliation
- Internal-looking IP addresses, CVE-like placeholders, scanner IDs, or raw asset identifiers
- Offensive step-by-step attack content beyond defensive risk framing

## Skills Demonstrated

`GRC` `Risk Assessment` `POA&M` `NIST 800-53` `FedRAMP` `Access Control` `Audit Logging` `Supply Chain Risk` `Critical Infrastructure` `Vendor Risk` `Business Continuity` `Security Governance`

## How I Would Explain This in an Interview

> I converted academic risk-management work into a public-safe GRC portfolio artifact. I identified business-critical risk themes, mapped them to security controls, built a sanitized risk register and POA&M summary, and documented how remediation should be owned, prioritized, and communicated to executives without exposing sensitive source material.
