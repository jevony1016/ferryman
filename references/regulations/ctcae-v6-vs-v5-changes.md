# CTCAE v5.0 to v6.0 Mapping and CTCAE v6.0 Errata (official NCI)

| Field | Value |
|---|---|
| Title | CTCAE v5.0 to v6.0 Mapping; Errata (two sheets of the official CTCAE v6.0 Excel workbook) |
| Issuer | National Cancer Institute (NCI), Division of Cancer Treatment and Diagnosis (DCTD), Cancer Therapy Evaluation Program (CTEP); National Institutes of Health, U.S. Department of Health and Human Services |
| Version / date | CTCAE v6.0 workbook "CTCAE v6.0 Final Clean-Tracked-Mapping_w_OS_Jan2026.xlsx" (CTCAE v6.0 "Publish Date: July 10, 2025"; errata dated 2026-01-20; HTTP Last-Modified 21 Jan 2026). The NCI page describes this file as "CTCAE v6.0 (2025, MedDRA 28.0) (Excel) - includes a tracked changes document and mapping to v5.0". |
| Official source | https://dctd.cancer.gov/research/ctep-trials/trial-development/ctcae-v6.0.xlsx (sheets "CTCAE v5.0 to v6.0 Mapping" and "Errata"); listed on https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events |
| Retrieved | 2026-11-08 |
| Status of this file | Verbatim text of the official Excel workbook; the official version prevails. No comparison of our own is added. |

NCI CTCAE v6.0 Implementation FAQ (September 9, 2025, https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events/ctcae-v6-faq.pdf), verbatim: "The NCI has developed a comprehensive mapping resource that aligns all term and grade combinations from CTCAE v5.0 to their corresponding terms and grades in CTCAE v6.0."

**Terms of use.** Neither the CTCAE Excel workbook nor the PDF Quick Reference contains a copyright, licence or reproduction statement. The NCI DCTD page that lists the CTCAE files (https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events) ends with this notice (verbatim):

> If you would like to reproduce some or all of this content, see Reuse of NCI Information for guidance about copyright and permissions. In the case of permitted digital reproduction, please credit the National Cancer Institute as the source and link to the original NCI product using the original product's title; e.g., “CTCAE and Adverse Event Reporting was originally published by the National Cancer Institute.”

