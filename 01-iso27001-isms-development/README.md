# ISO/IEC 27001:2022 Lead Auditor Case Study – SafeStore Pty Ltd

> **Disclaimer:** This project was completed as part of a GRC Mastery Lead Auditor training course. SafeStore Pty Ltd is a fictional organisation. The completed workbooks contain my own answers entered into the course's assessment templates. The course's case documents and brief are proprietary and are not included in this repository. Nothing here is professional advice or a real audit opinion.

## Project Overview

This project is an end-to-end simulated **ISO/IEC 27001:2022 Stage 2 (initial certification) audit** of a fictional cloud-storage company's Information Security Management System (ISMS). I carried it out as the **Lead Auditor** for an independent certification body, following **ISO 19011:2026** auditing guidance.

It covers the full audit life cycle – planning, leading the audit team, conducting the audit, reporting and closing, and professional behaviour. This repository also contains an interactive learning guide I wrote to explain the approach to newcomers.

## Business Context

SafeStore is a small Australian company providing encrypted cloud storage to individuals and small businesses through a web portal and mobile app. Customer data is hosted in third-party Australian data centres. As a holder of personal information, the company is subject to Australian privacy law, including the Privacy Act, the Australian Privacy Principles and the Notifiable Data Breaches scheme.

Having completed its Stage 1 audit, the company was seeking ISO/IEC 27001:2022 certification. Its risk register identified risks around access control, backup, incident response, equipment disposal, suppliers and vulnerabilities, and several risk treatments were overdue.

## Project Objectives

1. Determine the conformity of the ISMS with ISO/IEC 27001:2022 Clauses 4–10.
2. Evaluate the implementation and effectiveness of selected Annex A controls.
3. Evaluate the ISMS's ability to meet legal, regulatory and contractual requirements and its security objectives.
4. Reach an evidence-based audit conclusion and certification recommendation.
5. Demonstrate Lead Auditor competence in planning, team leadership, evidence evaluation, reporting and professional ethics.

## Scope

- **Audit type:** Stage 2 (initial certification), one day, three-person audit team (Lead, Technical and Compliance Auditors).
- **Coverage:** the company's cloud-storage service, including platform development, maintenance and operation, at its head office and supporting cloud infrastructure.
- **Focus controls:** A.8.3 Information access restriction · A.8.13 Information backup · A.7.14 Secure disposal or re-use of equipment.
- **Exclusions:** third-party data-centre physical operations, customer devices, and outsourced systems unrelated to the service.

## Frameworks and Standards

| Standard | Role in this project |
|---|---|
| **ISO/IEC 27001:2022** | Audit criteria – ISMS requirements (Clauses 4–10) and Annex A controls |
| **ISO 19011:2026** | Audit method – principles, planning, conducting, reporting and follow-up |
| **ISO/IEC 17021-1 / ISO/IEC 27006** | Context – requirements for certification bodies |
| **Australian privacy law** | Legal requirements the ISMS must address |

## Methodology

| Phase | What I did |
|---|---|
| **1 – Plan** | Evaluated a deficient draft audit plan – finding wrong objectives, an incorrect scope, mislabelled Annex A controls and poor use of the team – and produced a corrected risk-based plan with three parallel audit streams. |
| **2 – Lead** | Briefed and allocated the team by competence and impartiality; prepared the opening meeting; handled an auditor conflict of interest and unavailable evidence; reviewed draft findings. |
| **3 – Conduct** | Planned interviews and evidence checks; applied judgement-based sampling; recorded findings; reviewed the SoA against the risk register and the risk method against Clause 6.1.2; ran a team debrief. |
| **4 – Report & close** | Recorded the closing meeting, wrote the final audit report, and evaluated corrective action and follow-up. |
| **5 – Professional behaviour** | Responded to five ethics scenarios; completed a self-evaluation, a development plan and a reflection. |

**Sampling:** judgement-based, selected by the auditors from complete populations and weighted to risk, with a 100% check of very small populations.

## Key Findings

