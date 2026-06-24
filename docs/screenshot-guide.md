# Screenshot and Image Guide

Use images to make the repository stronger, but only after redaction. The safest approach is to create your own diagrams or crop only sanitized tables.

## Recommended Image Locations

| File Name | Folder | Use In | What To Show |
|---|---|---|---|
| `01-risk-workflow.png` | `assets/screenshots/` | `README.md`, `docs/executive-summary.md` | High-level process from risk identification to control mapping to POA&M closure. |
| `02-risk-register.png` | `assets/screenshots/` | `docs/risk-register.md` | Cropped risk register table with only generalized risks and no personal/course details. |
| `03-poam-dashboard.png` | `assets/screenshots/` | `docs/poam-summary.md` | Sanitized dashboard showing total POA&M items, high/moderate risks, owners, and timeline. |
| `04-control-map.png` | `assets/screenshots/` | `docs/control-mapping.md` | Control family map covering AC, AU, SI, IR, CP, RA, SR, PE, and IA. |
| `05-critical-infrastructure-map.png` | `assets/screenshots/` | `docs/critical-infrastructure.md` | Supplier/manufacturing/logistics dependency diagram. |

## Best Image Strategy

### 1. Use self-created diagrams first

Best options:

- Mermaid diagrams already included in Markdown
- Draw.io / diagrams.net exported PNGs
- Canva / Figma architecture-style diagrams
- Excel dashboard screenshots after redaction

### 2. Avoid screenshots of raw assignment pages

Do not upload assignment cover pages, pages with professor names, UIN, course details, page headers, FedRAMP template metadata, or full official template pages.

### 3. Redact before uploading

Before adding an image, remove:

- UIN or student IDs
- phone numbers and email addresses
- professor names and course submission metadata
- internal-looking IP addresses
- CVE-like placeholder numbers
- scanner/plugin IDs
- names of people used in templates
- official logos or brand marks
- anything labeled CUI, confidential, internal, or controlled

## Markdown Placement Examples

Add the image only after the file exists in `assets/screenshots/`.

```md
![Risk workflow](../assets/screenshots/01-risk-workflow.png)
```

From the root README, use:

```md
![Risk workflow](assets/screenshots/01-risk-workflow.png)
```

## Image Quality Checklist

- Text is readable at normal GitHub zoom.
- No broken image links.
- No personal or course metadata is visible.
- No raw sensitive identifiers are visible.
- Filename is clear and lowercase or numbered.
- Image supports the explanation rather than replacing it.
