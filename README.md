# Awesome-Gxp-Compliance

# Top GxP Compliance Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on eQMS, Document Control, CAPA, Training, Validation, Audit Trails & Life Sciences Quality Systems*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **GxP Compliance** (Good Practice regulations in life sciences). These systems support electronic quality management (eQMS), document control, CAPA, change control, training, validation, and audit readiness under frameworks such as FDA 21 CFR Part 11, EU Annex 11, ISO 13485, GMP, and related standards.

**Examples** include Scilife, Qualio, MasterControl, ComplianceQuest, Dot Compliance, Greenlight Guru, Sparta TrackWise, ETQ Reliance, ValGenesis, and Kneat (the category leaders).

**Open-source emphasis**: Fully validated, production eQMS platforms are almost entirely commercial because of regulatory validation burden. Useful open building blocks exist in **Open QMS**, **QAtrial**, **Senaite/Bika LIMS**, document-control-via-Git patterns, and GxP software toolkits. This section lists the most relevant options while acknowledging the commercial concentration of the category.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Scilife](https://www.scilife.io/)**  
  Modern eQMS platform aimed at life sciences companies needing document control, quality processes, and compliance workflows in a cloud-native package.

- **[Qualio](https://www.qualio.com/)**  
  Cloud-native eQMS built for early-stage and growth life sciences (medical devices, biotech, pharma) — document control, CAPA, training, design controls, and risk management.

- **[MasterControl](https://www.mastercontrol.com/)**  
  Established enterprise quality and compliance suite widely used in pharmaceuticals, medical devices, and other FDA-regulated industries — documents, change/CAPA, training, audits, and validation support.

- **[ComplianceQuest](https://www.compliancequest.com/)**  
  Quality and compliance platform (often Salesforce-based) covering QMS, EQMS, and related GxP processes including validation management.

- **[Dot Compliance](https://www.dotcompliance.com/)**  
  AI-oriented eQMS built natively on Salesforce, marketed as ready-to-deploy for GxP processes with pre-built workflows and validation packages.

- **[Greenlight Guru](https://www.greenlight.guru/)**  
  Medical-device-centric QMS platform aligned with FDA 21 CFR Part 820, ISO 13485, and EU MDR — design controls, risk, and quality processes tailored to device makers.

- **[Sparta TrackWise (PTC)](https://www.ptc.com/)**  
  Enterprise QMS long used in regulated manufacturing for quality events, CAPA, change control, and compliance tracking.

- **[ETQ Reliance](https://www.etq.com/)**  
  Quality management platform used across regulated manufacturing for document control, CAPA, audits, and compliance processes.

- **[ValGenesis](https://www.valgenesis.com/)**  
  Electronic validation lifecycle management (iVLMS) focused on CSV/CSA, validation protocols, and GxP system compliance evidence.

- **[Kneat](https://kneat.com/)**  
  Paperless validation and GxP compliance platform for creating, executing, and managing validation documentation in regulated environments.

## Open-Source GitHub Projects
- **[Open QMS](https://github.com/IridiumSoftware/open-qms)**  
  Open-source, GitHub-native QMS generator that produces traceable quality system scaffolds with clause-to-template traceability for regulated industries (including life sciences overlays).

- **[QAtrial](https://github.com/MeyerThorsten/QAtrial)**  
  Open-source quality management platform (AGPL) with requirements tracing, test management, risk, CAPA, e-signatures, audit trails, and compliance packs (FDA/GAMP, EU MDR, GMP, ISO 27001).

- **[Senaite / Bika LIMS](https://github.com/senaite)**  
  Open-source laboratory information management system used in regulated labs; includes audit trails, role-based security, and workflows relevant to GxP data integrity.

- **[GxP Python and software toolkits](https://github.com/)**  
  Libraries and frameworks that help implement audit trails, electronic signatures, and Part 11–oriented patterns in custom life-sciences applications.

- **[Document control via Git + CODEOWNERS](https://github.com/)**  
  Patterns that treat SOPs and controlled documents as versioned files with required reviewers, signed commits, and CI checks — used by some digital-native teams as a lightweight control layer.

- **[CAPA and quality event open trackers](https://github.com/)**  
  Issue-tracker templates and lightweight apps for CAPA, deviations, and complaints (typically needing extra validation for regulated use).

- **[Training record open systems](https://github.com/)**  
  Simple open tools for assigning and recording training on controlled documents.

- **[Validation protocol and CSV open templates](https://github.com/)**  
  Community templates and checklists aligned with GAMP 5 / CSA thinking for computer system validation.

- **[Audit trail and immutable log open components](https://github.com/)**  
  Libraries that append-only log critical quality actions for later inspection.

- **[Open regulatory standards mappings](https://github.com/)**  
  Machine-readable mappings of ISO, FDA, and EU requirements to process templates used by generators like Open QMS.

### Additional Strong Open-Source Options
- Using Open QMS or QAtrial as a starting scaffold, then validating the deployed instance under your own CSV/CSA program.
- Running Senaite for lab workflows that feed a commercial or open QMS.
- Git-based document control for early-stage teams before moving to a validated eQMS.
- Open analytics on exported quality metrics (CAPA cycle time, training completion) without replacing the system of record.
- Contributing validation evidence and test packs back to open GxP-oriented projects.

**Frameworks for building custom systems**: For early digital-native or research contexts, combine **Open QMS** / **QAtrial** scaffolds with Git workflows and rigorous internal validation. Production GxP environments (commercial manufacturing, medical devices, clinical supply) almost always require a validated commercial eQMS (Qualio, MasterControl, Greenlight Guru, TrackWise, ETQ, ValGenesis, Kneat, Scilife, Dot Compliance, etc.) that vendors support with 21 CFR Part 11 design, audit readiness, and change control. Open tools are best treated as accelerators and lab/data companions, not as drop-in replacements for a validated quality system of record.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- GxP systems are subject to regulatory inspection. Using open-source or custom software in a GxP-relevant process requires formal validation (CSV/CSA), change control, and documented evidence of fitness for intended use. Unvalidated tools must not be used as the sole system of record for regulated quality decisions. Always involve quality, regulatory, and validation professionals.
- This list is not regulatory or legal advice.

---
**Made for quality, regulatory, and digital teams in life sciences building compliant quality systems.**
Let's encourage more transparent, reviewable building blocks around GxP processes while respecting validation reality.
