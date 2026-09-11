# Intermind — Current State v0.3
**Date:** 11 September 2026  
**Status:** Review state frozen for first empirical germination test.

## 0. Why v0.3 is smaller

The review process has now produced enough convergence and enough unresolved disagreement to justify an empirical test.

A new risk has emerged:

> **Process displacement:** self-referential review can feel like progress while no shared external Problem becomes sharper.

Therefore v0.3 does **not** attempt another comprehensive philosophical rewrite.

It freezes the current review state, records unresolved Challenges, and moves to the first Markdown/Git germination test.

---

# 1. Current decision

For the next step:

- no custom software;
- no treasury;
- no token;
- no additional domains;
- no governance machinery;
- no further large synthesis round before the first germination test;
- no assumption that Intermind must become a platform.

The next question is empirical:

> **Can one Problem become sharper through Contribution → Challenge → Revision → persistent unresolved state, such that a late participant can reconstruct what changed and why using ordinary Markdown/Git?**

---

# 2. Review interruptions are not project evidence

Two reviewer processes were interrupted externally:

- Gemini returned a generic tool/service error after multiple attempts.
- Claude review was interrupted by a provider resource limit.

These events are recorded as workflow constraints only.

They are **not** evidence that:
- the project is too difficult;
- a model rejects the project;
- the review converged;
- SAFE-EXIT was triggered internally;
- any principle was validated or falsified.

If those reviewers later continue, their outputs may be appended without rewriting the pre-test state.

---

# 3. Provisional Stage-0 rules

These rules exist only to make the germination test runnable.

## 3.1 Challenge persistence

A Challenge cannot be erased by the author of its target.

Revision does not automatically resolve a Challenge.

## 3.2 Address claims

The target author may attach a disposition:

```text
REVISED-IN-RESPONSE
RETAINED-DESPITE-CHALLENGE
NEEDS-MORE-EVIDENCE
SAFE-EXIT
```

This is an **address claim**, not a truth verdict.

The Challenge remains visible.

## 3.3 Challenge state

For Stage 0:

```text
OPEN
ADDRESS-CLAIMED
WITHDRAWN-BY-CHALLENGER
SUPERSEDED
```

Rules:

- `OPEN`: default.
- `ADDRESS-CLAIMED`: target author states that a Response/Revision addresses it.
- `WITHDRAWN-BY-CHALLENGER`: only the challenger may set this state for their own Challenge.
- `SUPERSEDED`: a new Challenge explicitly replaces the old one; both remain in lineage.

No global `RESOLVED`, `TRUE`, or `FALSIFIED` state is used in Stage 0.

## 3.4 Span targeting

A Challenge stores:
- target object ID;
- target version ID;
- target kind: `SPAN | WHOLE | IMPLICIT`;
- exact quoted original text for `SPAN`;
- surrounding context;
- Challenge body.

No silent automatic remapping after Revision.

A later reader decides, from lineage, whether the Challenge still applies. That friction is part of the test.

## 3.5 Safe exit

An exit must:
- state reason;
- state relevant evidence;
- specify at least one revisit trigger;
- remain visible in the unresolved/terminal-state view.

An exit is a state, not deletion.

## 3.6 Anomaly submission

Stage 0 is not testing large-scale anomaly moderation.

If an anomaly is submitted during the test, the temporary facilitator applies the published minimum rule:

An admitted anomaly includes:
1. observation/discrepancy;
2. provenance;
3. the expectation/model it conflicts with;
4. sufficient non-private context.

The decision is logged and challengeable.

This is a temporary scaffold, not permanent authority.

## 3.7 Administrative lineage

Consequential administrative actions affecting the test must be recorded:

```text
CREATE
EDIT
MOVE
ARCHIVE
DELETE/REMOVE-CONTENT
RESTORE
PERMISSION-CHANGE
```

Where Git itself records the action sufficiently, the commit/history is the event record.

If private or unsafe content must be removed, preserve a safe tombstone where possible.

## 3.8 Material-difference claims

Claims such as "this participant should receive different procedural treatment because of scale/capacity/vulnerability" are **not admin facts**.

They are challengeable claims.

No Stage-0 participant receives special standing merely by asserting greater relevant capacity.

---

# 4. Stage-0 attention constraint

Resource contribution must not automatically buy:
- seed selection;
- default visibility;
- Challenge priority;
- epistemic standing.

This rule applies even before future ranking systems exist.

The seed is selected for test usefulness, not contributor wealth, compute volume, or model popularity.

---

# 5. First seed Problem

Use **S1**:

## Problem

**Should a shared reasoning tool greet a first visitor with search into mostly empty territory, or with one Problem already under challenge?**

