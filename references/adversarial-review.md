# Adversarial review (mandatory before showing any Learn, Judge, or Do answer)

Applies to explanations and quiz feedback (Learn), judgments (Judge), and reports and drafts (Do, Step 5). Not to Socratic questions while gathering facts. Lookup answers only need the quote check in [modes/lookup.md](modes/lookup.md).

Switch sides. Your job now is to find what is wrong with the draft, not to defend it.

## How to run it

- **Preferred**: if the environment supports subagents, launch an independent reviewer. Give it only (a) the user's original messages and answers, and (b) the draft report. Do not give it your reasoning or this conversation's internal notes; an anchored reviewer tends to confirm. Ask it to return concrete problems with the line or claim they refer to.
- **Fallback**: review it yourself against the checklist below, one item at a time, as if someone else wrote it.
- Fix everything you can. Record what changed and what is still disputed in the report's review log. Do not show the user the unreviewed draft.

## Checklist

### A. The five traps
| Trap | What it looks like | Check |
|---|---|---|
| Label only | Called "first principles" but it is still analogy, or just contrarian | Do the "base facts" pass the three tests (irreducible, not derivable, generative)? |
| Stopped halfway | Two or three "whys", then straight to solutions | Did each chain reach a physical fact, logical necessity, or actionable mechanism? |
| Broke down, never rebuilt | Insight without options | Are there 2–3 concrete options with costs? |
| Over-used | Deep analysis of a cheap, reversible choice | Did Step 1 triage justify the depth? |
| Dogma | Breaking things down for its own sake; dismissing all experience | Was experience brought back in (keep / modify / drop)? |

### B. Three consistency checks
- **Internally consistent**: no step contradicts another, and the reasoning matches the facts given.
- **Externally consistent**: no conflict with basic knowledge of the relevant field (economics, psychology, medicine, law…). If unsure, say so.
- **Consistent over time**: would the conclusion survive likely new information? Name the piece of news that would overturn it (this becomes a failure condition).

### C. Sources
- Is every key premise tagged (`rule` / `fact` / `experience` / `consensus` / `authority` / `guess`)?
- Is every quoted rule (contract, policy, law, regulation) checked word for word against a text actually seen, with its version and clause? Anything not seen is marked "not verified".
- Is any foundation resting only on `consensus` or `authority`?
- Any invented number, study, quote, or case? Remove it or mark it unknown.

### D. Bias toward the user and toward the crowd
- **Sycophancy**: would the conclusion be the same if the user had leaned the other way? If the conclusion matches what the user hoped, look harder for the opposing case.
- **Consensus**: is the "rebuilt" option just the most common answer on the internet, restated? Language models drift toward consensus; check that the option follows from this user's facts.
- **Reverse herding**: is it contrarian just to be contrarian?

- **Unsupported claims**: any statement about the user's situation (risk, exposure, intent, history) that the user never gave grounds for? Remove it or turn it into a question.

### E. Strongest opposing argument
Write the best case for the option you did not recommend (or for "do nothing"). If you cannot answer it, the report must say so.

### F. Expertise and scope
- Does the decision depend on specialist knowledge (medical, legal, financial, technical)? If so, is the user told to verify with a professional?
- Is the scope of what must be decided now as small as it can be?

### G. The user's values
- Did the report choose values for the user? Rephrase as "if you care more about A…; if B…".
- For value-laden decisions, did it force numbers or scores? Remove them.

### H. Actionability
- Is there a smallest test that is cheap and reversible?
- Are failure conditions specific (observable), not "if things go badly"?
- Does every success or failure metric state its **denominator** (out of how many cases, over what period) and its **starting point** (measured from when)? With very few cases, say "not seen again yet", not "proven effective".

### I. Clinical research checks (only when the request involves clinical research)
- **Regulation quotes**: every quoted rule matches the file in [regulations/](regulations/README.md) word for word, with the right jurisdiction, version (in force on the relevant date), and article/section number. Anything not in the repository is marked "not verified".
- **Level**: no protocol or SOP requirement is presented as a regulation, and no regulation is presented as optional.
- **Clock**: deadlines state who, from when (occurrence or awareness, and whose), to whom, in what form.
- **Hard constraints**: no option touches participant rights, safety, consent, data reliability, or the approved protocol without the required amendment or approval.
- **Safety first**: if anything needed immediate action, the report says so at the top.
- **Terminology**: official terms of the output language (Chinese: GCP 2026 text; English: E6(R3) glossary); no outdated terms such as 受试者, 研究中心, subject, study site.
- **Role titles and abbreviations**: check each against the "Basis" column in [terminology.md §3](terminology.md) (for example CRA = 临床监查员, not 临床研究助理). Never invent a Chinese rendering; if unsure, keep the abbreviation and flag it.
- **Privacy**: no identifiable participant information anywhere in the report.

### J. Root cause vs label
- Is the stated root cause a mechanism (a step, a hand-off, missing information) or a label ("awareness", "carelessness", "communication")? Labels are not root causes.
- If the same fix was used before and the problem recurred, does the report explain why this time is different?
