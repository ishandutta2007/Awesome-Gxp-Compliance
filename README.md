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
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Platform | Core Focus / Description | Pricing (Starting Tier) | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Scilife](https://www.scilife.io/)** | Cloud-native eQMS for life sciences providing document control, CAPA, change control, training, and audit management. | Starts at **$1,000/month** (~$9,000–$12,000/year base for Essential tier). | **14-day free trial** with access to core workspace and up to 5 user invites; no permanent free plan. |
| **[Qualio](https://www.qualio.com/)** | Cloud eQMS built for early-stage and growth life sciences (biotech, pharma, medical devices) covering CAPA, documents, and risk. | Starts at **$1,000/month** ($12,000/year billed annually for Growth tier). | **No free trial for core eQMS** (companion QualiHQ tier offers free starter for up to 5 users/basic document sharing; guided demo for main eQMS). |
| **[MasterControl](https://www.mastercontrol.com/)** | Enterprise QMS and Manufacturing Execution System (MES) suite for FDA-regulated life sciences and quality processes. | Starts at **$2,083/month** (~$25,000/year base tier for named-user packages). | **No free trial or free forever plan**; evaluation provided strictly via scheduled vendor demo and tailored sandbox PoC. |
| **[ComplianceQuest](https://www.compliancequest.com/)** | Salesforce-native enterprise QMS, EHS, and product lifecycle compliance platform with validation packs. | Starts at **$30/user/month** (~$10,000–$15,000/year minimum commitment). | **30-day sandbox trial** available on Salesforce AppExchange for up to 5 test users; no permanent free plan. |
| **[Dot Compliance](https://www.dotcompliance.com/)** | AI-driven eQMS built natively on Salesforce with pre-configured workflows and pre-packaged GxP validation. | Starts at **$1,667/month** (~$20,000/year base tier for standard life sciences starter package). | **14-day guided validation pilot** upon qualification; no open self-service free trial or free tier. |
| **[Greenlight Guru](https://www.greenlight.guru/)** | Medical-device-specific QMS aligned with FDA 21 CFR Part 820, ISO 13485, and EU MDR design controls. | Starts at **$2,083/month** (~$25,000/year base package for early-stage MedTech startups). | **No self-serve free trial or free tier**; evaluation available via interactive product tour and guided prototype evaluation sandbox. |
| **[Sparta TrackWise (PTC)](https://www.ptc.com/)** | Enterprise QMS and quality event management platform for regulated pharmaceutical and medical manufacturing. | Starts at **$200/user/month** (~$25,000–$50,000/year minimum contract threshold for TrackWise Digital). | **No self-serve free trial or free tier**; evaluation strictly via custom architectural review and guided proof-of-concept. |
| **[ETQ Reliance](https://www.etq.com/)** | Flexible, modular enterprise quality and compliance platform supporting CAPA, audits, and document control. | Starts at **$2,083/month** (~$25,000/year entry tier based on concurrent user [CCU] licensing). | **30-day proof-of-value (PoV) sandbox** for qualified buyers upon vendor consultation; no permanent free plan. |
| **[ValGenesis](https://www.valgenesis.com/)** | Electronic validation lifecycle management (iVLMS) system for CSV/CSA protocols and paperless validation evidence. | Starts at **$2,500/month** (~$30,000/year base subscription for entry validation lifecycle modules). | **No open self-service free trial or free tier**; evaluation via guided technical demo and scoped pilot validation workshops. |
| **[Kneat](https://kneat.com/)** | Paperless validation and GxP compliance platform for authoring, approving, and executing validation documentation. | Starts at **$2,900/month** (~$35,000/year base tier depending on user license count and deployment scope). | **No free forever plan or public self-serve trial**; evaluation provided through scheduled live interactive demo and tailored sandbox walkthrough. |

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
