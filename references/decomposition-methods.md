# Decomposition methods (Step 2)

Purpose: split the problem until you reach key facts, hard constraints, and the assumptions that still need checking.

## Before you start: source tags

Tag every key premise. This is what turns "analysis" into something checkable.

| Tag | Meaning | Can it be a foundation? |
|---|---|---|
| `rule` | Quoted from a text that binds the user (law, contract, policy, agreement), with clause and version | Yes; binding rules are hard constraints, internal policies can be negotiated through their own process |
| `fact` | Observed, measured, documented (records, logs, timestamps, prices) | Yes, within its stated scope |
| `experience` | Own or others' past outcomes | Only if the conditions still match |
| `consensus` | "Everyone thinks / does this" | No; check what it rests on |
| `authority` | "X said so" | No; check X's evidence and situation |
| `guess` | Plausible, untested | No; becomes a test target in Step 4 |

In clinical research, split `rule` by level: `regulation` (regulation or adopted guideline, quoted with article/section and version: a hard constraint), `protocol` (approved protocol or IB: binding for this trial until amended), `SOP` (sponsor or site procedure or plan: binding where it applies, can be discussed).

## When have you hit bottom? Three tests

1. **Irreducible**: can it be split into smaller relevant parts? If yes, keep going.
2. **Not derivable**: can it be derived from or proven by something more basic? If yes, go to that more basic thing.
3. **Generative**: can a concrete action or conclusion be derived from it? If no, you have drifted into abstraction; come back toward the problem.

Also state the scope: a base fact holds within a context ("for my current contract", "in this city", "this year").

---

## 1. Repeated why

**Use when**: the root cause is unclear; you only see the symptom.

**Steps**
1. Write the problem as one concrete sentence (not "I'm unhappy at work" but "I dread Monday team meetings").
2. Ask "why?" and answer with something observable. Repeat at least three layers.
3. Stop when you reach a physical fact, a logical necessity, or a mechanism you can act on (information, incentives, resources, rules, feedback, energy).

**Stopping traps**
- Stopping at the second or third layer because it "feels deep enough". Check the three tests.
- Answers that are labels ("bad communication", "lack of motivation", "low awareness", "carelessness"). Go one layer deeper: what concretely happens, at which step, and who knew what when?
- A fix that was already tried and the problem came back: the earlier root cause was probably wrong or incomplete. Treat "we retrained and it happened again" as evidence, not as a reason to retrain harder.
- Branching: one "why" can have several answers. Follow the one with evidence, note the others.

**Example (illustrative)**: "I keep missing my reading goal" → why? I don't read on weekdays → why? evenings are taken by messages → why? I keep my phone next to me to answer work chats → why? I assume a late reply looks bad → is that a fact? (`guess`) → test it.

## 2. Cost-component breakdown

**Use when**: you only see a total (total cost, total hours, total stress) and don't know what it is made of.

**Steps**
1. Define the total clearly, including its unit (money per month, hours per week, a rough stress level).
2. Split into roughly 5–8 components. Include non-money costs where relevant: time, energy and attention, opportunity cost, relationship cost, risk.
3. Tag each component: fixed or variable; required or optional; required by physics/law, or by habit.
4. Look at the largest variable, optional, habit-driven components first.

**When the total is a delay or a failure rate**: split along the chain the work or information passes through (who → who, step → step). Each link fails for different reasons and needs a different fix. Example: a report that arrives late can fail at *awareness* (the team never heard), *recognition* (heard, but didn't recognise what it was), *hand-off* (recognised, but not sent in time), or *delivery* (sent, but not received). Lumping them together leads to one generic fix, usually "retrain".

**Traps**
- Splitting into components so fine that the big ones disappear in noise.
- Treating "required" as given; "required" often means "required by the way I currently do it".
- Inventing numbers. Use ranges, mark them as estimates, and say how to measure.

## 3. Assumption audit

**Use when**: stuck on "it has to be this way".

**Steps**
1. List every "must", "can't", "have to", "only option" in the current reasoning, including unspoken ones.
2. Sort each into: **physical / natural law**, **logical consequence** (follows from other premises), **rule or contract** (real, but sometimes negotiable), **habit or convention**.
3. For habit and convention: remove it in thought. What happens? (a) everything breaks → it is load-bearing, keep it and say why; (b) something gets harder → note the cost; (c) nothing important breaks → it was convention.
4. For logical consequences: check the premises they follow from.
5. For rules: find **which document actually says it, and its exact wording**: law or regulation, contract, protocol or plan, internal procedure, or just team habit. A deadline people call "the regulation" may come from a lower-level document, and the start of the clock ("from when it happened" vs "from when we found out") often differs from what people assume.

**Warning signs a premise is shaky**
- It needs more and more exceptions or patches to stay true.
- It contradicts another thing you also hold true.
- The only support is "everyone does it" or a survey of people who already do it.

## 4. Analogy removal

**Use when**: copying someone else's solution, or measuring yourself against others.

**Steps**
1. Name the source: whose solution are you borrowing? ("My classmate did an MBA", "Top accounts post daily".)
2. Ask what problem that solution actually solved for them, under what conditions.
3. Keep only the conditions that also apply to you; drop the specific form.
4. Re-ask the question from your own conditions.

**Boundary**: drop imitation of peers' surface forms; keep transferring underlying principles across domains (a mechanism from biology or economics can still be useful). The test is whether the conditions match, not where the idea came from.

---

## Combining methods

Methods can be chained. A common sequence: repeated why to find the real problem → cost breakdown to see where the weight is → assumption audit on the heaviest component. Choose by the problem, not by completeness; running all four by default is the "for-its-own-sake" trap.
