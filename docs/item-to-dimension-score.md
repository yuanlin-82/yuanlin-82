# Competency item → dimension score (contract shape)

How a **spoken or choice item** becomes a **dimension contribution** on a hire report—methodology shape only.

This sits between **follow-up routing** ([ai-interview-decision-map](https://github.com/yuanlin-82/ai-interview-decision-map)) and the **session report** ([system-map.md](system-map.md)). It is **not** oral-ability composition ([english-speaking-assessment](https://github.com/yuanlin-82/english-speaking-assessment)).

No production rubrics, weights, judge prompts, or customer stems.

---

## What problem this closes

A session can look complete while three different things are still confused:

| Layer | Question it answers | Typical public artifact |
| --- | --- | --- |
| **Routing** | What to ask next / when to stop | Decision maps, probe-quality gates |
| **Item → dimension score** (this page) | Did this item yield **job-evidence** scorable for a competency dimension? | Evidence cells, judge order, roll-up shape |
| **Oral ability dimension** | How did speech perform under **standard speaking tasks**? | Pronunciation / fluency / coverage composition |

Follow-up quality ≠ hire signal. Fluency in a competency chat ≠ oral band.

---

## Unit of scoring

**One item → one item score (or structured sub-scores) → roll into one or more dimensions** per the session contract.

| Item form | Evidence used for competency scoring | Follow-up’s job |
| --- | --- | --- |
| **Spoken Q&A** | Dialogue text (ASR), after probing closes evidence gaps | Multi-angle sampling of job-evidence cells ([task-vs-interaction](https://github.com/yuanlin-82/english-speaking-assessment/blob/main/docs/task-vs-interaction.md#same-llm-follow-ups-different-evidence-gaps)) |
| **MCQ / scale** | Selected option(s) | None—nothing to probe |

Spoken competency items are scored for **job-relevant evidence quality** (specificity, ownership, judgment under constraint, … as defined per dimension)—**not** for pronunciation band. Delivery may be noted as **channel quality** (harder to harvest evidence); that is not an oral proficiency score unless a separate oral product line says so.

---

## Evidence cells (shape, not a rubric dump)

Competency scoring needs an explicit **what counts** list per item or type family. Public shape only:

```text
Item / type family
  → target dimension(s)
  → evidence cells (must / nice-to-have)
  → disallowed substitutes (e.g. pure “I would…” for behavioral past)
  → judge order: fatals → cell coverage → optional style notes
```

Illustrative cell families (names vary by product):

- **Episode grounding** — time, place, role, stakes (behavioral)  
- **Action / decision** — what *they* did; not only “we”  
- **Constraint / trade-off** — why this option under pressure  
- **Outcome / learning** — result and what changed next time  
- **Plan under scenario** — situational: rule + next step, not vibes  

Routing packs ([competency-to-scenario](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/competency-to-scenario.md)) exist to **fill empty cells**. Scoring reads whether cells are full enough to support a dimension judgment—not whether the probe sounded warm.

---

## Judge order (competency item)

Aligned in spirit with probe judging ([followup-quality](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/followup-quality.md)), but the object is the **candidate evidence**, not the interviewer utterance:

1. **Fatals** — wrong evidence type; invented premises in the stem path; empty after recovery budget; policy/safety breach content as defined by type  
2. **Cell coverage** — which required cells are present / partial / missing  
3. **Usable for dimension?** — yes / weak / no (product may map these to numeric bands privately)  
4. **Do not** let spoken polish, length, or praise-seeking style overturn empty cells  

Offline LLM judges and human audit stay on this contract; exact scales stay private.

---

## Roll-up into dimensions and the total

From [system-map.md](system-map.md):

1. Score **each item** when the item ends (spoken path after stop; choice path on submit).  
2. Map item results into **dimension buckets** (one item may feed one primary dimension; multi-dimension tagging is a product choice—declare it).  
3. After the candidate finishes the ordered bank and ends the session → **dimension-weighted total** → single report.  
4. **English oral ability**, when present, is usually a **separate dimension** fed by **task-based oral items** (or a dedicated oral module)—not by averaging competency dialogue charm.

Private: coefficients, band cut scores, per-customer overlays.

---

## Item equivalence (same dimension, different forms)

One dimension may hold spoken probes, MCQs, and scales together. That is convenient for HR configuration and dangerous for measurement:

- Same dimension label ≠ same construct grain.  
- A Likert “teamwork” tick and a behavioral episode are not automatically fungible.  
- Products should **name the risk**, prefer coherent item families per dimension when stakes are high, and avoid selling a blended dimension as precision finer than the weakest item type.

This page does not publish equivalence formulas—only the design obligation to treat equivalence as a **first-class risk** (see `Eq` on the system map).

---

## What this page is not

- Not a substitute for oral **construct / composition** docs  
- Not session-level orchestration (cross-item evidence ledger remains a known gap on the decision-map README)  
- Not production rubrics, prompts, or weight tables  

---

## Links

| Topic | Doc |
| --- | --- |
| Session diagram | [system-map.md](system-map.md) |
| Upstream competency → type | [competency-to-scenario.md](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/competency-to-scenario.md) |
| Probe quality (interviewer side) | [followup-quality.md](https://github.com/yuanlin-82/ai-interview-decision-map/blob/main/docs/followup-quality.md) |
| Channel vs object / gap geometry | [task-vs-interaction.md](https://github.com/yuanlin-82/english-speaking-assessment/blob/main/docs/task-vs-interaction.md) |
| Oral score assembly | [score-composition.md](https://github.com/yuanlin-82/english-speaking-assessment/blob/main/docs/score-composition.md) |
| Chinese one-pager | [zh-overview.md](zh-overview.md) |
