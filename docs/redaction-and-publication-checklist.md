# Redaction and Publication Checklist

Use this checklist before publishing screenshots, spreadsheets, PDFs, DOCX exports, or generated images to this repository.

## Do Not Publish

| Item | Why It Should Not Be Public |
|---|---|
| Raw assignment PDFs/DOCX files | They may include course details, professor names, student identifiers, and academic submission metadata. |
| Raw resume file | It contains personal contact information and should not be placed inside a public project repository. |
| Full POA&M workbook | It can contain internal-looking asset identifiers, IP addresses, CVE-like placeholders, and scanner IDs. |
| Full FedRAMP template | It is not necessary for a portfolio and may contain template banners, instructional text, or controlled-information markings. |
| Raw screenshots of assignment pages | Screenshots can expose UIN, names, course details, timestamps, and template metadata. |
| Nike logos or brand assets | Avoid trademark/affiliation confusion. Use text-only case-study language instead. |
| Real credentials, keys, tokens, domains, or internal IPs | These are sensitive and should never be in a public repository. |
| Offensive step-by-step attack instructions | Keep the repo focused on defensive risk analysis and remediation. |

## Safe to Publish

| Safer Artifact | Condition |
|---|---|
| Sanitized risk register | Use generalized assets and remove personal/course details. |
| Sanitized POA&M summary | Remove IPs, scanner IDs, CVE placeholders, and raw owner names. |
| Control mapping table | Use control families and descriptions, not full template pages. |
| Self-created diagrams | Do not include official logos or raw screenshots. |
| Executive summary | Keep it high-level, business-focused, and clearly labeled as a case study. |
| Interview talking points | Explain what you did without claiming real internal access. |

## Public Disclaimer to Keep

Use this language in the README and any LinkedIn/GitHub description:

> This is a sanitized academic/portfolio case study. It does not represent Nike, Inc., does not contain internal Nike data, and does not use confidential organizational information.

## Final Pre-Publish Review

Before pushing a file:

- [ ] No UIN, student ID, phone number, personal email, or professor name.
- [ ] No raw assignment cover page.
- [ ] No raw workbook screenshots with IP addresses or scanner identifiers.
- [ ] No CVE-like placeholders unless clearly marked as fictional and necessary.
- [ ] No official logos, copyrighted images, or screenshots from third-party templates.
- [ ] No credentials, tokens, domains, internal hostnames, or real network details.
- [ ] No claim that this was done for Nike or with Nike data.
- [ ] File adds evidence of skill: risk assessment, control mapping, POA&M, communication, or governance.

## Good GitHub Hygiene

- Keep Markdown readable and concise.
- Prefer sanitized tables over raw documents.
- Use screenshots only when they add visual evidence.
- Keep source files private unless fully redacted.
- Use clear filenames and folder structure.
