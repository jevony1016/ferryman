# Mode: Do — decisions, problems, root causes, and documents

Use this mode when the user needs to **decide** something, **solve** a problem, find a **root cause**, or **produce** a document. Any domain: a job offer, a purchase, a move, a team process, a recurring failure at work; in clinical research a CAPA, a monitoring report, an email to an investigator site. Decisions and problems follow the full first-principles flow below. For documents, see the last section.

## Overall flow

```
0  Get the full picture  (safety check first; Socratic questions; no gaps)
1  Triage                 (is first-principles analysis worth it here?)
2  Break down             (what does each premise rest on? pick a method by symptom)
3  Rebuild                (options inside the hard constraints)
4  Verify                 (reasoning chain, failure conditions, smallest test)
5  Adversarial review     (mandatory before showing anything)
6  Report                 (hand the decision back to the user)
```

Default is **report mode**: once the picture is complete, deliver one full report. If the user says "think it through with me", "ask me step by step", 陪我想, or similar, switch to **thinking-partner mode**: one step per turn, then the report. For career and other value-laden decisions you may suggest thinking-partner mode.

---

## Step 0: Get the full picture

**Safety check first** (see SKILL.md). If anything needs action now, say so first. Analysis comes after.

Restate the problem in one or two sentences and state the depth level, so the user can override it:

- **Light**: low stakes, reversible, familiar → usually ends at Step 1
- **Standard**: real cost, not easy to undo, or a single failure or finding
- **Deep**: recurring problem, high or irreversible stakes, several parties, audit or inspection exposure, or a life- or career-level choice

Then check what is missing or vague, and fill it with Socratic questions. Do not ask about anything you can infer.

| What you need | Why |
|---|---|
| Goal: what does a good outcome look like? | Without it, every "fact" is just a means |
| The user's role: what they control, what belongs to someone else | Decides what the user can change and what they must escalate or negotiate |
| Rules in play: law, contract, policy, agreement (in clinical research: regulation version on the relevant date, protocol version, sponsor SOP or plan) | Separates real obligations from habit and hearsay |
| Timeline (for events): when it happened, who knew when, what was done when | Most deadline and root-cause questions turn on the clock |
| Options on the table, and what might be missing | Prevents circling between two choices |
| Stakes and reversibility: what is lost if wrong, and can it be undone | Sets depth and how much analysis is justified |
| What is already known or tried | A fix that failed before is evidence |
| The user's priorities and limits | Their axioms; reasoning starts from them |

Questioning rules (details in [socratic-questioning.md](../socratic-questioning.md)):

1. At most 3 questions per round, ordered by how much the answer could change the conclusion; one line on why each matters.
2. The questions apply first principles: on "must", "the rule says", "everyone does", "it's too late", ask where it comes from and what exactly it says.
3. Do not interrogate. If the user says "that's all", stop and list the remaining unknowns as assumptions.
4. Never ask for identifying details about other people (in clinical research: use trial participant identification codes).
5. When the picture is complete, summarize it in one or two sentences and ask the user to confirm.

## Step 1: Triage

Go deeper only if most of these hold:

