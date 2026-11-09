# Common Terminology Criteria for Adverse Events (CTCAE) v6.0 (MedDRA 28.0)

| Field | Value |
|---|---|
| Title | Common Terminology Criteria for Adverse Events (CTCAE) v6.0 (MedDRA 28.0) |
| Issuer | National Cancer Institute (NCI), Division of Cancer Treatment and Diagnosis (DCTD), Cancer Therapy Evaluation Program (CTEP); National Institutes of Health, U.S. Department of Health and Human Services |
| Version | CTCAE v6.0; each term is a MedDRA v28.0 LLT. NCI FAQ (September 9, 2025): "No further changes are planned. The release version is the final version of CTCAE v6.0." |
| Release date | "Publish Date: July 10, 2025" (Publication Notes sheet of the Excel workbook); the PDF Quick Reference states "Published July 22, 2025"; the NCI page says v6.0 "was released in 2025". The current workbook includes the errata dated 2026-01-20 (Errata sheet; file name "CTCAE v6.0 Final Clean-Tracked-Mapping_w_OS_Jan2026.xlsx"; HTTP Last-Modified 21 Jan 2026). |
| Official source (this file) | https://dctd.cancer.gov/research/ctep-trials/trial-development/ctcae-v6.0.xlsx (sheet "CTCAE v6.0 Clean Copy") |
| Official pages | https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events ; https://dctd.cancer.gov/research/ctep-trials/trial-development (the old address https://ctep.cancer.gov/protocoldevelopment/electronic_applications/ctc.htm redirects to the latter) |
| Other official v6.0 files | PDF Quick Reference https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events/ctcae-v6.pdf ; Implementation FAQ https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events/ctcae-v6-faq.pdf ; official v5.0-to-v6.0 mapping and errata: ctcae-v6-vs-v5-changes.md |
| Retrieved | 2026-11-08 |
| Status of this file | Verbatim text of the official Excel workbook; the official version prevails. |

**Terms of use.** Neither the CTCAE Excel workbook nor the PDF Quick Reference contains a copyright, licence or reproduction statement. The NCI DCTD page that lists the CTCAE files (https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events) ends with this notice (verbatim):

> If you would like to reproduce some or all of this content, see Reuse of NCI Information for guidance about copyright and permissions. In the case of permitted digital reproduction, please credit the National Cancer Institute as the source and link to the original NCI product using the original product's title; e.g., “CTCAE and Adverse Event Reporting was originally published by the National Cancer Institute.”

NCI "Reuse of NCI Information" (https://www.cancer.gov/policies/copyright-reuse, marked "Reviewed: March 12, 2025"), section "Reuse of Text" (verbatim):

> Unless otherwise indicated, all text within National Cancer Institute (NCI) products is free of copyright and may be reused without our permission. Credit the National Cancer Institute as the source. In the case of digital reproduction, please link to the original NCI product using the original product's title; for example, "Targeted Therapy to Treat Cancer was originally published by the National Cancer Institute." Consider linking directly to our content rather than reproducing it, as our content may be updated over time.

Credit: "Common Terminology Criteria for Adverse Events (CTCAE) v6.0 (MedDRA 28.0)" was originally published by the National Cancer Institute: https://dctd.cancer.gov/research/ctep-trials/trial-development/ctcae-v6.0.xlsx

**MedDRA.** The workbook's Publication Notes state: "CTCAE incorporates elements of the MedDRA terminology. For further details on MedDRA refer to the MedDRA MSSO Web site (https://www.meddra.org/)." and "Each CTCAE v6.0 term is a MedDRA v28.0 LLT (Lowest Level Term)." NCI states no MedDRA licensing condition on its CTCAE pages or in the CTCAE files.

**Chinese version.** The NCI DCTD CTCAE pages list English files only; no NCI-authorized Chinese version is listed. No translation is included here.

**Conversion notes.** This is an unofficial Markdown conversion of the sheet "CTCAE v6.0 Clean Copy" (850 rows, one per CTCAE term), parsed directly from the .xlsx XML. Wording, spelling, punctuation and symbols are unchanged. Each row is rendered as `## <CTCAE v6.0 MedDRA 28.0 SOC>`, then `### <CTCAE v6.0 MedDRA 28.0 Term>`, then the LLT code, then the columns Grade 1 to Grade 5, Definition, Navigational Note and CTCAE v6.0 Change (the sheet's own column, describing the change from v5.0), each labelled with the sheet's column header. Rows keep the source order. A grade that is not available is shown as in the source: a single hyphen "-" (NCI: "A single dash (-) indicates a Grade is not available"). Line breaks inside a cell are shown as `<br>`. Spaces at the start or end of a cell, and before a line break, are removed. Characters such as `<`, `>` and `*` are not Markdown-escaped. The workbook's Errata sheet lists seven corrections dated 2026-01-20; all seven were checked and are already in the Clean Copy (the Errata sheet itself is reproduced in ctcae-v6-vs-v5-changes.md). The sheet "CTCAE v6.0 Tracked Changes", which marks changes by text formatting, is not converted. The "Publication Notes" sheet is reproduced below. The section "Contents" is added for navigation. This conversion is not endorsed by NCI.

---

## Publication Notes (verbatim from the workbook's "Publication Notes" sheet)

Common Terminology Criteria for Adverse Events (CTCAE) v6.0 (MedDRA 28.0)

Publish Date: July 10, 2025

**Introduction**

The NCI Common Terminology Criteria for Adverse Events is a descriptive terminology which can be utilized for Adverse Event (AE) reporting. A grading (severity) scale is provided for each AE term.

**SOC**

System Organ Class (SOC), the highest level of the MedDRA<sup>1</sup> hierarchy, is identified by anatomical orphysiological system, etiology, or purpose (e.g., SOC Investigations for laboratory test results).  CTCAE terms are grouped by MedDRA Primary SOCs. Within each SOC, AEs are listed and accompanied by descriptions of severity (Grade).

**CTCAE Terms**

An Adverse Event (AE) is any unfavorable and unintended sign (including an abnormal laboratory finding), symptom, or disease temporally associated with the use of a medical treatment or procedure that may or may not be considered related to the medical treatment or procedure. An AE is a term that is a unique representation of a specific event used for medical documentation and scientific analyses. Each CTCAE v6.0 term is a MedDRA v28.0 LLT (Lowest Level Term).

**Grades**

Grade refers to the severity of the AE. The CTCAE displays Grades 1 through 5 with unique clinical descriptions of severity for each AE based on this general guideline:

- Grade 1 Mild; asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated.
- Grade 2 Moderate; minimal, local or noninvasive intervention indicated; limiting age- appropriate instrumental ADL*.
- Grade 3 Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of hospitalization indicated; disabling; limiting self care ADL**.
- Grade 4 Life-threatening consequences; urgent intervention indicated.
- Grade 5 Death related to AE.

A Semi-colon indicates ‘or’ within the description of the grade.

A single dash (-) indicates a Grade is not available. Not all Grades are appropriate for all AEs.  Therefore, some AEs are listed with fewer than five options for Grade selection.

**Grade 5**

Grade 5 (Death) is not appropriate for some AEs and therefore is not an option.

**Definitions**

A brief Definition is provided to clarify the meaning of each AE term. A single dash (-) indicates a Definition is not available.

**Navigational Notes**

A Navigational Note is used to assist the reporter in choosing a correct AE. It may list other AEs that should be considered in addition to or in place of the AE in question. A single dash (-) indicates a Navigational Note has not been defined for the AE term.

**Activities of Daily Living (ADL)**

\*Instrumental ADL refer to preparing meals, shopping for groceries or clothes, using the telephone, managing money, etc.

\*\*Self care ADL refer to bathing, dressing and undressing, feeding self, using the toilet, taking medications.

**Pediatric Activities of Daily Living (ADL)**

\*Mild/moderate impact on age-appropriate normal daily activity

\*Ssevere impact on age-appropriate normal daily activity

<sup>1</sup> CTCAE  incorporates  elements of the MedDRA terminology. For further details on MedDRA refer to the MedDRA MSSO Web site (https://www.meddra.org/).

(Typos such as "orphysiological" and "Ssevere" are in the source; non-breaking spaces are shown as normal spaces. The PDF Quick Reference, https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events/ctcae-v6.pdf, page 2, words some of these notes differently, for example Grade 2 "Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)*." The per-term text below is from the Excel Clean Copy.)

---

## Contents (navigation added in this conversion; numbers are CTCAE terms per SOC in the source sheet)

- Blood and lymphatic system disorders (18)
- Cardiac disorders (30)
- Congenital, familial and genetic disorders (1)
- Ear and labyrinth disorders (8)
- Endocrine disorders (15)
- Eye disorders (26)
- Gastrointestinal disorders (122)
- General disorders and administration site conditions (24)
- Hepatobiliary disorders (20)
- Immune system disorders (8)
- Infections and infestations (89)
- Injury, poisoning and procedural complications (79)
- Investigations (40)
- Metabolism and nutrition disorders (26)
- Musculoskeletal and connective tissue disorders (44)
- Neoplasms benign, malignant and unspecified (incl cysts and polyps) (10)
- Nervous system disorders (71)
- Pregnancy, puerperium and perinatal conditions (4)
- Psychiatric disorders (21)
- Renal and urinary disorders (25)
- Reproductive system and breast disorders (47)
- Respiratory, thoracic and mediastinal disorders (61)
- Skin and subcutaneous tissue disorders (41)
- Social circumstances (1)
- Surgical and medical procedures (1)
- Vascular disorders (18)

Total: 850 terms.

---

## Blood and lymphatic system disorders

### Anemia

MedDRA 28.0 LLT code: 10002272

- **Grade 1:** Hemoglobin (Hgb) <LLN - 10.0 g/dL; <LLN - 6.2 mmol/L; <LLN - 100 g/L
- **Grade 2:** Hgb <10.0 - 8.0 g/dL; <6.2 - 4.9 mmol/L; <100 - 80 g/L
- **Grade 3:** Hgb <8.0 g/dL; <4.9 mmol/L; <80 g/L; transfusion indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a reduction in the amount of hemoglobin in 100 ml of blood. Signs and symptoms of anemia may include pallor of the skin and mucous membranes, shortness of breath, palpitations of the heart, soft systolic murmurs, lethargy, and fatigability.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Aplastic anemia

MedDRA 28.0 LLT code: 10002969

- **Grade 1:** -
- **Grade 2:** Use of growth factor indicated; transfusion indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the inability of the bone marrow to make enough new blood cells.
- **Navigational Note:** Do not report individual cell count decreases in addition to this term.
- **CTCAE v6.0 Change:** Addition: Term

### Blood and lymphatic system disorders - Other, specify

MedDRA 28.0 LLT code: 10005329

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Bone marrow hypocellular

MedDRA 28.0 LLT code: 10048580

- **Grade 1:** Mildly hypocellular or <=25% reduction from normal cellularity for age
- **Grade 2:** Moderately hypocellular or >25 - <50% reduction from normal cellularity for age
- **Grade 3:** Severely hypocellular or >50 - <=75% reduction cellularity from normal for age
- **Grade 4:** Aplastic persistent for longer than 2 weeks
- **Grade 5:** Death
- **Definition:** A disorder characterized by the inability of the bone marrow to produce hematopoietic elements.
- **Navigational Note:** Consider Blood and lymphatic system disorders: Anemia, Thrombocytopenia, and/or Investigations: Neutrophil count decreased if bone marrow hypocellularity is not seen.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Disseminated intravascular coagulation

MedDRA 28.0 LLT code: 10013442

- **Grade 1:** -
- **Grade 2:** Laboratory findings with no bleeding
- **Grade 3:** Laboratory findings and bleeding
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by systemic pathological activation of blood clotting mechanisms which results in clot formation throughout the body. There is an increase in the risk of hemorrhage as the body is depleted of platelets and coagulation factors.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Eosinophilia

MedDRA 28.0 LLT code: 10014950

- **Grade 1:** >ULN and >Baseline
- **Grade 2:** -
- **Grade 3:** Steroids initiated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by laboratory test results that indicate an increased number of eosinophils in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Febrile neutropenia

MedDRA 28.0 LLT code: 10016288

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** ANC <1000/mm3 with a single temperature of >38.3 degrees C (101 degrees F) or a sustained temperature of >=38 degrees C (100.4 degrees F) for more than one hour
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an ANC <1000/mm3 and a single temperature of >38.3 degrees C (101 degrees F) or a sustained temperature of >=38 degrees C (100.4 degrees F) for more than one hour.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Hemolysis

MedDRA 28.0 LLT code: 10019491

- **Grade 1:** Laboratory evidence of hemolysis only (e.g., direct antiglobulin test; DAT; Coombs'; schistocytes; decreased haptoglobin)
- **Grade 2:** Evidence of hemolysis and >=2 g decrease in hemoglobin
- **Grade 3:** Transfusion or medical intervention indicated (e.g., steroids)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate widespread erythrocyte cell membrane destruction.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hemolytic anemia

MedDRA 28.0 LLT code: 10019493

- **Grade 1:** <10% drop in Hgb from last assessment; intervention not indicated
- **Grade 2:** <=2 units of PRBCs transfused per day
- **Grade 3:** >2 units of PRBCs per day indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** Anemia resulting from hemolysis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Hemolytic uremic syndrome

MedDRA 28.0 LLT code: 10019515

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Laboratory findings with clinical consequences (e.g., renal insufficiency, petechiae)
- **Grade 4:** Life-threatening consequences, (e.g., CNS hemorrhage or thrombosis/embolism or renal failure)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a form of thrombotic microangiopathy with renal failure, hemolytic anemia, and severe thrombocytopenia when the etiology is due to infections with shiga-toxin producing bacteria, such as E coli O157:H7.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Leukocytosis

MedDRA 28.0 LLT code: 10024378

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** >100,000/mm3
- **Grade 4:** Clinical manifestations of leucostasis; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an increased number of white blood cells in the blood.
- **Navigational Note:** Do not use for increases due to growth factors, steroids, or leukemias.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Lymph node pain

MedDRA 28.0 LLT code: 10025182

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in a lymph node.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Lymphopenia

MedDRA 28.0 LLT code: 10025327

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in number of lymphocytes in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Methemoglobinemia

MedDRA 28.0 LLT code: 10027506

- **Grade 1:** -
- **Grade 2:** >ULN
- **Grade 3:** Requiring urgent intervention
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate increased methemoglobin in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Thrombocytopenia

MedDRA 28.0 LLT code: 10043554

- **Grade 1:** <LLN - 75,000/mm3; <LLN - 75.0 x 10^9/L
- **Grade 2:** <75,000 - 50,000/mm3; <75.0 - 50.0 x 10^9/L
- **Grade 3:** <50,000 - 10,000/mm3; <50.0 - 10.0 x 10^9/L; transfusion indicated
- **Grade 4:** <10,000/mm3; <10.0 x 10^9/L; life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in number of platelets in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Thrombocytosis

MedDRA 28.0 LLT code: 10043563

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in number of platelets in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Thrombotic microangiopathy

MedDRA 28.0 LLT code: 10043645

- **Grade 1:** -
- **Grade 2:** Outpatient intervention indicated (e.g., modification of immunosuppression)
- **Grade 3:** Transfusion or IV intervention indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by a form of thrombotic microangiopathy with laboratory findings that indicate hemolytic anemia, severe thrombocytopenia, and renal insufficiency/failure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Thrombotic thrombocytopenic purpura

MedDRA 28.0 LLT code: 10043648

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Laboratory findings with clinical consequences (e.g., renal insufficiency, petechiae)
- **Grade 4:** Life-threatening consequences, (e.g., CNS hemorrhage or thrombosis/embolism or renal failure)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a deficiency of ADAMTS13 and the presence of microangiopathic hemolytic anemia, thrombocytopenic purpura, fever, renal abnormalities and neurological abnormalities such as seizures, hemiplegia, and visual disturbances. It is an acute or subacute condition.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

## Cardiac disorders

### Aortic valve disease

MedDRA 28.0 LLT code: 10061589

- **Grade 1:** Asymptomatic valvular thickening with or without mild valvular regurgitation or stenosis by imaging
- **Grade 2:** Asymptomatic; moderate regurgitation or stenosis by imaging
- **Grade 3:** Symptomatic; severe regurgitation or stenosis by imaging; symptoms controlled with medical intervention
- **Grade 4:** Life-threatening consequences; urgent intervention indicated (e.g., valve replacement, valvuloplasty)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a defect in aortic valve function or structure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Asystole

MedDRA 28.0 LLT code: 10003586

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Intervention indicated; device (e.g., pacemaker)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia without cardiac electrical activity. Typically, this is accompanied by cessation of the pumping function of the heart.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Grade 3; Deletion: Grade 1

### Atrial fibrillation

MedDRA 28.0 LLT code: 10003658

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Non-urgent medical intervention indicated; electrical cardioversion
- **Grade 3:** Symptomatic, urgent intervention indicated; device (e.g., pacemaker); ablation; new onset
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia without discernible P waves and an irregular ventricular response due to multiple reentry circuits. The rhythm disturbance originates above the ventricles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 4

### Atrial flutter

MedDRA 28.0 LLT code: 10003662

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Non-urgent medical intervention indicated
- **Grade 3:** Symptomatic, urgent intervention indicated; device (e.g., pacemaker); ablation
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with organized rhythmic atrial contractions with a rate of 200-300 beats per minute. The rhythm disturbance originates in the atria.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 4

### Atrioventricular block complete

MedDRA 28.0 LLT code: 10003673

- **Grade 1:** -
- **Grade 2:** Non-urgent intervention indicated
- **Grade 3:** Symptomatic and incompletely controlled medically, or controlled with device (e.g., pacemaker); new onset
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with complete failure of atrial electrical impulse conduction through the AV node to the ventricles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Atrioventricular block first degree

MedDRA 28.0 LLT code: 10003674

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Non-urgent intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a dysrhythmia with a delay in the time required for the conduction of an electrical impulse through the atrioventricular (AV) node beyond 0.2 seconds; prolongation of the PR interval greater than 200 milliseconds.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cardiac arrest

MedDRA 28.0 LLT code: 10007515

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by cessation of the pumping function of the heart.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cardiac disorders - Other, specify

MedDRA 28.0 LLT code: 10007541

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Chest pain - cardiac

MedDRA 28.0 LLT code: 10008481

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; pain on exertion; hemodynamically stable; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Pain at rest; cardiac catheterization; new onset cardiac chest pain; unstable angina; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by substernal discomfort due to insufficient myocardial oxygenation e.g., angina pectoris.
- **Navigational Note:** Consider Cardiac disorders: Myocardial infarction. Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Heart failure

MedDRA 28.0 LLT code: 10019279

- **Grade 1:** Mild symptoms; no initiation or intensification of treatment
- **Grade 2:** Outpatient initiation or intensification of treatment
- **Grade 3:** Hospitalization indicated
- **Grade 4:** Requiring inotropic support, mechanical circulatory support, or consideration of cardiac transplantation
- **Grade 5:** Death
- **Definition:** A disorder characterized by the inability of the heart to pump blood at an adequate volume to meet tissue metabolic requirements, or, the ability to do so only at an elevation in the filling pressure.
- **Navigational Note:** If asymptomatic, consider Cardiac disorders: Left ventricular dysfunction.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4, Navigational Note

### Left ventricular dysfunction

MedDRA 28.0 LLT code: 10049694

- **Grade 1:** Left ventricular ejection fraction (LVEF) ≥50% AND one or more of the following:<br>1) New relative decline in Global Longitudinal Strain (GLS) >15% from baseline<br>2) New rise in cardiac biomarkers
- **Grade 2:** LVEF 40 - 49% AND one or more of the following:<br>1) LVEF reduction by ≥10%<br>2) New relative decline in GLS >15% from baseline<br>3) New rise in cardiac biomarkers
- **Grade 3:** New LVEF reduction to <40%
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an ASYMPTOMATIC abnormality of cardiac function.
- **Navigational Note:** If symptomatic, consider Cardiac disorders: Heart failure.
- **CTCAE v6.0 Change:** Addition: Term

### Mitral valve disease

MedDRA 28.0 LLT code: 10061532

- **Grade 1:** Asymptomatic valvular thickening with or without mild valvular regurgitation or stenosis by imaging
- **Grade 2:** Asymptomatic; moderate regurgitation or stenosis by imaging
- **Grade 3:** Symptomatic; severe regurgitation or stenosis by imaging; symptoms controlled with medical intervention
- **Grade 4:** Life-threatening consequences; urgent intervention indicated (e.g., valve replacement, valvuloplasty)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a defect in mitral valve function or structure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Mobitz (type) II atrioventricular block

MedDRA 28.0 LLT code: 10027786

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Symptomatic and incompletely controlled medically, or require a device (e.g., pacemaker)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with relatively constant PR interval prior to the block of an atrial impulse. This is the result of intermittent failure of atrial electrical impulse conduction through the atrioventricular (AV) node to the ventricles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Mobitz type I

MedDRA 28.0 LLT code: 10027787

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Symptomatic and incompletely controlled medically, or controlled with device (e.g., pacemaker)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with a progressively lengthening PR interval prior to the blocking of an atrial impulse. This is the result of intermittent failure of atrial electrical impulse conduction through the atrioventricular (AV) node to the ventricles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Myocardial infarction

MedDRA 28.0 LLT code: 10028596

- **Grade 1:** -
- **Grade 2:** Asymptomatic; imaging or ECG features consistent with myocardial infarction which may be of uncertain age
- **Grade 3:** Hemodynamically stable AND detection of a rise and/or fall of Cardiac troponin values with at least 1 value above the 99th percentile URL AND at least 1 of the following:<br>1) Symptoms of myocardial ischemia;<br>2) New ischemic ECG changes;<br>3) Development of pathological Q waves;<br>4) Imaging evidence of new loss of viable myocardium or new regional wall motion abnormality in a pattern consistent with an ischemic etiology;<br>5) Identification of a coronary thrombus by angiography
- **Grade 4:** Life-threatening consequences; hemodynamically UNstable AND detection of a rise and/or fall of Cardiac troponin values with at least 1 value above the 99th percentile URL AND at least 1 of the following:<br>1) Symptoms of myocardial ischemia;<br>2) New ischemic ECG changes;<br>3) Development of pathological Q waves;<br>4) Imaging evidence of new loss of viable myocardium or new regional wall motion abnormality in a pattern consistent with an ischemic etiology;<br>5) Identification of a coronary thrombus by angiography
- **Grade 5:** Death
- **Definition:** A disorder characterized by gross necrosis of the myocardium; this is due to an interruption of blood supply to the area.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, 4

### Myocarditis

MedDRA 28.0 LLT code: 10028606

- **Grade 1:** Asymptomatic with Lab or ECG findings only
- **Grade 2:** Symptoms with moderate activity or exertion
- **Grade 3:** Severe with symptoms at rest or with minimal activity or exertion; intervention indicated; new onset of symptoms
- **Grade 4:** Life-threatening consequences; urgent intervention indicated (e.g., continuous IV therapy or mechanical hemodynamic support); hemodynamically unstable requiring non-invasive or invasive ventilation; complete or high grade AV block; significant ventricular arrhythmia
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the muscle tissue of the heart.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Grade 1; Clarification: Grade 4

### Palpitations

MedDRA 28.0 LLT code: 10033557

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an unpleasant sensation of irregular and/or forceful beating of the heart.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Paroxysmal atrial tachycardia

MedDRA 28.0 LLT code: 10034040

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Non-urgent medical intervention indicated
- **Grade 3:** Symptomatic, urgent intervention indicated; ablation
- **Grade 4:** Life-threatening consequences; incompletely controlled medically; cardioversion indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with abrupt onset and sudden termination of atrial contractions with a rate of 150-250 beats per minute. The rhythm disturbance originates in the atria.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pericardial effusion

MedDRA 28.0 LLT code: 10034474

- **Grade 1:** -
- **Grade 2:** Asymptomatic effusion size small to moderate
- **Grade 3:** Effusion with physiologic consequences
- **Grade 4:** Life-threatening consequences; hospitalization
- **Grade 5:** Death
- **Definition:** A disorder characterized by fluid collection within the pericardial sac, usually due to inflammation.
- **Navigational Note:** Consider Cardiac disorders: Pericardial tamponade, Pericarditis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 4

### Pericardial tamponade

MedDRA 28.0 LLT code: 10053565

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an increase in intrapericardial pressure due to the collection of blood or fluid in the pericardium.
- **Navigational Note:** Consider Cardiac disorders: Pericarditis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Pericarditis

MedDRA 28.0 LLT code: 10034484

- **Grade 1:** Asymptomatic, ECG or physical findings (e.g., rub) consistent with pericarditis
- **Grade 2:** Symptomatic pericarditis (e.g., chest pain)
- **Grade 3:** Pericarditis with physiologic consequences (e.g., pericardial constriction)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by irritation to the layers of the pericardium (the protective sac around the heart).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pulmonary valve disease

MedDRA 28.0 LLT code: 10061541

- **Grade 1:** Asymptomatic valvular thickening with or without mild valvular regurgitation or stenosis by imaging
- **Grade 2:** Asymptomatic; moderate regurgitation or stenosis by imaging
- **Grade 3:** Symptomatic; severe regurgitation or stenosis by imaging; symptoms controlled with medical intervention
- **Grade 4:** Life-threatening consequences; urgent intervention indicated (e.g., valve replacement, valvuloplasty)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a defect in pulmonary valve function or structure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Sick sinus syndrome

MedDRA 28.0 LLT code: 10040639

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Symptomatic, intervention not indicated; change in medication initiated
- **Grade 3:** Symptomatic, intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with alternating periods of bradycardia and atrial tachycardia accompanied by syncope, fatigue and dizziness.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Sinus bradycardia

MedDRA 28.0 LLT code: 10040741

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Symptomatic, intervention not indicated; change in medication initiated
- **Grade 3:** Symptomatic, intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with a heart rate less than 60 beats per minute that originates in the sinus node.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Sinus tachycardia

MedDRA 28.0 LLT code: 10040752

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Symptomatic; non-urgent medical intervention indicated
- **Grade 3:** Urgent medical intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a dysrhythmia with a heart rate greater than 100 beats per minute that originates in the sinus node.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Supraventricular tachycardia

MedDRA 28.0 LLT code: 10042604

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Non-urgent medical intervention indicated
- **Grade 3:** Symptomatic, urgent intervention indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with a heart rate greater than 100 beats per minute that originates above the ventricles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Tricuspid valve disease

MedDRA 28.0 LLT code: 10061389

- **Grade 1:** Asymptomatic valvular thickening with or without mild valvular regurgitation or stenosis
- **Grade 2:** Asymptomatic; moderate regurgitation or stenosis by imaging
- **Grade 3:** Symptomatic; severe regurgitation or stenosis; symptoms controlled with medical intervention
- **Grade 4:** Life-threatening consequences; urgent intervention indicated (e.g., valve replacement, valvuloplasty)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a defect in tricuspid valve function or structure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ventricular arrhythmia

MedDRA 28.0 LLT code: 10047281

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Non-urgent medical intervention indicated
- **Grade 3:** Urgent intervention indicated
- **Grade 4:** Life-threatening consequences; hemodynamic compromise
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia that originates in the ventricles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ventricular fibrillation

MedDRA 28.0 LLT code: 10047290

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; hemodynamic compromise
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia without discernible QRS complexes due to rapid repetitive excitation of myocardial fibers without coordinated contraction of the ventricles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ventricular tachycardia

MedDRA 28.0 LLT code: 10047302

- **Grade 1:** -
- **Grade 2:** Non-urgent medical intervention indicated
- **Grade 3:** Symptomatic, urgent intervention indicated
- **Grade 4:** Life-threatening consequences; hemodynamic compromise
- **Grade 5:** Death
- **Definition:** A disorder characterized by a dysrhythmia with a heart rate greater than 100 beats per minute that originates distal to the bundle of His.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Congenital, familial and genetic disorders

### Congenital, familial and genetic disorders - Other, specify

MedDRA 28.0 LLT code: 10010331

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

## Ear and labyrinth disorders

### Ear and labyrinth disorders - Other, specify

MedDRA 28.0 LLT code: 10013993

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Ear pain

MedDRA 28.0 LLT code: 10014020

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the ear.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### External ear pain

MedDRA 28.0 LLT code: 10065785

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the external ear region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Hearing impaired

MedDRA 28.0 LLT code: 10019245

- **Grade 1:** Adult: Subjective change in hearing in the absence of documented hearing loss; threshold shift of 15 - 25 dB averaged at 2 contiguous test frequencies in at least one ear (on a 1, 2, 4, 3, 6, and 8 kHz audiogram);<br>Pediatric (on a 1, 2, 3, 4, 6, and 8 kHz audiogram): Threshold shift >20 dB hearing loss (HL) (i.e., 25 dB HL or greater); sensorineural hearing loss (SNHL) above 4 kHz (i.e., 6 or 8 kHz) in at least one ear
- **Grade 2:** Adult: Hearing loss not requiring hearing aid; intervention not indicated; limiting instrumental ADL; threshold shift of >25 dB averaged at 2 contiguous test frequencies in at least one ear (on a 1, 2, 3, 4, 6, and 8 kHz audiogram);<br>Pediatric (on a 1, 2, 3, 4, 6, and 8 kHz audiogram): Threshold shift >20 dB at 4 kHz in at least one ear; mild/moderate impact on age-appropriate normal daily activity
- **Grade 3:** Adult: Hearing loss requiring hearing aid; intervention indicated; limiting self-care ADL; threshold shift of >25 dB averaged at 3 contiguous test frequencies in at least one ear(on a 1, 2, 3, 4, 6, and 8 kHz audiogram);<br>Pediatric (on a 1, 2, 3, 4, 6, and 8 kHz audiogram): Hearing loss sufficient to indicate therapeutic intervention, including hearing aids; threshold shift >20 dB at 2 to <4 kHz in at least one ear; severe impact on age-appropriate normal daily activity
- **Grade 4:** Adult: Nonservicable hearing; decrease in hearing to profound bilateral loss (absolute threshold >80 dB HL at 2 kHz and above);<br>Pediatric: Audiologic indication for cochlear implant; >40 dB HL (i.e., 45 dB HL or more); SNHL at 2 kHz and above
- **Grade 5:** -
- **Definition:** A disorder characterized by partial or complete loss of the ability to detect or understand sounds resulting from damage to ear structures.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4

### Middle ear inflammation

MedDRA 28.0 LLT code: 10065838

- **Grade 1:** Serous otitis
- **Grade 2:** Serous otitis, medical intervention indicated
- **Grade 3:** Mastoiditis; necrosis of canal soft tissue or bone
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation (physiologic response to irritation), swelling and redness to the middle ear.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Tinnitus