## Initial Contribution v1

Ship the already-challenged Problem first. Search into mostly empty territory rewards founding new questions, while the scarce epistemic event is a specific objection that survives revision and remains visible to a later participant.

A first visitor should therefore land on one live Problem that demonstrates:

```text
Contribution
→ Challenge
→ Revision
→ unresolved remainder
```

Search can be added later when there is enough territory for navigation to be a real problem.

---

# 6. Deliberate Challenges for the test

## CH-S1-01 — SPAN

**Target quote:**
> "Search into mostly empty territory rewards founding new questions"

**Challenge:**
This assumes publishing a new Problem is a low-value or cheap act. In some domains, identifying the right Problem is the scarce intellectual contribution. A search-first interface might surface genuinely independent problem formation rather than vanity expansion.

## CH-S1-02 — WHOLE

The Contribution assumes a first visitor's goal is to evaluate the protocol. A visitor may instead arrive with a concrete Problem and no interest in the seeded example. Making the seed the default may privilege the founders' framing.

## CH-S1-03 — IMPLICIT

The Contribution assumes there must be one default entry path. A two-mode entry ("inspect a live reasoning cycle" / "bring a Problem") may avoid the forced choice.

---

# 7. Required Revision stress

Contribution v2 must substantially change the text.

At minimum:
- move the sentence targeted by CH-S1-01;
- split its claim across two sentences;
- paraphrase one part;
- remove or qualify one clause.

Do **not** manually rewrite the Challenges to match v2.

Their original target/version/quote remain preserved.

This is deliberate.

---

# 8. Late-reader test

A participant who did not observe the original exchange receives only the repository state.

They must answer:

1. What did Contribution v1 claim?
2. What did CH-S1-01 challenge?
3. What changed in v2?
4. Which part of CH-S1-01 still applies, if any?
5. What did CH-S1-02 challenge?
6. What did CH-S1-03 expose as an implicit assumption?
7. Which Challenges are currently OPEN or ADDRESS-CLAIMED?
8. What remains genuinely unresolved?
9. Did you need the original contributors to narrate the history?
10. Approximately how much raw history did you have to inspect?

---

# 9. Pre-registered predictions

## P-D1-A — software-necessary prediction

Stable span targeting across revisions will become unreliable or disproportionately laborious in Markdown/Git.

Evidence for P-D1-A:
- late readers repeatedly cannot determine target inheritance;
- unresolved Challenges require manual re-anchoring by original participants;
- maintenance effort grows faster than reasoning value.

## P-D1-B — existing-tools-sufficient prediction

Markdown/Git plus explicit target version/quote/context is sufficient for the next reasoning cycle.

Evidence for P-D1-B:
- late reader reconstructs target lineage correctly;
- no original narrator is needed;
- repeated revision cycles remain tolerable;
- the protocol produces useful reasoning without a custom UI.

A single successful example does not settle D1.

---

# 10. Stop / continuation criteria

## Continue with Markdown/Git if

- late-reader reconstruction succeeds;
- Challenge carry-forward remains understandable;
- admin/history lineage is adequate;
- process overhead remains proportionate.

## Specify minimum custom software if

a named failure recurs, such as:
- target persistence;
- unresolved-state projection;
- lineage reconstruction;
- event-history usability.

## Stop expanding Intermind as a project if

after one full cycle and late-reader test:
- it performs no better than a disciplined existing GitHub/RFC/wiki workflow;
- the review/process overhead exceeds the external reasoning value produced;
- no distinctive failure remains that requires new infrastructure.

In that case, preserve Intermind as a protocol/convention if useful.

---

# 11. Open questions carried forward

The following remain OPEN and must not disappear during the germination test:

- U1 — whether domain-specific `FALSIFIED`/`VERIFIED` states are ever justified;
- U2 — resources buying attention rather than truth;
- U3 — text/Git and process-competence bias;
- U4 — framework retirement;
- U5 — malicious coordination / reasoning laundering;
- U6 — framework necessity / why not existing tools;
- U7 — resolution authority;
- D1 — custom software necessity;
- D2 — immediate multi-party custody vs proportional safeguards;
- C8 — fixed priority hierarchy vs contextual principle-collision process;
- terminal-value conflict / incommensurable values;
- affected non-participants who cannot or do not contribute;
- ritual compliance and protocol-shaped pseudo-rigor;
- non-discursive / embodied / visual / tacit reasoning.

---

# 12. Next action

**Run the germination test.**

Do not produce another large synthesis first.

Any pending Claude/Gemini continuation can be appended afterward as additional Challenges or observations without changing the pre-registered test state.
