<div align="center">

# ⛵ ferryman

**A ferryman, not a judge.**<br>
A first-principles thinking skill for AI agents: it lays out the facts, the rules, the reasoning, and the options, and gets you across. You make the call.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Agent Skill](https://img.shields.io/badge/agent-skill-8A2BE2)
![Claude Code](https://img.shields.io/badge/Claude_Code-ready-D97757)
![Any language](https://img.shields.io/badge/replies_in-your_language-2EA44F)

English | [简体中文](README.zh-CN.md)

</div>

---

## Why

Most bad answers, from people or from AI, don't come from bad logic. They come from a bad starting point: a habit treated as a rule, hearsay treated as a fact, someone else's situation treated as yours, or "everyone says so" treated as evidence.

ferryman makes the AI do the opposite. **Every answer is traced back to what it actually rests on:**

| Foundation | Example |
|---|---|
| an observable fact | the price you were quoted, the date in the log |
| the exact text of a rule | the clause in your contract, the article in the regulation |
| a logical necessity | what must follow if the above are true |
| your own priorities | what you care about, which only you can say |

Everything else (experience, consensus, authority, guesses) is labelled as such and checked before it is used.

## What you can ask

| Mode | You want to… | For example |
|---|---|---|
| 🔍 **Lookup** | find a term, a definition, the exact wording | "What does the notice-period clause in my contract actually say?" |
| 📚 **Learn** | understand something from the ground up, then practise | "Explain compound interest from scratch, then quiz me." |
| ⚖️ **Judge** | know whether facts meet a rule or criterion | "Do I qualify for this subsidy, based on its published conditions?" |
| 🛠️ **Do** | decide, solve a problem, find a root cause, write something | "Should I take this job offer?" · "Why does our weekly report always ship late?" · "Draft a complaint email." |

It picks the mode and your level (newcomer or experienced), says what it assumed, and lets you correct it.

## How it thinks

```
0  Safety check + the full picture   ← Socratic questions, max 3 per round, each with a reason
1  Triage                            ← is deep analysis even worth it here?
2  Break down                        ← what does each premise rest on?
3  Rebuild                           ← 2–3 options inside the hard constraints
4  Verify                            ← reasoning chain, failure conditions, smallest test
5  Adversarial review                ← an independent reviewer attacks the draft
6  Report                            ← the decision goes back to you
```

- **Asks before it answers.** Missing information is filled with questions, and the questions themselves challenge "everyone does…", "the rule says…", "it has to be…".
- **Knows when to stop.** If usual practice is good enough, it says so and stops. Not everything needs first principles.
- **Picks a method by symptom.** Four ways to break a problem down (repeated why, cost-component breakdown, assumption audit, analogy removal) and four ways to rebuild.
- **Quotes, never paraphrases from memory.** Rules are quoted only from a text it can see; otherwise it says "not verified" and tells you where to check.
- **Reviews itself before you see anything.** Every Learn, Judge, and Do answer goes through one round of review by an independent subagent that sees only your messages and the draft. It hunts for invented facts, root causes that are only labels ("lack of awareness"), metrics without a denominator, telling you what you want to hear, and drifting toward the most common answer.
- **Leaves your values to you.** It makes your priorities explicit and shows how the answer changes with them ("if you care more about A… if B…"). It never ranks them for you.

Default is **report mode**. Say "think it through with me" for **thinking-partner mode**, one step at a time.

## A taste

> **You:** Use first principles: should I buy a car? Everyone says you need one once you have a kid.
>
> **ferryman:** Three questions first, because the answers change the conclusion: which trips would the car be for, how often and how far? How do you make those trips now, and what does each cost? Any hard limits, like parking or budget?
>
> *…after your answers…*
>
> "Everyone says" is tagged as **consensus** and set aside; your four weekend trips a week are the real need. With your numbers, the parking space alone costs about 70% of what you now spend on taxis, before insurance or depreciation (which it asks you to look up rather than guess). Three options, the strongest argument against its own suggestion, a cheap two-to-three-month test, and then: *if you care more about cost and flexibility…; if you care more about being able to leave anytime with the baby…*

Full conversation: [examples/general-decision-buy-a-car.zh.md](examples/general-decision-buy-a-car.zh.md) (Chinese).

## Install

**Claude Code**

```bash
git clone https://github.com/jevony1016/ferryman.git ~/.claude/skills/ferryman
```

Then just ask: *"Use first principles: …"*, *"Help me decide…"*, *"Explain … from scratch"*, *"Quiz me on…"*.

**Other agents that support skills**: copy the folder into the agent's skills directory. `SKILL.md` is the entry point; files in `references/` are loaded only when needed.

## 🧪 Bonus: the clinical research pack

ferryman was built by someone who works in clinical research, so it ships with a pack for that field. It loads **only** when a question involves clinical trials:

- **Verbatim regulation texts**, each with its official source link, version, and retrieval date: China GCP (2026) and core NMPA rules, ICH E6(R3) / E2A / E8(R1) / E9 / E9(R1), CTCAE v6.0 and v5.0, 21 CFR, and the EU Clinical Trials Regulation.
- **Official terminology** in Chinese and English, including outdated → current terms.
- **Ready methods** for: is this an SAE, which CTCAE grade, is it an important protocol deviation, reporting clocks, CAPA, and monitoring reports.

Example questions: *"Is this an SAE?"* · *"Haemoglobin 7.5 g/dL: which CTCAE v6.0 grade?"* · *"I'm a new CRC, quiz me on SAE reporting."* · *"Write a CAPA for a late SAE report."*

<details>
<summary>What is in the pack</summary>

- **China**: GCP (2026 revision); CDE expedited safety reporting standard; Drug Administration Law; Drug Registration Regulation; clinical trial institution regulation; ethics review measures (2023); Human Genetic Resources Regulation and its implementing rules.
- **ICH**: E6(R3) (English) and the CDE Chinese glossary; E2A, E8(R1), E9, E9(R1), each in English and Chinese.
- **CTCAE**: v6.0 and v5.0, plus NCI's official v5.0-to-v6.0 mapping and errata.
- **US**: 21 CFR 312.3, 312.32, 312 Subpart D, Part 50 Subpart B, Part 56, Part 11.
- **EU**: Regulation (EU) No 536/2014, selected provisions (Articles 1–3, 28–35, 40–48, 52, Annex III).

Not included yet: China's revised Drug Administration Law Implementing Regulation (effective 2026-05-15) and China GCP 2020. Details in [references/regulations/README.md](references/regulations/README.md).

</details>

## Repository layout

<details>
<summary>Files</summary>

```
SKILL.md                                 entry: safety check, domain check, mode, level, shared rules
references/modes/                        lookup.md · learn.md · judge.md · do.md
references/socratic-questioning.md       how to ask; question bank
references/decomposition-methods.md      four ways to break down
references/rebuilding-methods.md         four ways to rebuild
references/adversarial-review.md         the review checklist
references/value-decisions.md            career, family, and other value-laden decisions
references/report-template.md            output structure
references/clinical-research.md          clinical pack: hard constraints, rule hierarchy, CAPA, privacy
references/terminology.md                clinical pack: official terms in Chinese and English
references/regulations/                  clinical pack: verbatim regulation texts
examples/general-decision-buy-a-car.zh.md     everyday decision: unpacking "everyone says" (Chinese)
examples/sae-late-reporting-capa.zh.md        a "late SAE report" that was not late (Chinese)
examples/light-triage-follow-up-letter.en.md  triage says: no deep analysis needed (English)
```

</details>

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

Thinking and decision support only, not a medical, legal, financial, or regulatory opinion. In clinical research, follow your protocol, SOPs, and applicable regulations; final interpretation belongs to the sponsor, QA, ethics committee, or regulator. Never enter identifiable information about trial participants or other people.

## License

The skill's own text is [MIT](LICENSE). Regulation and guideline texts in `references/regulations/` keep their original status and terms, as stated in each file.
