# ferryman

English | [简体中文](README.zh-CN.md)

> A ferryman, not a judge: it lays out the facts, the rules, the reasoning, and the options, and gets you across. You make the call.

An agent skill for **first-principles thinking on any question**: decisions (career, money, where to live, how to run a team), problems and root causes, learning a topic from the ground up, judging whether facts meet a rule, and drafting documents.

It also carries a **clinical research pack**: verbatim regulation texts, official terminology, and ready methods for SAE, CTCAE, deviation, and CAPA questions. The pack loads only when a question involves clinical research.

It answers in whatever language you write in.

## The one principle

Trace every answer to what it actually rests on: an observable fact, the exact text of a rule, a logical necessity, or your own priorities. Keep these apart from experience, consensus, authority, and guesses. In clinical research this becomes: regulation, protocol, SOP, or habit, quoted verbatim.

## Four modes

| You want to… | Mode | Clinical research examples |
|---|---|---|
| find a term, a definition, the exact wording of a rule | **Lookup** | "SUSAR in Chinese, and where is it defined?" |
| understand a topic from the ground up, or practise | **Learn** | "I'm a new CRC, quiz me on SAE reporting" |
| know whether facts meet a rule or criterion | **Judge** | "Is this an SAE?", "What CTCAE v6.0 grade is this?" |
| decide, solve a problem, find a root cause, write something | **Do** | "Write a CAPA for a late SAE report" |

The skill picks the mode and your level (newcomer or experienced) and tells you what it assumed, so you can correct it.

## What it does differently

1. **Safety first.** If something needs action now (a health or safety risk, a deadline about to pass; in clinical research an unreported SAE), it says so before any analysis.
2. **Gets the full picture.** Socratic questions, at most three per round, each with a reason. The questions themselves challenge "everyone does…", "the rule says…", "it has to be…".
3. **Finds which document actually says it.** Rules are quoted only from a text it can see; otherwise it says "not verified". A protocol's "within 24 hours" is not the same as a regulation's "immediately".
4. **Triages.** Tells you when usual practice is enough, and when a question is simply a rule lookup.
5. **Picks a method by symptom.** Four ways to break a problem down (repeated why, cost-component breakdown, assumption audit, analogy removal) and four ways to rebuild, inside the hard constraints.
6. **Reviews itself adversarially before you see anything.** Every Learn, Judge, and Do answer goes through one round of review by an independent subagent (when the host supports it) that sees only your messages and the draft: quotes against sources, root causes that are only labels, metrics without a denominator, sycophancy, drift toward the common answer. Lookup answers are checked word for word against the source.
7. **Hands the decision back to you.** Your values are yours; it makes them explicit and does not rank them.

Decision flow (Do mode):

```
0 Safety check + full picture → 1 Triage → 2 Break down → 3 Rebuild → 4 Verify → 5 Adversarial review → 6 Report
```

Default is **report mode**. Say "think it through with me" for **thinking-partner mode**, one step at a time.

## The clinical research pack

Verbatim texts in [references/regulations/](references/regulations/README.md), each with its official source link, version, and retrieval date:

- **China**: GCP (2026 revision); CDE expedited safety reporting standard; Drug Administration Law; Drug Registration Regulation; clinical trial institution regulation; ethics review measures (2023); Human Genetic Resources Regulation and its implementing rules.
- **ICH**: E6(R3) (English) and the CDE Chinese glossary; E2A, E8(R1), E9, E9(R1), each in English and Chinese.
- **CTCAE**: v6.0 and v5.0, plus NCI's official v5.0-to-v6.0 mapping and errata.
- **US**: 21 CFR 312.3, 312.32, 312 Subpart D, Part 50 Subpart B, Part 56, Part 11.
- **EU**: Regulation (EU) No 536/2014, selected provisions (Articles 1–3, 28–35, 40–48, 52, Annex III).

Not included yet: China's revised Drug Administration Law Implementing Regulation (effective 2026-05-15) and China GCP 2020. See the regulations README for details.

