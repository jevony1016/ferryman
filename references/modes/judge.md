# Mode: Judge — does this rule apply to these facts?

Use this mode when the user asks whether a **rule or criterion applies to a set of facts**. Any domain: "Does my contract let me leave before the notice period?", "Do I qualify for this subsidy?", "Is this refund policy being applied correctly?"; in clinical research "Is this an SAE?", "What CTCAE grade is this?", "Is this an important protocol deviation?", "Do we need to re-consent?", "Is this reportable, and by when?"

A judgment has three parts. Keep them visibly separate in the answer:

1. **The rule**: quoted verbatim from the governing document, with version.
2. **The facts**: what the user told you, and what is missing.
3. **The match**: which criterion the facts meet or do not meet, and how sure that is.

Then say **who makes the final call**. AI output here is decision support only.

## General protocol

1. Safety check first (SKILL.md; for clinical research [clinical-research.md §1](../clinical-research.md)).
2. **Identify the governing document** and get its text: the contract, policy, law, official notice, the user's own paperwork; in clinical research the regulation, guideline, protocol (with version), or sponsor plan. More specific documents often define their own criteria (a contract's own definitions; a protocol's own SAE rules or deviation categories). Ask for them; do not assume. If you cannot see the text, say the judgment cannot be confirmed and what text is needed.
3. List the facts needed to apply the criteria. Ask for the missing ones (Socratic rules apply, max 3 per round). Never ask for identifying details about other people.
4. Apply the criteria one by one. Show which ones are met, not met, or cannot be determined.
5. Conclusion: "meets / does not meet / cannot be determined without X". Never round "cannot be determined" up to a conclusion.
6. Who decides (the other party, the authority, a professional; in clinical research usually the investigator, sponsor, or ethics committee), and what to do next.
7. Adversarial review with an independent subagent before showing (sections C, D and F of the checklist at minimum; for clinical research also section I).

---

## Clinical research judgments

Read [clinical-research.md](../clinical-research.md) and [terminology.md](../terminology.md) first.

### SAE: serious or not?

- **Quote the definition from the governing source.** China GCP 2026 does not define SAE itself: Article 54 defines five terms and says other terms "可参考ICH E6（R3）中文版术语表". So for China, quote the CDE glossary entry (`../regulations/cn-ich-e6r3-glossary.md`, search 严重不良事件). Other sources: ICH E6(R3) Glossary (`ich-e6-r3.md`); ICH E2A II.B (`ich-e2a.md`, `cn-ich-e2a.md`); 21 CFR 312.32(a) for US INDs; EU CTR Article 2 for EU trials. Use the one that applies; show others only if useful.
- Check each seriousness criterion in the quoted definition against the facts. Note the protocol's own rules (for example planned hospitalisations, disease-progression events, endpoint events).
- **Seriousness is not severity.** Quote E2A II.B rather than paraphrasing: "The term "severe" is often used to describe the intensity (severity) of a specific event … This is not the same as "serious," which is based on patient/event outcome or action criteria … Seriousness (not severity) serves as a guide for defining regulatory reporting obligations." (Chinese: `cn-ich-e2a.md`, the paragraph beginning "“重度”一词常用于描述".) A CTCAE grade is severity.
- If it is serious: the reporting clock, from the governing text (for example GCP 2026 Article 26(2) "在获知后立即", with its exception for SAEs that the protocol or other documents such as the IB say need not be reported immediately; E6(R3) 2.7.2(b)). A window in hours usually comes from the protocol, and is a protocol requirement. Expedited reporting to regulators (SUSARs) is the sponsor's obligation: see the CDE expedited reporting standard, E2A, 21 CFR 312.32.
- Who decides: the investigator assesses seriousness and causality; the sponsor also assesses (GCP 2026 Article 44).

### CTCAE grading

1. **Which version?** The protocol states it (for example v5.0 or v6.0). Do not mix versions. Files: `../regulations/ctcae-v6.md` and `../regulations/ctcae-v5.md`; official v5.0-to-v6.0 mapping and errata: `../regulations/ctcae-v6-vs-v5-changes.md`.
2. **Find the term.** Search `### <term>` in the right version (each term is a MedDRA LLT; the file gives the code). If no term matches, say so; each version has "Other, specify" terms in many SOCs. Do not force a near term. Read the term's Navigational Note: it may point to a different term.
3. **Quote the grade definitions** for that term verbatim (Grades 1–5 as given; a single dash "-" means that grade is not available for the term), plus the Definition and Navigational Note.
4. **Use the general instructions at the top of the version file** and quote them when they matter: the general grading guideline, "A Semi-colon indicates 'or' within the description of the grade", the meaning of "-", and the definitions of instrumental and self-care ADL (and the paediatric wording in v6.0).
5. **Match the facts.** Many grades depend on facts the user may not have given: measured values with units relative to ULN, LLN, or baseline; symptoms; whether and what intervention was indicated; limits on ADL; hospitalisation. List what is missing and ask.
6. **Answer**: the grade whose description the facts meet, or the candidate grades and the fact that would decide between them. The CTCAE files do not contain a rule for choosing when facts fall between grades; do not invent one. If the protocol or sponsor gives grading conventions, use and quote them.
7. **Grade vs seriousness**: a grade is severity. Whether the event is an SAE is a separate judgment (see above); Grade 3 or 4 does not by itself make an event serious, and an SAE can have a low grade.
8. **Who decides**: the investigator grades the event. Say so in every grading answer.
9. Never grade from a lab value alone if the term's criteria also need clinical information.
10. **v6.0 vs v5.0 questions** ("what changed for this term?"): quote the official mapping file only; do not write your own comparison.

### Protocol deviation: deviation, important deviation, or neither?

- Quote the governing text: China GCP 2026 Article 23 (uses 方案偏离 and 重要方案偏离); E6(R3) (search "deviation" in `ich-e6-r3.md`, including the glossary and 2.5); the protocol or sponsor's deviation plan for categories and definitions.
- Ask for the protocol requirement that was not followed (section and exact wording), the facts, and the effect on participant rights, safety, and well-being and on the reliability of data.
- Classification categories usually come from the sponsor's plan. If the user does not have it, say the category cannot be confirmed and give what the regulation itself requires (documenting, explaining important deviations, CAPA, reporting to the ethics committee and sponsor, as quoted).

### Re-consent, reportability, timelines, and other "does the rule apply" questions

Same protocol: find the rule (often the ethics committee's decision or the protocol, not only GCP), quote it, list the facts, match, say who decides. If the honest answer is "the ethics committee decides", say that.

---

## Output for judge mode

```
Conclusion: meets / does not meet / cannot be determined without …
Rule: "…" (source, version, article or clause)
Facts given → criterion by criterion
Missing facts that would change the answer
Who decides; what to do next
Review log (short)
```

For newcomers, add one plain-language line on the reasoning; for experienced users keep it to the essentials.
