# Mode: Lookup — terms, definitions, and rule text

Use this mode when the user wants to **find** something: what a term means or how it is translated, which clause or article covers a topic, what the exact wording says, how two rule sets differ on one point.

The answer is only as good as its source. For exact wording, never answer from memory: quote a text you can actually see, or say you cannot verify it.

## General lookup

1. **Find the governing source**: the document the user is bound by or asks about (their contract, a policy, a law, a standard). If the user can paste or attach it, ask for it. If the host can open official sources (web access), use the official version and give the link and date.
2. **Quote verbatim** only from that text, with document name, version or date, and clause number. Quote only the part that answers the question, but do not cut a sentence in a way that changes its meaning (keep exceptions such as "except…" / "除……外" and qualifiers).
3. **If you cannot see the text**, say "not verified": give your best understanding clearly labelled as such, and where to check. Do not present remembered wording as a quote.
4. **General-knowledge terms** (a concept, not a binding text): give the meaning, and say whether it is a standard definition (and whose) or common usage.
5. If the question is really a judgment ("so does this apply to me?"), answer the lookup, then offer [judge mode](judge.md).

---

## Clinical research lookup

Look it up in the repository files every time.

### Terms

1. Search in this order and stop at the first hit:
   1. [terminology.md](../terminology.md) (outdated → current table, core terms, abbreviations with their basis)
   2. China GCP 2026 Article 54 definitions: `grep -n "^### 第五十四条" -A 20 ../regulations/cn-gcp-2026.md` (it defines five terms and refers other terms to the CDE E6(R3) glossary)
   3. CDE Chinese E6(R3) glossary: `../regulations/cn-ich-e6r3-glossary.md`
   4. ICH E6(R3) English glossary: `../regulations/ich-e6-r3.md` (Glossary section)
   5. Other definitions in the regulation files (E2A, E9(R1), 21 CFR 312.3, EU CTR Article 2, CTCAE definitions)
2. Answer with: the term in the user's language, the other language, the outdated form if any, a one-line meaning, and the **basis** (which file and article/section).
3. If two official sources differ (for example 试验现场 in GCP 2026 vs 研究者现场 in the CDE glossary), show both and say which prevails per the order of authority in terminology.md.
4. If no official source has it, say so, give the common industry usage only if you are sure and label it "industry usage", otherwise keep the abbreviation and say the rendering is unverified.

### Regulation text

1. Find the location with the topic map in [regulations/README.md](../regulations/README.md), then `grep` the heading (`### 第二十六条`, `#### 2.7.2`, `### §312.64`, `### Article 41`).
2. Quote the relevant text **verbatim**, with: document name, version, effective date, article/section number, following the cutting rule above (keep qualifiers such as "in accordance with applicable regulatory requirements").
3. If the user writes in another language than the source, add a translation labelled "unofficial translation". Do not upgrade the tone: should → 应, must/shall → 必须, may → 可.
4. If the topic is covered in several jurisdictions, offer a short side-by-side (max 4 columns), each cell quoting or pointing to the exact article.
5. Say what applies by date: if the event or trial date might fall under an older version not in the repository (for example China GCP 2020 before 2026-09-01), say so.

---

## Output

Short. For a newcomer, add one plain-language sentence explaining what the rule means in practice, clearly separated from the quote and without adding requirements the text does not contain.

## Check before answering

- Quote matches the source character for character.
- Version and article or clause number are right.
- No habit, recommendation, or lower-level document (in clinical research: protocol or SOP) presented as a higher-level rule.