MedDRA 28.0 LLT code: 10043882

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by noise in the ears, such as ringing, buzzing, roaring or clicking.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Vertigo

MedDRA 28.0 LLT code: 10047340

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation as if the external world were revolving around the patient (objective vertigo) or as if he himself were revolving in space (subjective vertigo).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Vestibular disorder

MedDRA 28.0 LLT code: 10047386

- **Grade 1:** -
- **Grade 2:** Symptomatic; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dizziness, imbalance, nausea, and vision problems.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

## Endocrine disorders

### Adrenal insufficiency

MedDRA 28.0 LLT code: 10001367

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe symptoms; hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the adrenal cortex not producing enough of the hormone cortisol and in some cases, the hormone aldosterone. It may be due to a disorder of the adrenal cortex as in Addison's disease or primary adrenal insufficiency.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cushingoid

MedDRA 28.0 LLT code: 10011655

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe symptoms, medical intervention or hospitalization indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by signs and symptoms that resemble Cushing's disease or syndrome: buffalo hump obesity, striations, adiposity, hypertension, diabetes, and osteoporosis, usually due to exogenous corticosteroids.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Delayed puberty

MedDRA 28.0 LLT code: 10012205

- **Grade 1:** -
- **Grade 2:** No breast development by age 13 yrs for females; testes volume of <3 cc or no Tanner Stage 2 development by age 14.5 yrs for males
- **Grade 3:** No breast development by age 14 yrs for females; no increase in testes volume or no Tanner Stage 2 by age 16 yrs for males; hormone replacement indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by unusually late sexual maturity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Endocrine disorders - Other, specify

MedDRA 28.0 LLT code: 10014698

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hyperparathyroidism

MedDRA 28.0 LLT code: 10020705

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an increase in production of parathyroid hormone by the parathyroid glands. This results in hypercalcemia (abnormally high levels of calcium in the blood).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hyperthyroidism

MedDRA 28.0 LLT code: 10020850

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; thyroid suppression therapy indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by excessive levels of thyroid hormone in the body. Common causes include an overactive thyroid gland or thyroid hormone overdose.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hypogonadism

MedDRA 28.0 LLT code: 10058359

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in production of sex hormones from the gonads.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Hypoparathyroidism

MedDRA 28.0 LLT code: 10021041

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe symptoms; medical intervention or hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in production of parathyroid hormone by the parathyroid glands.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypophysitis

MedDRA 28.0 LLT code: 10062767

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation and cellular infiltration of the pituitary gland.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hypopituitarism

MedDRA 28.0 LLT code: 10021067

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in production of hormones from the pituitary gland.
- **Navigational Note:** Consider Endocrine disorders: Hypophysitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Hypothyroidism

MedDRA 28.0 LLT code: 10021114

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; thyroid replacement initiated; increase in current thyroid replacement therapy; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in production of thyroid hormone by the thyroid gland.
- **Navigational Note:** Consider Endocrine disorders: Hypophysitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Precocious puberty

MedDRA 28.0 LLT code: 10058084

- **Grade 1:** Physical signs of puberty with no biochemical markers for females <8 years and males <9 years
- **Grade 2:** Physical signs and biochemical markers of puberty for females <8 years and males <9 years
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by unusually early development of secondary sexual features; the onset of sexual maturation begins usually before age 8 for girls and before age 9 for boys.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Testosterone deficiency

MedDRA 28.0 LLT code: 10067734

- **Grade 1:** Asymptomatic; mild symptoms with no intervention indicated
- **Grade 2:** Replacement therapy initiated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by low testosterone.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Thyroiditis

MedDRA 28.0 LLT code: 10043778

- **Grade 1:** Asymptomatic
- **Grade 2:** Medical intervention indicated
- **Grade 3:** Hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation or destruction of the thyroid gland.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Virilization

MedDRA 28.0 LLT code: 10047488

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by inappropriate masculinization occurring in a female or prepubertal male.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Eye disorders

### Blurred vision

MedDRA 28.0 LLT code: 10005886

- **Grade 1:** Intervention not indicated
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by visual perception of unclear or fuzzy images.
- **Navigational Note:** Consider: Eye disorders: Uveitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Cataract

MedDRA 28.0 LLT code: 10007739

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline); glare symptoms affecting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by partial or complete opacity of the crystalline lens of one or both eyes. This results in a decrease in visual acuity and eventual blindness if untreated.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Corneal ulcer

MedDRA 28.0 LLT code: 10048492

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Corneal ulcer without perforation in the affected eye
- **Grade 4:** Perforation in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by an area of epithelial tissue loss on the surface of the cornea. It is associated with inflammatory cells in the cornea and anterior chamber.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Decreased night vision

MedDRA 28.0 LLT code: 10011974

- **Grade 1:** Symptomatic
- **Grade 2:** Moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by an inability to see clearly in dim light.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Dry eye

MedDRA 28.0 LLT code: 10013774

- **Grade 1:** Clinical or diagnostic observations only; symptoms relieved by lubricants
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dryness of the cornea and conjunctiva.
- **Navigational Note:** If corneal ulcer is present, grade under Eye disorders: Corneal ulcer. If related to syndromes not present in CTCAE (ex. Sjogren's syndrome, etc.), report as Other, specify in the most representative SOC.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 3, Navigational Note

### Extraocular muscle paresis

MedDRA 28.0 LLT code: 10015829

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only
- **Grade 2:** Unilateral paresis without double vision
- **Grade 3:** Bilateral paresis or unilateral paresis causing double vision in peripheral gaze, but not in central gaze
- **Grade 4:** Bilateral paresis requiring head turning to see beyond central 60 degrees or double vision in central gaze
- **Grade 5:** -
- **Definition:** A disorder characterized by incomplete paralysis of an extraocular muscle.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Eye disorders - Other, specify

MedDRA 28.0 LLT code: 10015919

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated; no change in vision
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately sight-threatening; decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Sight-threatening consequences; urgent intervention indicated; best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Eye pain

MedDRA 28.0 LLT code: 10015958

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the eye.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Eyelid function disorder

MedDRA 28.0 LLT code: 10061145

- **Grade 1:** Clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; nonoperative intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Operative intervention indicated requiring hospitalization; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by impaired eyelid function.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Flashing lights

MedDRA 28.0 LLT code: 10016757

- **Grade 1:** Symptomatic
- **Grade 2:** Limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sudden or brief burst of light.
- **Navigational Note:** Consider Eye disorders: Retinal tear, Retinal detachment.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, Navigational Note

### Floaters

MedDRA 28.0 LLT code: 10016778

- **Grade 1:** Symptomatic
- **Grade 2:** Limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an individual seeing spots before their eyes. The spots are shadows of opaque cell fragments in the vitreous humor or lens.
- **Navigational Note:** Consider Eye disorders: Retinal tear, Retinal detachment.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, Navigational Note

### Glaucoma

MedDRA 28.0 LLT code: 10018304

- **Grade 1:** Less than 8 mmHg of elevated intraocular pressure (EIOP); no visual field deficit
- **Grade 2:** Topical medication indicated
- **Grade 3:** EIOP causing visual field deficits
- **Grade 4:** Visual field deficit within the central 10 degrees of the visual field in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by an increase in pressure in the eyeball due to obstruction of the aqueous humor outflow.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Keratitis

MedDRA 28.0 LLT code: 10023332

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); corneal ulcer; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Perforation; best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation to the cornea of the eye.
- **Navigational Note:** Consider Eye disorders: Corneal ulcer.
- **CTCAE v6.0 Change:** Clarification: Grade 3, Navigational Note

### Optic nerve disorder

MedDRA 28.0 LLT code: 10061322

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only
- **Grade 2:** Moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline)
- **Grade 3:** Marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by involvement of the optic nerve (second cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Papilledema

MedDRA 28.0 LLT code: 10033703

- **Grade 1:** Asymptomatic; no visual field deficit
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by swelling around the optic disc.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Periorbital edema

MedDRA 28.0 LLT code: 10054541

- **Grade 1:** Soft or non-pitting
- **Grade 2:** Indurated or pitting edema; topical intervention indicated
- **Grade 3:** Edema associated with visual disturbance; increased intraocular pressure, glaucoma or retinal hemorrhage; diuretics indicated; operative intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by swelling due to an excessive accumulation of fluid around the orbits of the face.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 3

### Photophobia

MedDRA 28.0 LLT code: 10034960

- **Grade 1:** Symptomatic
- **Grade 2:** Limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by fear and avoidance of light.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Retinal detachment

MedDRA 28.0 LLT code: 10038848

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Macular sparing rhegmatogenous detachment
- **Grade 4:** Macula-off rhegmatogenous retinal detachment
- **Grade 5:** -
- **Definition:** A disorder characterized by the separation of the inner retina layers from the underlying pigment epithelium.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Retinal tear

MedDRA 28.0 LLT code: 10038897

- **Grade 1:** No retinal detachment and treatment not indicated
- **Grade 2:** No retinal detachment and treatment indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a small laceration of the retina. Symptoms include flashes and floaters.
- **Navigational Note:** If retinal detachment is present, grade under Eye disorders: Retinal detachment.
- **CTCAE v6.0 Change:** Clarification: Definition, Navigational Note

### Retinal vascular disorder

MedDRA 28.0 LLT code: 10038901

- **Grade 1:** -
- **Grade 2:** Retinal vascular disorder without neovascularization
- **Grade 3:** Retinal vascular disorder with neovascularization
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by pathological retinal blood vessels that adversely affects vision.
- **Navigational Note:** If vitreous hemorrhage is present, report under Eye disorders: Vitreous hemorrhage.
- **CTCAE v6.0 Change:** No Change

### Retinopathy

MedDRA 28.0 LLT code: 10038923

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder involving the retina.
- **Navigational Note:** If vitreous hemorrhage is present, report under Eye disorders: Vitreous hemorrhage.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Scleral disorder

MedDRA 28.0 LLT code: 10061510

- **Grade 1:** No change in vision from baseline
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by involvement of the sclera of the eye.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Uveitis

MedDRA 28.0 LLT code: 10046851

- **Grade 1:** Anterior uveitis with trace cells
- **Grade 2:** Anterior uveitis with 1+ or 2+ cells
- **Grade 3:** Anterior uveitis with 3+ or greater cells; intermediate posterior or pan-uveitis
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation to the uvea of the eye.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vision decreased

MedDRA 28.0 LLT code: 10047516

- **Grade 1:** -
- **Grade 2:** Moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline)
- **Grade 3:** Marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in visual acuity.
- **Navigational Note:** If etiology is known, use a more specific CTCAE term. Consider: Eye disorders: Uveitis
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Vitreous hemorrhage

MedDRA 28.0 LLT code: 10047656

- **Grade 1:** Intervention not indicated
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); vitrectomy indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by bleeding into the vitreous humor.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Watering eyes

MedDRA 28.0 LLT code: 10047848

- **Grade 1:** Intervention not indicated
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline)
- **Grade 3:** Marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive tearing in the eyes; it can be caused by overproduction of tears or impaired drainage of the tear duct.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Gastrointestinal disorders

### Abdominal distension

MedDRA 28.0 LLT code: 10000060

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe discomfort; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by swelling of the abdomen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Abdominal pain

MedDRA 28.0 LLT code: 10000081

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the abdominal region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Anal fissure

MedDRA 28.0 LLT code: 10002153

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a tear in the lining of the anus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anal fistula

MedDRA 28.0 LLT code: 10002156

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the opening in the anal canal to the perianal skin.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anal mucositis

MedDRA 28.0 LLT code: 10065721

- **Grade 1:** Asymptomatic or mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by ulceration or inflammation of the mucous membrane of the anus.
- **Navigational Note:** Report Grade 4 and 5 as Gastrointestinal disorders: Anal ulcer.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Anal necrosis

MedDRA 28.0 LLT code: 10065722

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** TPN or hospitalization indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the anal region.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anal pain

MedDRA 28.0 LLT code: 10002167

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the anal region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Anal stenosis

MedDRA 28.0 LLT code: 10002176

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Symptomatic and severely altered GI function; non-emergent operative intervention indicated; TPN or hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the anal canal.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anal ulcer

MedDRA 28.0 LLT code: 10002180

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the anal canal.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ascites

MedDRA 28.0 LLT code: 10003445

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention or paracentesis indicated
- **Grade 3:** Severe symptoms; catheter placement indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by accumulation of serous or hemorrhagic fluid in the peritoneal cavity.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Belching

MedDRA 28.0 LLT code: 10004222

- **Grade 1:** Increase from baseline
- **Grade 2:** Intervention initiated (including over the counter medications)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** To expel gas noisily from the mouth.
- **Navigational Note:** Synonym: Burping
- **CTCAE v6.0 Change:** No Change

### Bloating

MedDRA 28.0 LLT code: 10005265

- **Grade 1:** No change in bowel function or oral intake
- **Grade 2:** Symptomatic, decreased oral intake; change in bowel function
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by subject-reported feeling of uncomfortable fullness of the abdomen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cecal hemorrhage

MedDRA 28.0 LLT code: 10065747

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the cecum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Cheilitis

MedDRA 28.0 LLT code: 10008417

- **Grade 1:** Clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation of the lip.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Chylous ascites

MedDRA 28.0 LLT code: 10009167

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated (e.g., fat-restricted diet); paracentesis or tube drainage indicated
- **Grade 3:** Severe symptoms; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by accumulation of milky fluid in the peritoneal cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Colitis

MedDRA 28.0 LLT code: 10009887

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Abdominal pain; mucus or blood in stool
- **Grade 3:** Severe abdominal pain; peritoneal signs
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the colon.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Colonic fistula

MedDRA 28.0 LLT code: 10009995

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the large intestine and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Colonic obstruction

MedDRA 28.0 LLT code: 10010000

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Hospitalization indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the intestinal contents in the colon.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Colonic perforation

MedDRA 28.0 LLT code: 10010001

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the colonic wall.
- **Navigational Note:** Consider Gastrointestinal disorders: Colitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Colonic stenosis

MedDRA 28.0 LLT code: 10010004

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the colon.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Colonic ulcer

MedDRA 28.0 LLT code: 10010006

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the colon.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Constipation

MedDRA 28.0 LLT code: 10010774

- **Grade 1:** Occasional or intermittent symptoms; occasional use of stool softeners, laxatives, dietary modification, or enema
- **Grade 2:** Persistent symptoms with regular use of laxatives or enemas; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Obstipation with manual evacuation indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by irregular and infrequent or difficult evacuation of the bowels.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Dental caries

MedDRA 28.0 LLT code: 10012318

- **Grade 1:** One or more dental caries, not involving the root
- **Grade 2:** Dental caries involving the root
- **Grade 3:** Dental caries resulting in pulpitis or periapical abscess or resulting in tooth loss
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the decay of a tooth, in which it becomes softened, discolored and/or porous.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Diarrhea

MedDRA 28.0 LLT code: 10012727

- **Grade 1:** Change in consistency or frequency
- **Grade 2:** Increase of 4 - 6 stools per day over baseline; moderate increase in ostomy output compared to baseline; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric); change in consistency or frequency AND limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Increase of >=7 stools per day over baseline; hospitalization indicated; severe increase in ostomy output compared to baseline; requires IV intervention; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an increase in frequency and/or loose or watery bowel movements.
- **Navigational Note:** Consider Gastrointestinal disorders: Colitis, Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 1, 2, 3

### Dry mouth

MedDRA 28.0 LLT code: 10013781