NCI "Reuse of NCI Information" (https://www.cancer.gov/policies/copyright-reuse, marked "Reviewed: March 12, 2025"), section "Reuse of Text" (verbatim):

> Unless otherwise indicated, all text within National Cancer Institute (NCI) products is free of copyright and may be reused without our permission. Credit the National Cancer Institute as the source. In the case of digital reproduction, please link to the original NCI product using the original product's title; for example, "Targeted Therapy to Treat Cancer was originally published by the National Cancer Institute." Consider linking directly to our content rather than reproducing it, as our content may be updated over time.

Credit: "Common Terminology Criteria for Adverse Events (CTCAE) v6.0 (MedDRA 28.0)" was originally published by the National Cancer Institute: https://dctd.cancer.gov/research/ctep-trials/trial-development/ctcae-v6.0.xlsx

**MedDRA.** The workbook's Publication Notes state: "CTCAE incorporates elements of the MedDRA terminology. For further details on MedDRA refer to the MedDRA MSSO Web site (https://www.meddra.org/)." NCI states no MedDRA licensing condition on its CTCAE pages or in the CTCAE files.

**Chinese version.** The NCI DCTD CTCAE pages list English files only; no NCI-authorized Chinese version is listed. No translation is included here.

**Conversion notes.** Unofficial Markdown conversion, parsed directly from the .xlsx XML; wording, spelling, punctuation and symbols are unchanged. The mapping sheet has 4070 data rows (plus a top row "V5" / "V6" and a header row; 3 empty rows at the end are skipped). Because one file would exceed 1.5 MB, the mapping is split into one file per CTCAE v5.0 SOC in the folder `ctcae-v6-vs-v5-changes/`, indexed below. In each SOC file, rows keep the source order; consecutive rows for the same CTCAE v5.0 term are grouped under `### <CTCAE v5.0 MedDRA 20.1 Term>`, and each row is rendered as one list item with all twelve columns, each labelled with the sheet's column header. Line breaks inside a cell are shown as `<br>`; spaces at the start or end of a cell or before a line break are removed. Characters such as `<`, `>` and `*` are not Markdown-escaped. The Errata sheet is reproduced in full below; its "Update Date" values are Excel date serials, shown here as ISO dates. The sheet "CTCAE v6.0 Tracked Changes" (changes marked by text formatting) is not converted; the per-term "CTCAE v6.0 Change" column is in ctcae-v6.md. This conversion is not endorsed by NCI.

---

## Errata (verbatim from the workbook's "Errata" sheet)

- **Decreased night vision** (CTCAE v6.0 MedDRA 28.0 LLT Code: 10011974; CTCAE v6.0 MedDRA 28.0 SOC: Eye disorders)
  - **Grade/Definition:** Grade 1
  - **Previous Version:** Symptomatic but not limiting ADL
  - **Updated Version:** Symptomatic
  - **Update Date:** 2026-01-20 (Excel serial 46042)
- **Vomiting** (CTCAE v6.0 MedDRA 28.0 LLT Code: 10047700; CTCAE v6.0 MedDRA 28.0 SOC: Gastrointestinal disorders)
  - **Grade/Definition:** Grade 2
  - **Previous Version:** Initiation of outpatient IV hydration; medical intervention indicated
  - **Updated Version:** Initiation of outpatient IV hydration; medical intervention indicated
  - **Update Date:** 2026-01-20 (Excel serial 46042)
- **Pneumonia** (CTCAE v6.0 MedDRA 28.0 LLT Code: 10035664; CTCAE v6.0 MedDRA 28.0 SOC: Infections and infestations)
  - **Grade/Definition:** Definition
  - **Previous Version:** A disorder characterized by an infectious process involving the lungs, including pneumonia.
  - **Updated Version:** A disorder characterized by an infectious process involving the lungs.
  - **Update Date:** 2026-01-20 (Excel serial 46042)
- **White blood cell decreased** (CTCAE v6.0 MedDRA 28.0 LLT Code: 10049182; CTCAE v6.0 MedDRA 28.0 SOC: Investigations)
  - **Grade/Definition:** Definition
  - **Previous Version:** A finding based on laboratory test results that indicate an decrease in number of white blood cells (WBC) in a blood specimen.
  - **Updated Version:** A finding based on laboratory test results that indicate a decrease in number of white blood cells (WBC) in a blood specimen.
  - **Update Date:** 2026-01-20 (Excel serial 46042)
- **Creatinine increased** (CTCAE v6.0 MedDRA 28.0 LLT Code: 10011368; CTCAE v6.0 MedDRA 28.0 SOC: Investigations)
  - **Grade/Definition:** Grade 2
  - **Previous Version:** >1.5 - 3.0 x if baseline is below LLN; >1.5 - 3.0 x ULN
  - **Updated Version:** >1.5 - 3.0 x baseline if baseline is below LLN; >1.5 - 3.0 x ULN
  - **Update Date:** 2026-01-20 (Excel serial 46042)
- **Creatinine increased** (CTCAE v6.0 MedDRA 28.0 LLT Code: 10011368; CTCAE v6.0 MedDRA 28.0 SOC: Investigations)
  - **Grade/Definition:** Grade 3
  - **Previous Version:** >3.0 x if baseline is below LLN; >3.0 - 6.0 x ULN
  - **Updated Version:** >3.0 x baseline if baseline is below LLN; >3.0 - 6.0 x ULN
  - **Update Date:** 2026-01-20 (Excel serial 46042)
- **Thrombocytopenia** (CTCAE v6.0 MedDRA 28.0 LLT Code: 10043554; CTCAE v6.0 MedDRA 28.0 SOC: Blood and lymphatic system disorders)
  - **Grade/Definition:** Grade 4
  - **Previous Version:** <10,000/mm3; 10.0 x 10^9/L; life-threatening consequences; urgent intervention indicated
  - **Updated Version:** <10,000/mm3; <10.0 x 10^9/L; life-threatening consequences; urgent intervention indicated
  - **Update Date:** 2026-01-20 (Excel serial 46042)

---

## CTCAE v5.0 to v6.0 Mapping: files per CTCAE v5.0 SOC

Column headers of the mapping sheet (verbatim): "CTCAE v5.0 MedDRA 20.1 LLT Code"; "CTCAE v5.0 MedDRA 20.1 SOC"; "CTCAE v5.0 MedDRA 20.1 Term"; "CTCAE v5.0 Grade/Definition/Navigational Note"; "CTCAE v5.0 Description"; "Change Type"; "CTCAE v6.0 MedDRA 28.0 LLT Code"; "CTCAE v6.0 MedDRA 28.0 SOC"; "CTCAE v6.0 MedDRA 28.0 Term"; "CTCAE v6.0 Grade/Definition/Navigational Note"; "CTCAE v6.0 Description"; "CTCAE v6.0 Other Specify".

| CTCAE v5.0 SOC | File | Mapping rows | CTCAE v5.0 terms |
|---|---|---|---|
| Blood and lymphatic system disorders | [ctcae-v6-vs-v5-changes/blood-and-lymphatic-system-disorders.md](ctcae-v6-vs-v5-changes/blood-and-lymphatic-system-disorders.md) | 56 | 12 |
| Cardiac disorders | [ctcae-v6-vs-v5-changes/cardiac-disorders.md](ctcae-v6-vs-v5-changes/cardiac-disorders.md) | 174 | 34 |
| Congenital, familial and genetic disorders | [ctcae-v6-vs-v5-changes/congenital-familial-and-genetic-disorders.md](ctcae-v6-vs-v5-changes/congenital-familial-and-genetic-disorders.md) | 5 | 1 |
| Ear and labyrinth disorders | [ctcae-v6-vs-v5-changes/ear-and-labyrinth-disorders.md](ctcae-v6-vs-v5-changes/ear-and-labyrinth-disorders.md) | 35 | 8 |
| Endocrine disorders | [ctcae-v6-vs-v5-changes/endocrine-disorders.md](ctcae-v6-vs-v5-changes/endocrine-disorders.md) | 62 | 14 |
| Eye disorders | [ctcae-v6-vs-v5-changes/eye-disorders.md](ctcae-v6-vs-v5-changes/eye-disorders.md) | 121 | 26 |
| Gastrointestinal disorders | [ctcae-v6-vs-v5-changes/gastrointestinal-disorders.md](ctcae-v6-vs-v5-changes/gastrointestinal-disorders.md) | 643 | 122 |
| General disorders and administration site conditions | [ctcae-v6-vs-v5-changes/general-disorders-and-administration-site-conditions.md](ctcae-v6-vs-v5-changes/general-disorders-and-administration-site-conditions.md) | 107 | 25 |
| Hepatobiliary disorders | [ctcae-v6-vs-v5-changes/hepatobiliary-disorders.md](ctcae-v6-vs-v5-changes/hepatobiliary-disorders.md) | 84 | 18 |
| Immune system disorders | [ctcae-v6-vs-v5-changes/immune-system-disorders.md](ctcae-v6-vs-v5-changes/immune-system-disorders.md) | 36 | 6 |
| Infections and infestations | [ctcae-v6-vs-v5-changes/infections-and-infestations.md](ctcae-v6-vs-v5-changes/infections-and-infestations.md) | 440 | 88 |
| Injury, poisoning and procedural complications | [ctcae-v6-vs-v5-changes/injury-poisoning-and-procedural-complications.md](ctcae-v6-vs-v5-changes/injury-poisoning-and-procedural-complications.md) | 447 | 79 |
| Investigations | [ctcae-v6-vs-v5-changes/investigations.md](ctcae-v6-vs-v5-changes/investigations.md) | 186 | 42 |
| Metabolism and nutrition disorders | [ctcae-v6-vs-v5-changes/metabolism-and-nutrition-disorders.md](ctcae-v6-vs-v5-changes/metabolism-and-nutrition-disorders.md) | 145 | 26 |
| Musculoskeletal and connective tissue disorders | [ctcae-v6-vs-v5-changes/musculoskeletal-and-connective-tissue-disorders.md](ctcae-v6-vs-v5-changes/musculoskeletal-and-connective-tissue-disorders.md) | 199 | 44 |
| Neoplasms benign, malignant and unspecified (incl cysts and polyps) | [ctcae-v6-vs-v5-changes/neoplasms-benign-malignant-and-unspecified-incl-cysts-and-polyps.md](ctcae-v6-vs-v5-changes/neoplasms-benign-malignant-and-unspecified-incl-cysts-and-polyps.md) | 28 | 7 |
| Nervous system disorders | [ctcae-v6-vs-v5-changes/nervous-system-disorders.md](ctcae-v6-vs-v5-changes/nervous-system-disorders.md) | 311 | 68 |
| Pregnancy, puerperium and perinatal conditions | [ctcae-v6-vs-v5-changes/pregnancy-puerperium-and-perinatal-conditions.md](ctcae-v6-vs-v5-changes/pregnancy-puerperium-and-perinatal-conditions.md) | 16 | 4 |
| Psychiatric disorders | [ctcae-v6-vs-v5-changes/psychiatric-disorders.md](ctcae-v6-vs-v5-changes/psychiatric-disorders.md) | 96 | 21 |
| Renal and urinary disorders | [ctcae-v6-vs-v5-changes/renal-and-urinary-disorders.md](ctcae-v6-vs-v5-changes/renal-and-urinary-disorders.md) | 103 | 23 |
| Reproductive system and breast disorders | [ctcae-v6-vs-v5-changes/reproductive-system-and-breast-disorders.md](ctcae-v6-vs-v5-changes/reproductive-system-and-breast-disorders.md) | 209 | 49 |
| Respiratory, thoracic and mediastinal disorders | [ctcae-v6-vs-v5-changes/respiratory-thoracic-and-mediastinal-disorders.md](ctcae-v6-vs-v5-changes/respiratory-thoracic-and-mediastinal-disorders.md) | 321 | 62 |
| Skin and subcutaneous tissue disorders | [ctcae-v6-vs-v5-changes/skin-and-subcutaneous-tissue-disorders.md](ctcae-v6-vs-v5-changes/skin-and-subcutaneous-tissue-disorders.md) | 153 | 39 |
| Social circumstances | [ctcae-v6-vs-v5-changes/social-circumstances.md](ctcae-v6-vs-v5-changes/social-circumstances.md) | 5 | 1 |
| Surgical and medical procedures | [ctcae-v6-vs-v5-changes/surgical-and-medical-procedures.md](ctcae-v6-vs-v5-changes/surgical-and-medical-procedures.md) | 5 | 1 |
| Vascular disorders | [ctcae-v6-vs-v5-changes/vascular-disorders.md](ctcae-v6-vs-v5-changes/vascular-disorders.md) | 83 | 17 |
| **Total** | | 4070 | |