Terminology rules ([references/terminology.md](references/terminology.md)): Chinese follows the China GCP 2026 text, then the CDE E6(R3) glossary; English follows the ICH E6(R3) glossary.

## Install

**Claude Code**

```bash
git clone https://github.com/jevony1016/ferryman.git
cp -r ferryman ~/.claude/skills/ferryman
```

Then just ask, for example: "Use first principles: should I take this job offer?" or "Is this an SAE?"

**Other skill-aware agents**: copy the folder into the agent's skills directory. `SKILL.md` is the entry point; files in `references/` are loaded on demand.

## Files

```
SKILL.md                                 entry: safety check, domain check, mode, level, shared rules
references/modes/                        lookup.md, learn.md, judge.md, do.md
references/socratic-questioning.md       how to ask, question bank
references/decomposition-methods.md      four ways to break down
references/rebuilding-methods.md         four ways to rebuild
references/adversarial-review.md         pre-output review checklist
references/value-decisions.md            career, family, and other value-laden decisions
references/report-template.md            output structure
references/clinical-research.md          clinical pack: hard constraints, rule hierarchy, decision types, CAPA, privacy
references/terminology.md                clinical pack: official terms in Chinese and English
references/regulations/                  clinical pack: verbatim regulation texts (see its README)
examples/general-decision-buy-a-car.zh.md     an everyday decision: unpack "everyone says" (Chinese, Standard)
examples/sae-late-reporting-capa.zh.md        a "late SAE report" that was not late (Chinese, Standard)
examples/light-triage-follow-up-letter.en.md  triage ends early (English, Light)
```

## Sources and credits

**Thinking method**, distilled in my own words from two Chinese books on first-principles thinking (no text reproduced):

- 武从文 (Wu Congwen), *第一性原理：普通人的人生高效手册* (2026): the four decomposition and four rebuilding methods, three tests for a first principle, five common traps, and when analysis is not worth its cost.
- 李善友 (Li Shanyou), *第一性原理* (Posts & Telecom Press, 2021): hidden assumptions behind induction and deduction, conformity effects, and the internal / external / over-time consistency checks.

**Regulations and guidelines** in `references/regulations/` are reproduced verbatim from official sources; the official published versions prevail. Reuse terms are quoted in each file:

- ICH guidelines: reproduced under ICH's notice, quoted in each ICH file.
- CTCAE: originally published by the National Cancer Institute. Source: [NCI DCTD, CTCAE and Adverse Event Reporting](https://dctd.cancer.gov/research/ctep-trials/for-sites/adverse-events).
- EU Regulation 536/2014: Source: EUR-Lex, https://eur-lex.europa.eu, © European Union, 1998–2026.
- 21 CFR: US government work, from eCFR.
- Chinese laws, regulations, and official texts: from the issuing authorities' websites.

Design ideas were also learned from these open-source skills: [awesome-skills/first-principles-skill](https://github.com/awesome-skills/first-principles-skill), [huangmingche/first-principles-skill](https://github.com/huangmingche/first-principles-skill), [jiaosl/first-principles-reasoning-skill](https://github.com/jiaosl/first-principles-reasoning-skill), [swapnildahiphale/first-principles-thinking-skill](https://github.com/swapnildahiphale/first-principles-thinking-skill), [reshadat/first-principles-destructor](https://github.com/reshadat/first-principles-destructor).

This project is not affiliated with the book authors, publishers, regulators, ICH, NCI, the European Union, or any employer.

## Disclaimer

Thinking and decision support only. It is not a medical, legal, financial, or regulatory opinion. In clinical research, follow your protocol, SOPs, and applicable regulations; final interpretation belongs to the sponsor, QA, ethics committee, or regulator. Never enter identifiable information about trial participants or other people.

## License

The skill's own text is [MIT](LICENSE). Regulation and guideline texts in `references/regulations/` keep their original status and terms, as stated in each file.