| Ref | Control | Classification | Summary |
|---|---|---|---|
| C1 | A.8.3 Information access restriction | ✅ Conformity | Least privilege, MFA and time-limited elevated access verified on sampled accounts. |
| C2 | A.8.13 Information backup | ✅ Conformity | Encrypted backups, an offsite copy and successful restore testing verified. |
| N1 | A.7.14 Secure disposal or re-use | ⚠️ Minor NC | No approved way to verify that storage media are wiped before disposal or re-use; the related risk treatment was overdue. Isolated gap, with no data exposed. |
| OFI1 | A.5.19–A.5.22 Supplier security | 💡 OFI | No documented schedule for periodic supplier-security reviews. |
| OFI2 | A.6.3 Awareness and training | 💡 OFI | Training-completion reports lacked dates and links to individual records. |

**Overall result:** 0 major · 1 minor · 2 OFIs. The ISMS is effective overall, with one minor gap.

## Recommendations

- **Certification recommendation:** recommend certification subject to an accepted corrective action plan for N1. The certification body makes the final decision.
- **Improvement areas for the organisation** (what to improve, not how – auditors don't prescribe solutions, to stay impartial): verification of media sanitisation, tracking of overdue risk-treatment actions, periodic supplier reviews, and dated training records.
- **Follow-up:** corrective-action implementation verified; effectiveness to be confirmed at the first surveillance audit.

## Deliverables

| Deliverable | File |
|---|---|
| Audit plan evaluation and final audit plan | [`workbooks/SafeStore_Student_Workbook_Stage1_Plan_COMPLETED.xlsx`](workbooks/SafeStore_Student_Workbook_Stage1_Plan_COMPLETED.xlsx) |
| Team briefing, opening meeting and finding review | [`workbooks/SafeStore_Student_Workbook_Stage2_Lead_the_Team_COMPLETED.xlsx`](workbooks/SafeStore_Student_Workbook_Stage2_Lead_the_Team_COMPLETED.xlsx) |
| Checklist, sampling record, findings, debrief and SoA review | [`workbooks/SafeStore_Student_Workbook_Stage3_Conduct_COMPLETED.xlsx`](workbooks/SafeStore_Student_Workbook_Stage3_Conduct_COMPLETED.xlsx) |
| Closing meeting, final audit report and corrective-action record | [`workbooks/SafeStore_Student_Workbook_Stage4_Report_and_Close_COMPLETED.xlsx`](workbooks/SafeStore_Student_Workbook_Stage4_Report_and_Close_COMPLETED.xlsx) |
| Ethics scenarios, self-evaluation and reflection | [`workbooks/SafeStore_Student_Workbook_Stage5_Professional_Behaviour_COMPLETED.xlsx`](workbooks/SafeStore_Student_Workbook_Stage5_Professional_Behaviour_COMPLETED.xlsx) |
| **Interactive learning guide** | [`SafeStore_Lead_Auditor_Learning_Guide.html`](SafeStore_Lead_Auditor_Learning_Guide.html) · [View online](https://uchemanuels.github.io/grc-portfolio/01-iso27001-isms-development/SafeStore_Lead_Auditor_Learning_Guide.html) |

The workbooks are Excel files – download them to view. GitHub can't preview `.xlsx` files.

The **learning guide** explains ISO 27001 and ISO 19011 concepts in plain language, how each audit decision was reached, and lessons learned. It includes click-to-explain terms, a searchable glossary, a progress tracker and a quiz.

**Repository structure:**
```
├── README.md
├── SafeStore_Lead_Auditor_Learning_Guide.html
└── workbooks/        # My completed assessment workbooks (Stages 1–5)
```

## Skills Demonstrated

- Risk-based audit planning and feasibility assessment
- Audit team leadership, work allocation and impartiality management
- Interviewing, evidence verification and audit sampling
- SoA and risk methodology evaluation
- Grading nonconformities against certification body criteria
- Audit reporting, closing meetings and corrective-action follow-up
- Professional ethics, confidentiality and reflective practice

## Limitations

- **Simulated case:** a fictional organisation and a one-day training simulation, not a real certification audit.
- **Sampling:** the conclusions rest on small samples, so undetected nonconformities may exist.
- **Assumptions:** the audit date was chosen to match the case timeline; some inputs the course referred to were not supplied and were reasonably assumed or simulated, and labelled as such.
- **Clause numbering:** ISO 19011:2026 clause references follow the course materials.
- **Course materials:** the case documents and brief are not published here, out of respect for the training provider's intellectual property.

---

**Author:** Emmanuel Okorie – ISO/IEC 27001 Lead Auditor (candidate)