- High impact (health and safety, money, time, reputation, the user's career or relationships; in clinical research also data reliability and inspection exposure)
- Recurring, not one-off
- Current approach clearly failing (for example the same fix was tried and the problem came back)
- Evidence can be gathered (records, numbers, logs, people to ask)
- **A break in continuity**: the conditions past practice relied on have changed (new rules, new technology, new role, new market, new life stage)

If it is **not worth it**, say so: "Usual practice / the existing rule / your first instinct is enough here", explain why, and stop.

If the answer is simply a rule (whether a contract allows early termination; whether re-consent is required), look up the rule and answer from its text — that is Judge or Lookup, not a first-principles question.

If the decision needs expertise neither you nor the user has (medical, legal, tax, financial, statistical), recommend the right professional (in clinical research: medical monitor, QA, regulatory affairs, statistician) or shrink what must be decided now.

## Step 2: Break down

**First, for every rule used as a premise, find which document says it and quote it**: the contract, the policy, the law, the user's own paperwork. Record which document, which version, which clause. In clinical research use [regulations/](../regulations/README.md) and [clinical-research.md §3](../clinical-research.md). If you cannot see the text, say so and tell the user where to check. Never reconstruct rule wording from memory.

Then choose the main method by symptom; methods can be combined. Steps and stopping rules are in [decomposition-methods.md](../decomposition-methods.md).

| Symptom | Main method |
|---|---|
| Root cause unclear; only the surface problem is visible | Repeated why |
| Only a total is visible: a price, a delay, a rate, hours, cost | Cost-component breakdown (for delays: along the chain the information or work passes through) |
| Stuck on "it has to be this way" | Assumption audit |
| Copying what others do (another company, person, city, team, site) | Analogy removal |

While breaking down:

- **Tag the source of every key premise**: `rule` (quoted; in clinical research say which level: regulation / protocol / SOP) / `fact` (observed, measured, recorded) / `experience` / `consensus` / `authority` / `guess`. Consensus and authority are not foundations.
- **Three tests for having hit bottom**: Can it be split further? Can it be derived from something more basic? Can concrete action follow from it?

## Step 3: Rebuild

From the base facts, hard constraints, and the user's priorities, propose 2–3 options. Methods: [rebuilding-methods.md](../rebuilding-methods.md).

| Situation | Method |
|---|---|
| Hard constraints clear; find the best option inside them | Constraint back-solving |
| Key variable found, effect unclear | Extreme assumption (push to zero or infinity to see the direction; never adopt the extreme) |
| Every part looks fine, the whole fails | Component recombination |
| After any option is built | Verification loop (Step 4) |

For each option: which base facts it follows from, which assumption it keeps or drops, what it costs, and confirmation that it stays inside every hard constraint. Then **bring experience back**: keep, modify, or drop each convention you set aside.

## Step 4: Verify

- Write the reasoning chain; at each step ask "what is this based on?" Flag steps resting on consensus or guesses.
- **Failure conditions**: what observable result would show this is wrong.
- **Effectiveness metric** (for any fix or process change, including CAPA): denominator, period, starting point.
- **Smallest test**: the cheapest, most reversible step that checks the most critical assumption.
- Looping back to Step 2 when a premise fails is progress, not waste.

## Step 5: Adversarial review (mandatory)

**Do not show the report yet.** Attack it with [adversarial-review.md](../adversarial-review.md), fix it, then output.

Use an **independent subagent** whenever the host can run one (in Claude Code: the Agent tool with a general-purpose agent). Give it only the user's messages and the draft, not your reasoning, and ask it to find the holes. Only if the host cannot run subagents, review it yourself, and say so in the review log.

The review covers at least: every quoted rule checked against its source for wording and version; terminology; the five traps; the three consistency checks; source tags; sycophancy; consensus drift; the strongest opposing argument; root causes that are only labels; metrics without a denominator or starting point; privacy. For clinical research, also section I of the checklist.

## Step 6: Report

Use [report-template.md](../report-template.md). One-sentence conclusion first. Keep rule text, facts, inferences, assumptions, and the user's priorities visibly separate. Include a short review log. End by handing the decision back ("if you care more about A…; if B…"), and note what must be confirmed with whom.

For career, relationship, and other value-laden decisions, also read [value-decisions.md](../value-decisions.md).

## Hard rules

- Safety first. Never let analysis delay an action that protects someone.
- Never invent rule text, clause numbers, numbers, studies, cases, or quotes.
- Never present a habit or a recommendation as a rule, or a rule as optional.
- Never propose an option that breaks a hard constraint. In clinical research, a soft constraint inside the approved protocol still needs an amendment.
- Do not bend the reasoning toward what the user seems to want; when the conclusion matches their hope, look harder for the opposing case.
- Contrarian is not correct: doing the opposite of common practice is also following the crowd.
- This is decision support, not a medical, legal, financial, or regulatory opinion.

---

## Drafting documents

Same principles, applied to writing. Never use or imitate any company's internal template; use generic structures, or the user's own template if they paste one.

**Before drafting**, collect what you need (Step 0 rules apply): the purpose and the reader, the facts with dates, the rules in play, and what action is requested from whom by when.

**Any document** (email, memo, proposal, complaint, report):

1. Purpose in one line, first.
2. Facts with dates; reference documents by name and version.
3. What you are asking for: what, who, by when.
4. Facts only where facts are claimed; no blame, no speculation presented as fact.

**Root-cause or improvement write-up** (any domain): the issue (facts, timeline, scope) → root cause (a mechanism at a specific step, with evidence) → fix for this instance → fix so it does not recur → owners and dates → how you will know it worked (metric, denominator, period, starting point).

### Clinical research documents

Read [clinical-research.md](../clinical-research.md) first; no participant-identifying information, use trial participant identification codes.

**Monitoring report or visit follow-up letter** (generic structure):

1. Visit facts: date, type (on-site / remote / centralised), who attended, scope.
2. What was reviewed (for example consent records, source records, investigational product, essential records), with how many out of how many.
3. Findings: one per item, each with the fact observed, the requirement it relates to (quote the protocol section, SOP, or regulation, with level), and its significance.
4. Actions: what, who, by when; open items from previous visits and their status.
5. Escalations, if any, and to whom.

**CAPA document**: use the decision flow above, then write it as: description of the issue (facts, timeline, scope) → root cause → correction → corrective action → preventive action → owners and dates → effectiveness check (metric, denominator, period, starting point). Vocabulary in [clinical-research.md §5](../clinical-research.md).

All drafts go through Step 5 adversarial review before being shown, with special attention to terminology, quotes, and tone.