- **Grade 1:** Symptomatic (e.g., dry or thick saliva) without significant dietary alteration; unstimulated saliva flow >0.2 ml/min
- **Grade 2:** Moderate symptoms; oral intake alterations (e.g., copious water, other lubricants, diet limited to purees and/or soft, moist foods); unstimulated saliva 0.1 to 0.2 ml/min
- **Grade 3:** Inability to adequately aliment orally; tube feeding or TPN indicated; unstimulated saliva <0.1 ml/min
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by reduced salivary flow in the oral cavity.
- **Navigational Note:** If related to syndromes not present in CTCAE (ex. Sjogren's syndrome, etc.), report as Other, specify in the most representative SOC.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Duodenal fistula

MedDRA 28.0 LLT code: 10013828

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the duodenum and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Duodenal hemorrhage

MedDRA 28.0 LLT code: 10055242

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the duodenum.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 3

### Duodenal obstruction

MedDRA 28.0 LLT code: 10013830

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Hospitalization indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of stomach contents through the duodenum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Duodenal perforation

MedDRA 28.0 LLT code: 10013832

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the duodenal wall.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Duodenal stenosis

MedDRA 28.0 LLT code: 10050094

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the duodenum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Duodenal ulcer

MedDRA 28.0 LLT code: 10013836

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the duodenal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Dyspepsia

MedDRA 28.0 LLT code: 10013946

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe symptoms; operative intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an uncomfortable, often painful feeling in the stomach, resulting from impaired digestion. Symptoms include burning stomach, bloating, heartburn, nausea and vomiting.
- **Navigational Note:** Consider Gastrointestinal disorders: Gastritis, Gastroparesis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Dysphagia

MedDRA 28.0 LLT code: 10013950

- **Grade 1:** Symptomatic, able to eat regular diet
- **Grade 2:** Symptomatic and altered eating/swallowing
- **Grade 3:** Severely altered eating/swallowing; tube feeding, TPN, or hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by difficulty in swallowing.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Enterocolitis

MedDRA 28.0 LLT code: 10014893

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Abdominal pain; mucus or blood in stool
- **Grade 3:** Severe or persistent abdominal pain; fever; ileus; peritoneal signs
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the small and large intestines.
- **Navigational Note:** If reporting a known abnormality of the colon, use Gastrointestinal disorders: Colitis. If reporting a documented infection, use Infections and infestations: Enterocolitis infectious.
- **CTCAE v6.0 Change:** No Change

### Enterovesical fistula

MedDRA 28.0 LLT code: 10062570

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the urinary bladder and the intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Esophageal fistula

MedDRA 28.0 LLT code: 10065851

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the esophagus and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Esophageal hemorrhage

MedDRA 28.0 LLT code: 10015384

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the esophagus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Esophageal necrosis

MedDRA 28.0 LLT code: 10065727

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Inability to aliment adequately by GI tract; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the esophageal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Esophageal obstruction

MedDRA 28.0 LLT code: 10015387

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Hospitalization indicated; invasive intervention indicated; limiting self care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the contents in the esophagus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Esophageal pain

MedDRA 28.0 LLT code: 10015388

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the esophageal region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Esophageal perforation

MedDRA 28.0 LLT code: 10055472

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the wall of the esophagus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Esophageal stenosis

MedDRA 28.0 LLT code: 10015448

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the esophagus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Esophageal ulcer

MedDRA 28.0 LLT code: 10015451

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the esophageal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Esophageal varices hemorrhage

MedDRA 28.0 LLT code: 10015453

- **Grade 1:** -
- **Grade 2:** Self-limited; intervention not indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from esophageal varices.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Esophagitis

MedDRA 28.0 LLT code: 10015461

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered eating/swallowing; oral supplements indicated
- **Grade 3:** Severely altered eating/swallowing; tube feeding, TPN, or hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the esophageal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Fecal incontinence

MedDRA 28.0 LLT code: 10016296

- **Grade 1:** Occasional use of pads required
- **Grade 2:** Daily use of pads required
- **Grade 3:** Severe symptoms; elective operative intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by inability to control the escape of stool from the rectum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Flatulence

MedDRA 28.0 LLT code: 10016766

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate; persistent; psychosocial sequelae
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a discharge of excessive gas from the lower GI tract.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastric fistula

MedDRA 28.0 LLT code: 10065713

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the stomach and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastric hemorrhage

MedDRA 28.0 LLT code: 10017789

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the gastric wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Gastric necrosis

MedDRA 28.0 LLT code: 10051886

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Inability to aliment adequately by GI tract; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the gastric wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastric perforation

MedDRA 28.0 LLT code: 10017815

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the stomach wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastric stenosis

MedDRA 28.0 LLT code: 10061970

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the stomach.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastric ulcer

MedDRA 28.0 LLT code: 10017822

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the stomach.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Gastritis

MedDRA 28.0 LLT code: 10017853

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; medical intervention indicated
- **Grade 3:** Severely altered eating or gastric function; TPN or hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the stomach.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastroesophageal reflux disease

MedDRA 28.0 LLT code: 10066874

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe symptoms; operative intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by reflux of the gastric and/or duodenal contents into the distal esophagus. It is chronic in nature and usually caused by incompetence of the lower esophageal sphincter, and may result in injury to the esophageal mucosal. Symptoms include heartburn and acid indigestion.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastrointestinal disorders - Other, specify

MedDRA 28.0 LLT code: 10017947

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Gastrointestinal fistula

MedDRA 28.0 LLT code: 10017877

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between any part of the gastrointestinal system and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastrointestinal pain

MedDRA 28.0 LLT code: 10017999

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the gastrointestinal region.
- **Navigational Note:** Consider Gastrointestinal disorders: Colitis, Enterocolitis. Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Gastroparesis

MedDRA 28.0 LLT code: 10018043

- **Grade 1:** Mild nausea, early satiety and bloating, able to maintain caloric intake on regular diet
- **Grade 2:** Moderate symptoms; able to maintain nutrition with dietary and lifestyle modifications; may need pharmacologic intervention
- **Grade 3:** Weight loss >=20% from baseline; tube feeding or TPN indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by an incomplete paralysis of the muscles of the stomach wall resulting in delayed emptying of the gastric contents into the small intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gingival pain

MedDRA 28.0 LLT code: 10018286

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain interfering with oral intake
- **Grade 3:** Severe pain; inability to aliment orally
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the gingival region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Hematemesis

MedDRA 28.0 LLT code: 10019418

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the vomiting of blood.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Term

### Hematochezia

MedDRA 28.0 LLT code: 10060544

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the passage of fresh blood per anus, usually in or with stools.
- **Navigational Note:** Consider Gastrointestinal disorders: Colitis, Enterocolitis, Proctitis; Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Term

### Hemorrhoidal hemorrhage

MedDRA 28.0 LLT code: 10060640

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the hemorrhoids.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Hemorrhoids

MedDRA 28.0 LLT code: 10019611

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; banding or medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the presence of dilated veins in the rectum and surrounding area.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ileal fistula

MedDRA 28.0 LLT code: 10065728

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the ileum and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ileal hemorrhage

MedDRA 28.0 LLT code: 10055287

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the ileal wall.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 3

### Ileal obstruction

MedDRA 28.0 LLT code: 10065730

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; naso-gastric tube indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Hospitalization indicated; invasive intervention indicated; long intestinal tube indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the intestinal contents in the ileum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Ileal perforation

MedDRA 28.0 LLT code: 10021305

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the ileal wall.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Ileal stenosis

MedDRA 28.0 LLT code: 10021307

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the ileum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ileal ulcer

MedDRA 28.0 LLT code: 10021309

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the ileum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ileus

MedDRA 28.0 LLT code: 10021328

- **Grade 1:** Asymptomatic and radiologic observations only
- **Grade 2:** Symptomatic; altered GI function; bowel rest indicated
- **Grade 3:** Severely altered GI function; TPN indicated; tube placement indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by failure of the ileum to transport intestinal contents.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Intra-abdominal hemorrhage

MedDRA 28.0 LLT code: 10055291

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding in the abdominal cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Jejunal fistula

MedDRA 28.0 LLT code: 10065719

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the jejunum and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Jejunal hemorrhage

MedDRA 28.0 LLT code: 10055300

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the jejunal wall.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 3

### Jejunal obstruction

MedDRA 28.0 LLT code: 10065732

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Hospitalization indicated; invasive intervention indicated; limiting self care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the intestinal contents in the jejunum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Jejunal perforation

MedDRA 28.0 LLT code: 10023174

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the jejunal wall.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Jejunal stenosis

MedDRA 28.0 LLT code: 10023176

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the jejunum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Jejunal ulcer

MedDRA 28.0 LLT code: 10023177

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the jejunum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Lip pain

MedDRA 28.0 LLT code: 10024561

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort of the lip.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Malabsorption

MedDRA 28.0 LLT code: 10025476

- **Grade 1:** -
- **Grade 2:** Altered diet; oral intervention indicated
- **Grade 3:** Inability to aliment adequately; TPN indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inadequate absorption of nutrients in the small intestine. Symptoms include abdominal marked discomfort, bloating and diarrhea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Melena

MedDRA 28.0 LLT code: 10027162

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by black, tarry stools.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Term

### Mucositis oral

MedDRA 28.0 LLT code: 10028130

- **Grade 1:** Asymptomatic or mild symptoms; intervention not indicated
- **Grade 2:** Moderate pain or ulcer that does not interfere with oral intake; modified diet indicated
- **Grade 3:** Severe pain; interfering with oral intake
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by ulceration or inflammation of the oral mucosal.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Nausea

MedDRA 28.0 LLT code: 10028813

- **Grade 1:** Loss of appetite without alteration in eating habits
- **Grade 2:** Oral intake decreased without significant weight loss, dehydration or malnutrition; IV intervention indicated
- **Grade 3:** Inadequate oral caloric or fluid intake; tube feeding, TPN, or hospitalization indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a queasy sensation and/or the urge to vomit.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis, Gastritis and/or Endocrine disorders: Adrenal insufficiency, Hypophysitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2

### Obstruction gastric

MedDRA 28.0 LLT code: 10029957

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Hospitalization indicated; invasive intervention indicated; limiting self care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the contents in the stomach.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Oral cavity fistula

MedDRA 28.0 LLT code: 10065720

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the oral cavity and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Oral dysesthesia

MedDRA 28.0 LLT code: 10054520

- **Grade 1:** Mild discomfort; not interfering with oral intake
- **Grade 2:** Moderate pain; interfering with oral intake
- **Grade 3:** Disabling pain; tube feeding or TPN indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a burning or tingling sensation on the lips, tongue or entire mouth.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Oral hemorrhage

MedDRA 28.0 LLT code: 10030980

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the mouth.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Oral pain

MedDRA 28.0 LLT code: 10031009

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the mouth, tongue or lips.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Pancreatic duct stenosis

MedDRA 28.0 LLT code: 10065703

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the pancreatic duct.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pancreatic fistula

MedDRA 28.0 LLT code: 10049192

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the pancreas and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pancreatic hemorrhage

MedDRA 28.0 LLT code: 10033626

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the pancreas.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Pancreatic insufficiency

MedDRA 28.0 LLT code: 10033628

- **Grade 1:** Asymptomatic and pancreatic enzymes <LLN
- **Grade 2:** Increase in stool frequency, bulk, or odor; steatorrhea
- **Grade 3:** Sequelae of absorption deficiency
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by impaired exocrine pancreatic function usually associated with decreased pancreatic exocrine enzymes production.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Pancreatic necrosis

MedDRA 28.0 LLT code: 10058096

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Tube feeding or TPN indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the pancreas.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pancreatitis

MedDRA 28.0 LLT code: 10033645

- **Grade 1:** -
- **Grade 2:** Radiologic findings only
- **Grade 3:** Severe pain; vomiting; medical intervention indicated (e.g., analgesia, nutritional support)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the pancreas with no documented pancreas infection.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Periodontal disease

MedDRA 28.0 LLT code: 10034536

- **Grade 1:** Gingival recession or gingivitis; limited bleeding on probing; mild local bone loss
- **Grade 2:** Moderate gingival recession or gingivitis; multiple sites of bleeding on probing; moderate bone loss
- **Grade 3:** Spontaneous bleeding; severe bone loss with or without tooth loss; osteonecrosis of maxilla or mandible
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder in the gingival tissue around the teeth.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Peritoneal necrosis

MedDRA 28.0 LLT code: 10065704

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Tube feeding or TPN indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the peritoneum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Proctitis

MedDRA 28.0 LLT code: 10036774

- **Grade 1:** Rectal discomfort, intervention not indicated
- **Grade 2:** Symptomatic (e.g., rectal discomfort, passing blood or mucus); fecal urgency or stool incontinence; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the rectum.
- **Navigational Note:** Consider Gastrointestinal disorders: Fecal incontinence.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Rectal fissure

MedDRA 28.0 LLT code: 10064993

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a tear in the lining of the rectum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rectal fistula

MedDRA 28.0 LLT code: 10038062

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the rectum and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rectal mucositis

MedDRA 28.0 LLT code: 10063190

- **Grade 1:** Asymptomatic or mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by ulceration or inflammation of the mucous membrane of the rectum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Rectal necrosis

MedDRA 28.0 LLT code: 10065709

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Tube feeding or TPN indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the rectal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rectal obstruction

MedDRA 28.0 LLT code: 10065707

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Hospitalization indicated; invasive intervention indicated; limiting self care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the intestinal contents in the rectum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Rectal pain

MedDRA 28.0 LLT code: 10038072

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the rectal region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Rectal perforation

MedDRA 28.0 LLT code: 10038073

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the rectal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rectal stenosis

MedDRA 28.0 LLT code: 10038079

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Severely altered GI function; tube feeding or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the rectum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rectal ulcer

MedDRA 28.0 LLT code: 10038080

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function (e.g., altered dietary habits, vomiting, diarrhea)
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the rectum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Retroperitoneal hemorrhage

MedDRA 28.0 LLT code: 10038981

- **Grade 1:** -
- **Grade 2:** Self-limited; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the retroperitoneal area.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Salivary duct inflammation

MedDRA 28.0 LLT code: 10056681

- **Grade 1:** Slightly thickened saliva; slightly altered taste (e.g., metallic)
- **Grade 2:** Thick, ropy, sticky saliva; markedly altered taste; alteration in diet indicated; secretion-induced symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Acute salivary gland necrosis; severe secretion-induced symptoms (e.g., thick saliva/oral secretions or gagging); tube feeding or TPN indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the salivary duct.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Salivary gland fistula

MedDRA 28.0 LLT code: 10039411

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between a salivary gland and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Small intestinal mucositis

MedDRA 28.0 LLT code: 10065710

- **Grade 1:** Asymptomatic or mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; interfering with oral intake; tube feeding, TPN or hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by ulceration or inflammation of the mucous membrane of the small intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Small intestinal obstruction

MedDRA 28.0 LLT code: 10041101

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Hospitalization indicated; invasive intervention indicated; limiting self care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the intestinal contents of the small intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Small intestinal perforation

MedDRA 28.0 LLT code: 10041103

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the small intestine wall.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Small intestinal stenosis

MedDRA 28.0 LLT code: 10062263

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function
- **Grade 3:** Symptomatic and severely altered GI function; tube feeding, TPN or hospitalization indicated; non-emergent operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the small intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Small intestine ulcer

MedDRA 28.0 LLT code: 10041133

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severely altered GI function; TPN indicated; elective invasive intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the mucosal surface of the small intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Stomach pain

MedDRA 28.0 LLT code: 10042112

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the stomach.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Tooth development disorder

MedDRA 28.0 LLT code: 10044030

- **Grade 1:** Asymptomatic; hypoplasia of tooth or enamel
- **Grade 2:** Impairment correctable with oral surgery
- **Grade 3:** Maldevelopment with impairment not surgically correctable; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a pathological process of the teeth occurring during tooth development.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Tooth discoloration

MedDRA 28.0 LLT code: 10044031

- **Grade 1:** Surface stains
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in tooth hue or tint.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Toothache

MedDRA 28.0 LLT code: 10044055

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the tooth.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Typhlitis

MedDRA 28.0 LLT code: 10045271

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Symptomatic (e.g., abdominal pain, fever, change in bowel habits with ileus); peritoneal signs
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by necrotizing enterocolitis in neutropenic patients. Also referred to as neutropenic enterocolitis, ileocecal syndrome, or cecitis.
- **Navigational Note:** Includes Clostridioides difficile (c. diff, c. difficile). Also report Investigations: Neutrophil count decreased; Also consider Infections and infestations: Cecal infection.
- **CTCAE v6.0 Change:** Clarification: Definition, Navigational Note

### Upper gastrointestinal hemorrhage

MedDRA 28.0 LLT code: 10055356

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the upper gastrointestinal tract (oral cavity, pharynx, esophagus, and stomach).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Visceral arterial ischemia

MedDRA 28.0 LLT code: 10054692

- **Grade 1:** -
- **Grade 2:** Brief (<24 hrs) episode of ischemia managed medically and without permanent deficit
- **Grade 3:** Prolonged (>=24 hrs) or recurring symptoms and/or invasive intervention indicated
- **Grade 4:** Life-threatening consequences; evidence of end organ damage; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in blood supply due to narrowing or blockage of a visceral (mesenteric) artery.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vomiting

MedDRA 28.0 LLT code: 10047700

- **Grade 1:** Intervention not indicated
- **Grade 2:** Initiation of outpatient IV hydration; medical intervention indicated
- **Grade 3:** Initiation of tube feeding, or TPN; hospitalization indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by the reflexive act of ejecting the contents of the stomach through the mouth.
- **Navigational Note:** Consider Gastrointestinal disorders: Enterocolitis, Gastritis and/or Endocrine disorders: Adrenal insufficiency, Hypophysitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

## General disorders and administration site conditions

### Chills

MedDRA 28.0 LLT code: 10008531

- **Grade 1:** Mild sensation of cold; shivering; chattering of teeth
- **Grade 2:** Moderate tremor of the entire body; narcotics indicated
- **Grade 3:** Severe or prolonged, not responsive to narcotics
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of cold that often marks a physiologic response to sweating after a fever.
- **Navigational Note:** Consider Injury, poisoning and procedural complications: Infusion related reaction.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Death neonatal

MedDRA 28.0 LLT code: 10011912

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Neonatal loss of life
- **Grade 5:** -
- **Definition:** Newborn death occurring during the first 28 days after birth.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Death NOS

MedDRA 28.0 LLT code: 10011914

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** Death
- **Definition:** Death that cannot be attributed to a CTCAE term associated with Grade 5.
- **Navigational Note:** If death is due to an AE (ex., Cardiac disorders: Cardiac arrest), report as a Grade 5 event under that AE.
- **CTCAE v6.0 Change:** No Change

### Disease progression

MedDRA 28.0 LLT code: 10061818

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** Death
- **Definition:** Death due to disease progression that cannot be attributed to a CTCAE term associated with Grade 5.
- **Navigational Note:** If death is due to an AE (ex., Cardiac disorders: Cardiac arrest), report as a Grade 5 event under that AE.
- **CTCAE v6.0 Change:** No Change

### Edema face

MedDRA 28.0 LLT code: 10014222

- **Grade 1:** Localized edema
- **Grade 2:** Moderate localized edema; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe swelling; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by swelling due to excessive fluid accumulation in facial area tissues.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 1, 2, 3, Definition

### Facial pain

MedDRA 28.0 LLT code: 10016059

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the face.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Fatigue

MedDRA 28.0 LLT code: 10016256

- **Grade 1:** Fatigue relieved by rest
- **Grade 2:** Fatigue not relieved by rest; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Fatigue not relieved by rest, limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a state of generalized weakness with a pronounced inability to summon sufficient energy to accomplish daily activities.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Fever

MedDRA 28.0 LLT code: 10016558

- **Grade 1:** 38.0 - 39.0 degrees C (100.4 - 102.2 degrees F)
- **Grade 2:** >39.0 - 40.0 degrees C (102.3 - 104.0 degrees F)
- **Grade 3:** >40.0 degrees C (>104.0 degrees F) for <=24 hrs
- **Grade 4:** >40.0 degrees C (>104.0 degrees F) for >24 hrs
- **Grade 5:** Death
- **Definition:** A disorder characterized by elevation of the body's temperature above the upper limit of normal.
- **Navigational Note:** Consider Injury, poisoning and procedural complications: Infusion related reaction.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Flu like symptoms

MedDRA 28.0 LLT code: 10016791

- **Grade 1:** Mild flu-like symptoms present
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a group of symptoms similar to those observed in patients with the flu. It includes fever, chills, body aches, malaise, loss of appetite and dry cough.
- **Navigational Note:** Synonym: Flu, Influenza; Consider Injury, poisoning and procedural complications: Infusion related reaction.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Gait disturbance

MedDRA 28.0 LLT code: 10017577

- **Grade 1:** Mild change in gait (e.g., wide-based, limping or hobbling)
- **Grade 2:** Moderate change in gait (e.g., wide-based, limping or hobbling); assistive device indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by walking difficulties.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### General disorders and administration site conditions - Other, specify

MedDRA 28.0 LLT code: 10018065

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Generalized edema

MedDRA 28.0 LLT code: 10018112

- **Grade 1:** Noted on exam; 1+ pitting edema
- **Grade 2:** Oral therapy initiated; interfering with instrumental ADLs or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Interferes with self-care ADL or severe impact on age-appropriate normal daily activity (pediatric); intravenous IV therapy indicated; skin breakdown
- **Grade 4:** Life-threatening consequences
- **Grade 5:** -
- **Definition:** A disorder characterized by fluid accumulation in the tissues of the body including the skin.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Hypothermia

MedDRA 28.0 LLT code: 10021113

- **Grade 1:** -
- **Grade 2:** 35 - >32 degrees C; 95 - >89.6 degrees F
- **Grade 3:** 32 - >28 degrees C; 89.6 - >82.4 degrees F
- **Grade 4:** <=28 degrees C; 82.4 degrees F; life-threatening consequences (e.g., coma, hypotension, pulmonary edema, acidemia, ventricular fibrillation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormally low body temperature. Treatment is required when the body temperature is 35C (95F) or below.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Infusion site extravasation

MedDRA 28.0 LLT code: 10064774

- **Grade 1:** Painless edema
- **Grade 2:** Erythema with associated symptoms (e.g., edema, pain, induration, phlebitis)
- **Grade 3:** Ulceration or necrosis; severe tissue damage; operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by leakage of the infusion into the surrounding tissue. Signs and symptoms may include induration, erythema, swelling, burning sensation and marked discomfort at the infusion site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Injection site reaction

MedDRA 28.0 LLT code: 10022095

- **Grade 1:** Tenderness with or without associated symptoms (e.g., warmth, erythema, itching)
- **Grade 2:** Pain; lipodystrophy; edema; phlebitis
- **Grade 3:** Ulceration or necrosis; severe tissue damage; operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an intense adverse reaction (usually immunologic) developing at the site of an injection.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Localized edema

MedDRA 28.0 LLT code: 10062466

- **Grade 1:** Localized to dependent areas, no disability or functional impairment
- **Grade 2:** Moderate localized edema and intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe localized edema and intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by swelling due to excessive fluid accumulation at a specific anatomic site.
- **Navigational Note:** Prior to using this term consider specific edema areas and/or causes: Cardiac disorders: Heart failure; General disorders and administration site conditions: Edema face, Peripheral edema; Nervous system disorders: Edema cerebral; Respiratory, thoracic and mediastinal disorders: Laryngeal edema, Pulmonary edema; Eye disorders: Periorbital edema; Vascular disorders: Lymphedema. Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Malaise

MedDRA 28.0 LLT code: 10025482

- **Grade 1:** Uneasiness or lack of well being
- **Grade 2:** Uneasiness or lack of well being limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Uneasiness or lack of well being limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a feeling of general discomfort or uneasiness, an out-of-sorts feeling.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Multi-organ failure

MedDRA 28.0 LLT code: 10028154

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Shock with azotemia and acid-base disturbances; significant coagulation abnormalities
- **Grade 4:** Life-threatening consequences (e.g., vasopressor dependent and oliguric or anuric or ischemic colitis or lactic acidosis)
- **Grade 5:** Death
- **Definition:** A disorder characterized by progressive deterioration of the lungs, liver, kidney and clotting mechanisms.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Non-cardiac chest pain

MedDRA 28.0 LLT code: 10062501

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the chest unrelated to a heart disorder.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Pain

MedDRA 28.0 LLT code: 10033371

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the sensation of marked discomfort, distress or agony.
- **Navigational Note:** Prior to using this term consider using a specific body part pain term found throughout the CTCAE (over 40 different pain terms). Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Peripheral edema

MedDRA 28.0 LLT code: 10034570

- **Grade 1:** Swelling or obscuration of anatomic architecture on close inspection
- **Grade 2:** Readily apparent obscuration of anatomic architecture; obliteration of skin folds; readily apparent deviation from normal anatomic contour; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Gross deviation from normal anatomic contour; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by swelling due to excessive fluid accumulation in the body periphery.
- **Navigational Note:** Consider Cardiac disorders: Heart failure; Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Term

### Pneumatosis

MedDRA 28.0 LLT code: 10051986

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe symptoms; operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of gas in the bowel wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Sudden death NOS

MedDRA 28.0 LLT code: 10042435

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** Death
- **Definition:** An unexpected death that cannot be attributed to a CTCAE term associated with Grade 5.
- **Navigational Note:** If death is due to an AE (ex., Cardiac disorders: Cardiac arrest), report as a Grade 5 event under that AE.
- **CTCAE v6.0 Change:** No Change

### Vaccination site lymphadenopathy

MedDRA 28.0 LLT code: 10069480

- **Grade 1:** Local lymph node enlargement
- **Grade 2:** Localized ulceration; generalized lymph node enlargement
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by lymph node enlargement after vaccination.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Hepatobiliary disorders

### Bile duct stenosis

MedDRA 28.0 LLT code: 10051341

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; IV fluids indicated <24 hrs
- **Grade 3:** Severely altered GI function; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the lumen of the bile duct.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Biliary fistula

MedDRA 28.0 LLT code: 10004665

- **Grade 1:** -
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the bile ducts and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Biliary obstruction

MedDRA 28.0 LLT code: 10084247

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; IV fluids indicated <24 hrs
- **Grade 3:** Symptomatic and severely altered GI function; hospitalization indicated; non-emergent operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the normal flow of bile.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Budd-Chiari syndrome

MedDRA 28.0 LLT code: 10006537

- **Grade 1:** -
- **Grade 2:** Medical management indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; asterixis; mild encephalopathy
- **Grade 4:** Life-threatening consequences; moderate to severe encephalopathy; coma
- **Grade 5:** Death
- **Definition:** A disorder characterized by occlusion of the hepatic veins and typically presents with abdominal pain, ascites and hepatomegaly.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cholecystitis

MedDRA 28.0 LLT code: 10008612

- **Grade 1:** -
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation involving the gallbladder. It may be associated with the presence of gallstones.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gallbladder fistula

MedDRA 28.0 LLT code: 10017631

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the gallbladder and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gallbladder necrosis

MedDRA 28.0 LLT code: 10059446

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; urgent invasive intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the gallbladder.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gallbladder obstruction

MedDRA 28.0 LLT code: 10017636

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; altered GI function; IV fluids indicated <24 hrs
- **Grade 3:** Symptomatic and severely altered GI function; hospitalization indicated; non-emergent operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the contents of the gallbladder.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Gallbladder pain

MedDRA 28.0 LLT code: 10017638

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the gallbladder region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Gallbladder perforation

MedDRA 28.0 LLT code: 10017639

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the gallbladder wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hepatic failure

MedDRA 28.0 LLT code: 10019663

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Asterixis; mild encephalopathy; drug-induced liver injury (DILI); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; moderate to severe encephalopathy; coma
- **Grade 5:** Death
- **Definition:** A disorder characterized by the inability of the liver to metabolize chemicals in the body. Laboratory test results reveal abnormal plasma levels of ammonia, bilirubin, lactic dehydrogenase, alkaline phosphatase, aminotransferase, and/or prolongation of prothrombin time (INR.) Drug-induced liver injury (DILI) as defined by Hy's Law.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3, Definition

### Hepatic hemorrhage

MedDRA 28.0 LLT code: 10019678

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the liver.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Hepatic necrosis

MedDRA 28.0 LLT code: 10019692

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; urgent invasive intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the hepatic parenchyma.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hepatic pain

MedDRA 28.0 LLT code: 10019705

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the liver region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Hepatitis

MedDRA 28.0 LLT code: 10019717

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Symptomatic liver dysfunction; compensated cirrhosis; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** Life-threatening consequences; severe decompensated liver function (e.g., coagulopathy, encephalopathy, coma)
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the liver.
- **Navigational Note:** Consider Infections and infestations: Hepatitis viral, Hepatobiliary disorders: Hepatic failure. Report Autoimmune hepatitis under Hepatobiliary disorders: Other, specify.
- **CTCAE v6.0 Change:** Addition: Term

### Hepatobiliary disorders - Other, specify

MedDRA 28.0 LLT code: 10019805

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Perforation bile duct

MedDRA 28.0 LLT code: 10034405

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the wall of the extrahepatic or intrahepatic bile duct.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Portal hypertension

MedDRA 28.0 LLT code: 10036200

- **Grade 1:** -
- **Grade 2:** Decreased portal vein flow
- **Grade 3:** Reversal/retrograde portal vein flow; associated with varices and/or ascites
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an increase in blood pressure in the portal venous system.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Portal vein thrombosis

MedDRA 28.0 LLT code: 10036206

- **Grade 1:** -
- **Grade 2:** Intervention not indicated
- **Grade 3:** Medical intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the formation of a thrombus (blood clot) in the portal vein.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Sinusoidal obstruction syndrome

MedDRA 28.0 LLT code: 10063675

- **Grade 1:** -
- **Grade 2:** Blood bilirubin 2 - 5 mg/dL; minor interventions required (i.e., blood product, diuretic, oxygen)
- **Grade 3:** Blood bilirubin >5 mg/dL; coagulation modifier indicated (e.g., defibrotide); reversal of flow on ultrasound
- **Grade 4:** Life-threatening consequences (e.g., ventilatory support, dialysis, plasmapheresis, peritoneal drainage)
- **Grade 5:** Death
- **Definition:** A disorder characterized by severe hepatic injury as a result of the blood vessels of the liver becoming inflamed and/or blocked.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

## Immune system disorders

### Allergic reaction

MedDRA 28.0 LLT code: 10001718

- **Grade 1:** Systemic intervention not indicated
- **Grade 2:** Oral intervention indicated
- **Grade 3:** Bronchospasm; hospitalization indicated for clinical sequelae; IV intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an adverse general response from exposure to an allergen.
- **Navigational Note:** If related to infusion, consider Injury, poisoning and procedural complications: Infusion related reaction. If related to immunization, consider Injury, poisoning and procedural complications: Systemic post-immunization reaction. Do not report both.
- **CTCAE v6.0 Change:** Clarification: Grade 3, Definition, Navigational Note

### Anaphylaxis

MedDRA 28.0 LLT code: 10002218

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Symptomatic bronchospasm, with or without urticaria; parenteral intervention indicated; allergy-related edema/angioedema; hypotension
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an acute inflammatory reaction resulting from the release of histamine and histamine-like substances from mast cells, causing a hypersensitivity immune response. Clinically, it presents with breathing difficulty, dizziness, hypotension, cyanosis and loss of consciousness and may lead to death.
- **Navigational Note:** If related to infusion, consider Injury, poisoning and procedural complications: Infusion related reaction. Do not report both.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Autoimmune disorder

MedDRA 28.0 LLT code: 10061664

- **Grade 1:** Asymptomatic; serologic or other evidence of autoimmune reaction, with normal organ function; intervention not indicated
- **Grade 2:** Evidence of autoimmune reaction involving a non-essential organ or function (e.g., hypothyroidism)
- **Grade 3:** Autoimmune reactions involving major organ (e.g., colitis, anemia, myocarditis, kidney)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by loss of function or tissue destruction of an organ or multiple organs, arising from humoral or cellular immune responses of the individual to his own tissue constituents.
- **Navigational Note:** Prior to using this term consider specific autoimmune AEs.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Cytokine release syndrome

MedDRA 28.0 LLT code: 10052015

- **Grade 1:** Fever with or without constitutional symptoms
- **Grade 2:** Hypotension responding to fluids; hypoxia requiring low-flow nasal cannula or blow-by
- **Grade 3:** Hypotension managed with one pressor; hypoxia requiring high-flow nasal cannula, facemask, nonrebreather mask, or Venturi mask
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by fever, tachypnea, headache, tachycardia, hypotension, rash, and/or hypoxia caused by the release of cytokines.
- **Navigational Note:** Consider reporting other organ dysfunctions including neurological toxicities such as: Psychiatric disorders: Confusion, Hallucinations; Nervous system disorders: Dysphasia, Headache, Seizure, Tremor.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Graft versus host disease

MedDRA 28.0 LLT code: 10018651

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated
- **Grade 3:** IV intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by donor cells attacking the recipient's organs.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Immune system disorders - Other, specify

MedDRA 28.0 LLT code: 10021428

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** Use for diagnoses not present in CTCAE (ex. Sjogren's syndrome, etc.).
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Secondary hemophagocytic lymphohistiocytosis

MedDRA 28.0 LLT code: 10081409

- **Grade 1:** Asymptomatic or mild symptoms; requiring clinical and/or diagnostic evaluation; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated (e.g., immunosuppressive agents)
- **Grade 3:** Severe or medically significant but not immediately life threatening; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the development of a pathological and biochemical hyperinflammatory syndrome characterized by fever, cytopenias, hyperferritinemia, coagulopathy, hypofibrinogenemia and/or transaminitis and is attributable to therapy.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Serum sickness

MedDRA 28.0 LLT code: 10040400

- **Grade 1:** Clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate arthralgia; fever, rash, urticaria, antihistamines indicated
- **Grade 3:** Severe arthralgia or arthritis; extensive rash; steroids or IV fluids indicated
- **Grade 4:** Life-threatening consequences; pressor or ventilatory support indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a delayed-type hypersensitivity reaction to foreign proteins derived from an animal serum. It occurs approximately six to twenty-one days following the administration of the foreign antigen. Symptoms include fever, arthralgias, myalgias, skin eruptions, lymphadenopathy, chest marked discomfort and dyspnea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

## Infections and infestations

### Abdominal infection

MedDRA 28.0 LLT code: 10056519

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the abdominal cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anorectal infection

MedDRA 28.0 LLT code: 10061640

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the anal area and the rectum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Appendicitis

MedDRA 28.0 LLT code: 10003011

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by acute inflammation to the vermiform appendix caused by a pathogenic agent.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Appendicitis perforated

MedDRA 28.0 LLT code: 10003012

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Medical intervention indicated; operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by acute inflammation to the vermiform appendix caused by a pathogenic agent with gangrenous changes resulting in the rupture of the appendiceal wall. The appendiceal wall rupture causes the release of inflammatory and bacterial contents from the appendiceal lumen into the abdominal cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Arteritis infective

MedDRA 28.0 LLT code: 10065744

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving an artery.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Aseptic meningitis

MedDRA 28.0 LLT code: 10003458

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Steroid therapy indicated; severe changes in mental status; self-limited seizure activity; neurologic abnormalities
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an inflammatory process of the meninges of the brain and/or spinal cord.
- **Navigational Note:** Consider Infections and infestations: Meningitis.
- **CTCAE v6.0 Change:** Addition: Term

### Bacteremia

MedDRA 28.0 LLT code: 10003999

- **Grade 1:** -
- **Grade 2:** Blood culture positive with no signs or symptoms
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the presence of bacteria in the blood stream.
- **Navigational Note:** Grade 2 with hospitalization is acceptable; Consider Infections and infestations: Sepsis (Grades 3, 4 & 5).
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Biliary tract infection

MedDRA 28.0 LLT code: 10061695

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the biliary tract.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bladder infection

MedDRA 28.0 LLT code: 10005047

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the bladder.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bone infection

MedDRA 28.0 LLT code: 10061017

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the bones.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Breast infection

MedDRA 28.0 LLT code: 10006259

- **Grade 1:** -
- **Grade 2:** Local infection with moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; severe infection; axillary adenitis
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the breast.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bronchial infection

MedDRA 28.0 LLT code: 10055078

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the bronchi.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Candidiasis

MedDRA 28.0 LLT code: 10007152

- **Grade 1:** Asymptomatic; local symptom management indicated
- **Grade 2:** Oral intervention indicated (e.g., antifungal)
- **Grade 3:** IV antifungal intervention indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by a fungal infection caused by candida.
- **Navigational Note:** If recovered in bloodstream report as Infections and infestations: Fungemia.
- **CTCAE v6.0 Change:** Addition: Term

### Catheter related infection

MedDRA 28.0 LLT code: 10007810

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process that involves a catheter or port.
- **Navigational Note:** If related to a device other than a catheter or port, use Infections and infestations: Device related infection.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Definition

### Cecal infection

MedDRA 28.0 LLT code: 10065761

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the cecum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cervicitis infection

MedDRA 28.0 LLT code: 10008330

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the uterine cervix.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Conjunctivitis

MedDRA 28.0 LLT code: 10010741

- **Grade 1:** Asymptomatic or mild symptoms; intervention not indicated
- **Grade 2:** Symptomatic; moderate decrease in visual acuity (best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline)
- **Grade 3:** Symptomatic with marked decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation, swelling and redness to the conjunctiva of the eye.
- **Navigational Note:** Consider Infections and infestations: Conjunctivitis infective if caused by infection.
- **CTCAE v6.0 Change:** Clarification: Grade 3, Navigational Note

### Conjunctivitis infective

MedDRA 28.0 LLT code: 10010742

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by an infectious process involving the conjunctiva. Clinical manifestations include pink or red color in the eyes.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Corneal infection

MedDRA 28.0 LLT code: 10061788

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the cornea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cranial nerve infection

MedDRA 28.0 LLT code: 10065765

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving a cranial nerve.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cytomegalovirus infection reactivation

MedDRA 28.0 LLT code: 10058666

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; IV intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated; blindness
- **Grade 5:** Death
- **Definition:** A disorder characterized by the reactivation of cytomegalovirus (CMV).
- **Navigational Note:** Synonym: CMV
- **CTCAE v6.0 Change:** No Change

### Device related infection

MedDRA 28.0 LLT code: 10064687

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the use of a medical device.
- **Navigational Note:** If related to a catheter or port, use Infections and infestations: Catheter related infection.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Duodenal infection

MedDRA 28.0 LLT code: 10065752

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; medical intervention indicated (e.g., oral antibiotics)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the duodenum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Encephalitis

MedDRA 28.0 LLT code: 10014581

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; steroid therapy indicated; severe changes in mental status; self-limited seizure activity; neurologic abnormalities
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious or inflammatory process involving the brain tissue.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Encephalomyelitis

MedDRA 28.0 LLT code: 10014619

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; steroid therapy indicated; severe changes in mental status; self-limited seizure activity; neurologic abnormalities
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious or inflammatory process involving the brain and spinal cord tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Endocarditis infective

MedDRA 28.0 LLT code: 10014678

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the endocardial layer of the heart.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Endophthalmitis

MedDRA 28.0 LLT code: 10014801

- **Grade 1:** -
- **Grade 2:** Local intervention indicated
- **Grade 3:** Systemic intervention; hospitalization indicated
- **Grade 4:** Best corrected visual acuity of 20/200 or worse in the affected eye
- **Grade 5:** -
- **Definition:** A disorder characterized by an infectious process involving the internal structures of the eye.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Enterocolitis infectious

MedDRA 28.0 LLT code: 10058838

- **Grade 1:** -
- **Grade 2:** Passage of >3 unformed stools per 24 hrs or duration of illness >48 hrs; moderate abdominal pain; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated; profuse watery diarrhea with signs of hypovolemia; bloody diarrhea; fever; severe abdominal pain; hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the small and/or large intestines.
- **Navigational Note:** Includes Clostridioides difficile (c. diff, c. difficile). Consider Gastrointestinal disorders: Typhlitis, Infections and infestations: Cecal infection.
- **CTCAE v6.0 Change:** Clarification: Definition, Navigational Note

### Epstein-Barr virus infection reactivation

MedDRA 28.0 LLT code: 10015109

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; IV intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the reactivation of Epstein-Barr virus (EBV).
- **Navigational Note:** Synonym: EBV
- **CTCAE v6.0 Change:** No Change

### Esophageal infection

MedDRA 28.0 LLT code: 10058804

- **Grade 1:** -
- **Grade 2:** Local intervention indicated (e.g., oral antibiotic, antifungal, antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the esophagus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Eye infection

MedDRA 28.0 LLT code: 10015929

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated; enucleation
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the eye.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Folliculitis

MedDRA 28.0 LLT code: 10016936

- **Grade 1:** No intervention indicated
- **Grade 2:** Topical intervention initiated
- **Grade 3:** Systemic intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation or infection of the hair follicles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Fungemia

MedDRA 28.0 LLT code: 10017544

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the presence of fungus in the blood stream.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gallbladder infection

MedDRA 28.0 LLT code: 10062632

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the gallbladder.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gum infection

MedDRA 28.0 LLT code: 10018784

- **Grade 1:** Local therapy indicated (swish and swallow)
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the gums.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hepatic infection

MedDRA 28.0 LLT code: 10056522

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the liver.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hepatitis B reactivation

MedDRA 28.0 LLT code: 10058827

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; IV intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated; severe decompensated liver function (e.g., coagulopathy, encephalopathy, coma)
- **Grade 5:** Death
- **Definition:** A disorder characterized by the reactivation of hepatitis B virus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hepatitis viral

MedDRA 28.0 LLT code: 10019799

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Symptomatic liver dysfunction; fibrosis by biopsy; compensated cirrhosis; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** Life-threatening consequences; severe decompensated liver function (e.g., coagulopathy, encephalopathy, coma)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a viral pathologic process involving the liver parenchyma.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Herpes simplex reactivation

MedDRA 28.0 LLT code: 10080137

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; IV intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the reactivation of Herpes simplex virus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Infections and infestations - Other, specify

MedDRA 28.0 LLT code: 10021881

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Infective myositis

MedDRA 28.0 LLT code: 10021918

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the skeletal muscles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Joint infection

MedDRA 28.0 LLT code: 10023216

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral); needle aspiration indicated (single or multiple)
- **Grade 3:** Arthroscopic intervention indicated (e.g., drainage) or arthrotomy (e.g., open surgical drainage)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving a joint.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Kidney infection

MedDRA 28.0 LLT code: 10023424

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the kidney.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Laryngitis

MedDRA 28.0 LLT code: 10023874

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an inflammatory process involving the larynx.
- **Navigational Note:** For symptoms and no intervention, consider Respiratory, thoracic and mediastinal disorders: Hoarseness, Sore throat.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Lip infection

MedDRA 28.0 LLT code: 10065755

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an infectious process involving the lips.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Lymph gland infection

MedDRA 28.0 LLT code: 10050823

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the lymph nodes.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Mediastinal infection

MedDRA 28.0 LLT code: 10057483

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the mediastinum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Meningitis

MedDRA 28.0 LLT code: 10027199

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; steroid therapy indicated; severe changes in mental status; self-limited seizure activity; neurologic abnormalities
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious or inflammatory process of the meninges of the brain and/or spinal cord.
- **Navigational Note:** Consider Infections and infestations: Aseptic meningitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 3, Definition

### Meningoencephalitis

MedDRA 28.0 LLT code: 10027282

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; steroid therapy indicated; severe changes in mental status; self-limited seizure activity; neurologic abnormalities
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious or inflammatory process involving the meninges and the brain tissue.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Mucosal infection

MedDRA 28.0 LLT code: 10065764

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving a mucosal surface.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Myelitis

MedDRA 28.0 LLT code: 10028524

- **Grade 1:** Asymptomatic; mild signs (e.g., Babinski's reflex or Lhermitte's sign)
- **Grade 2:** Moderate weakness or sensory loss; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe weakness or sensory loss; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation involving the spinal cord. Symptoms include weakness, paresthesia, sensory loss, marked discomfort and incontinence.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Nail infection

MedDRA 28.0 LLT code: 10061304

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an infectious process involving the nail.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Otitis externa

MedDRA 28.0 LLT code: 10033072

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the outer ear and ear canal. Contributory factors include excessive water exposure (swimmer's ear infection) and cuts in the ear canal. Symptoms include fullness, itching, swelling and marked discomfort in the ear and ear drainage.
- **Navigational Note:** Changes associated with radiation to external ear (pinnae) are graded under Injury, poisoning and procedural complications: Dermatitis radiation.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Otitis media

MedDRA 28.0 LLT code: 10033078

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the middle ear.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ovarian infection

MedDRA 28.0 LLT code: 10055005

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the ovary.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pancreas infection

MedDRA 28.0 LLT code: 10051741

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the pancreas.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Paronychia

MedDRA 28.0 LLT code: 10034016

- **Grade 1:** Nail fold edema or erythema; disruption of the cuticle
- **Grade 2:** Local intervention indicated; oral intervention indicated (e.g., antibiotic, antifungal, antiviral); nail fold edema or erythema with pain; associated with discharge or nail plate separation; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Operative intervention indicated; IV antibiotics indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an infectious process involving the soft tissues around the nail.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Pelvic infection

MedDRA 28.0 LLT code: 10058674

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the pelvic cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Penile infection

MedDRA 28.0 LLT code: 10061912

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the penis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Periorbital infection

MedDRA 28.0 LLT code: 10051472

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process near or around the orbit of the eye.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Peripheral nerve infection

MedDRA 28.0 LLT code: 10065766

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the peripheral nerves.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Peritoneal infection

MedDRA 28.0 LLT code: 10057262

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the peritoneum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pharyngitis

MedDRA 28.0 LLT code: 10034835

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the throat.
- **Navigational Note:** For Grade 1 Consider Respiratory, thoracic and mediastinal disorders: Sore throat.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Phlebitis infective

MedDRA 28.0 LLT code: 10056627

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the vein. Clinical manifestations include erythema, marked discomfort, swelling, and induration along the course of the infected vein.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pleural infection

MedDRA 28.0 LLT code: 10061351

- **Grade 1:** -
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the pleura.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pneumonia

MedDRA 28.0 LLT code: 10035664

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the lungs.
- **Navigational Note:** Replaces Lung infection as this term is more commonly used. If due to aspiration, consider reporting Respiratory, thoracic and mediastinal disorders: Aspiration
- **CTCAE v6.0 Change:** Addition: Term

### Prostate infection

MedDRA 28.0 LLT code: 10050662

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the prostate gland.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rash pustular

MedDRA 28.0 LLT code: 10037888

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a circumscribed and elevated skin lesion filled with pus.
- **Navigational Note:** Consider Skin and subcutaneous tissue disorders: Pustular drug eruption.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Rhinitis infective

MedDRA 28.0 LLT code: 10059827

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an infectious process involving the nasal mucosal.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Salivary gland infection

MedDRA 28.0 LLT code: 10039413

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the salivary gland.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Scrotal infection

MedDRA 28.0 LLT code: 10062156

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the scrotum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Sepsis

MedDRA 28.0 LLT code: 10040047

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV intervention indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by the presence of pathogenic microorganisms in the blood stream that cause varying degrees of organ dysfunction due to a dysregulated host response to infection.
- **Navigational Note:** Consider Infections and infestations: Bacteremia (Grade 2).
- **CTCAE v6.0 Change:** Clarification: Grade 3, 4, Definition, Navigational Note

### Shingles

MedDRA 28.0 LLT code: 10040555

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Local infection with moderate symptoms; oral intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; IV intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the reactivation of herpes zoster virus.
- **Navigational Note:** Synonym: Herpes zoster
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Sinusitis

MedDRA 28.0 LLT code: 10040753

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the mucous membranes of the paranasal sinuses.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Skin infection

MedDRA 28.0 LLT code: 10040872

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the skin such as cellulitis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Small intestine infection

MedDRA 28.0 LLT code: 10065771

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the small intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Soft tissue infection

MedDRA 28.0 LLT code: 10062255

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving soft tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Splenic infection

MedDRA 28.0 LLT code: 10062112

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the spleen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Stoma site infection

MedDRA 28.0 LLT code: 10064505

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving a stoma (surgically created opening on the surface of the body).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Tooth infection

MedDRA 28.0 LLT code: 10048762

- **Grade 1:** -
- **Grade 2:** Localized; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving a tooth.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Tracheitis

MedDRA 28.0 LLT code: 10044302

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the trachea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Upper respiratory infection

MedDRA 28.0 LLT code: 10046300

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the upper respiratory tract (nose, paranasal sinuses, pharynx, larynx, or trachea).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urethral infection

MedDRA 28.0 LLT code: 10052298

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the urethra.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urinary tract infection

MedDRA 28.0 LLT code: 10046571

- **Grade 1:** -
- **Grade 2:** Localized; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the urinary tract, most commonly the bladder and the urethra.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Uterine infection

MedDRA 28.0 LLT code: 10062233

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the endometrium. It may extend to the myometrium and parametrial tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vaginal infection

MedDRA 28.0 LLT code: 10046914

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the vagina.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Viremia

MedDRA 28.0 LLT code: 10054688

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the presence of a virus in the blood stream.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vulval infection

MedDRA 28.0 LLT code: 10065772

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the vulva.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Wound infection

MedDRA 28.0 LLT code: 10048038

- **Grade 1:** Localized, local intervention indicated
- **Grade 2:** Oral intervention indicated (e.g., antibiotic, antifungal, or antiviral)
- **Grade 3:** IV antibiotic, antifungal, or antiviral intervention indicated; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an infectious process involving the wound.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Injury, poisoning and procedural complications

### Anesthetic complication

MedDRA 28.0 LLT code: 10054322

- **Grade 1:** -
- **Grade 2:** Any anesthesia effects requiring medical intervention for reversal of symptomatic effects and requiring unplanned hospitalization of <24 hours.
- **Grade 3:** Any anesthesia effects requiring medical intervention for reversal of symptomatic effects and requiring unplanned hospitalization of >=24 hours.
- **Grade 4:** Anesthesia effects with life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by reactions related to the administration of local or moderate sedation given for a procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Aortic injury

MedDRA 28.0 LLT code: 10002899

- **Grade 1:** -
- **Grade 2:** Operative intervention not indicated
- **Grade 3:** Severe symptoms; repair or revision indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; evidence of end organ damage; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the aorta.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Arterial injury

MedDRA 28.0 LLT code: 10003162

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; repair or revision not indicated
- **Grade 3:** Severe symptoms; repair or revision indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; evidence of end organ damage; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to an artery.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Biliary anastomotic leak

MedDRA 28.0 LLT code: 10050458

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage of bile due to breakdown of a biliary anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bladder anastomotic leak

MedDRA 28.0 LLT code: 10065802

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage of urine due to breakdown of a bladder anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bruising

MedDRA 28.0 LLT code: 10006504

- **Grade 1:** Localized or in a dependent area
- **Grade 2:** Generalized
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding of injury of the soft tissues or bone characterized by leakage of blood into surrounding tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Burn

MedDRA 28.0 LLT code: 10006634

- **Grade 1:** Minimal symptoms; intervention not indicated
- **Grade 2:** Medical intervention; minimal debridement indicated
- **Grade 3:** Moderate to major debridement or reconstruction indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A finding of impaired integrity to the anatomic site of an adverse thermal reaction. Burns can be caused by exposure to chemicals, direct heat, electricity, flames and radiation. The extent of damage depends on the length and intensity of exposure and time until provision of treatment.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Dermatitis radiation

MedDRA 28.0 LLT code: 10061103

- **Grade 1:** Faint erythema or dry desquamation
- **Grade 2:** Moderate to brisk erythema; patchy moist desquamation, mostly confined to skin folds and creases; moderate edema
- **Grade 3:** Moist desquamation in areas other than skin folds and creases; bleeding induced by minor trauma or abrasion
- **Grade 4:** Life-threatening consequences; skin necrosis or ulceration of full thickness dermis; spontaneous bleeding from involved site; skin graft indicated
- **Grade 5:** Death
- **Definition:** A finding of cutaneous inflammatory reaction occurring as a result of exposure to biologically effective levels of ionizing radiation.
- **Navigational Note:** Synonym: Radiation induced skin toxicities (CTCAE v3.0 )
- **CTCAE v6.0 Change:** No Change

### Esophageal anastomotic leak

MedDRA 28.0 LLT code: 10065961

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of an esophageal anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Fall

MedDRA 28.0 LLT code: 10016173

- **Grade 1:** Minor with no resultant injuries; intervention not indicated
- **Grade 2:** Symptomatic; noninvasive intervention indicated
- **Grade 3:** Hospitalization indicated; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding of sudden movement downward, usually resulting in injury.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Fallopian tube anastomotic leak

MedDRA 28.0 LLT code: 10065788

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a fallopian tube anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

### Fallopian tube perforation

MedDRA 28.0 LLT code: 10065790

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated (e.g., organ resection)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture of the fallopian tube wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Fracture

MedDRA 28.0 LLT code: 10017076

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic but non-displaced; immobilization indicated
- **Grade 3:** Severe symptoms; displaced or open wound with bone exposure; operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A state in which the continuity of the bone is broken.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3, Definition; Deletion: Navigational Note

### Gastric anastomotic leak

MedDRA 28.0 LLT code: 10065893

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a gastric anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastrointestinal anastomotic leak

MedDRA 28.0 LLT code: 10065879

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a gastrointestinal anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gastrointestinal stoma necrosis

MedDRA 28.0 LLT code: 10065712

- **Grade 1:** -
- **Grade 2:** Superficial necrosis; intervention not indicated
- **Grade 3:** Severe symptoms; hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the gastrointestinal tract stoma.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Infusion related reaction

MedDRA 28.0 LLT code: 10051792

- **Grade 1:** Mild transient reaction; infusion interruption not indicated; intervention not indicated
- **Grade 2:** Therapy or infusion interruption indicated but responds promptly to symptomatic treatment (e.g., antihistamines, NSAIDS, narcotics, IV fluids); prophylactic medications indicated for <=24 hrs
- **Grade 3:** Prolonged (e.g., not rapidly responsive to symptomatic medication and/or brief interruption of infusion); recurrence of symptoms following initial improvement; hospitalization indicated for clinical sequelae
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by adverse reaction to the infusion of pharmacological or biological substances.
- **Navigational Note:** If the reaction is an allergic reaction related to an agent, consider reporting as Immune system disorders: Allergic reaction. Do not report both.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Injury to carotid artery

MedDRA 28.0 LLT code: 10022161

- **Grade 1:** -
- **Grade 2:** Repair or revision not indicated
- **Grade 3:** Severe symptoms (e.g., transient cerebral ischemia); repair or revision indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the carotid artery.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Injury to inferior vena cava

MedDRA 28.0 LLT code: 10022213

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; repair or revision not indicated
- **Grade 3:** Severe symptoms; repair or revision indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the inferior vena cava.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Injury to jugular vein

MedDRA 28.0 LLT code: 10065849

- **Grade 1:** -
- **Grade 2:** Repair or revision not indicated
- **Grade 3:** Symptomatic; repair or revision indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the jugular vein.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Injury to superior vena cava

MedDRA 28.0 LLT code: 10022356

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; repair or revision not indicated
- **Grade 3:** Severe symptoms; repair or revision indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the superior vena cava.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Injury, poisoning and procedural complications - Other, specify

MedDRA 28.0 LLT code: 10022117

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Intestinal stoma leak

MedDRA 28.0 LLT code: 10059095

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage of contents from an intestinal stoma (surgically created opening on the surface of the body).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Intestinal stoma obstruction

MedDRA 28.0 LLT code: 10059094

- **Grade 1:** -
- **Grade 2:** Self-limited; intervention not indicated
- **Grade 3:** Severe symptoms; IV fluids, tube feeding, or TPN indicated >=24 hrs; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of the contents of the intestinal stoma.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Intestinal stoma site bleeding

MedDRA 28.0 LLT code: 10049468

- **Grade 1:** Minimal bleeding identified on clinical exam; intervention not indicated
- **Grade 2:** Moderate bleeding; medical intervention indicated
- **Grade 3:** Invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the intestinal stoma.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative arterial injury

MedDRA 28.0 LLT code: 10065826

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to an artery during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative breast injury

MedDRA 28.0 LLT code: 10065831

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the breast parenchyma during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative cardiac injury

MedDRA 28.0 LLT code: 10065843

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Primary repair of injured organ/structure indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the heart during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Intraoperative ear injury

MedDRA 28.0 LLT code: 10065844

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL (e.g., impaired hearing; impaired balance) or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the ear during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative endocrine injury

MedDRA 28.0 LLT code: 10065834

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the endocrine gland during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative gastrointestinal injury

MedDRA 28.0 LLT code: 10065825

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the gastrointestinal system during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative head and neck injury

MedDRA 28.0 LLT code: 10065842

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the head and neck during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative hemorrhage

MedDRA 28.0 LLT code: 10055298

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Postoperative invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of uncontrolled bleeding during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Intraoperative hepatobiliary injury

MedDRA 28.0 LLT code: 10065827

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the hepatic parenchyma and/or biliary tract during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative musculoskeletal injury

MedDRA 28.0 LLT code: 10065829

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the musculoskeletal system during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative neurological injury

MedDRA 28.0 LLT code: 10065830

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the nervous system during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative ocular injury

MedDRA 28.0 LLT code: 10065841

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the eye during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative renal injury

MedDRA 28.0 LLT code: 10065845

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the kidney during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative reproductive tract injury

MedDRA 28.0 LLT code: 10065840

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the reproductive organs during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative respiratory injury

MedDRA 28.0 LLT code: 10065832

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the respiratory system during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative splenic injury

MedDRA 28.0 LLT code: 10065847

- **Grade 1:** -
- **Grade 2:** Primary repair of injured organ/structure indicated
- **Grade 3:** Resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the spleen during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative urinary injury

MedDRA 28.0 LLT code: 10065828

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to the urinary system during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Intraoperative venous injury

MedDRA 28.0 LLT code: 10065848

- **Grade 1:** Primary repair of injured organ/structure indicated
- **Grade 2:** Partial resection of injured organ/structure indicated
- **Grade 3:** Complete resection or reconstruction of injured organ/structure indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to a vein during a surgical procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Kidney anastomotic leak

MedDRA 28.0 LLT code: 10065803

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage of urine due to breakdown of a kidney anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Large intestinal anastomotic leak

MedDRA 28.0 LLT code: 10065891

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of an anastomosis (surgical connection of two separate anatomic structures) in the large intestine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Nerve injury

MedDRA 28.0 LLT code: 10052897

- **Grade 1:** -
- **Grade 2:** Limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Invasive intervention indicated; hospitalization; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to a nerve.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Pancreatic anastomotic leak

MedDRA 28.0 LLT code: 10050457

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a pancreatic anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pharyngeal anastomotic leak

MedDRA 28.0 LLT code: 10065705

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a pharyngeal anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Post biopsy bleeding

MedDRA 28.0 LLT code: 10054113

- **Grade 1:** -
- **Grade 2:** Requiring additional observation
- **Grade 3:** Transfusion indicated; invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding as a result of a biopsy procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Postoperative hemorrhage

MedDRA 28.0 LLT code: 10055322

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate bleeding requiring transfusion <2 units (10 cc/kg for pediatrics) of pRBCs
- **Grade 3:** Transfusion indicated of >=2 units (10 cc/kg for pediatrics) pRBCs; invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding occurring after a surgical procedure.
- **Navigational Note:** Consider Injury, poisoning and procedural complications: Post biopsy bleeding.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2

### Postoperative thoracic procedure complication

MedDRA 28.0 LLT code: 10056745

- **Grade 1:** -
- **Grade 2:** Extubated within 24 - 72 hrs postoperatively
- **Grade 3:** Extubated >72 hrs postoperatively, but before tracheostomy indicated
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A finding of a previously undocumented problem that occurs after a thoracic procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Prolapse of intestinal stoma

MedDRA 28.0 LLT code: 10065745

- **Grade 1:** Asymptomatic; reducible
- **Grade 2:** Recurrent after manual reduction; local irritation or stool leakage; difficulty to fit appliance; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; elective operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of protrusion of the intestinal stoma (surgically created opening on the surface of the body) above the abdominal surface.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Prolapse of urostomy

MedDRA 28.0 LLT code: 10065822

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Local care or maintenance; minor revision indicated
- **Grade 3:** Dysfunctional stoma; elective operative intervention or major stomal revision indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of displacement of the urostomy.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Radiation recall reaction (dermatologic)

MedDRA 28.0 LLT code: 10037767

- **Grade 1:** Faint erythema or dry desquamation
- **Grade 2:** Moderate to brisk erythema; patchy moist desquamation, mostly confined to skin folds and creases; moderate edema
- **Grade 3:** Moist desquamation in areas other than skin folds and creases; bleeding induced by minor trauma or abrasion
- **Grade 4:** Life-threatening consequences; skin necrosis or ulceration of full thickness dermis; spontaneous bleeding from involved site; skin graft indicated
- **Grade 5:** Death
- **Definition:** A finding of acute skin inflammatory reaction caused by drugs, especially chemotherapeutic agents, for weeks or months following radiotherapy. The inflammatory reaction is confined to the previously irradiated skin and the symptoms disappear after the removal of the pharmaceutical agent.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rectal anastomotic leak

MedDRA 28.0 LLT code: 10065894

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a rectal anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Seroma

MedDRA 28.0 LLT code: 10040102

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; simple aspiration indicated
- **Grade 3:** Symptomatic, elective invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding of tumor-like collection of serum in the tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Small intestinal anastomotic leak

MedDRA 28.0 LLT code: 10065892

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of an anastomosis (surgical connection of two separate anatomic structures) in the small bowel.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Spermatic cord anastomotic leak

MedDRA 28.0 LLT code: 10065897

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a spermatic cord anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Stenosis of gastrointestinal stoma

MedDRA 28.0 LLT code: 10065898

- **Grade 1:** -
- **Grade 2:** Symptomatic; IV fluids indicated <24 hrs; manual dilation at bedside
- **Grade 3:** Severely altered GI function; tube feeding, TPN or hospitalization indicated; elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of narrowing of the gastrointestinal stoma (surgically created opening on the surface of the body).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Stomal ulcer

MedDRA 28.0 LLT code: 10042127

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; elective operative intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the jejunal mucosal surface close to the anastomosis site following a gastroenterostomy procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Systemic post-immunization reaction

MedDRA 28.0 LLT code: 10089920

- **Grade 1:** Mild pain; erythema 2.5 - 5 cm; induration/swelling 2.5 - 5 cm; does not interfere with activity
- **Grade 2:** Moderate pain; erythema >5 - 10 cm; Induration/swelling >5 - 10 cm; lipodystrophy; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; erythema >10 cm; Induration/swelling >10 cm; necrosis; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by a systemic manifestation that occurs after the injection of a substance with antigenic properties, administered to activate the immune system.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Tissue injury

MedDRA 28.0 LLT code: 10080903

- **Grade 1:** -
- **Grade 2:** Limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Invasive intervention indicated; hospitalization; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to an organ or tissue as a result of a procedure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Tracheal hemorrhage

MedDRA 28.0 LLT code: 10062548

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the trachea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Tracheal obstruction

MedDRA 28.0 LLT code: 10044291

- **Grade 1:** Partial asymptomatic obstruction on examination (e.g., visual, radiologic or endoscopic)
- **Grade 2:** Symptomatic (e.g., noisy airway breathing), no respiratory distress; medical intervention indicated (e.g., steroids); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Stridor or respiratory distress; invasive intervention indicated (e.g., stent, laser); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the lumen of the trachea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Tracheostomy site bleeding

MedDRA 28.0 LLT code: 10065749

- **Grade 1:** Minimal bleeding identified on clinical exam; intervention not indicated
- **Grade 2:** Moderate bleeding; medical intervention indicated
- **Grade 3:** Invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the tracheostomy site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Ureteric anastomotic leak

MedDRA 28.0 LLT code: 10065814

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a ureteral anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urethral anastomotic leak

MedDRA 28.0 LLT code: 10065815

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a urethral anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urostomy leak

MedDRA 28.0 LLT code: 10065882

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage of contents from a urostomy.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urostomy obstruction

MedDRA 28.0 LLT code: 10065883

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; dilation or endoscopic repair or stent placement indicated
- **Grade 3:** Altered organ function (e.g., sepsis or hydronephrosis, or renal dysfunction); elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; organ failure; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the urostomy.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urostomy site bleeding

MedDRA 28.0 LLT code: 10065748

- **Grade 1:** Minimal bleeding identified on clinical exam; intervention not indicated
- **Grade 2:** Moderate bleeding; medical intervention indicated
- **Grade 3:** Invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the urostomy site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Urostomy stenosis

MedDRA 28.0 LLT code: 10065885

- **Grade 1:** -
- **Grade 2:** Symptomatic but no hydronephrosis, sepsis, or renal dysfunction; dilation or endoscopic repair or stent placement indicated
- **Grade 3:** Symptomatic (e.g., hydronephrosis, or renal dysfunction); elective operative intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of narrowing of the opening of a urostomy.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Uterine anastomotic leak

MedDRA 28.0 LLT code: 10065886

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a uterine anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Uterine perforation

MedDRA 28.0 LLT code: 10046810

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the uterine wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vaginal anastomotic leak

MedDRA 28.0 LLT code: 10065887

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a vaginal anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vas deferens anastomotic leak

MedDRA 28.0 LLT code: 10065888

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of leakage due to breakdown of a vas deferens anastomosis (surgical connection of two separate anatomic structures).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vascular access complication

MedDRA 28.0 LLT code: 10062169

- **Grade 1:** TPA administration into line with no intent for systemic therapy indicated
- **Grade 2:** Device dislodgement, blockage, leak, or malposition; device replacement indicated
- **Grade 3:** Pulmonary embolism, deep vein or cardiac thrombosis; intervention indicated
- **Grade 4:** Life-threatening consequences with hemodynamic or neurologic instability
- **Grade 5:** Death
- **Definition:** A finding of a previously undocumented problem related to the vascular access site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Venous injury

MedDRA 28.0 LLT code: 10047228

- **Grade 1:** Asymptomatic diagnostic finding; intervention not indicated
- **Grade 2:** Symptomatic (e.g., claudication); repair or revision not indicated
- **Grade 3:** Severe symptoms; repair or revision indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; evidence of end organ damage; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A finding of damage to a vein.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Wound complication

MedDRA 28.0 LLT code: 10053692

- **Grade 1:** Observation only; topical intervention indicated
- **Grade 2:** Bedside local care indicated
- **Grade 3:** Operative intervention indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A finding of development of a new problem at the site of an existing wound.
- **Navigational Note:** Prior to using this term consider Injury, poisoning and procedural complications: Wound dehiscence or Infections and infestations: Wound infection.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Wound dehiscence

MedDRA 28.0 LLT code: 10048031

- **Grade 1:** Incisional separation, intervention not indicated
- **Grade 2:** Incisional separation, local care (e.g., suturing) or medical intervention indicated (e.g., analgesic)
- **Grade 3:** Fascial disruption or dehiscence without evisceration; revision by operative intervention indicated
- **Grade 4:** Life-threatening consequences; symptomatic hernia with evidence of strangulation; fascial disruption with evisceration; major reconstruction flap, grafting, resection, or amputation indicated
- **Grade 5:** Death
- **Definition:** A finding of separation of the approximated margins of a surgical wound.
- **Navigational Note:** Consider Infections and infestations: Wound infection.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

## Investigations

### Activated partial thromboplastin time prolonged

MedDRA 28.0 LLT code: 10000636

- **Grade 1:** >ULN - 1.5 x ULN
- **Grade 2:** >1.5 - 2.5 x ULN
- **Grade 3:** >2.5 x ULN; bleeding
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results in which the partial thromboplastin time is found to be greater than the control value. As a possible indicator of coagulopathy, a prolonged partial thromboplastin time (PTT) may occur in a variety of diseases and disorders, both primary and related to treatment.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Alanine aminotransferase increased

MedDRA 28.0 LLT code: 10001551

- **Grade 1:** >ULN - 3.0 x ULN if baseline was normal or less than normal; 1.0 - 1.5 x baseline if baseline was >ULN
- **Grade 2:** >3.0 - 5.0 x ULN if baseline was normal or less than normal; >1.5 - 2.0 x baseline if baseline was >ULN
- **Grade 3:** >5.0 - 20.0 x ULN if baseline was normal or less than normal; >2.0 - 4.0 x baseline if baseline was >ULN up to 5 x ULN
- **Grade 4:** >20.0 x ULN if baseline was normal or less than normal; >4.0 x baseline if baseline was >ULN
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in the level of alanine aminotransferase (ALT or SGPT) in the blood specimen.
- **Navigational Note:** Consider Hepatobiliary disorders: Hepatic failure. Report Autoimmune hepatitis under Hepatobiliary disorders: Other, specify.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4, Navigational Note

### Alkaline phosphatase increased

MedDRA 28.0 LLT code: 10001675

- **Grade 1:** >Baseline and ULN
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in the level of alkaline phosphatase (ALP) in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, Definition; Deletion Grade 2, 3, 4

### Aspartate aminotransferase increased

MedDRA 28.0 LLT code: 10003481

- **Grade 1:** >ULN - 3.0 x ULN if baseline was normal or less than normal; 1.0 - 1.5 x baseline if baseline was >ULN
- **Grade 2:** >3.0 - 5.0 x ULN if baseline was normal or less than normal; >1.5 - 2.0 x baseline if baseline was >ULN
- **Grade 3:** >5.0 - 20.0 x ULN if baseline was normal or less than normal; >2.0 - 4.0 x baseline if baseline was >ULN up to 5 x ULN
- **Grade 4:** >20.0 x ULN if baseline was normal or less than normal; >4.0 x baseline if baseline was >ULN
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in the level of aspartate aminotransferase (AST or SGOT) in a blood specimen.
- **Navigational Note:** Consider Hepatobiliary disorders: Hepatic failure. Report Autoimmune hepatitis under Hepatobiliary disorders: Other, specify.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4, Navigational Note

### Blood antidiuretic hormone abnormal

MedDRA 28.0 LLT code: 10005332

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Hospitalization indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate abnormal levels of antidiuretic hormone (ADH) in the blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Blood bicarbonate decreased

MedDRA 28.0 LLT code: 10005359

- **Grade 1:** <LLN and no intervention initiated
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in levels of bicarbonate in a venous blood specimen.
- **Navigational Note:** Consider Metabolism and nutrition disorders: Acidosis, Alkalosis.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Blood bilirubin increased

MedDRA 28.0 LLT code: 10005364

- **Grade 1:** >ULN - 1.5 x ULN if baseline was normal or less than normal; 1.0 - 1.5 x baseline if baseline was >ULN
- **Grade 2:** >1.5 - 3.0 x ULN if baseline was normal or less than normal; >1.5 - 2.5 x baseline if baseline was >ULN
- **Grade 3:** >3.0 - 10.0 x ULN if baseline was normal or less than normal; >2.5 - 10.0 x baseline if baseline was >ULN
- **Grade 4:** >10.0 x ULN if baseline was normal or less than normal; >10.0 x baseline if baseline was >ULN
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an abnormally high level of total bilirubin in the blood. Excess bilirubin is associated with jaundice.
- **Navigational Note:** Consider Hepatobiliary disorders: Hepatic failure. Report Autoimmune hepatitis under Hepatobiliary disorders: Other, specify.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4, Definition, Navigational Note

### Blood corticotrophin decreased

MedDRA 28.0 LLT code: 10005452

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Hospitalization indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in the expected levels of corticotrophin (ACTH) in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Blood gonadotrophin abnormal

MedDRA 28.0 LLT code: 10005561

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate abnormal levels of gonadotrophin hormone in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2; Deletion: Grade 3

### Blood lactate dehydrogenase increased

MedDRA 28.0 LLT code: 10005630

- **Grade 1:** >ULN
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate increased levels of lactate dehydrogenase (LDH) in the blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Blood prolactin abnormal

MedDRA 28.0 LLT code: 10005778

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate abnormal levels of prolactin hormone in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Carbon monoxide diffusing capacity decreased

MedDRA 28.0 LLT code: 10065906

- **Grade 1:** 3 - 5 units below LLN if no baseline available; for follow-up, a decrease of 3 - 5 units (ml/min/mmHg) below the baseline value; asymptomatic and intervention not indicated
- **Grade 2:** 6 - 8 units below LLN if no baseline available; for follow-up, an asymptomatic decrease of >5 - 8 units (ml/min/mmHg) below the baseline value; symptomatic and intervention not indicated
- **Grade 3:** Asymptomatic decrease of >8 units drop; >5 units drop along with the presence of pulmonary symptoms (e.g., >Grade 2 hypoxia or >Grade 2 dyspnea); intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on lung function test results that indicate a decrease in the lung capacity to absorb carbon monoxide (DLCO or TLCO).
- **Navigational Note:** Consider Respiratory, thoracic and mediastinal disorders: Dyspnea, Respiratory failure.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, Definition, Navigational Note

### CD4 lymphocytes decreased

MedDRA 28.0 LLT code: 10007839

- **Grade 1:** <LLN - 500/mm3; <LLN - 0.5 x 10^9/L
- **Grade 2:** <500 - 200/mm3; <0.5 - 0.2 x 10^9/L
- **Grade 3:** <200 - 50/mm3; <0.2 - 0.05 x 10^9/L
- **Grade 4:** <50/mm3; <0.05 x 10^9/L
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in levels of CD4 lymphocytes in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4, Definition

### Cholesterol high

MedDRA 28.0 LLT code: 10008661

- **Grade 1:** >ULN - 300 mg/dL; >ULN - 7.75 mmol/L
- **Grade 2:** >300 - 400 mg/dL; >7.75 - 10.34 mmol/L
- **Grade 3:** >400 - 500 mg/dL; >10.34 - 12.92 mmol/L
- **Grade 4:** >500 mg/dL; >12.92 mmol/L
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate higher than normal levels of cholesterol in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Creatinine clearance decreased

MedDRA 28.0 LLT code: 10011363

- **Grade 1:** -
- **Grade 2:** 26 - 49 ml/min
- **Grade 3:** 10 - 25 ml/min
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in creatinine clearance (CrCl) in a 24-hour urine collection.
- **Navigational Note:** Report Grade 4 and 5 as Renal and urinary disorders: Acute kidney injury or Chronic kidney disease.
- **CTCAE v6.0 Change:** Addition: Term

### Creatinine increased

MedDRA 28.0 LLT code: 10011368

- **Grade 1:** >ULN - 1.5 x ULN
- **Grade 2:** >1.5 - 3.0 x baseline if baseline is below LLN; >1.5 - 3.0 x ULN
- **Grade 3:** >3.0 x baseline if baseline is below LLN; >3.0 - 6.0 x ULN
- **Grade 4:** >6.0 x ULN
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate increased levels of creatinine in a biological specimen.
- **Navigational Note:** Consider Renal and urinary disorders: Acute kidney injury, Glomerulonephritis, Tubulointerstitial nephritis.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Electrocardiogram QT corrected interval prolonged

MedDRA 28.0 LLT code: 10014383

- **Grade 1:** Average QTc 450 - 480 ms
- **Grade 2:** Average QTc 481 - 500 ms
- **Grade 3:** Average QTc >500 ms; >60 ms change from baseline
- **Grade 4:** Life-threatening consequences; Torsade de pointes; polymorphic ventricular tachycardia
- **Grade 5:** -
- **Definition:** A finding of a cardiac dysrhythmia characterized by an abnormally long corrected QT interval.
- **Navigational Note:** Consider Cardiac disorders: Ventricular arrhythmia, Ventricular fibrillation, Ventricular tachycardia.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 3, 4

### Fibrinogen decreased

MedDRA 28.0 LLT code: 10016596

- **Grade 1:** <1.0 - 0.75 x LLN; if abnormal, <25% decrease from baseline
- **Grade 2:** <0.75 - 0.5 x LLN; if abnormal, 25 - <50% decrease from baseline
- **Grade 3:** <0.5 - 0.25 x LLN; if abnormal, 50 - <75% decrease from baseline
- **Grade 4:** <0.25 x LLN; if abnormal, 75% decrease from baseline; absolute value <50 mg/dL
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an decrease in levels of fibrinogen in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Forced expiratory volume decreased

MedDRA 28.0 LLT code: 10016987

- **Grade 1:** FEV1% (percentages of observed FEV1 and FVC related to their respective predicted values) 99 - 70% predicted; Global Lung Function Initiative (GLI) Z-score -1.65 to -2.5
- **Grade 2:** FEV1% 60 - 69%; GLI Z-score <-2.5 to -4
- **Grade 3:** FEV1% 50 - 59%; GLI Z-score <-4
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on test results that indicate a relative decrease in the fraction of the forced vital capacity that is exhaled in a specific number of seconds.
- **Navigational Note:** Consider Respiratory, thoracic and mediastinal disorders: Dyspnea, Respiratory failure.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, Navigational Note; Deletion: Grade 4

### GGT increased

MedDRA 28.0 LLT code: 10056910

- **Grade 1:** >ULN - 2.5 x ULN if baseline was normal or less than normal; 1.0 - 1.5 x baseline if baseline was >ULN
- **Grade 2:** >2.5 - 5.0 x ULN if baseline was normal or less than normal; >1.5 - 3.0 x baseline if baseline was >ULN
- **Grade 3:** >5.0 - 20.0 x ULN if baseline was normal or less than normal; >3.0 - 10.0 x baseline if baseline was >ULN
- **Grade 4:** >20.0 x ULN if baseline was normal or less than normal; >10.0 x baseline if baseline was >ULN
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate higher than normal levels of the enzyme gamma-glutamyltransferase in the blood specimen. GGT (gamma-glutamyltransferase ) catalyzes the transfer of a gamma glutamyl group from a gamma glutamyl peptide to another peptide, amino acids or water.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4

### Growth hormone abnormal

MedDRA 28.0 LLT code: 10018748

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate abnormal levels of growth hormone (GH) in a biological specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, Definition

### Haptoglobin decreased

MedDRA 28.0 LLT code: 10019150

- **Grade 1:** <LLN
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an decrease in levels of haptoglobin (HP) in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### HDL decreased

MedDRA 28.0 LLT code: 10019186

- **Grade 1:** <LLN
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in HDL in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Hemoglobin increased

MedDRA 28.0 LLT code: 10055599

- **Grade 1:** Increase in >0 - 2 g/dL above ULN
- **Grade 2:** Increase in >2 - 4 g/dL above ULN
- **Grade 3:** Increase in >4 g/dL above ULN
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate increased levels of hemoglobin (Hgb) above normal.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, Definition

### INR increased

MedDRA 28.0 LLT code: 10022402

- **Grade 1:** >1.2 - 1.5; >1 - 1.5 x baseline if on anticoagulation; monitoring only indicated
- **Grade 2:** >1.5 - 2.5; >1.5 - 2.5 x baseline if on anticoagulation; dose adjustment indicated
- **Grade 3:** >2.5; >2.5 x baseline if on anticoagulation; bleeding
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in the ratio of the patient's prothrombin time (PT) to a control sample in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Investigations - Other, specify

MedDRA 28.0 LLT code: 10022891

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### LDL increased

MedDRA 28.0 LLT code: 10024057

- **Grade 1:** >ULN
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in LDL in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Lipase increased

MedDRA 28.0 LLT code: 10024574

- **Grade 1:** >ULN - 1.5 x ULN
- **Grade 2:** >1.5 - 3.0 x ULN; >3.0 - 5.0 x ULN and asymptomatic
- **Grade 3:** >3.0 - 5.0 x ULN with signs or symptoms; >5.0 x ULN and asymptomatic
- **Grade 4:** >5.0 x ULN and with signs or symptoms
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in the level of lipase in a biological specimen.
- **Navigational Note:** Consider Gastrointestinal disorders: Pancreatitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Lymphocyte count increased

MedDRA 28.0 LLT code: 10025258

- **Grade 1:** -
- **Grade 2:** >4000/mm3 - 20,000/mm3
- **Grade 3:** >20,000/mm3
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an abnormal increase in the number of lymphocytes in the blood, effusions or bone marrow.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Neutrophil count decreased

MedDRA 28.0 LLT code: 10029366

- **Grade 1:** <1500 - 1000/mm3; <1.5 - 1.0 x 10^9/L
- **Grade 2:** <1000 - 500/mm3; <1.0 - 0.5 x 10^9/L
- **Grade 3:** <500 - 100/mm3; <0.5 - 0.1 x 10^9/L
- **Grade 4:** <100/mm3; <0.1 x 10^9/L
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in number of neutrophils (ANC) in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4, Definition

### Neutrophil count increased

MedDRA 28.0 LLT code: 10029368

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in number of neutrophils (ANC) in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Serum amylase increased

MedDRA 28.0 LLT code: 10040139

- **Grade 1:** >ULN - 1.5 x ULN
- **Grade 2:** >1.5 - 2.0 x ULN; >2.0 - 5.0 x ULN and asymptomatic or with mild signs or symptoms
- **Grade 3:** >2.0 - 5.0 x ULN with moderate or severe signs or symptoms; >5.0 x ULN and asymptomatic
- **Grade 4:** >5.0 x ULN and with signs or symptoms
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate an increase in the levels of amylase in a serum specimen.
- **Navigational Note:** Consider Gastrointestinal disorders: Pancreatitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Thyroid stimulating hormone increased

MedDRA 28.0 LLT code: 10043770

- **Grade 1:** TSH increased and no intervention indicated
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an increase in thyroid stimulating hormone (TSH).
- **Navigational Note:** If intervention initiated or symptomatic, report as Endocrine disorders: Hypothyroidism.
- **CTCAE v6.0 Change:** Clarification: Grade 1, Definition

### Urinary protein increased

MedDRA 28.0 LLT code: 10046553

- **Grade 1:** Adult: 1+ proteinuria; urinary protein ≥ULN - <1.0 g/24 hrs; P/C <1;<br>Pediatric: 1 + proteinuria
- **Grade 2:** Adult: 2+ and 3+ proteinuria; urinary protein 1.0 - <3.5 g/24 hrs; P/C 1 - 3.5;<br>Pediatric: Urine P/C (Protein/Creatinine) ratio 0.5 - 1.9; 2 - 3+ proteinuria
- **Grade 3:** Adult: Urinary protein >=3.5 g/24 hrs; 4+ proteinuria; P/C >3.5;<br>Pediatric: Urine P/C (Protein/Creatinine) ratio >1.9, 4+ proteinuria
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate the presence of excessive protein in the urine. It is predominantly albumin, but also globulin.
- **Navigational Note:** 24-hour urine collection takes precedence over dipstick.
- **CTCAE v6.0 Change:** Addition: Term

### Urine output decreased

MedDRA 28.0 LLT code: 10059895

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Adult: Oliguria (<80 ml in 8 hr);<br>Infants: <1 ml/kg/hour;<br>Children: <0.5 ml/kg/hour
- **Grade 4:** Adult: Anuria (<240 ml in 24 hr);<br>Pediatric: No urine output over 12 hours
- **Grade 5:** -
- **Definition:** A finding based on test results that indicate urine production is less relative to previous output.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Vital capacity abnormal

MedDRA 28.0 LLT code: 10047580

- **Grade 1:** 90 - 75% of predicted value
- **Grade 2:** <75 - 50% of predicted value; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** <50% of predicted value; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on pulmonary function test results that indicate an abnormal vital capacity (VC) (amount of exhaled after a maximum inhalation) when compared to the predicted value.
- **Navigational Note:** Consider Investigations: Forced expiratory volume decreased; Respiratory, thoracic and mediastinal disorders: Dyspnea, Respiratory failure.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Definition, Navigational Note

### Vitamin D decreased

MedDRA 28.0 LLT code: 10062189

- **Grade 1:** Vitamin D decreased <LLN
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a low concentration of Vitamin D in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Weight gain

MedDRA 28.0 LLT code: 10047896

- **Grade 1:** 5 - <10% from baseline
- **Grade 2:** 10 - <20% from baseline
- **Grade 3:** >=20% from baseline
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding characterized by an unexpected or abnormal increase in overall body weight; for pediatrics, percentages represent the absolute increase above that expected from the baseline growth curve (not change in growth percentiles).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition; Deletion: Navigational Note

### Weight loss

MedDRA 28.0 LLT code: 10047900

- **Grade 1:** 5 - <10% from baseline; intervention not indicated
- **Grade 2:** 10 - <20% from baseline; nutritional support indicated
- **Grade 3:** >=20% from baseline; tube feeding or TPN indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A finding characterized by a decrease in overall body weight; for pediatrics, less than the baseline growth curve.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

### White blood cell decreased

MedDRA 28.0 LLT code: 10049182

- **Grade 1:** <LLN - 3000/mm3; <LLN - 3.0 x 10^9/L
- **Grade 2:** <3000 - 2000/mm3; <3.0 - 2.0 x 10^9/L
- **Grade 3:** <2000 - 1000/mm3; <2.0 - 1.0 x 10^9/L
- **Grade 4:** <1000/mm3; <1.0 x 10^9/L
- **Grade 5:** -
- **Definition:** A finding based on laboratory test results that indicate a decrease in number of white blood cells (WBC) in a blood specimen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4, Definition

## Metabolism and nutrition disorders

### Acidosis

MedDRA 28.0 LLT code: 10000486

- **Grade 1:** pH <normal, but >=7.3
- **Grade 2:** -
- **Grade 3:** pH <7.3
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by abnormally high acidity (high hydrogen-ion concentration) of the blood and other body tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Alcohol intolerance

MedDRA 28.0 LLT code: 10001598

- **Grade 1:** -
- **Grade 2:** Present
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an increase in sensitivity to the adverse effects of alcohol, which can include nasal congestion, skin flushes, heart dysrhythmias, nausea, vomiting, indigestion and headaches.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Alkalosis

MedDRA 28.0 LLT code: 10001680

- **Grade 1:** pH >normal, but <=7.5
- **Grade 2:** -
- **Grade 3:** pH >7.5
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by abnormally high alkalinity (low hydrogen-ion concentration) of the blood and other body tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anorexia

MedDRA 28.0 LLT code: 10002646

- **Grade 1:** Loss of appetite without alteration in eating habits
- **Grade 2:** Oral intake altered without significant weight loss or malnutrition; oral nutritional supplements indicated
- **Grade 3:** Associated with significant weight loss or malnutrition (e.g., inadequate oral caloric and/or fluid intake); tube feeding or TPN indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a loss of appetite.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Dehydration

MedDRA 28.0 LLT code: 10012174

- **Grade 1:** Increased oral fluids indicated; dry mucous membranes; diminished skin turgor
- **Grade 2:** IV fluids indicated
- **Grade 3:** Hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by excessive loss of water from the body. It is usually caused by severe diarrhea, vomiting or diaphoresis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Diabetes mellitus

MedDRA 28.0 LLT code: 10012601

- **Grade 1:** Abnormal glucose above baseline; diet changes only; no change in baseline diabetic management
- **Grade 2:** Oral antiglycemic agent initiated; insulin sliding scale initiated
- **Grade 3:** Insulin therapy initiated or increased; hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated; diabetic ketoacidosis
- **Grade 5:** Death
- **Definition:** A disorder characterized by increased Hgb A1C that may result in organ damage.
- **Navigational Note:** Consider Metabolism and nutrition disorders: Hyperglycemia.
- **CTCAE v6.0 Change:** Addition: Term

### Failure to thrive

MedDRA 28.0 LLT code: 10016165

- **Grade 1:** -
- **Grade 2:** Limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A condition characterized by global decline with weight loss, decreased appetite, poor intake, and/or inactivity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Hypercalcemia

MedDRA 28.0 LLT code: 10020587

- **Grade 1:** Corrected serum calcium of >ULN - 11.5 mg/dL; >ULN - 2.9 mmol/L; Ionized calcium >ULN - 1.5 mmol/L
- **Grade 2:** Corrected serum calcium of >11.5 - 12.5 mg/dL; >2.9 - 3.1 mmol/L; Ionized calcium >1.5 - 1.6 mmol/L; symptomatic
- **Grade 3:** Corrected serum calcium of >12.5 - 13.5 mg/dL; >3.1 - 3.4 mmol/L; Ionized calcium >1.6 - 1.8 mmol/L; hospitalization indicated
- **Grade 4:** Corrected serum calcium of >13.5 mg/dL; >3.4 mmol/L; Ionized calcium >1.8 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of calcium (corrected for albumin) in blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hyperglycemia

MedDRA 28.0 LLT code: 10020639

- **Grade 1:** Fasting glucose value >ULN - 160 mg/dL; Fasting glucose value >ULN - 8.9 mmol/L
- **Grade 2:** Fasting glucose value >160 - 250 mg/dL; Fasting glucose value >8.9 - 13.9 mmol/L
- **Grade 3:** >250 - 500 mg/dL; >13.9 - 27.8 mmol/L; hospitalization indicated
- **Grade 4:** >500 mg/dL; >27.8 mmol/L; life-threatening consequences
- **Grade 5:** -
- **Definition:** A condition characterized by laboratory test results that indicate a confirmed, short lasting and unexpected elevation in the concentration of blood sugar (glycemia).
- **Navigational Note:** Consider Metabolism and nutrition disorders: Diabetes mellitus.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Deletion: Grade 5; Clarification: Grade 1, 2, 3, 4, Definition

### Hyperkalemia

MedDRA 28.0 LLT code: 10020647

- **Grade 1:** >ULN - 5.5 mmol/L
- **Grade 2:** >5.5 - 6.0 mmol/L; intervention initiated
- **Grade 3:** >6.0 - 7.0 mmol/L; hospitalization indicated
- **Grade 4:** >7.0 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of potassium in the blood; associated with kidney failure or sometimes with the use of diuretic drugs.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hyperlipidemia

MedDRA 28.0 LLT code: 10020667

- **Grade 1:** Requiring diet changes
- **Grade 2:** Requiring pharmaceutical intervention
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences
- **Grade 5:** -
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of lipids in blood.
- **Navigational Note:** Consider Gastrointestinal disorders: Pancreatitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 3

### Hypermagnesemia

MedDRA 28.0 LLT code: 10020670

- **Grade 1:** >ULN - 3.0 mg/dL; >ULN - 1.23 mmol/L
- **Grade 2:** -
- **Grade 3:** >3.0 - 8.0 mg/dL; >1.23 - 3.30 mmol/L
- **Grade 4:** >8.0 mg/dL; >3.30 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of magnesium in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypernatremia

MedDRA 28.0 LLT code: 10020680

- **Grade 1:** >ULN - 150 mmol/L
- **Grade 2:** >150 - 155 mmol/L; intervention initiated
- **Grade 3:** >155 - 160 mmol/L; hospitalization indicated
- **Grade 4:** >160 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of sodium in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hyperphosphatemia

MedDRA 28.0 LLT code: 10020712

- **Grade 1:** Laboratory finding only and intervention not indicated
- **Grade 2:** Noninvasive intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated (e.g., dialysis)
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of phosphate in a blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypertriglyceridemia

MedDRA 28.0 LLT code: 10020870

- **Grade 1:** 150 mg/dL - 300 mg/dL; 1.71 mmol/L - 3.42 mmol/L
- **Grade 2:** >300 mg/dL - 500 mg/dL; >3.42 mmol/L - 5.7 mmol/L
- **Grade 3:** >500 mg/dL - 1000 mg/dL; >5.7 mmol/L - 11.4 mmol/L
- **Grade 4:** >1000 mg/dL; >11.4 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of triglyceride concentration in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hyperuricemia

MedDRA 28.0 LLT code: 10020907

- **Grade 1:** >ULN without physiologic consequences
- **Grade 2:** -
- **Grade 3:** >ULN with physiologic consequences
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate an elevation in the concentration of uric acid.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypoalbuminemia

MedDRA 28.0 LLT code: 10020943

- **Grade 1:** <LLN - 3 g/dL; <LLN - 30 g/L
- **Grade 2:** <3 - 2 g/dL; <30 - 20 g/L
- **Grade 3:** <2 g/dL; <20 g/L
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate a low concentration of albumin in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypocalcemia

MedDRA 28.0 LLT code: 10020949

- **Grade 1:** Corrected serum calcium of <LLN - 8.0 mg/dL; <LLN - 2.0 mmol/L; Ionized calcium <LLN - 1.0 mmol/L
- **Grade 2:** Corrected serum calcium of <8.0 - 7.0 mg/dL; <2.0 - 1.75 mmol/L; Ionized calcium <1.0 - 0.9 mmol/L; symptomatic
- **Grade 3:** Corrected serum calcium of <7.0 - 6.0 mg/dL; <1.75 - 1.5 mmol/L; Ionized calcium <0.9 - 0.8 mmol/L; hospitalization indicated
- **Grade 4:** Corrected serum calcium of <6.0 mg/dL; <1.5 mmol/L; Ionized calcium <0.8 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate a low concentration of calcium (corrected for albumin) in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypoglycemia

MedDRA 28.0 LLT code: 10021005

- **Grade 1:** <LLN - 55 mg/dL; <LLN - 3.0 mmol/L
- **Grade 2:** <55 - 40 mg/dL; <3.0 - 2.2 mmol/L
- **Grade 3:** <40 - 30 mg/dL; <2.2 - 1.7 mmol/L
- **Grade 4:** <30 mg/dL; <1.7 mmol/L; life-threatening consequences; seizures
- **Grade 5:** Death
- **Definition:** A condition characterized by laboratory test results that indicate a low concentration of glucose in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Hypokalemia

MedDRA 28.0 LLT code: 10021018

- **Grade 1:** <LLN - 3.0 mmol/L
- **Grade 2:** Symptomatic with <LLN - 3.0 mmol/L; intervention indicated
- **Grade 3:** <3.0 - 2.5 mmol/L; hospitalization indicated
- **Grade 4:** <2.5 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate a low concentration of potassium in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypomagnesemia

MedDRA 28.0 LLT code: 10021028

- **Grade 1:** <LLN - 1.2 mg/dL; <LLN - 0.5 mmol/L
- **Grade 2:** <1.2 - 0.9 mg/dL; <0.5 - 0.4 mmol/L
- **Grade 3:** <0.9 - 0.7 mg/dL; <0.4 - 0.3 mmol/L
- **Grade 4:** <0.7 mg/dL; <0.3 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate a low concentration of magnesium in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hyponatremia

MedDRA 28.0 LLT code: 10021038

- **Grade 1:** <LLN - 130 mmol/L
- **Grade 2:** 125 - <130 mmol/L and asymptomatic
- **Grade 3:** 125 - <130 mmol/L symptomatic; 120 - <125 mmol/L regardless of symptoms
- **Grade 4:** <120 mmol/L; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate a low concentration of sodium in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hypophosphatemia

MedDRA 28.0 LLT code: 10021059

- **Grade 1:** Laboratory finding only and intervention not indicated
- **Grade 2:** Oral replacement therapy indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate a low concentration of phosphates in the blood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Iron overload

MedDRA 28.0 LLT code: 10065973

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; intervention not indicated
- **Grade 3:** Severe symptoms; intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by accumulation of iron in the tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Metabolism and nutrition disorders - Other, specify

MedDRA 28.0 LLT code: 10027433

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Tumor lysis syndrome

MedDRA 28.0 LLT code: 10045152

- **Grade 1:** Laboratory tumor lysis syndrome (LTLS) AND creatinine >ULN - 1.5 × ULN
- **Grade 2:** LTLS AND creatinine >1.5 – 3.0 × ULN; cardiac arrhythmia managed medically; one brief generalized seizure; seizure(s) well controlled by anticonvulsants; infrequent focal motor seizures not limiting age-appropriate instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** LTLS AND creatinine >3.0 – 6.0 × ULN; cardiac arrhythmia controlled with device (e.g. defibrillator); seizure in which consciousness is altered; poorly controlled seizure disorder; breakthrough generalized seizures despite medical intervention
- **Grade 4:** LTLS AND creatinine >6.0 x ULN; life-threatening cardiac arrhythmia or seizure
- **Grade 5:** Death
- **Definition:** A disorder characterized by metabolic abnormalities that result from a spontaneous or therapy-related cytolysis of tumor cells. Clinical tumor lysis syndrome (CTLS) requires one or more clinical manifestations along with criteria for laboratory tumor lysis syndrome (LTLS). LTLS is defined by two or more of the following laboratory abnormalities within 3 days before or 7 days after the initiation of chemotherapy: Uric acid ≥ 476 mcmol/L or 25% increase from baseline, Potassium ≥ 6.0 mmol/L or 25% increase from baseline, Phosphorous ≥ 2.1 mmol/L (children), ≥1.45 mmol/L (adults) or 25% increase from baseline, Calcium ≤ 1.75 mmol/L or 25% decrease from baseline.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Grade 1, 2; Clarification: Grade 3, 4, Definition

## Musculoskeletal and connective tissue disorders

### Abdominal soft tissue necrosis

MedDRA 28.0 LLT code: 10065775

- **Grade 1:** -
- **Grade 2:** Local wound care; medical intervention indicated (e.g., dressings or topical medications)
- **Grade 3:** Operative debridement or other invasive intervention indicated (e.g., tissue reconstruction, flap, or grafting)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the soft tissues of the abdominal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Arthralgia

MedDRA 28.0 LLT code: 10003239

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in a joint.
- **Navigational Note:** Report Inflammatory arthritis as Musculoskeletal and connective tissue disorder - Other, specify (Inflammatory arthritis).
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Arthritis

MedDRA 28.0 LLT code: 10003246

- **Grade 1:** Mild pain with inflammation, erythema, or joint swelling
- **Grade 2:** Moderate pain associated with signs of inflammation, erythema, or joint swelling; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain associated with signs of inflammation, erythema, or joint swelling; irreversible joint damage; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation involving a joint.
- **Navigational Note:** Report Inflammatory arthritis as Musculoskeletal and connective tissue disorder - Other, specify (Inflammatory arthritis).
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Back pain

MedDRA 28.0 LLT code: 10003988

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the back region.
- **Navigational Note:** Consider Injury, poisoning and procedural complications: Infusion related reaction; Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Bone pain

MedDRA 28.0 LLT code: 10006002

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the bones.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Buttock pain

MedDRA 28.0 LLT code: 10048677

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the buttocks.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Chest wall necrosis

MedDRA 28.0 LLT code: 10048831

- **Grade 1:** -
- **Grade 2:** Local wound care; medical intervention indicated (e.g., dressings or topical medications)
- **Grade 3:** Operative debridement or other invasive intervention indicated (e.g., tissue reconstruction, flap, or grafting)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the soft tissues of the chest wall including breast.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Chest wall pain

MedDRA 28.0 LLT code: 10008496

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the chest wall.
- **Navigational Note:** Report Inflammatory costochondritis as Musculoskeletal and connective tissue disorder - Other, specify (Inflammatory costochondritis). Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Exostosis

MedDRA 28.0 LLT code: 10015688

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; elective operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by non-neoplastic overgrowth of bone.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Fibrosis deep connective tissue

MedDRA 28.0 LLT code: 10065799

- **Grade 1:** Mild induration, able to move skin parallel to plane (sliding) and perpendicular to skin (pinching up)
- **Grade 2:** Moderate induration, able to slide skin, unable to pinch skin; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe induration; unable to slide or pinch skin; limiting joint or orifice movement (e.g., mouth, anus); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Generalized; associated with signs or symptoms of impaired breathing or feeding
- **Grade 5:** Death
- **Definition:** A disorder characterized by fibrotic degeneration of the deep connective tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Flank pain

MedDRA 28.0 LLT code: 10016750

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort on the lateral side of the body in the region below the ribs and above the hip.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Generalized muscle weakness

MedDRA 28.0 LLT code: 10062572

- **Grade 1:** Symptomatic; perceived by patient but not evident on physical exam
- **Grade 2:** Symptomatic; evident on physical exam; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a reduction in the strength of muscles in multiple anatomic sites.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Growth accelerated

MedDRA 28.0 LLT code: 10018746

- **Grade 1:** -
- **Grade 2:** >=+2 SD (standard deviation) above mid parental height or target height
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by greater growth than expected for age.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** SOC change; Clarification: Grade 2

### Growth suppression

MedDRA 28.0 LLT code: 10018761

- **Grade 1:** Reduction in growth velocity by 10 - 29% ideally measured over the period of a year
- **Grade 2:** Reduction in growth velocity by 30 - 49% ideally measured over the period of a year or 0 - 49% reduction in growth from the baseline growth curve
- **Grade 3:** Reduction in growth velocity of >=50% ideally measured over the period of a year
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by stature that is smaller than normal as expected for age.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Head soft tissue necrosis

MedDRA 28.0 LLT code: 10065779

- **Grade 1:** -
- **Grade 2:** Local wound care; medical intervention indicated (e.g., dressings or topical medications)
- **Grade 3:** Operative debridement or other invasive intervention indicated (e.g., tissue reconstruction, flap, or grafting)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the soft tissues of the head.
- **Navigational Note:** Consider Respiratory, thoracic and mediastinal disorders: Sinus disorder, Grade 4.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Joint effusion

MedDRA 28.0 LLT code: 10023215

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; invasive intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive fluid in a joint, usually as a result of joint inflammation.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Joint range of motion decreased

MedDRA 28.0 LLT code: 10048706

- **Grade 1:** <=25% loss of ROM (range of motion); decreased ROM limiting athletic activity
- **Grade 2:** >25 - 50% decrease in ROM; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** >50% decrease in ROM; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in joint flexibility of any joint.
- **Navigational Note:** Report Inflammatory arthritis as Musculoskeletal and connective tissue disorder - Other, specify (Inflammatory arthritis).
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Joint range of motion decreased cervical spine

MedDRA 28.0 LLT code: 10065796

- **Grade 1:** Mild restriction of rotation or flexion between 60 - 70 degrees
- **Grade 2:** Rotation <60 degrees to right or left; <60 degrees of flexion
- **Grade 3:** Ankylosed/fused over multiple segments with no C-spine rotation
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in flexibility of a cervical spine joint.
- **Navigational Note:** Report Inflammatory arthritis as Musculoskeletal and connective tissue disorder - Other, specify (Inflammatory arthritis).
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Joint range of motion decreased lumbar spine

MedDRA 28.0 LLT code: 10065800

- **Grade 1:** Stiffness; difficulty bending to the floor to pick up a very light object but able to do athletic activity
- **Grade 2:** Pain with range of motion (ROM) in lumbar spine; requires a reaching aid to pick up a very light object from the floor
- **Grade 3:** <50% lumbar spine flexion; associated with symptoms of ankylosis or fused over multiple segments with no L-spine flexion (e.g., unable to reach to floor to pick up a very light object)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in flexibility of a lumbar spine joint.
- **Navigational Note:** Report Inflammatory arthritis as Musculoskeletal and connective tissue disorder - Other, specify (Inflammatory arthritis).
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Kyphosis

MedDRA 28.0 LLT code: 10023509

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate accentuation; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe accentuation; operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an abnormal increase in the curvature of the thoracic portion of the spine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Lordosis

MedDRA 28.0 LLT code: 10024842

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate accentuation; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe accentuation; operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an abnormal increase in the curvature of the lumbar portion of the spine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Muscle cramp

MedDRA 28.0 LLT code: 10028294

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by marked cramping sensation originating from a muscle or group of muscles.
- **Navigational Note:** Synonym: Muscle spasm
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Muscle weakness lower limb

MedDRA 28.0 LLT code: 10065776

- **Grade 1:** Symptomatic; perceived by patient but not evident on physical exam
- **Grade 2:** Symptomatic; evident on physical exam; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a reduction in the strength of the lower limb muscles.
- **Navigational Note:** Consider Musculoskeletal and connective tissue disorders: Myositis; Immune system disorders: Immune system disorders - Other, specify; Injury, poisoning and procedural complications: Fall.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Muscle weakness trunk

MedDRA 28.0 LLT code: 10065795

- **Grade 1:** Symptomatic; perceived by patient but not evident on physical exam
- **Grade 2:** Symptomatic; evident on physical exam; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a reduction in the strength of the trunk muscles.
- **Navigational Note:** Consider Musculoskeletal and connective tissue disorders: Myositis; Immune system disorders: Immune system disorders - Other, specify; Injury, poisoning and procedural complications: Fall.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Muscle weakness upper limb

MedDRA 28.0 LLT code: 10065895

- **Grade 1:** Symptomatic; perceived by patient but not evident on physical exam
- **Grade 2:** Symptomatic; evident on physical exam; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a reduction in the strength of the upper limb muscles.
- **Navigational Note:** Consider Musculoskeletal and connective tissue disorders: Myositis; Immune system disorders: Immune system disorders - Other, specify; Injury, poisoning and procedural complications: Fall.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Musculoskeletal and connective tissue disorder - Other, specify

MedDRA 28.0 LLT code: 10028395

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Musculoskeletal deformity

MedDRA 28.0 LLT code: 10065783

- **Grade 1:** Cosmetically and functionally insignificant hypoplasia
- **Grade 2:** Deformity, hypoplasia, or asymmetry able to be remediated by prosthesis (e.g., shoe insert) or covered by clothing
- **Grade 3:** Significant deformity, hypoplasia, or asymmetry, unable to be remediated by prosthesis or covered by clothing; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an abnormality of the musculoskeletal system.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3, Definition

### Myalgia

MedDRA 28.0 LLT code: 10028411

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by marked discomfort sensation originating from a muscle or group of muscles.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Myositis

MedDRA 28.0 LLT code: 10028653

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain associated with weakness; pain limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Pain associated with severe weakness; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation involving the skeletal muscles.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Neck pain

MedDRA 28.0 LLT code: 10028836

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the neck area.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Neck soft tissue necrosis

MedDRA 28.0 LLT code: 10065781

- **Grade 1:** -
- **Grade 2:** Local wound care; medical intervention indicated (e.g., dressings or topical medications)
- **Grade 3:** Operative debridement or other invasive intervention indicated (e.g., tissue reconstruction, flap, or grafting)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the soft tissues of the neck.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Osteonecrosis

MedDRA 28.0 LLT code: 10031264

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated (e.g., analgesics or bisphosphonates); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; elective operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by necrotic changes in the bone tissue due to interruption of blood supply. Most often affecting the epiphysis of the long bones, the necrotic changes result in the collapse and the destruction of the bone structure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Osteonecrosis of jaw

MedDRA 28.0 LLT code: 10064658

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated (e.g., topical agents); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; elective operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the bone of the mandible.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Osteoporosis

MedDRA 28.0 LLT code: 10031282

- **Grade 1:** Adult: Radiologic evidence of osteoporosis or Bone Mineral Density (BMD) t-score -1 to -2.5 (osteopenia);<br>Pediatric: BMD z score of <=-2.0 and no history of significant fractures
- **Grade 2:** Adult: BMD t-score <-2.5; loss of height <2 cm; therapy to improve BMD indicated; limiting instrumental ADL;<br>Pediatric: BMD z-score <=-2.0 and significant fracture history (defined as a long bone fracture of the lower extremity, vertebral compression, 2 or more long bone fractures of the upper extremities); mild/moderate impact on age-appropriate normal daily activity
- **Grade 3:** Adult: Loss of height >=2 cm; hospitalization indicated; limiting self-care ADL;<br>Pediatric: Severe impact on age-appropriate normal daily activity
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by reduced bone mass, with a decrease in cortical thickness and in the number and size of the trabeculae of cancellous bone (but normal chemical composition), resulting in increased fracture incidence.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Pain in extremity

MedDRA 28.0 LLT code: 10033425

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the upper or lower extremities.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Pelvic soft tissue necrosis

MedDRA 28.0 LLT code: 10065793

- **Grade 1:** -
- **Grade 2:** Local wound care; medical intervention indicated (e.g., dressings or topical medications)
- **Grade 3:** Operative debridement or other invasive intervention indicated (e.g., tissue reconstruction, flap, or grafting)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the soft tissues of the pelvis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Rhabdomyolysis

MedDRA 28.0 LLT code: 10039020

- **Grade 1:** Asymptomatic, intervention not indicated; laboratory findings only
- **Grade 2:** Non-urgent intervention indicated
- **Grade 3:** Symptomatic, urgent intervention indicated
- **Grade 4:** Life-threatening consequences; dialysis
- **Grade 5:** Death
- **Definition:** A disorder characterized by the breakdown of muscle tissue resulting in the release of muscle fiber contents into the bloodstream.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Rotator cuff injury

MedDRA 28.0 LLT code: 10039226

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental AD or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an injury of the rotator cuff.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Scoliosis

MedDRA 28.0 LLT code: 10039722

- **Grade 1:** <20 degrees; clinically undetectable
- **Grade 2:** >20 - 45 degrees; visible by forward flexion; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** >45 degrees; scapular prominence in forward flexion; operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a lateral curvature of the spine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Definition

### Soft tissue necrosis lower limb

MedDRA 28.0 LLT code: 10065777

- **Grade 1:** -
- **Grade 2:** Local wound care; medical intervention indicated (e.g., dressings or topical medications)
- **Grade 3:** Operative debridement or other invasive intervention indicated (e.g., tissue reconstruction, flap, or grafting)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the soft tissues of the lower extremity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Soft tissue necrosis upper limb

MedDRA 28.0 LLT code: 10065778

- **Grade 1:** -
- **Grade 2:** Local wound care; medical intervention indicated (e.g., dressings or topical medications)
- **Grade 3:** Operative debridement or other invasive intervention indicated (e.g., tissue reconstruction, flap, or grafting)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the soft tissues of the upper extremity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Superficial soft tissue fibrosis

MedDRA 28.0 LLT code: 10065798

- **Grade 1:** Mild induration, able to move skin parallel to plane (sliding) and perpendicular to skin (pinching up)
- **Grade 2:** Moderate induration, able to slide skin, unable to pinch skin; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe induration; unable to slide or pinch skin; limiting joint or orifice movement (e.g., mouth, anus); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Generalized; associated with signs or symptoms of impaired breathing or feeding
- **Grade 5:** Death
- **Definition:** A disorder characterized by fibrotic degeneration of the superficial soft tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Trismus

MedDRA 28.0 LLT code: 10044684

- **Grade 1:** Decreased ROM (range of motion) without impaired eating
- **Grade 2:** Decreased ROM requiring small bites, soft foods or purees
- **Grade 3:** Decreased ROM with inability to adequately aliment or hydrate orally
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by lack of ability to open the mouth fully due to a decrease in the range of motion of the muscles of mastication.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Unequal limb length

MedDRA 28.0 LLT code: 10065738

- **Grade 1:** Mild length discrepancy <2 cm
- **Grade 2:** Moderate length discrepancy 2 - 5 cm; shoe lift indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe length discrepancy >5 cm; operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a discrepancy between the lengths of the lower or upper extremities.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

## Neoplasms benign, malignant and unspecified (incl cysts and polyps)

### Differentiation syndrome

MedDRA 28.0 LLT code: 10080638

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local, or noninvasive intervention indicated; limiting age appropriate instrumental ADL
- **Grade 3:** Severe or medically significant but not immediately life-threatening; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A potentially fatal complication of treatment in certain molecular subgroups of leukemia characterized by fever, rash, dyspnea and/or hypoxia, pulmonary infiltrates, peripheral edema with rapid weight gain, pleuropericardial effusion, acute renal failure, disseminated intravascular coagulation (DIC), bone pain and/or hypotension.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Keratoacanthoma

MedDRA 28.0 LLT code: 10023347

- **Grade 1:** -
- **Grade 2:** Present
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a cutaneous tumor that most commonly presents a dome-shaped nodule with a central keratin-filled crater.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Leukemia secondary to oncology chemotherapy

MedDRA 28.0 LLT code: 10048293

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Present
- **Grade 5:** Death
- **Definition:** A disorder characterized by leukemia arising as a result of the mutagenic effect of chemotherapy agents.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Myelodysplastic syndrome

MedDRA 28.0 LLT code: 10028533

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by insufficiently healthy hematapoietic cell production by the bone marrow.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Neoplasms benign, malignant and unspecified (incl cysts and polyps) - Other, specify

MedDRA 28.0 LLT code: 10029104

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Retinoic acid syndrome

MedDRA 28.0 LLT code: 10038921

- **Grade 1:** Fluid retention; <3 kg of weight gain; intervention with fluid restriction and/or diuretics indicated
- **Grade 2:** Moderate signs or symptoms; steroids indicated
- **Grade 3:** Severe symptoms; hospitalization indicated
- **Grade 4:** Life-threatening consequences; ventilatory support indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by weight gain, dyspnea, pleural and pericardial effusions, leukocytosis and/or renal failure originally described in patients treated with all-trans retinoic acid.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** SOC change

### Skin papilloma

MedDRA 28.0 LLT code: 10040907

- **Grade 1:** Asymptomatic; intervention not indicated
- **Grade 2:** Intervention initiated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the presence of one or more warts.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Treatment related secondary malignancy

MedDRA 28.0 LLT code: 10049737

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Non life-threatening secondary malignancy
- **Grade 4:** Acute life-threatening secondary malignancy; blast crisis in leukemia
- **Grade 5:** Death
- **Definition:** A disorder characterized by development of a malignancy most probably as a result of treatment for a previously existing malignancy.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Tumor hemorrhage

MedDRA 28.0 LLT code: 10055351

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding in a tumor.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Tumor pain

MedDRA 28.0 LLT code: 10045158

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort from a neoplasm that may be pressing on a nerve, blocking blood vessels, inflamed or fractured from metastasis.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

## Nervous system disorders

### Abducens nerve disorder

MedDRA 28.0 LLT code: 10053662

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the abducens nerve (sixth cranial nerve).
- **Navigational Note:** Consider Nervous system disorders: Peripheral motor neuropathy, Peripheral sensory neuropathy.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Accessory nerve disorder

MedDRA 28.0 LLT code: 10060929

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the accessory nerve (eleventh cranial nerve).
- **Navigational Note:** Consider Nervous system disorders: Peripheral motor neuropathy, Peripheral sensory neuropathy.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Acoustic nerve disorder NOS

MedDRA 28.0 LLT code: 10000521

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the acoustic nerve (eighth cranial nerve).
- **Navigational Note:** Consider Nervous system disorders: Peripheral motor neuropathy, Peripheral sensory neuropathy.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Akathisia

MedDRA 28.0 LLT code: 10001540

- **Grade 1:** Mild restlessness or increased motor activity
- **Grade 2:** Moderate restlessness or increased motor activity; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe restlessness or increased motor activity; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an uncomfortable feeling of inner restlessness and inability to stay still; this is a side effect of some psychotropic drugs.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Amnesia

MedDRA 28.0 LLT code: 10001949

- **Grade 1:** Mild; transient memory loss
- **Grade 2:** Moderate; short term memory loss; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe; long term memory loss; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by systematic and extensive loss of memory.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Anosmia

MedDRA 28.0 LLT code: 10002653

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in the sense of smell.
- **Navigational Note:** Consider Nervous system disorders: Olfactory nerve disorder.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Arachnoiditis

MedDRA 28.0 LLT code: 10003074

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the arachnoid membrane and adjacent subarachnoid space.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Ataxia

MedDRA 28.0 LLT code: 10003591

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; mechanical assistance indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by lack of coordination of muscle movements resulting in the impairment or inability to perform voluntary activities.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 1, 2, 3

### Autonomic neuropathy

MedDRA 28.0 LLT code: 10061666

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by damage to nerves that control your internal organs.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Brachial plexopathy

MedDRA 28.0 LLT code: 10065417

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by regional paresthesia of the brachial plexus, marked discomfort and muscle weakness, and limited movement in the arm or hand.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Brain fog

MedDRA 28.0 LLT code: 10088940

- **Grade 1:** Present
- **Grade 2:** Limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by thinking and memory problems that a patient with cancer may have during or after cancer treatment.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Central nervous system necrosis

MedDRA 28.0 LLT code: 10065784

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; corticosteroids indicated
- **Grade 3:** Severe symptoms; medical intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the brain and/or spinal cord.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cerebral venous sinus thrombosis

MedDRA 28.0 LLT code: 10083037

- **Grade 1:** -
- **Grade 2:** Intervention not indicated
- **Grade 3:** Medical intervention indicated (e.g., anticoagulants)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a thrombus (blood clot) in the brain’s venous sinuses leading to swelling and bleeding.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Cerebrospinal fluid leakage

MedDRA 28.0 LLT code: 10008164

- **Grade 1:** Post-craniotomy: asymptomatic; post-lumbar puncture: transient headache; postural care indicated
- **Grade 2:** Post-craniotomy: moderate symptoms; medical intervention indicated; post-lumbar puncture: persistent moderate symptoms; blood patch indicated
- **Grade 3:** Severe symptoms; medical intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by loss of cerebrospinal fluid into the surrounding tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2

### Cognitive disturbance

MedDRA 28.0 LLT code: 10009845

- **Grade 1:** Mild cognitive disability; not interfering with work/school/life performance; specialized educational services/devices not indicated
- **Grade 2:** Moderate cognitive disability; interfering with work/school/life performance but capable of independent living; specialized resources on part time basis indicated
- **Grade 3:** Severe cognitive disability; significant impairment of work/school/life performance
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a conspicuous change in cognitive function.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Concentration impairment

MedDRA 28.0 LLT code: 10010250

- **Grade 1:** Mild inattention or decreased level of concentration
- **Grade 2:** Moderate impairment in attention or decreased level of concentration; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe impairment in attention or decreased level of concentration; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a deterioration in the ability to concentrate.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Depressed level of consciousness

MedDRA 28.0 LLT code: 10012373

- **Grade 1:** Decreased level of alertness
- **Grade 2:** Sedation; slow response to stimuli; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Difficult to arouse
- **Grade 4:** Life-threatening consequences; coma; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in ability to perceive and respond.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2

### Dizziness

MedDRA 28.0 LLT code: 10013573

- **Grade 1:** Mild unsteadiness or sensation of movement
- **Grade 2:** Moderate unsteadiness or sensation of movement; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe unsteadiness or sensation of movement; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a disturbing sensation of lightheadedness, unsteadiness, giddiness, spinning or rocking.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Dysarthria

MedDRA 28.0 LLT code: 10013887

- **Grade 1:** Mild slurred speech
- **Grade 2:** Moderate impairment of articulation or slurred speech
- **Grade 3:** Severe impairment of articulation or slurred speech
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by slow and slurred speech resulting from an inability to coordinate the muscles used in speech.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Dysesthesia

MedDRA 28.0 LLT code: 10062872

- **Grade 1:** Mild sensory alteration
- **Grade 2:** Moderate sensory alteration; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe sensory alteration; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by distortion of sensory perception, resulting in an abnormal and unpleasant sensation.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Dysgeusia

MedDRA 28.0 LLT code: 10013911

- **Grade 1:** Altered taste but no change in diet
- **Grade 2:** Altered taste with change in diet (e.g., oral supplements); noxious or unpleasant taste; loss of taste
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by abnormal sensual experience with the taste of foodstuffs; it can be related to a decrease in the sense of smell.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Dysphasia

MedDRA 28.0 LLT code: 10013951

- **Grade 1:** Awareness of receptive or expressive characteristics; not impairing ability to communicate
- **Grade 2:** Moderate receptive or expressive characteristics; impairing ability to communicate spontaneously
- **Grade 3:** Severe receptive or expressive characteristics; impairing ability to read, write or communicate intelligibly
- **Grade 4:** Total loss of the ability to read, write, or communicate intelligibly
- **Grade 5:** -
- **Definition:** A disorder characterized by impairment of verbal communication skills, often resulting from brain damage.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Grade 4, Navigational Note

### Edema cerebral

MedDRA 28.0 LLT code: 10014217

- **Grade 1:** Radiographic finding only and no medical management initiated
- **Grade 2:** -
- **Grade 3:** New onset; worsening from baseline; initiation of steroid therapy
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by swelling due to an excessive accumulation of fluid in the brain.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Grade 1, Navigational Note; Clarification: Grade 3

### Encephalopathy

MedDRA 28.0 LLT code: 10014625

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a pathologic process involving the brain.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Extrapyramidal disorder

MedDRA 28.0 LLT code: 10015832

- **Grade 1:** Mild involuntary movements
- **Grade 2:** Moderate involuntary movements; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe involuntary movements or torticollis; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by abnormal, repetitive, involuntary muscle movements, frenzied speech and extreme restlessness.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3; Deletion: Navigational Note

### Facial muscle weakness

MedDRA 28.0 LLT code: 10051272

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a reduction in the strength of the facial muscles.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 1, 2, 3

### Facial nerve disorder

MedDRA 28.0 LLT code: 10061457

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the facial nerve (seventh cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Glossopharyngeal nerve disorder

MedDRA 28.0 LLT code: 10061185

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by dysfunction of the glossopharyngeal nerve (ninth cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Guillain-Barre syndrome

MedDRA 28.0 LLT code: 10018767

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated; intubation
- **Grade 5:** Death
- **Definition:** A disorder characterized by the body's immune system attacking the peripheral nervous system causing ascending paralysis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Headache

MedDRA 28.0 LLT code: 10019211

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in various parts of the head, not confined to the area of distribution of any nerve.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hemiparesis

MedDRA 28.0 LLT code: 10019465

- **Grade 1:** Symptomatic; perceived by patient but not evident on physical exam
- **Grade 2:** Symptomatic; evident on physical exam; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a reduction in the strength of the muscles on one side of the body.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Hydrocephalus

MedDRA 28.0 LLT code: 10020508

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention not indicated
- **Grade 3:** Severe symptoms or neurological deficit; intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal increase of cerebrospinal fluid in the ventricles of the brain.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypersomnia

MedDRA 28.0 LLT code: 10020765

- **Grade 1:** Mild increased need for sleep
- **Grade 2:** Moderate increased need for sleep
- **Grade 3:** Severe increased need for sleep
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive sleepiness during the daytime.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Hypoglossal nerve disorder

MedDRA 28.0 LLT code: 10061212

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the hypoglossal nerve (twelfth cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Immune effector cell-associated neurotoxicity syndrome

MedDRA 28.0 LLT code: 10083347

- **Grade 1:** Mild symptoms; Immune Effector Cell-Associated Encephalopathy (ICE) score 7 - 9; Cornell Assessment of Pediatric Delirium (CAPD) score 1 - 8 AND awakens spontaneously
- **Grade 2:** Moderate symptoms; ICE score 3 - 6; CAPD score 1 - 8 AND awakens to voice; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; ICE score 0 - 2; CAPD score >=9 AND awakens only to tactile stimulus; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a pathologic process involving the central nervous system following any immune therapy that results in the activation or engagement of endogenous or infused T cells and/or other immune effector cells. Symptoms or signs can be progressive and may include aphasia, altered level of consciousness, impairment of cognitive skills, motor weakness, seizures, and cerebral edema.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Intracranial hemorrhage

MedDRA 28.0 LLT code: 10022763

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Ventriculostomy, ICP monitoring, intraventricular thrombolysis, or invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from within the cranium.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, Definition

### Lethargy

MedDRA 28.0 LLT code: 10024264

- **Grade 1:** Mild symptoms; reduced alertness and awareness
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in consciousness characterized by mental and physical inertness.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2

### Leukoencephalopathy

MedDRA 28.0 LLT code: 10024382

- **Grade 1:** Asymptomatic; small focal T2/FLAIR hyperintensities; involving periventricular white matter or <1/3 of susceptible areas of cerebrum +/- mild increase in subarachnoid space (SAS) and/or mild ventriculomegaly
- **Grade 2:** Moderate symptoms; focal T2/FLAIR hyperintensities, involving periventricular white matter extending into centrum semiovale or involving 1/3 to 2/3 of susceptible areas of cerebrum +/- moderate increase in SAS and/or moderate ventriculomegaly
- **Grade 3:** Severe symptoms; extensive T2/FLAIR hyperintensities, involving periventricular white matter involving 2/3 or more of susceptible areas of cerebrum +/- moderate to severe increase in SAS and/or moderate to severe ventriculomegaly
- **Grade 4:** Life-threatening consequences; extensive T2/FLAIR hyperintensities, involving periventricular white matter involving most of susceptible areas of cerebrum +/- moderate to severe increase in SAS and/or moderate to severe ventriculomegaly
- **Grade 5:** Death
- **Definition:** A disorder characterized by diffuse reactive astrocytosis with multiple areas of necrotic foci without inflammation.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Memory impairment

MedDRA 28.0 LLT code: 10027175

- **Grade 1:** Mild memory impairment
- **Grade 2:** Moderate memory impairment; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe memory impairment; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a deterioration in memory function.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Meningismus

MedDRA 28.0 LLT code: 10027198

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by neck stiffness, headache, and photophobia resulting from irritation of the cerebral meninges.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Movements involuntary

MedDRA 28.0 LLT code: 10028041

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by uncontrolled and purposeless movements.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Myasthenia gravis

MedDRA 28.0 LLT code: 10028417

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by weakness and rapid fatigue of any of the skeletal muscles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Nervous system disorders - Other, specify

MedDRA 28.0 LLT code: 10029205

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Neuralgia

MedDRA 28.0 LLT code: 10029223

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by intense painful sensation along a nerve or group of nerves.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Nystagmus

MedDRA 28.0 LLT code: 10029864

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by involuntary movements of the eyeballs.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Oculomotor nerve disorder

MedDRA 28.0 LLT code: 10053661

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the oculomotor nerve (third cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Olfactory nerve disorder

MedDRA 28.0 LLT code: 10056388

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the olfactory nerve (first cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Optic neuritis

MedDRA 28.0 LLT code: 10030942

- **Grade 1:** Asymptomatic or mild symptoms; only enhancement on MRI scan with no change in vision
- **Grade 2:** Treatment indicated; best corrected visual acuity 20/40 and better or 3 lines or less decreased vision from known baseline in the affected eye; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately sight-threatening; decrease in visual acuity (best corrected visual acuity worse than 20/40 or more than 3 lines of decreased vision from known baseline, up to 20/200) in the affected eye; oral steroids indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Sight-threatening consequences; urgent intervention indicated; best corrected visual acuity of 20/200 or worse in the affected eye: significant visual field loss; marked optic disc edema or enhancement on MRI scan; intravenous steroids indicated; blindness
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation and demyelination of the optic nerve that causes acute, usually monocular, visual loss.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Paresthesia

MedDRA 28.0 LLT code: 10033987

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by functional disturbances of sensory neurons resulting in abnormal cutaneous sensations of tingling, numbness, pressure, cold, and/or warmth.
- **Navigational Note:** Consider Nervous system disorders: Peripheral motor neuropathy, Peripheral sensory neuropathy.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Peripheral motor neuropathy

MedDRA 28.0 LLT code: 10034580

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by damage or dysfunction of the peripheral motor nerves.
- **Navigational Note:** Consider Nervous system disorders: Peripheral sensory neuropathy.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, Navigational Note

### Peripheral sensory neuropathy

MedDRA 28.0 LLT code: 10034620

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by damage or dysfunction of the peripheral sensory nerves.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Phantom pain

MedDRA 28.0 LLT code: 10056238

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort related to a limb or an organ that is removed from or is not physically part of the body.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Presyncope

MedDRA 28.0 LLT code: 10036653

- **Grade 1:** -
- **Grade 2:** Present (e.g., near fainting)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an episode of lightheadedness and dizziness which may precede an episode of syncope.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Pyramidal tract syndrome

MedDRA 28.0 LLT code: 10063636

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by dysfunction of the corticospinal (pyramidal) tracts of the spinal cord. Symptoms include an increase in the muscle tone in the lower extremities, hyperreflexia, positive Babinski and a decrease in fine motor coordination.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Radiculitis

MedDRA 28.0 LLT code: 10061928

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation involving a nerve root. Patients experience marked discomfort radiating along a nerve path because of spinal pressure on the connecting nerve root.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Recurrent laryngeal nerve palsy

MedDRA 28.0 LLT code: 10038130

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms
- **Grade 3:** Severe symptoms; medical intervention indicated (e.g., thyroplasty, vocal cord injection)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by paralysis of the recurrent laryngeal nerve.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

### Reversible posterior leukoencephalopathy syndrome

MedDRA 28.0 LLT code: 10063761

- **Grade 1:** -
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; hospitalization; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by headaches, mental status changes, visual disturbances, and/or seizures associated with imaging findings of posterior leukoencephalopathy. It has been observed in association with hypertensive encephalopathy, eclampsia, and immunosuppressive and cytotoxic drug treatment. It is an acute or subacute reversible condition. Also known as posterior reversible encephalopathy syndrome (PRES).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Seizure

MedDRA 28.0 LLT code: 10039906

- **Grade 1:** Brief partial/focal seizure and no loss of consciousness
- **Grade 2:** Brief generalized seizure; seizure(s) well controlled by anticonvulsants; infrequent partial/focal motor seizures
- **Grade 3:** New onset seizures (partial/focal or generalized); multiple seizures despite medical intervention
- **Grade 4:** Life-threatening consequences; prolonged repetitive generalized seizures
- **Grade 5:** Death
- **Definition:** A disorder characterized by a sudden, involuntary skeletal muscular contractions of cerebral or brain stem origin.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4

### Somnolence

MedDRA 28.0 LLT code: 10041349

- **Grade 1:** Mild but more than usual drowsiness or sleepiness
- **Grade 2:** Moderate sedation; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Obtundation or stupor
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by characterized by excessive sleepiness and drowsiness.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Spasticity

MedDRA 28.0 LLT code: 10041416

- **Grade 1:** Mild or slight increase in muscle tone
- **Grade 2:** Moderate increase in muscle tone and increase in resistance through range of motion
- **Grade 3:** Severe increase in muscle tone and increase in resistance through range of motion
- **Grade 4:** Life-threatening consequences; unable to move active or passive range of motion
- **Grade 5:** Death
- **Definition:** A disorder characterized by increased involuntary muscle tone that affects the regions interfering with voluntary movement. It results in gait, movement, and speech disturbances.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Spinal cord compression

MedDRA 28.0 LLT code: 10041549

- **Grade 1:** Radiologic findings only
- **Grade 2:** Mild or moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by pressure on the spinal cord.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Grade 1, 2; Clarification: Grade 3

### Stroke

MedDRA 28.0 LLT code: 10042244

- **Grade 1:** Incidental radiographic findings only
- **Grade 2:** Mild to moderate neurologic deficit; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe neurologic deficit; hospitalization; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an interruption of blood supply to parts of the brain resulting in neurological damage.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Definition

### Syncope

MedDRA 28.0 LLT code: 10042772

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Fainting; orthostatic collapse
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by spontaneous loss of consciousness caused by insufficient blood supply to the brain.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Tendon reflex decreased

MedDRA 28.0 LLT code: 10043245

- **Grade 1:** Ankle reflex reduced
- **Grade 2:** Ankle reflex absent; other reflexes reduced
- **Grade 3:** Absence of all reflexes
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by less than normal deep tendon reflexes.
- **Navigational Note:** Consider Nervous system disorders: Peripheral motor neuropathy, Peripheral sensory neuropathy.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Transient ischemic attacks

MedDRA 28.0 LLT code: 10044391

- **Grade 1:** Mild neurologic deficit with or without imaging confirmation
- **Grade 2:** Moderate neurologic deficit with or without imaging confirmation
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a brief attack (less than 24 hours) of cerebral dysfunction of vascular origin, with no persistent neurological deficit.
- **Navigational Note:** If >24 hours, Consider Nervous system disorders: Stroke.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Tremor

MedDRA 28.0 LLT code: 10044565

- **Grade 1:** Mild symptoms
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the uncontrolled shaking movement of the whole body or individual parts.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Trigeminal nerve disorder

MedDRA 28.0 LLT code: 10060890

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the trigeminal nerve (fifth cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Trochlear nerve disorder

MedDRA 28.0 LLT code: 10074765

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dysfunction of the trochlear nerve (fourth cranial nerve).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Tumor inflammation-associated neurotoxicity

MedDRA 28.0 LLT code: 10091322

- **Grade 1:** Headaches associated with fevers; mild worsening of existing neurological clinical signs and symptoms from baseline, resulting in minor functional deficits for which only observation or symptomatic management is needed
- **Grade 2:** Moderate changes in the neurological exam from baseline that substantially affect function
- **Grade 3:** Severe neurological clinical signs and symptoms that may affect critical cardiorespiratory functions; clinical signs and symptoms of increased intracranial pressure (>20 mmHg) that are responsive to intervention
- **Grade 4:** Life-threatening, clinically significant elevated ICP (>20 mmHg) refractory to CSF drainage with no improvement in clinical symptoms in response to CSF drainage, possibly warranting urgent escalation of neurosurgical intervention; clinical signs and symptoms of impending/early herniation; severe medullary dysfunction requiring endotracheal intubation for airway protection and/or mechanical ventilation
- **Grade 5:** Death
- **Definition:** A disorder characterized by localized neurotoxicity related to cellular therapies or other immunotherapies for CNS tumors (TIAN).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Vagus nerve disorder

MedDRA 28.0 LLT code: 10061403

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by dysfunction of the vagus nerve (tenth cranial nerve).
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 1, 2, 3

### Vasovagal reaction

MedDRA 28.0 LLT code: 10047166

- **Grade 1:** -
- **Grade 2:** No management indicated
- **Grade 3:** Requires active management
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a sudden drop of the blood pressure, bradycardia, and peripheral vasodilation that may lead to loss of consciousness. It results from an increase in the stimulation of the vagus nerve.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Grade 2; Clarification: Grade 3

## Pregnancy, puerperium and perinatal conditions

### Fetal growth retardation

MedDRA 28.0 LLT code: 10054746

- **Grade 1:** -
- **Grade 2:** 5 - <10% percentile of weight for gestational age
- **Grade 3:** 1 - <5% percentile of weight for gestational age
- **Grade 4:** <1% percentile of weight for gestational age
- **Grade 5:** -
- **Definition:** A disorder characterized by inhibition of fetal growth resulting in the inability of the fetus to achieve its potential weight.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Pregnancy loss

MedDRA 28.0 LLT code: 10072314

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Fetal loss at any gestational age
- **Grade 5:** -
- **Definition:** Death in utero.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pregnancy, puerperium and perinatal conditions - Other, specify

MedDRA 28.0 LLT code: 10036585

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Premature delivery

MedDRA 28.0 LLT code: 10036595

- **Grade 1:** Delivery of a liveborn infant at >34 to 37 weeks gestation
- **Grade 2:** Delivery of a liveborn infant at >28 to 34 weeks gestation
- **Grade 3:** Delivery of a liveborn infant at 24 to 28 weeks gestation
- **Grade 4:** Delivery of a liveborn infant at 24 weeks of gestation or less
- **Grade 5:** -
- **Definition:** A disorder characterized by delivery of a viable infant before the normal end of gestation. Typically, viability is achievable between the twentieth and thirty-seventh week of gestation.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Psychiatric disorders

### Agitation

MedDRA 28.0 LLT code: 10001497

- **Grade 1:** Mild mood alteration
- **Grade 2:** Moderate mood alteration
- **Grade 3:** Severe agitation; hospitalization not indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by a state of restlessness associated with unpleasant feelings of irritability and tension.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anorgasmia

MedDRA 28.0 LLT code: 10002652

- **Grade 1:** Inability to achieve orgasm not adversely affecting relationship
- **Grade 2:** Inability to achieve orgasm adversely affecting relationship
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an inability to achieve orgasm.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Anxiety

MedDRA 28.0 LLT code: 10002855

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by apprehension of danger and dread accompanied by restlessness, tension, tachycardia, and dyspnea unattached to a clearly identifiable stimulus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Confusion

MedDRA 28.0 LLT code: 10010300

- **Grade 1:** Mild disorientation
- **Grade 2:** Moderate disorientation; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe disorientation; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by a lack of clear and orderly thought and behavior.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Delayed orgasm

MedDRA 28.0 LLT code: 10057066

- **Grade 1:** Delay in achieving orgasm not adversely affecting relationship
- **Grade 2:** Delay in achieving orgasm adversely affecting relationship
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by sexual dysfunction characterized by a delay in climax.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Delirium

MedDRA 28.0 LLT code: 10012218

- **Grade 1:** Mild acute confusional state
- **Grade 2:** Moderate and acute confusional state; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe and acute confusional state; hospitalization indicated; urgent intervention indicated; new onset; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences, threats of harm to self or others; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the acute and sudden development of confusion, illusions, movement changes, inattentiveness, agitation, and hallucinations. Usually, it is a reversible condition.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Delusions

MedDRA 28.0 LLT code: 10012260

- **Grade 1:** -
- **Grade 2:** Moderate delusional symptoms
- **Grade 3:** Severe delusional symptoms; outpatient management; new onset
- **Grade 4:** Life-threatening consequences, threats of harm to self or others; hospitalization indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by false personal beliefs held contrary to reality, despite contradictory evidence and common sense.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Depression

MedDRA 28.0 LLT code: 10012378

- **Grade 1:** Mild depressive symptoms
- **Grade 2:** Moderate depressive symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe depressive symptoms; hospitalization not indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences, threats of harm to self or others; hospitalization indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by melancholic feelings of grief or unhappiness.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Euphoria

MedDRA 28.0 LLT code: 10015533

- **Grade 1:** Mild mood elevation
- **Grade 2:** Moderate mood elevation
- **Grade 3:** Severe mood elevation (e.g., hypomania)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an exaggerated feeling of well-being which is disproportionate to events and stimuli.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hallucinations

MedDRA 28.0 LLT code: 10019077

- **Grade 1:** Mild hallucinations (e.g., perceptual distortions)
- **Grade 2:** Moderate hallucinations
- **Grade 3:** Severe hallucinations; hospitalization not indicated
- **Grade 4:** Life-threatening consequences, threats of harm to self or others; hospitalization indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a false sensory perception in the absence of an external stimulus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Insomnia

MedDRA 28.0 LLT code: 10022437

- **Grade 1:** Mild difficulty falling asleep, staying asleep or waking up early
- **Grade 2:** Moderate difficulty falling asleep, staying asleep or waking up early
- **Grade 3:** Severe difficulty in falling asleep, staying asleep or waking up early
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by difficulty in falling asleep and/or remaining asleep.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Irritability

MedDRA 28.0 LLT code: 10022998

- **Grade 1:** Mild; easily consolable
- **Grade 2:** Moderate; increased attention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe abnormal or excessive response; inconsolable; medical or psychiatric intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an abnormal responsiveness to stimuli or physiological arousal; may be in response to pain, fright, a drug, an emotional situation or a medical condition.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Libido decreased

MedDRA 28.0 LLT code: 10024419

- **Grade 1:** Decrease in sexual interest not adversely affecting relationship
- **Grade 2:** Decrease in sexual interest adversely affecting relationship
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in sexual desire.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Libido increased

MedDRA 28.0 LLT code: 10024421

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an increase in sexual desire.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Mania

MedDRA 28.0 LLT code: 10026749

- **Grade 1:** Mild manic symptoms (e.g., elevated mood, rapid thoughts, rapid speech, decreased need for sleep)
- **Grade 2:** Moderate manic symptoms (e.g., relationship and work difficulties; poor hygiene)
- **Grade 3:** Severe manic symptoms (e.g., hypomania; major sexual or financial indiscretions); hospitalization not indicated; new onset
- **Grade 4:** Life-threatening consequences, threats of harm to self or others; hospitalization indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by excitement of psychotic proportions manifested by mental and physical hyperactivity, disorganization of behavior and elevation of mood.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Personality change

MedDRA 28.0 LLT code: 10034719

- **Grade 1:** Mild personality change
- **Grade 2:** Moderate personality change
- **Grade 3:** Severe personality change; hospitalization not indicated
- **Grade 4:** Life-threatening consequences, threats of harm to self or others; hospitalization indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by a conspicuous change in a person's behavior and thinking.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Psychiatric disorders - Other, specify

MedDRA 28.0 LLT code: 10037175

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; hospitalization or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Psychosis

MedDRA 28.0 LLT code: 10037234

- **Grade 1:** Mild psychotic symptoms
- **Grade 2:** Moderate psychotic symptoms (e.g., disorganized speech; impaired reality testing)
- **Grade 3:** Severe psychotic symptoms (e.g., paranoid, extreme disorganization); hospitalization not indicated; new onset
- **Grade 4:** Life-threatening consequences, threats of harm to self or others; hospitalization indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by personality change, impaired functioning, and loss of touch with reality. It may be a manifestation of schizophrenia, bipolar disorder or brain tumor.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Restlessness

MedDRA 28.0 LLT code: 10038743

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an inability to rest, relax or be still.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Suicidal ideation

MedDRA 28.0 LLT code: 10042458

- **Grade 1:** Increased thoughts of death but no wish to kill oneself
- **Grade 2:** Suicidal ideation with no specific plan or intent
- **Grade 3:** Specific plan to commit suicide without serious intent to die which may not require hospitalization
- **Grade 4:** Specific plan to commit suicide with serious intent to die which requires hospitalization
- **Grade 5:** -
- **Definition:** A disorder characterized by thoughts of taking one's own life.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Suicide attempt

MedDRA 28.0 LLT code: 10042464

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Suicide attempt or gesture without intent to die
- **Grade 4:** Suicide attempt with intent to die which requires hospitalization
- **Grade 5:** Death
- **Definition:** A disorder characterized by self-inflicted harm in an attempt to end one's own life.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Renal and urinary disorders

### Acute kidney injury

MedDRA 28.0 LLT code: 10069339

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Hospitalization indicated
- **Grade 4:** Life-threatening consequences; dialysis indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the acute loss of renal function (within 2 weeks).
- **Navigational Note:** Consider Investigations: Creatinine increased; Renal and urinary disorders: Tubulointerstitial nephritis.
- **CTCAE v6.0 Change:** Clarification: Definition, Navigational Note

### Bladder perforation

MedDRA 28.0 LLT code: 10063575

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; organ failure; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the bladder wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bladder spasm

MedDRA 28.0 LLT code: 10048994

- **Grade 1:** Intervention not indicated
- **Grade 2:** Antispasmodics indicated
- **Grade 3:** Hospitalization indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sudden and involuntary contraction of the bladder wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Chronic kidney disease

MedDRA 28.0 LLT code: 10064848

- **Grade 1:** eGFR (estimated Glomerular Filtration Rate) or CrCl (creatinine clearance) <LLN - 60 ml/min/1.73 m2 or proteinuria 2+ present; urine protein/creatinine >0.5
- **Grade 2:** eGFR or CrCl <60 - 30 ml/min/1.73 m2
- **Grade 3:** eGFR or CrCl <30 - 15 ml/min/1.73 m2
- **Grade 4:** eGFR or CrCl <15 ml/min/1.73 m2; dialysis or renal transplant indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by loss of kidney function greater than three months duration.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Definition

### Cystitis noninfective

MedDRA 28.0 LLT code: 10063057

- **Grade 1:** Microscopic hematuria; minimal increase in frequency, urgency, dysuria, or nocturia; new onset of incontinence
- **Grade 2:** Moderate hematuria; moderate increase in frequency, urgency, dysuria, nocturia or incontinence; urinary catheter placement or bladder irrigation indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Gross hematuria; transfusion, IV medications, or hospitalization indicated; elective invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent invasive intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the bladder which is not caused by an infection of the urinary tract.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Dysuria

MedDRA 28.0 LLT code: 10013990

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by painful urination.
- **Navigational Note:** If associated with an infection, report the infection. For grades higher than Grade 1, consider Renal and urinary disorders: Bladder spasm, Cystitis noninfective; Infections and infestations: Urinary tract infection.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Glomerulonephritis

MedDRA 28.0 LLT code: 10018364

- **Grade 1:** Asymptomatic; laboratory findings only
- **Grade 2:** Declining glomerular filtration rate (GFR); edema; hypertension; oral management indicated
- **Grade 3:** IV therapy indicated; immunosuppressant indicated; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated; renal replacement therapy
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the glomerulus, usually based on renal biopsy.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Glucosuria

MedDRA 28.0 LLT code: 10068405

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by laboratory test results that indicate glucose in the urine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hematuria

MedDRA 28.0 LLT code: 10019450

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; urinary catheter or bladder irrigation indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Gross hematuria; transfusion, IV medications, or hospitalization indicated; elective invasive intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent invasive intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by laboratory test results that indicate blood in the urine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hemoglobinuria

MedDRA 28.0 LLT code: 10019489

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by laboratory test results that indicate the presence of free hemoglobin in the urine.
- **Navigational Note:** Report underlying AE if > Grade 1.
- **CTCAE v6.0 Change:** No Change

### Nephrotic syndrome

MedDRA 28.0 LLT code: 10029164

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** IV therapy indicated; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated; renal replacement therapy; anasarca
- **Grade 5:** Death
- **Definition:** A disorder characterized by symptoms that include severe edema, proteinuria, and hypoalbuminemia; it is indicative of renal dysfunction.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3, 4

### Nocturia

MedDRA 28.0 LLT code: 10029446

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the need to get up at night on a regular basis to urinate.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Renal and urinary disorders - Other, specify

MedDRA 28.0 LLT code: 10038359

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Renal calculi

MedDRA 28.0 LLT code: 10038385

- **Grade 1:** Asymptomatic or mild symptoms; occasional use of nonprescription analgesics indicated
- **Grade 2:** Symptomatic; oral antiemetics indicated; around the clock nonprescription analgesics or any oral narcotic analgesics indicated
- **Grade 3:** Hospitalization indicated; IV intervention (e.g., analgesics, antiemetics); elective invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent invasive intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the formation of crystals/kidney stones in the pelvis of the kidney.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Renal colic

MedDRA 28.0 LLT code: 10038419

- **Grade 1:** Mild pain not interfering with activity; nonprescription medication indicated
- **Grade 2:** Moderate pain; prescription medication indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by paroxysmal and severe flank marked discomfort radiating to the inguinal area. Often, the cause is the passage of crystals/kidney stones.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Renal hemorrhage

MedDRA 28.0 LLT code: 10038463

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Analgesics and hematocrit monitoring indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the kidney.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Tubulointerstitial nephritis

MedDRA 28.0 LLT code: 10048302

- **Grade 1:** Laboratory findings without increase in creatinine
- **Grade 2:** Increase in creatinine; oral management indicated with steroid
- **Grade 3:** IV therapy indicated; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the renal tubule and surrounding tissues.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Urinary fistula

MedDRA 28.0 LLT code: 10065368

- **Grade 1:** -
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent invasive intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between any part of the urinary system and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urinary frequency

MedDRA 28.0 LLT code: 10046539

- **Grade 1:** Present
- **Grade 2:** Medical management indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by urination at short intervals.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Urinary incontinence

MedDRA 28.0 LLT code: 10046543

- **Grade 1:** Occasional (e.g., with coughing, sneezing, etc.), pads not indicated
- **Grade 2:** Spontaneous; pads indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Intervention indicated (e.g., clamp, collagen injections); operative intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by inability to control the flow of urine from the bladder.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Urinary retention

MedDRA 28.0 LLT code: 10046555

- **Grade 1:** Urinary, suprapubic or intermittent catheter placement not indicated; able to void with some residual
- **Grade 2:** Placement of urinary, suprapubic or intermittent catheter placement indicated; medication indicated
- **Grade 3:** Elective invasive intervention indicated; substantial loss of affected kidney function or mass
- **Grade 4:** Life-threatening consequences; organ failure; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by accumulation of urine within the bladder because of the inability to urinate.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urinary tract obstruction

MedDRA 28.0 LLT code: 10061574

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic but no hydronephrosis, sepsis, or renal dysfunction; urethral dilation, urinary or suprapubic catheter indicated
- **Grade 3:** Altered organ function (e.g., hydronephrosis or renal dysfunction); invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the normal flow of contents of the urinary tract.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Urinary tract pain

MedDRA 28.0 LLT code: 10062225

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the urinary tract.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Urinary urgency

MedDRA 28.0 LLT code: 10046593

- **Grade 1:** Present
- **Grade 2:** Medical management indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sudden compelling urge to urinate.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Urine discoloration

MedDRA 28.0 LLT code: 10046628

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in the color of the urine.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Reproductive system and breast disorders

### Amenorrhea

MedDRA 28.0 LLT code: 10001927

- **Grade 1:** -
- **Grade 2:** Present
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the abnormal absence of menses for at least three consecutive menstrual cycles.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Azoospermia

MedDRA 28.0 LLT code: 10003883

- **Grade 1:** -
- **Grade 2:** Absence of sperm in ejaculate
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by laboratory test results that indicate complete absence of spermatozoa in the semen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Breast pain

MedDRA 28.0 LLT code: 10006298

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the breast region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Dysmenorrhea

MedDRA 28.0 LLT code: 10013934

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by abnormally painful abdominal cramps during menses.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Dyspareunia

MedDRA 28.0 LLT code: 10013941

- **Grade 1:** Mild discomfort or pain associated with vaginal penetration; discomfort relieved with use of vaginal lubricants or estrogen
- **Grade 2:** Moderate discomfort or pain associated with vaginal penetration; discomfort or pain partially relieved with use of vaginal lubricants or estrogen
- **Grade 3:** Severe discomfort or pain associated with vaginal penetration; discomfort or pain unrelieved by vaginal lubricants or estrogen
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by painful or difficult coitus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ejaculation disorder

MedDRA 28.0 LLT code: 10014326

- **Grade 1:** Diminished ejaculation
- **Grade 2:** Anejaculation or retrograde ejaculation
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by problems related to ejaculation. This category includes premature, delayed, retrograde and painful ejaculation.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Erectile dysfunction

MedDRA 28.0 LLT code: 10061461

- **Grade 1:** Decrease in erectile function (frequency or rigidity of erections) but intervention not indicated (e.g., medication or use of mechanical device, penile pump)
- **Grade 2:** Decrease in erectile function (frequency/rigidity of erections), erectile intervention indicated, (e.g., medication or mechanical devices such as penile pump)
- **Grade 3:** Decrease in erectile function (frequency/rigidity of erections) but erectile intervention not helpful (e.g., medication or mechanical devices such as penile pump); placement of a permanent penile prosthesis indicated (not previously present)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the persistent or recurrent inability to achieve or to maintain an erection during sexual activity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Fallopian tube obstruction

MedDRA 28.0 LLT code: 10065789

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; elective intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by blockage of the normal flow of the contents in the fallopian tube.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Feminization acquired

MedDRA 28.0 LLT code: 10054382

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the development of secondary female sex characteristics in males due to extrinsic factors.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Gynecomastia

MedDRA 28.0 LLT code: 10018801

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic (e.g., pain or psychosocial impact)
- **Grade 3:** Severe symptoms; elective operative intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive development of the breasts in males.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hematosalpinx

MedDRA 28.0 LLT code: 10060602

- **Grade 1:** Minimal bleeding identified on imaging study or laparoscopy; intervention not indicated
- **Grade 2:** Moderate bleeding; medical intervention indicated
- **Grade 3:** Invasive intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the presence of blood in a fallopian tube.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Irregular menstruation

MedDRA 28.0 LLT code: 10022992

- **Grade 1:** Intermittent/irregular menses for <=3 consecutive menstrual cycles
- **Grade 2:** Intermittent/irregular menses for >3 consecutive menstrual cycles
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in cycle or duration of menses from baseline.
- **Navigational Note:** Consider Reproductive system and breast disorders: Amenorrhea.
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, Navigational Note

### Lactation disorder

MedDRA 28.0 LLT code: 10061261

- **Grade 1:** Mild changes in lactation, not significantly affecting production or expression of breast milk
- **Grade 2:** Changes in lactation, significantly affecting breast production or expression of breast milk
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by disturbances of milk secretion. It is not necessarily related to pregnancy that is observed in females and can be observed in males.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Menorrhagia

MedDRA 28.0 LLT code: 10027313

- **Grade 1:** Mild; iron supplements indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated (e.g., hormones)
- **Grade 3:** Hospitalization; operative intervention indicated (e.g., hysterectomy)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by abnormally heavy vaginal bleeding during menses.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Nipple deformity

MedDRA 28.0 LLT code: 10065823

- **Grade 1:** Asymptomatic; asymmetry with slight retraction and/or thickening of the nipple areolar complex
- **Grade 2:** Symptomatic; asymmetry of nipple areolar complex with moderate retraction and/or thickening of the nipple areolar complex
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an abnormality of the nipple.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Oligospermia

MedDRA 28.0 LLT code: 10030300

- **Grade 1:** Sperm concentration >0 to <15 million/ml
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in the number of spermatozoa in the semen.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

### Ovarian function insufficiency

MedDRA 28.0 LLT code: 10033169

- **Grade 1:** Intermittent/irregular menses for 3 consecutive months with basal FSH levels >25 IU/L but less than postmenopausal range
- **Grade 2:** Amenorrhea for 3 consecutive months with basal FSH levels >40 IU/L or in the postmenopausal range
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the development of oligomenorrhea or amenorrhea for at least 3 consecutive months and serum follicle-stimulating hormone (FSH) levels in the menopausal range before age 40. Symptoms of estrogen deficiency may include hot flashes, night sweats, mood swings, and vaginal dryness. Laboratory findings include elevated serum FSH. Other supportive laboratory findings include decreased serum estradiol and anti-Mullerian hormone (AMH) levels.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Ovarian hemorrhage

MedDRA 28.0 LLT code: 10065763

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the ovary.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Ovarian rupture

MedDRA 28.0 LLT code: 10033279

- **Grade 1:** Asymptomatic clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic and intervention not indicated
- **Grade 3:** Transfusion; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by tearing or disruption of the ovarian tissue.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Ovulation pain

MedDRA 28.0 LLT code: 10033314

- **Grade 1:** -
- **Grade 2:** Present
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in one side of the abdomen between menstrual cycles, around the time of the discharge of the ovum from the ovarian follicle.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Pelvic floor muscle weakness

MedDRA 28.0 LLT code: 10064026

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic, not interfering with bladder, bowel, or vaginal function; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a reduction in the strength of the muscles of the pelvic floor.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Pelvic pain

MedDRA 28.0 LLT code: 10034263

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the pelvis.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Penile pain

MedDRA 28.0 LLT code: 10034310

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the penis.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Perineal pain

MedDRA 28.0 LLT code: 10061339

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the area between the genital organs and the anus.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Prostatic hemorrhage

MedDRA 28.0 LLT code: 10055325

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the prostate gland.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Prostatic obstruction

MedDRA 28.0 LLT code: 10055026

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; elective intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by compression of the urethra secondary to enlargement of the prostate gland. This results in voiding difficulties (straining to void, slow urine stream, and incomplete emptying of the bladder).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Prostatic pain

MedDRA 28.0 LLT code: 10036968

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the prostate gland.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Reproductive system and breast disorders - Other, specify

MedDRA 28.0 LLT code: 10038604

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Scrotal pain

MedDRA 28.0 LLT code: 10039757

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the scrotal area.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Spermatic cord hemorrhage

MedDRA 28.0 LLT code: 10065762

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the spermatic cord.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Spermatic cord obstruction

MedDRA 28.0 LLT code: 10065805

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; elective intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by blockage of the normal flow of the contents of the spermatic cord.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Testicular disorder

MedDRA 28.0 LLT code: 10043306

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic but not interfering with sexual function; intervention not indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; interfering with sexual function; intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by abnormal function or appearance of the testis.
- **Navigational Note:** Consider other AE terms in the Renal and urinary disorders SOC or Reproductive system and breast disorders SOC.
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Navigational Note

### Testicular hemorrhage

MedDRA 28.0 LLT code: 10055347

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the testis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Testicular pain

MedDRA 28.0 LLT code: 10043345

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the testis.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Uterine fistula

MedDRA 28.0 LLT code: 10065811

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the uterus and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Uterine hemorrhage

MedDRA 28.0 LLT code: 10046789

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the uterus.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Uterine obstruction

MedDRA 28.0 LLT code: 10065928

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; elective intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by blockage of the uterine outlet.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Uterine pain

MedDRA 28.0 LLT code: 10046809

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the uterus.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Vaginal discharge

MedDRA 28.0 LLT code: 10046901

- **Grade 1:** Mild vaginal discharge (greater than baseline for patient)
- **Grade 2:** Moderate to heavy vaginal discharge; use of perineal pad or tampon indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by vaginal secretions. Mucus produced by the cervical glands is discharged from the vagina naturally, especially during the childbearing years.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vaginal dryness

MedDRA 28.0 LLT code: 10046904

- **Grade 1:** Mild vaginal dryness not interfering with sexual function
- **Grade 2:** Moderate vaginal dryness interfering with sexual function or causing frequent discomfort
- **Grade 3:** Severe vaginal dryness resulting in dyspareunia or severe discomfort
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an uncomfortable feeling of itching and burning in the vagina.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vaginal fistula

MedDRA 28.0 LLT code: 10065813

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the vagina and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vaginal hemorrhage

MedDRA 28.0 LLT code: 10046912

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the vagina.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Vaginal inflammation

MedDRA 28.0 LLT code: 10046916

- **Grade 1:** Mild discomfort or pain, edema, or redness
- **Grade 2:** Moderate discomfort or pain, edema, or redness; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe discomfort or pain, edema, or redness; small areas of mucosal ulceration; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; widespread areas of mucosal ulceration; urgent intervention indicated
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation involving the vagina. Symptoms may include redness, edema, marked discomfort and an increase in vaginal discharge.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Vaginal obstruction

MedDRA 28.0 LLT code: 10065817

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; elective intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by blockage of vaginal canal.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vaginal pain

MedDRA 28.0 LLT code: 10046937

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the vagina.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Vaginal perforation

MedDRA 28.0 LLT code: 10065818

- **Grade 1:** -
- **Grade 2:** Invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a rupture in the vaginal wall.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vaginal stricture

MedDRA 28.0 LLT code: 10053496

- **Grade 1:** Asymptomatic; mild vaginal shortening or narrowing
- **Grade 2:** Vaginal narrowing and/or shortening not interfering with physical examination
- **Grade 3:** Vaginal narrowing and/or shortening interfering with the use of tampons, sexual activity or physical examination
- **Grade 4:** -
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the vaginal canal.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Respiratory, thoracic and mediastinal disorders

### Adult respiratory distress syndrome

MedDRA 28.0 LLT code: 10001409

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Present with radiologic findings; intubation not indicated
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by progressive and life-threatening pulmonary distress in the absence of an underlying pulmonary condition, usually following major trauma or surgery.
- **Navigational Note:** Consider Respiratory, thoracic and mediastinal disorders: Pneumonitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Allergic rhinitis

MedDRA 28.0 LLT code: 10001723

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an inflammation of the nasal mucous membranes caused by an IgE-mediated response to external allergens. The inflammation may also involve the mucous membranes of the sinuses, eyes, middle ear, and pharynx. Symptoms include sneezing, nasal congestion, rhinorrhea and itching.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Aphonia

MedDRA 28.0 LLT code: 10002953

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Voicelessness; unable to speak
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the inability to speak. It may result from injuries to the vocal cords or may be functional (psychogenic).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** SOC change

### Apnea

MedDRA 28.0 LLT code: 10002972

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Present; medical intervention indicated
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by cessation of breathing.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Aspiration

MedDRA 28.0 LLT code: 10003504

- **Grade 1:** Clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Altered eating habits; coughing or choking episodes after eating or swallowing; medical intervention indicated (e.g., suction or oxygen)
- **Grade 3:** Dyspnea and pneumonia symptoms (e.g., aspiration pneumonia); hospitalization indicated; unable to aliment orally
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inhalation of solids or liquids into the lungs.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

### Atelectasis

MedDRA 28.0 LLT code: 10003598

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic (e.g., dyspnea, cough); medical intervention indicated (e.g., chest physiotherapy, suctioning); bronchoscopic suctioning
- **Grade 3:** Supplemental oxygen indicated; hospitalization or elective operative intervention indicated (e.g., stent, laser)
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the collapse of part or the entire lung.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bronchial fistula

MedDRA 28.0 LLT code: 10006437

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the bronchus and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bronchial obstruction

MedDRA 28.0 LLT code: 10006440

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic (e.g., mild wheezing); endoscopic evaluation indicated; radiographic evidence of atelectasis/lobar collapse; medical management indicated (e.g., steroids, bronchodilators)
- **Grade 3:** Shortness of breath with stridor; endoscopic intervention indicated (e.g., laser, stent placement)
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of a bronchus passage, most often by bronchial secretions and exudates.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bronchial stricture

MedDRA 28.0 LLT code: 10063524

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic (e.g., rhonchi or wheezing) but without respiratory distress; medical intervention indicated (e.g., steroids, bronchodilators)
- **Grade 3:** Shortness of breath with stridor; endoscopic intervention indicated (e.g., laser, stent placement)
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the bronchial tube.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bronchopleural fistula

MedDRA 28.0 LLT code: 10053481

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Hospitalization; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between a bronchus and the pleural cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Bronchopulmonary hemorrhage

MedDRA 28.0 LLT code: 10065746

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; invasive intervention not indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the bronchial wall and/or lung parenchyma.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Bronchospasm

MedDRA 28.0 LLT code: 10006482

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Supplemental oxygen indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a sudden contraction of the smooth muscles of the bronchial wall or narrowing of the airway. May be manifested as wheezing.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Definition

### Chylothorax

MedDRA 28.0 LLT code: 10051228

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated (e.g., fat-restricted diet); thoracentesis or tube drainage indicated
- **Grade 3:** Severe symptoms; elective operative intervention indicated
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by milky pleural effusion (abnormal collection of fluid) resulting from accumulation of lymph fluid in the pleural cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Cough

MedDRA 28.0 LLT code: 10011224

- **Grade 1:** Mild symptoms; nonprescription intervention indicated
- **Grade 2:** Moderate symptoms, medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by sudden, often repetitive, spasmodic contraction of the thoracic cavity, resulting in violent release of air from the lungs and usually accompanied by a distinctive sound.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Dyspnea

MedDRA 28.0 LLT code: 10013963

- **Grade 1:** Shortness of breath with moderate exertion
- **Grade 2:** Shortness of breath with minimal exertion; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Shortness of breath at rest; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an uncomfortable sensation of difficulty breathing.
- **Navigational Note:** Consider Cardiac disorders: Heart failure; Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Epistaxis

MedDRA 28.0 LLT code: 10015090

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated (e.g., nasal packing, cauterization; topical vasoconstrictors)
- **Grade 3:** Transfusion; invasive intervention indicated (e.g., hemostasis of bleeding site)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the nose.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hiccups

MedDRA 28.0 LLT code: 10020039

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; interfering with sleep; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by repeated gulp sounds that result from an involuntary opening and closing of the glottis. This is attributed to a spasm of the diaphragm.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hoarseness

MedDRA 28.0 LLT code: 10020201

- **Grade 1:** Mild or intermittent voice change; fully understandable; self-resolves
- **Grade 2:** Moderate or persistent voice changes; may require occasional repetition but understandable on telephone; medical evaluation indicated
- **Grade 3:** Severe voice changes including predominantly whispered speech
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by harsh and raspy voice arising from or spreading to the larynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypoxia

MedDRA 28.0 LLT code: 10021143

- **Grade 1:** Asymptomatic decrease in oxygen saturation <LLN
- **Grade 2:** Decreased oxygen saturation with exercise (e.g., pulse oximeter <88%); intermittent supplemental oxygen
- **Grade 3:** Decreased oxygen saturation at rest (e.g., pulse oximeter <88% or PaO2 <=55 mmHg); continuous supplemental oxygen
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a decrease in the level of oxygen in the body.
- **Navigational Note:** Consider Respiratory, thoracic and mediastinal disorders: Dyspnea, Pneumonitis; Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Grade1, Navigational Note; Clarification: Grade 3

### Laryngeal edema

MedDRA 28.0 LLT code: 10023838

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated (e.g., dexamethasone, epinephrine, antihistamines)
- **Grade 3:** Stridor; respiratory distress; hospitalization indicated
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by swelling due to an excessive accumulation of fluid in the larynx.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Laryngeal fistula

MedDRA 28.0 LLT code: 10065786

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the larynx and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Laryngeal hemorrhage

MedDRA 28.0 LLT code: 10065759

- **Grade 1:** Mild cough or trace hemoptysis; laryngoscopic findings
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the larynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Laryngeal inflammation

MedDRA 28.0 LLT code: 10065735

- **Grade 1:** Mild sore throat; raspy voice
- **Grade 2:** Moderate sore throat; analgesics indicated
- **Grade 3:** Severe throat pain; endoscopic intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an inflammation involving the larynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Laryngeal mucositis

MedDRA 28.0 LLT code: 10065880

- **Grade 1:** Endoscopic findings only; mild discomfort with normal intake
- **Grade 2:** Moderate pain, analgesics indicated; altered oral intake; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; severely altered eating/swallowing; medical intervention indicated
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by ulceration or inflammation involving the mucous membrane of the larynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Laryngeal obstruction

MedDRA 28.0 LLT code: 10059639

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic (e.g., noisy airway breathing), no respiratory distress; medical intervention indicated (e.g., steroids); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Stridor; endoscopic intervention indicated (e.g., stent, laser); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by blockage of the laryngeal airway.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Laryngeal stenosis

MedDRA 28.0 LLT code: 10023862

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic (e.g., noisy airway breathing), no respiratory distress; medical intervention indicated (e.g., steroids); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Stridor; endoscopic intervention indicated (e.g., stent, laser); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the laryngeal airway.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Laryngopharyngeal dysesthesia

MedDRA 28.0 LLT code: 10062667

- **Grade 1:** Mild symptoms; no anxiety; intervention not indicated
- **Grade 2:** Moderate symptoms; mild anxiety, but no dyspnea; short duration of observation and/or anxiolytic indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; dyspnea and swallowing difficulty; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by an uncomfortable persistent sensation in the area of the laryngopharynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Laryngospasm

MedDRA 28.0 LLT code: 10023891

- **Grade 1:** -
- **Grade 2:** Transient episode; intervention not indicated
- **Grade 3:** Recurrent episodes; noninvasive intervention indicated (e.g., breathing technique, pressure point massage)
- **Grade 4:** Persistent or severe episodes associated with syncope; urgent intervention indicated (e.g., fiberoptic laryngoscopy, intubation, botox injection)
- **Grade 5:** Death
- **Definition:** A disorder characterized by paroxysmal spasmodic muscular contraction of the vocal cords.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Mediastinal hemorrhage

MedDRA 28.0 LLT code: 10056356

- **Grade 1:** Mild symptoms; intervention not indicated; radiologic evidence only
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the mediastinum.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Nasal congestion

MedDRA 28.0 LLT code: 10028735

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** Associated with bloody nasal discharge or epistaxis
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by obstruction of the nasal passage due to mucosal edema.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Oropharyngeal pain

MedDRA 28.0 LLT code: 10068319

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; altered oral intake; non-narcotics initiated; topical analgesics initiated
- **Grade 3:** Severe pain; severely altered eating/swallowing; narcotics initiated; requires parenteral nutrition
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the oropharynx or pain on swallowing.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Definition

### Pharyngeal fistula

MedDRA 28.0 LLT code: 10034825

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the pharynx and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pharyngeal hemorrhage

MedDRA 28.0 LLT code: 10055315

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; intervention indicated
- **Grade 3:** Hospitalization
- **Grade 4:** Life-threatening consequences; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the pharynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Pharyngeal mucositis

MedDRA 28.0 LLT code: 10065881

- **Grade 1:** Endoscopic findings only; minimal symptoms with normal oral intake; mild pain but analgesics not indicated
- **Grade 2:** Moderate pain, analgesics indicated; altered oral intake; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; unable to adequately aliment or hydrate orally; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by ulceration or inflammation involving the mucous membrane of the pharynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Pharyngeal necrosis

MedDRA 28.0 LLT code: 10065706

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Inability to aliment adequately by GI tract; invasive intervention indicated; tube feeding or TPN indicated
- **Grade 4:** Life-threatening consequences; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a necrotic process occurring in the pharynx.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pharyngeal stenosis

MedDRA 28.0 LLT code: 10050028

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic (e.g., noisy airway breathing), no respiratory distress; medical intervention indicated (e.g., steroids); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Stridor; endoscopic intervention indicated (e.g., stent, laser); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the pharyngeal airway.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Pharyngolaryngeal pain

MedDRA 28.0 LLT code: 10034844

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the pharyngolaryngeal region.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Pleural effusion

MedDRA 28.0 LLT code: 10035598

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; intervention indicated (e.g., diuretics or therapeutic thoracentesis)
- **Grade 3:** Symptomatic with respiratory distress and hypoxia; operative intervention including chest tube or pleurodesis indicated
- **Grade 4:** Life-threatening respiratory or hemodynamic compromise; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an increase in amounts of fluid within the pleural cavity. Symptoms include shortness of breath, cough and marked chest discomfort.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Pleural hemorrhage

MedDRA 28.0 LLT code: 10055319

- **Grade 1:** Asymptomatic; mild hemorrhage confirmed by thoracentesis
- **Grade 2:** Symptomatic or associated with pneumothorax; chest tube drainage indicated
- **Grade 3:** >1000 ml of blood evacuated; persistent bleeding (150-200 ml/hr for 2 - 4 hr); persistent transfusion indicated; elective operative intervention indicated; hospitalization
- **Grade 4:** Life-threatening consequences; intubation or urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by bleeding from the pleural cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pleuritic pain

MedDRA 28.0 LLT code: 10035623

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the pleura.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Pneumonitis

MedDRA 28.0 LLT code: 10035742

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; oxygen indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening respiratory compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation focally or diffusely affecting the lung parenchyma.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Pneumothorax

MedDRA 28.0 LLT code: 10035759

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; intervention indicated
- **Grade 3:** Sclerosis and/or operative intervention indicated; hospitalization indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by abnormal presence of air in the pleural cavity resulting in the collapse of the lung.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Postnasal drip

MedDRA 28.0 LLT code: 10036402

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive mucous secretion in the back of the nasal cavity or throat, causing sore throat and/or coughing.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Productive cough

MedDRA 28.0 LLT code: 10036790

- **Grade 1:** Occasional/minimal production of sputum with cough
- **Grade 2:** Moderate sputum production; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Persistent or copious production of sputum; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by expectorated secretions upon coughing.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Pulmonary edema

MedDRA 28.0 LLT code: 10037375

- **Grade 1:** Radiologic findings only; minimal dyspnea on exertion
- **Grade 2:** Moderate dyspnea on exertion; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe dyspnea or dyspnea at rest; oxygen indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening respiratory compromise; urgent intervention or intubation with ventilatory support indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by accumulation of fluid in the lung tissues that causes a disturbance of the gas exchange that may lead to respiratory failure.
- **Navigational Note:** Unless there is a clear non-cardiac cause, please record this event as Cardiac disorders: Heart failure. Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Pulmonary fibrosis

MedDRA 28.0 LLT code: 10037383

- **Grade 1:** Radiologic pulmonary fibrosis <25% of lung volume associated with hypoxia
- **Grade 2:** Evidence of pulmonary hypertension; radiographic pulmonary fibrosis 25 - 50% associated with hypoxia
- **Grade 3:** Severe hypoxia; evidence of right-sided heart failure; radiographic pulmonary fibrosis >50 - 75%
- **Grade 4:** Life-threatening consequences (e.g., hemodynamic/pulmonary complications); intubation with ventilatory support indicated; radiographic pulmonary fibrosis >75% with severe honeycombing
- **Grade 5:** Death
- **Definition:** A disorder characterized by the replacement of the lung tissue by connective tissue, leading to progressive dyspnea, respiratory failure or right heart failure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pulmonary fistula

MedDRA 28.0 LLT code: 10065873

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the lung and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Pulmonary hypertension

MedDRA 28.0 LLT code: 10037400

- **Grade 1:** Asymptomatic; radiographic, physical, or diagnostic findings
- **Grade 2:** Symptomatic; requiring medical intervention
- **Grade 3:** Severe symptoms, associated with hypoxia, right heart failure; oxygen indicated
- **Grade 4:** Life-threatening airway consequences; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by an increase in pressure within the pulmonary circulation due to lung or heart disorder.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2

### Respiratory failure

MedDRA 28.0 LLT code: 10038695

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Life-threatening consequences; urgent intervention, intubation, or ventilatory support indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by impaired gas exchange by the respiratory system resulting in hypoxia and a decrease in oxygenation of the tissues that may be associated with an increase in arterial levels of carbon dioxide.
- **Navigational Note:** Consider Respiratory, thoracic and mediastinal disorders: Pneumonitis.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Respiratory, thoracic and mediastinal disorders - Other, specify

MedDRA 28.0 LLT code: 10038738

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Rhinorrhea

MedDRA 28.0 LLT code: 10039100

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive mucous secretions draining from the nose.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Sinus disorder

MedDRA 28.0 LLT code: 10062244

- **Grade 1:** Asymptomatic mucosal crusting; blood-tinged secretions
- **Grade 2:** Symptomatic stenosis or edema/narrowing interfering with airflow; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Stenosis with significant nasal obstruction; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Necrosis of soft tissue or bone; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by involvement of the paranasal sinuses.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Sinus pain

MedDRA 28.0 LLT code: 10040747

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the face, between the eyes, or upper teeth originating from the sinuses.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Sleep apnea

MedDRA 28.0 LLT code: 10040975

- **Grade 1:** Snoring and nocturnal sleep arousal without apneic periods
- **Grade 2:** Moderate apnea and oxygen desaturation; excessive daytime sleepiness; medical evaluation indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Oxygen desaturation; associated with pulmonary hypertension; medical intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Cardiovascular or neuropsychiatric symptoms; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by cessation of breathing for short periods during sleep.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Sneezing

MedDRA 28.0 LLT code: 10041232

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; medical intervention indicated
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the involuntary expulsion of air from the nose.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Sore throat

MedDRA 28.0 LLT code: 10041367

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting ability to swallow; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by marked discomfort in the throat.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Stridor

MedDRA 28.0 LLT code: 10042241

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Respiratory distress; medical intervention indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a high pitched breathing sound due to laryngeal or upper airway obstruction.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Tracheal fistula

MedDRA 28.0 LLT code: 10065787

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic, invasive intervention not indicated
- **Grade 3:** Invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an abnormal communication between the trachea and another organ or anatomic site.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Tracheal mucositis

MedDRA 28.0 LLT code: 10065900

- **Grade 1:** Endoscopic findings only; minimal hemoptysis, pain, or respiratory symptoms
- **Grade 2:** Moderate symptoms; medical intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; hemorrhage or respiratory symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an inflammation or ulceration involving the mucous membrane of the trachea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Tracheal stenosis

MedDRA 28.0 LLT code: 10050816

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic (e.g., noisy airway breathing), no respiratory distress; medical intervention indicated (e.g., steroids); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Stridor or respiratory distress; invasive intervention indicated (e.g., stent, laser); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening airway compromise; urgent intervention indicated (e.g., tracheotomy or intubation)
- **Grade 5:** Death
- **Definition:** A disorder characterized by a narrowing of the trachea.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Voice alteration

MedDRA 28.0 LLT code: 10047681

- **Grade 1:** Mild or intermittent change from normal voice
- **Grade 2:** Moderate or persistent change from normal voice; still understandable
- **Grade 3:** Severe voice changes including predominantly whispered speech; may require frequent repetition or face-to-face contact for understandability; may require assistive technology
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in the sound and/or speed of the voice.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

## Skin and subcutaneous tissue disorders

### Alopecia

MedDRA 28.0 LLT code: 10001760

- **Grade 1:** Hair loss of <50% of normal for that individual that is not obvious from a distance but only on close inspection; a different hair style may be required to cover the hair loss but it does not require a wig or hair piece to camouflage
- **Grade 2:** Hair loss of >=50% normal for that individual that is readily apparent to others; a wig or hair piece is necessary if the patient desires to completely camouflage the hair loss; associated with psychosocial impact
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a decrease in density of hair compared to normal for a given individual at a given age and body location.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Body odor

MedDRA 28.0 LLT code: 10005901

- **Grade 1:** Mild odor; physician intervention not indicated; self care interventions
- **Grade 2:** Pronounced odor; psychosocial impact; patient seeks medical intervention
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an abnormal body smell resulting from the growth of bacteria on the body.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Dermatitis psoriasiform

MedDRA 28.0 LLT code: 10058675

- **Grade 1:** Present; topical intervention indicated
- **Grade 2:** oral intervention indicated
- **Grade 3:** IV intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by large, red, rounded plaques covered with thicker scales.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Dermatosis bullous

MedDRA 28.0 LLT code: 10012519

- **Grade 1:** Asymptomatic
- **Grade 2:** Painful blisters; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Blisters covering >50% BSA; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Blisters covering >75% BSA; associated with fluid or electrolyte abnormalities; ICU care or burn unit indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation of the skin characterized by the presence of bullae which are filled with fluid.
- **Navigational Note:** If infectious, consider Infections and infestations: Rash pustular or other site-specific Infections and infestations term.
- **CTCAE v6.0 Change:** Addition: Term

### Dry skin

MedDRA 28.0 LLT code: 10013786

- **Grade 1:** No associated erythema or pruritus
- **Grade 2:** Associated with erythema or pruritus; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by flaky and dull skin; the pores are generally fine, the texture is a papery thin texture.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2; Deletion: Grade 3

### Eczematous dermatitis

MedDRA 28.0 LLT code: 10014206

- **Grade 1:** Present; topical intervention indicated
- **Grade 2:** Oral intervention indicated
- **Grade 3:** IV intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by dry and itchy patches of skin involving the epidermis and superficial dermis and includes some scaling, crusting, or serous oozing.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Erythema multiforme

MedDRA 28.0 LLT code: 10015218

- **Grade 1:** Not associated with skin tenderness
- **Grade 2:** Associated with skin tenderness
- **Grade 3:** Associated with oral or genital erosions
- **Grade 4:** Associated with fluid or electrolyte abnormalities; ICU care or burn unit indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by target lesions (a pink-red ring around a pale center).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3, 4

### Erythroderma

MedDRA 28.0 LLT code: 10015277

- **Grade 1:** -
- **Grade 2:** Erythema covering >90% BSA without associated symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Erythema covering >90% BSA with associated symptoms (e.g., pruritus or tenderness); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Erythema covering >90% BSA with associated fluid or electrolyte abnormalities; ICU care or burn unit indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by generalized inflammatory erythema and exfoliation. The inflammatory process involves >90% of the body surface area.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, Definition

### Exfoliative dermatitis

MedDRA 28.0 LLT code: 10015665

- **Grade 1:** Present; topical intervention indicated
- **Grade 2:** oral intervention indicated
- **Grade 3:** IV intervention indicated
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by diffuse erythema and scaling involving > 90% of the body surface area.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Hair color changes

MedDRA 28.0 LLT code: 10055525

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by change in hair color or loss of normal pigmentation.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hair texture abnormal

MedDRA 28.0 LLT code: 10019049

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in the way the hair feels.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hirsutism

MedDRA 28.0 LLT code: 10020112

- **Grade 1:** In women, increase in length, thickness or density of hair in a male distribution that the patient is able to camouflage by periodic shaving, bleaching, or removal of hair
- **Grade 2:** In women, increase in length, thickness or density of hair in a male distribution that requires daily shaving or consistent destructive means of hair removal to camouflage; associated with psychosocial impact
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the presence of excess hair growth in women in anatomic sites where growth is considered to be a secondary male characteristic and under androgen control (beard, moustache, chest, abdomen).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hyperhidrosis

MedDRA 28.0 LLT code: 10020642

- **Grade 1:** Limited to one site (palms, soles, or axillae); self care interventions
- **Grade 2:** Involving >1 site; patient seeks medical intervention; associated with psychosocial impact
- **Grade 3:** Associated with electrolyte/hemodynamic imbalance
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive sweating.
- **Navigational Note:** Synonym: Night sweats, diaphoresis.
- **CTCAE v6.0 Change:** No Change

### Hyperkeratosis

MedDRA 28.0 LLT code: 10020649

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** Limiting self-care ADLs or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a thickening of the outer layer of the skin.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Hypertrichosis

MedDRA 28.0 LLT code: 10020864

- **Grade 1:** Increase in length, thickness or density of hair that the patient is either able to camouflage by periodic shaving or removal of hairs or is not concerned enough about the overgrowth to use any form of hair removal
- **Grade 2:** Increase in length, thickness or density of hair at least on the usual exposed areas of the body [face (not limited to beard/moustache area) plus/minus arms] that requires frequent shaving or use of destructive means of hair removal to camouflage; associated with psychosocial impact
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by hair density or length beyond the accepted limits of normal in a particular body region, for a particular age or race.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Hypohidrosis

MedDRA 28.0 LLT code: 10021013

- **Grade 1:** -
- **Grade 2:** Symptomatic; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Increase in body temperature; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by reduced sweating.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, 4

### Lichenoid dermatitis

MedDRA 28.0 LLT code: 10024441

- **Grade 1:** Present; topical intervention indicated
- **Grade 2:** oral intervention indicated
- **Grade 3:** IV intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a symmetric eruption of flat-topped, red or purple papules on the trunk and extremities.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Nail changes

MedDRA 28.0 LLT code: 10028689

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in the nails.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Nail discoloration

MedDRA 28.0 LLT code: 10028691

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a change in the color of the nail plate.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

### Nail loss

MedDRA 28.0 LLT code: 10049281

- **Grade 1:** Asymptomatic separation of the nail bed from the nail plate or nail loss
- **Grade 2:** Symptomatic separation of the nail bed from the nail plate or nail loss; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by loss of all or a portion of the nail.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2

### Nail ridging

MedDRA 28.0 LLT code: 10062283

- **Grade 1:** Present
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by vertical or horizontal ridges on the nails.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1

### Pain of skin

MedDRA 28.0 LLT code: 10033474

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the skin.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Palmar-plantar erythrodysesthesia syndrome

MedDRA 28.0 LLT code: 10054524

- **Grade 1:** Minimal skin changes or dermatitis (e.g., erythema, edema, or hyperkeratosis) without pain
- **Grade 2:** Skin changes (e.g., peeling, blisters, bleeding, fissures, edema, or hyperkeratosis) with pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe skin changes (e.g., peeling, blisters, bleeding, fissures, edema, or hyperkeratosis) with pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by redness, marked discomfort, swelling, and tingling in the palms of the hands or the soles of the feet. Also known as Hand-Foot Syndrome.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Papulovesicular rash

MedDRA 28.0 LLT code: 10033740

- **Grade 1:** Asymptomatic
- **Grade 2:** Associated with psychosocial impact; mild symptoms
- **Grade 3:** Covering >50% BSA; moderate or severe symptoms
- **Grade 4:** Blisters covering >75% BSA; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by an eruption consisting of papules (a small, raised pimple) and vesicles (a small fluid filled blister).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Photosensitivity

MedDRA 28.0 LLT code: 10034966

- **Grade 1:** Painless erythema
- **Grade 2:** Tender erythema
- **Grade 3:** Erythema with blistering; oral corticosteroid therapy indicated; pain control indicated (e.g., narcotics or NSAIDs)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by an increase in sensitivity of the skin to light.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Pruritus

MedDRA 28.0 LLT code: 10037087

- **Grade 1:** Mild or localized; topical intervention indicated
- **Grade 2:** Widespread and intermittent; skin changes from scratching (e.g., edema, papulation, excoriations, lichenification, oozing/crusts); oral intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Widespread and constant; systemic corticosteroid or immunosuppressive therapy indicated; limiting sleep or self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an intense itching sensation.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Purpura

MedDRA 28.0 LLT code: 10037549

- **Grade 1:** Combined area of lesions covering <10% BSA
- **Grade 2:** Combined area of lesions covering 10 - 30% BSA
- **Grade 3:** Combined area of lesions covering >30% BSA
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by hemorrhagic areas of the skin and mucous membrane. Newer lesions appear reddish in color. Older lesions are usually a darker purple color and eventually become a brownish-yellow color.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Pustular drug eruption

MedDRA 28.0 LLT code: 10082061

- **Grade 1:** Asymptomatic
- **Grade 2:** Associated with psychosocial impact; oral antibiotics or steroid indicated; local intervention indicated (e.g., topical antibiotic, antifungal, or antiviral); limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; IV antibiotic or steroid indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by the development of nonfollicular, sterile pustules on an erythematous base.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Addition: Term

### Rash maculo-papular

MedDRA 28.0 LLT code: 10037868

- **Grade 1:** Asymptomatic
- **Grade 2:** Mild symptoms
- **Grade 3:** Macules/papules covering >50% BSA; moderate or severe symptoms
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the presence of macules (flat) and papules (elevated). Also known as morbilliform rash, it is one of the most common cutaneous adverse events, frequently affecting the upper trunk, spreading centripetally and associated with pruritis.
- **Navigational Note:** Consider Skin and subcutaneous tissue disorders: Pustular drug eruption.
- **CTCAE v6.0 Change:** Addition: Grade 4, 5, Navigational Note; Clarification: Grade 1, 2, 3, Definition

### Scalp pain

MedDRA 28.0 LLT code: 10049120

- **Grade 1:** Mild pain
- **Grade 2:** Moderate pain; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe pain; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a sensation of marked discomfort in the skin covering the top and the back of the head.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Skin and subcutaneous tissue disorders - Other, specify

MedDRA 28.0 LLT code: 10040785

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Skin atrophy

MedDRA 28.0 LLT code: 10040799

- **Grade 1:** Associated with telangiectasias or changes in skin color
- **Grade 2:** Associated with striae or adnexal structure loss
- **Grade 3:** Associated with ulceration
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by the degeneration and thinning of the epidermis and dermis.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Skin hyperpigmentation

MedDRA 28.0 LLT code: 10040865

- **Grade 1:** Present
- **Grade 2:** Associated with psychosocial impact
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by darkening of the skin due to excessive melanin deposition.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2

### Skin hypopigmentation

MedDRA 28.0 LLT code: 10040868

- **Grade 1:** Present
- **Grade 2:** Associated with psychosocial impact
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by loss of skin pigment (e.g., vitiligo).
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2

### Skin induration

MedDRA 28.0 LLT code: 10051837

- **Grade 1:** Mild induration, able to move skin parallel to plane (sliding) and perpendicular to skin (pinching up)
- **Grade 2:** Moderate induration, able to slide skin, unable to pinch skin; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe induration; unable to slide or pinch skin; limiting joint or orifice movement (e.g., mouth, anus); limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Generalized; associated with signs or symptoms of impaired breathing or feeding
- **Grade 5:** Death
- **Definition:** A disorder characterized by an area of hardness in the skin.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Skin ulceration

MedDRA 28.0 LLT code: 10040947

- **Grade 1:** Combined area of ulcers <1 cm; nonblanchable erythema of intact skin with associated warmth or edema
- **Grade 2:** Combined area of ulcers 1 - 2 cm; partial thickness skin loss involving skin or subcutaneous fat
- **Grade 3:** Combined area of ulcers >2 cm; full-thickness skin loss involving damage to or necrosis of subcutaneous tissue that may extend down to fascia
- **Grade 4:** Any size ulcer with extensive destruction, tissue necrosis, or damage to muscle, bone, or supporting structures with or without full thickness skin loss
- **Grade 5:** Death
- **Definition:** A disorder characterized by a circumscribed, erosive lesion on the skin.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Stevens-Johnson syndrome

MedDRA 28.0 LLT code: 10042033

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Skin sloughing covering <10% BSA
- **Grade 4:** Skin sloughing covering >=10% BSA; life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by less than 10% total body skin area separation of dermis. The syndrome is thought to be a hypersensitivity complex affecting the skin and the mucous membranes.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3, 4

### Subcutaneous emphysema

MedDRA 28.0 LLT code: 10042344

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by air in the subcutaneous tissue.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3

### Telangiectasia

MedDRA 28.0 LLT code: 10043189

- **Grade 1:** Present
- **Grade 2:** Associated with psychosocial impact
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by local dilatation of small vessels resulting in red discoloration of the skin or mucous membranes.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2

### Toxic epidermal necrolysis

MedDRA 28.0 LLT code: 10044223

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** -
- **Grade 4:** Skin sloughing covering >=30% BSA with associated symptoms (e.g., erythema, purpura, or epidermal detachment); life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by greater than 30% total body skin area separation of dermis. The syndrome is thought to be a hypersensitivity complex affecting the skin and the mucous membranes.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 4

### Urticaria

MedDRA 28.0 LLT code: 10046735

- **Grade 1:** Topical intervention indicated
- **Grade 2:** Oral intervention indicated
- **Grade 3:** IV intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an itchy skin eruption characterized by wheals with pale interiors and well-defined red margins.
- **Navigational Note:** Consider Immune system disorders: Allergic reaction, Anaphylaxis.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 1, 2, 3

## Social circumstances

### Social circumstances - Other, specify

MedDRA 28.0 LLT code: 10041244

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

## Surgical and medical procedures

### Surgical and medical procedures - Other, specify

MedDRA 28.0 LLT code: 10042613

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

## Vascular disorders

### Arterial thromboembolism

MedDRA 28.0 LLT code: 10073529

- **Grade 1:** -
- **Grade 2:** -
- **Grade 3:** Urgent intervention indicated
- **Grade 4:** Life-threatening consequences; hemodynamic or neurologic instability; organ damage; loss of extremity(ies)
- **Grade 5:** Death
- **Definition:** A disorder characterized by occlusion of an arterial vessel by a blood clot that develops in an artery.
- **Navigational Note:** Consider Nervous system disorders: Stroke, Transient ischemic attacks for CNS-related events or Cardiac disorders: Myocardial infarction.
- **CTCAE v6.0 Change:** Clarification: Navigational Note

### Capillary leak syndrome

MedDRA 28.0 LLT code: 10007196

- **Grade 1:** Asymptomatic
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms
- **Grade 4:** Life-threatening consequences
- **Grade 5:** Death
- **Definition:** A disorder characterized by leakage of intravascular fluids into the extravascular space. This syndrome is observed in patients who demonstrate a state of generalized leaky capillaries following shock syndromes, low-flow states, ischemia-reperfusion injuries, toxemias, medications, or poisoning. It can lead to generalized edema and multiple organ failure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 3, 4

### Cyanosis

MedDRA 28.0 LLT code: 10011703

- **Grade 1:** -
- **Grade 2:** Present
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a bluish discoloration of the skin and/or mucous membranes.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** SOC change

### Flushing

MedDRA 28.0 LLT code: 10016825

- **Grade 1:** Mild symptoms; clinical or diagnostic observations only
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Symptomatic, associated with hypotension and/or tachycardia; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by episodic reddening of the skin, especially face, neck, or chest.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 1, 2, 3

### Hematoma

MedDRA 28.0 LLT code: 10019428

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Minimally invasive evacuation or aspiration indicated
- **Grade 3:** Transfusion; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a localized collection of blood, usually clotted, in an organ, space, or tissue, due to a break in the wall of a blood vessel.
- **Navigational Note:** Report subdural and epidural hematoma under Nervous system disorders: Intracranial hemorrhage.
- **CTCAE v6.0 Change:** Addition: Navigational Note

### Hot flashes

MedDRA 28.0 LLT code: 10020407

- **Grade 1:** Mild symptoms; intervention not indicated
- **Grade 2:** Moderate symptoms; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by an uncomfortable and temporary sensation of intense body warmth, flushing, sometimes accompanied by sweating upon cooling.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Hypertension

MedDRA 28.0 LLT code: 10020772

- **Grade 1:** -
- **Grade 2:** Adult: Systolic BP 140 - 159 mmHg or diastolic BP 90 - 99 mmHg; recurrent or persistent;<br>Pediatric and adolescent: Recurrent or persistent (>=24 hrs) BP >ULN; monotherapy indicated; systolic and /or diastolic BP between the 95th percentile and 5 mmHg above the 99th percentile;<br>Adolescent: Systolic between 130 - 139 or diastolic between 80 - 89 even if <95th percentile
- **Grade 3:** Adult: Systolic BP 160 - 179 mmHg or diastolic BP 100 - 109 mmHg persisting over 1 hour; SBP >140 and plus either increase in SBP >20 mmHg or increase MAP >15 mmHg from baseline;<br>Pediatric and adolescent: Systolic and/or diastolic >5 mmHg above the 99th percentile
- **Grade 4:** Adult and Pediatric: SBP≥180 or DBP ≥110 mmHg persisting over 1 hour; BP associated with acute hypertension mediated organ damage; life-threatening consequences (e.g., malignant hypertension, transient or permanent neurologic deficit, hypertensive crisis); urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a pathological increase in blood pressure.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, 4; Deletion: Grade 1

### Hypotension

MedDRA 28.0 LLT code: 10021097

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Non-urgent medical intervention indicated
- **Grade 3:** Medical intervention indicated; hospitalization indicated
- **Grade 4:** Life-threatening consequences and urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by a blood pressure that is below the normal expected for an individual in a given environment.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Lymph leakage

MedDRA 28.0 LLT code: 10065773

- **Grade 1:** -
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by the loss of lymph fluid into the surrounding tissue or body cavity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Lymphedema

MedDRA 28.0 LLT code: 10025233

- **Grade 1:** Trace thickening or faint discoloration
- **Grade 2:** Marked discoloration; leathery skin texture; papillary formation; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe symptoms; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by excessive fluid collection in tissues that causes swelling.
- **Navigational Note:** Record final diagnosis/cause once determined.
- **CTCAE v6.0 Change:** Addition: Navigational Note; Clarification: Grade 2, 3

### Lymphocele

MedDRA 28.0 LLT code: 10048642

- **Grade 1:** Asymptomatic; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Symptomatic; medical intervention indicated
- **Grade 3:** Severe symptoms; invasive intervention indicated
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a cystic lesion containing lymph.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Peripheral ischemia

MedDRA 28.0 LLT code: 10034578

- **Grade 1:** -
- **Grade 2:** Brief (<24 hrs) episode of ischemia managed medically and without permanent deficit; claudication
- **Grade 3:** Prolonged (>=24 hrs) or recurring symptoms and/or invasive intervention indicated; pain at rest
- **Grade 4:** Life-threatening consequences; major tissue loss; urgent operative intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by impaired circulation to an extremity.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3, 4

### Phlebitis

MedDRA 28.0 LLT code: 10034879

- **Grade 1:** -
- **Grade 2:** Present
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by inflammation of the wall of a peripheral vein associated with an intravenous line.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Definition

### Superficial thrombophlebitis

MedDRA 28.0 LLT code: 10042554

- **Grade 1:** -
- **Grade 2:** Present
- **Grade 3:** -
- **Grade 4:** -
- **Grade 5:** -
- **Definition:** A disorder characterized by a blood clot and inflammation involving a superficial vein of the extremities.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Superior vena cava syndrome

MedDRA 28.0 LLT code: 10042569

- **Grade 1:** Asymptomatic; incidental finding of SVC thrombosis
- **Grade 2:** Symptomatic; medical intervention indicated (e.g., anticoagulation, radiation or chemotherapy)
- **Grade 3:** Severe symptoms; multi-modality intervention indicated (e.g., anticoagulation, chemotherapy, radiation, stenting)
- **Grade 4:** Life-threatening consequences; urgent multi-modality intervention indicated (e.g., lysis, thrombectomy, surgery)
- **Grade 5:** Death
- **Definition:** A disorder characterized by obstruction of the blood flow in the superior vena cava. Signs and symptoms include swelling and cyanosis of the face, neck, and upper arms, cough, orthopnea and headache.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Vascular disorders - Other, specify

MedDRA 28.0 LLT code: 10047065

- **Grade 1:** Asymptomatic or mild symptoms; clinical or diagnostic observations only; intervention not indicated
- **Grade 2:** Moderate; minimal, local or noninvasive intervention indicated; limiting instrumental ADL or mild/moderate impact on age-appropriate normal daily activity (pediatric)
- **Grade 3:** Severe or medically significant but not immediately life-threatening; hospitalization or prolongation of existing hospitalization indicated; limiting self-care ADL or severe impact on age-appropriate normal daily activity (pediatric)
- **Grade 4:** Life-threatening consequences; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** -
- **Navigational Note:** -
- **CTCAE v6.0 Change:** Clarification: Grade 2, 3

### Vasculitis

MedDRA 28.0 LLT code: 10047115

- **Grade 1:** Asymptomatic, intervention not indicated
- **Grade 2:** Moderate symptoms, medical intervention indicated
- **Grade 3:** Severe symptoms, medical intervention indicated (e.g., steroids)
- **Grade 4:** Life-threatening consequences; evidence of peripheral or visceral ischemia; urgent intervention indicated
- **Grade 5:** Death
- **Definition:** A disorder characterized by inflammation involving the wall of a vessel.
- **Navigational Note:** -
- **CTCAE v6.0 Change:** No Change

### Venous thromboembolism

MedDRA 28.0 LLT code: 10066899

- **Grade 1:** Medical intervention not indicated (e.g., superficial thrombosis)
- **Grade 2:** Medical intervention indicated
- **Grade 3:** Urgent medical intervention indicated
- **Grade 4:** Life-threatening consequences with hemodynamic or neurologic instability
- **Grade 5:** Death
- **Definition:** A disorder characterized by occlusion of a vessel by a thrombus that has migrated from a distal site via the blood stream (for example, deep vein thrombosis (DVT), pulmonary embolism (PE), etc.).
- **Navigational Note:** Consider Nervous system disorders: Stroke, Transient ischemic attacks for CNS-related events. Use Vascular disorders: Arterial thromboembolism for arterial thrombi. Use Injury, poisoning and procedural complications: Vascular access complication if related to a catheter.
- **CTCAE v6.0 Change:** Addition: Term
