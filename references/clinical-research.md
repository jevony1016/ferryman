# Clinical research context

The clinical research pack of this skill: for people who work on clinical trials (CRAs, CRCs, investigators, study nurses, project and trial managers, QA and auditors, sponsor clinical operations, safety and regulatory staff, ethics committee staff) and for their career decisions.

Read this file whenever a request involves clinical research, in any mode. It adds to the general method; it does not replace it. Regulation texts are in [regulations/](regulations/README.md).

---

## 1. Safety first, analysis second

If the conversation reveals something that needs action **now** (an SAE not yet reported, a participant at immediate risk, an unblinding need, a dosing error), tell the user to act first under the protocol and SOP: report, escalate, protect the participant. Analysis and CAPA come after. Never let Step 0 questioning delay a safety action.

## 2. Hard constraints in clinical research

These are never "first-principled away". A rebuilt option that breaks any of them is not an option.

- The rights, safety, and well-being of trial participants.
- Informed consent, obtained and documented as required.
- Reliability of trial data and source records.
- Applicable regulatory requirements, in the version that applies.
- The approved protocol. It changes only through an amendment with the required approvals. A soft constraint inside the protocol is still binding until amended.
- Participant privacy and confidentiality.

What *can* be questioned: habits, "how this site always does it", sponsor templates used beyond their purpose, monitoring intensity chosen by custom rather than risk, assumptions about what a regulation says.

## 3. Which document actually says it?

Before treating a rule as a premise, find its source and exact wording. Tag it with the level it comes from.

| Level | Examples | How to use |
|---|---|---|
| Law / regulation | China: GCP (2026 revision); US: 21 CFR 312, 50, 56 | Hard constraint. Quote the article from [regulations/](regulations/README.md). |
| International guideline | ICH E6(R3), E2A | Binding where adopted by the regulator; quote the section. |
| Approved protocol, IB | Reporting windows, visit windows, SAE definitions specific to the protocol | Hard for this trial until amended. |
| Sponsor procedure / plan | Safety management plan, monitoring plan, sponsor SOPs | Binding by agreement; can be discussed with the sponsor. |
| Institution / site SOP | Site workflows, delegation, back-up | Binding at the site; changeable through the site's process. |
| Habit | "We always…", templates, "the auditor will want…" | Soft. Check what it rests on. |

Checks that catch most errors:

1. **Wording.** Quote the text; do not paraphrase it as stricter or looser than it is. "Immediately" is not "within 24 hours"; "should" is not "must". Many specific windows come from the protocol, not the regulation.
2. **Version and date.** Which version applied when the event happened? The 2026 revision of China's GCP took effect on 2026-09-01; events before that date may fall under the 2020 version. Check the transition rules if this matters.
3. **Jurisdiction.** A multi-country trial can be subject to several rule sets at once; say which one you are quoting.
4. **The clock.** For any deadline: who must act, starting from when (occurrence or awareness, and whose awareness), to whom, in what form (for example written), within what time.
5. **Responsibility.** Who holds the obligation (principal investigator, institution, sponsor, service provider), and what has been delegated in writing.

Known points that need interpretation (flag them, do not resolve them):

- **Delegating safety reporting.** China GCP 2026 Article 20 (last sentence) says the principal investigator's formal reports to the ethics committee, institution, and sponsor 原则上不得授权; ICH E6(R3) 2.7.2(d) allows delegating safety reporting *activities* to qualified site staff while the investigator retains overall responsibility. Quote both and leave the reading to the sponsor or QA.
- **"Immediately" vs a protocol window.** Whether a report within the protocol's window also counts as "immediately" is an interpretation question.

Do not give a final regulatory or legal interpretation. When the answer depends on interpretation, say so and recommend confirming with the sponsor, QA, or regulatory affairs.

## 4. Common decision types

Starting points only; choose methods by the actual symptom.

| Decision | Start with | Watch for |
|---|---|---|
| Recurring deviation, late safety report, audit finding → CAPA | Break the delay or failure along its chain (cost-component breakdown); repeated why on the failing link; assumption audit on "retrain" | Root cause written as a label ("low awareness"); same fix as last time; no denominator in the effectiveness check |
| Slow enrolment | Break the funnel: identified → pre-screened → screened → consented → randomised; find the narrowest step | Copying another site's tactics without its patient population |
| Monitoring approach, SDV extent | Assumption audit: is the intensity set by risk or by habit? | E6(R3) asks for proportionate, risk-based approaches; the monitoring plan still binds |
| Re-consent after an ICF update | Find the rule first (regulation, protocol, ethics committee decision) | Hard constraint; not a first-principles question once the rule is clear |
| Site selection, feasibility | Analogy removal: past performance under a different protocol is a lead, not a fact | Survivorship: only remembering the sites that did well |
| Query backlog, data cleaning | Cost-component breakdown by query type and source | Fixing volume instead of the upstream cause |
| Workload, delegation, staffing | Cost-component breakdown of hours; assumption audit on "only I can do this" | Delegation must be documented and within role |
| Career moves (CRC → CRA, CRO → sponsor, leaving the field) | See [value-decisions.md](value-decisions.md) | Treating a common career script as a base fact |

## 5. CAPA vocabulary

The rule behind it: China GCP 2026 Article 43(2) and ICH E6(R3) 3.12.2 both require, for noncompliance that significantly affects or may affect participants' rights and safety or the reliability of results, a root cause analysis and appropriate corrective and preventive actions; E6(R3) adds "confirm their adequacy", and Article 43(2) adds a timely written report to the ethics committee. Quote the exact text from [regulations/](regulations/README.md) when it matters.

- **Correction**: fixing this instance (report the late SAE, document the reason).
- **Corrective action**: removing the cause so this does not recur in this trial or site.
- **Preventive action**: preventing a similar problem elsewhere (other trials, other sites).
- **Effectiveness check**: a metric with a denominator (out of how many events, over what period) and a defined starting point. With very few events, report "not seen again yet", not "effective".
- **Root cause**: a mechanism at a specific step. "Insufficient training" is a root cause only if a knowledge gap was actually shown.

## 6. Privacy

Never ask for, repeat, or output information that identifies a participant (name, ID card number, address, medical record number, photos). Use the trial participant identification code or "Participant A". If the user pastes identifiable data, do not repeat it and suggest removing it.

---

Terminology rules and tables are in [terminology.md](terminology.md).
