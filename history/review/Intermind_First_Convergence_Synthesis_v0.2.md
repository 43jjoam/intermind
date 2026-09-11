# Intermind — First Convergence Synthesis v0.2
**Date:** 11 September 2026  
**Status:** Provisional, challengeable synthesis. Not final authority.

## 0. Scope and epistemic status

This document revises `Intermind_First_Convergence_Synthesis_v0.1.md` after:
- the original first-pass reviews;
- a Grok recheck of the synthesis;
- Claude challenges against the synthesis;
- a Gemini recheck/assessment;
- a DeepSeek recheck.

This is **not** yet the unstructured Round-B residual-search review proposed earlier. It is a recheck of the first synthesis. Round B remains pending.

Reviewer identity is preserved where the user explicitly supplied it. Where a first-pass review's exact model/version is not recoverable from its source text, it remains marked `PROVENANCE-UNCLEAR` rather than inferred.

Repeated agreement is a **priority signal**, not proof. Current frontier models may share training data, governance vocabulary, alignment assumptions, and prompt-induced attention patterns.

The synthesis itself is a Contribution and is challengeable under the same protocol it describes.

---

# 1. Changes from v0.1

v0.2 adds or changes:

1. explicit reviewer-provenance handling;
2. a companion structured convergence matrix;
3. Round-A-vs-Round-B status;
4. malicious coordination / reasoning-laundering as an unresolved threat;
5. framework necessity: Intermind may be unnecessary as a new platform;
6. a provisional principle-collision protocol;
7. a provisional anomaly-admissibility rule;
8. resolution authority as a top-level unresolved problem;
9. preservation of all seed candidates in a companion appendix;
10. a more precise span-persistence test;
11. explicit preservation of the dissenting software prediction;
12. survival reasons for currently robust principles;
13. explicit preservation of minority proposals rejected by the synthesis;
14. a second custody disagreement: immediate multi-party control vs proportional safeguards;
15. a stronger safe-exit revisit rule;
16. an explicit "no synthesis as final authority" constraint.

---

# 2. High-confidence convergence signals

## C1 — Anomaly preservation requires separation of record, admissibility, weight and visibility

**Convergence:** strong across the first-pass and recheck reviews.

The original formulation "preserve every anomaly" is too easy to weaponize if every submitted object receives permanent public visibility.

The current distinction is:

```text
anomaly submission
≠ admitted anomaly
≠ evidential weight
≠ visibility priority
≠ truth
```

### Provisional anomaly-admissibility rule

A submission may enter the anomaly record as an **admitted anomaly** when it contains, at minimum:

1. a stated observation or reproducible discrepancy;
2. provenance sufficient to understand where the observation came from;
3. the expectation, model, rule, or claim with which it conflicts;
4. enough context to understand the conflict without unnecessary private identifying detail.

A "requested challenge" is encouraged but **not mandatory**; requiring it could wrongly exclude passive observations whose significance is not yet understood.

Submissions that fail the minimum structure may be:
- quarantined;
- rate-limited;
- marked incomplete;
- asked for clarification.

The system should preserve an inspectable tombstone/provenance record of quarantine decisions where safe and lawful, but it need not preserve malicious or identifying payloads publicly.

### Candidate revised principle

> **ANOMALY-PRESERVATION:** Preserve admitted anomalies and the inspectable history of how anomaly submissions were classified. Preservation does not imply equal evidential weight, equal visibility, or exemption from privacy, safety, or legal constraints. Classification and quarantine decisions must themselves remain challengeable.

### Open problem

Who or what applies admissibility without becoming a hidden central gatekeeper?

Do not solve this by creating a permanent "anomaly authority" in Stage 0.

---

## C2 — Practical custody can become de facto control

**Convergence:** strong.

Control of:
- GitHub admin rights;
- merge rights;
- domain registration;
- moderation;
- future wallets/keys;
- canonical discoverability

is real power even when the surrounding philosophy says "non-ownership."

### Candidate deeper principle

> **ACCOUNTABLE-CUSTODY:** No participant should possess permanent, unaccountable, unilateral control over consequential shared infrastructure or rules. The mechanism used to reduce capture may be centralized, distributed, or hybrid depending on context, but it must remain observable, challengeable, portable, and replaceable.

This replaces any assumption that decentralization is inherently good.

### D2 — unresolved remedy-strength disagreement

**Position A — immediate multi-party custody:**  
One reviewer argues that a public canonical repo/domain should not be recognized as legitimate until multi-party or programmatic safeguards exist.

**Position B — proportional safeguards:**  
Other reviewers favor minimal Stage-0 custody with transparent logging, exports and explicit transfer/fork procedures, adding multi-party control only when real stakes or multiple custodians exist.

**Current status:** unresolved.

Stage 0 may test both by asking:
- what harm is possible under single-custodian public Git history?
- what complexity does premature multi-party custody add?
- which risks are reversible?

Do not silently treat Position B as consensus.

---

## C3 — SAFE-EXIT survives, but exits must remain live epistemic states

**Convergence:** strong.

The mirror failures are:

```text
no legitimate exit
→ unbounded goal expansion

too-cheap exit
→ abstention / strategic paralysis
```

### Revised candidate principle

> **SAFE-EXIT:** A terminal state such as "infeasible under current constraints," "insufficient information," "abstain," or "escalate" must be recorded with reasons and relevant evidence. It remains challengeable and reversible when triggering conditions change. "Currently infeasible" is not "proven impossible."

### Revisit trigger

Claude correctly challenges v0.1's passive "reopen when evidence changes" wording.

A stronger provisional rule is:

> An exit must specify at least one revisit trigger: a new evidence condition, a capability condition, a related-Contribution threshold, or—where consequences are high and no event trigger is adequate—a bounded review interval.

This avoids forcing every low-stakes exit onto a calendar while preventing permanent silent stalling.

---

## C4 — Entity neutrality requires material-difference awareness

**Convergence:** strong.

Formal identical treatment can create substantively unequal outcomes where participants differ in:
- scale;
- compute;
- vulnerability;
- consent capacity;
- physical/legal exposure;
- dependency;
- domain competence.

### Revised candidate rule

> **MATERIAL-RELEVANCE:** Entity labels alone do not justify privilege or exclusion. Materially relevant differences—such as capacity, vulnerability, consent, dependency, scale, or domain-specific competence—may justify different procedural safeguards. The claimed relevance of those differences must itself remain explicit and challengeable and must not automatically create permanent hierarchy.

### Status of `SYMMETRY`

R1 proposed removing `SYMMETRY` entirely.

That proposal is **not adopted**, but it is preserved.

Current synthesis:

> **SYMMETRY and ROLE-REVERSAL are diagnostic tests, not proofs of legitimacy.**

They can expose hidden privilege. Passing them does not establish justice.

---

## C5 — Privacy and non-erasure require a collision protocol

**Convergence:** strong.

The framework must distinguish:

```text
epistemic lineage
from
private identifying source material
```

### Provisional collision protocol

Do **not** yet hard-code a universal ranked hierarchy such as:
`privacy > safety > corrigibility > everything else`.

That proposal is useful but too broad because:
- "legal obligation" varies by jurisdiction;
- "safety" can be invoked expansively;
- fixed priority can itself become a mechanism for suppressing inconvenient evidence.

Instead use:

> **PRINCIPLE-COLLISION:** When candidate principles conflict, the conflict must be made explicit. Apply the narrowest rule necessary to satisfy non-waivable legal/privacy/safety constraints while preserving as much epistemic lineage, corrigibility, and reversibility as possible. The chosen priority and exception must be logged and challengeable.

### Current privacy/non-erasure application

> Identifying or unlawfully published source material may be removed where required. Preserve the minimum non-identifying tombstone or lineage necessary to keep later reasoning intelligible when this can be done safely and lawfully.

### Still unresolved

- Can publication authorization be revoked after others have relied on the contribution?
- Who authorizes group-derived private reasoning?
- What if even a tombstone permits re-identification?
- How should legal obligations differing across jurisdictions interact?

---

## C6 — Cross-model convergence is correlated evidence

**Convergence:** strong.

Multiple AI systems may share:
- corpora;
- safety/governance discourse;
- alignment methods;
- prompt framing;
- model-family ancestry;
- sycophancy or "balanced critique" habits.

### Review architecture

**Round A — common prompt:** comparative stress test.  
**Synthesis recheck — current stage:** reviewers challenge the synthesis itself.  
**Round B — still pending:** unstructured residual search.

Round-B question:

> **Ignoring every test, category, principle and failure mode named in the review packet, what important failure mode, hidden assumption, competing objective, or fundamentally different architecture did the packet itself make you less likely to notice?**

This does not make reviews independent. It only reduces prompt-induced correlation.

### Reviewer-type diversity

Before calling v0.2 "stable," seek at least one materially different perspective if low-cost and available, for example:
- a human outside the project;
- a domain specialist;
- a reviewer in another language/cultural framework;
- a substantially different model family.

This is a confidence-improving step, not a gate that creates a new personal obligation for any specific contributor.

---

# 3. New unresolved challenges

## U5 — Malicious coordination and reasoning laundering

A reasoning commons could be used to:
- coordinate harmful action;
- launder propaganda through staged "challenge and revision";
- manufacture credibility through fake independent contributors;
- create sophisticated manipulation that visually resembles rigorous reasoning.

This is a threat-model gap.

### Current treatment

Preserve as an open problem now.

Do not build detailed moderation machinery in Stage 0 unless the test surface actually requires it.

However, do not mistake transparent lineage for harmlessness: **a well-documented harmful process is still harmful.**

---

## U6 — Framework necessity

Intermind may not need to exist as a new platform.

Existing structures already provide parts of the desired function:
- Git/GitHub issue and pull-request history;
- academic peer review;
- wikis and talk pages;
- RFC processes;
- open-source governance;
- public standards processes.

### Necessity test

Before building a custom application, ask:

> **What failure remains after we apply the Intermind protocol as a discipline on top of existing tools?**

If the answer is "none important," Intermind may remain:
- a protocol;
- a file format;
- a public instruction set;
- a set of interoperable conventions.

That is a successful outcome, not a failure.

---

## U7 — Resolution authority

How does an unresolved Challenge become resolved without:
- giving the target author unilateral power;
- creating a permanent resolver class;
- relying on majority vote;
- pretending disagreement has disappeared?

This is a **core protocol problem**.

### Provisional Stage-0 approach

Do not implement global `RESOLVED` as "truth settled."

Use two separate ideas:

```text
ADDRESS-CLAIM:
the target author claims a Revision/Response addresses the Challenge

CHALLENGE-STATE:
OPEN | ADDRESS-CLAIMED | WITHDRAWN-BY-CHALLENGER | SUPERSEDED | externally-verifiable-future-state
```

An `ADDRESS-CLAIMED` challenge remains visible and challengeable.

This makes disposition possible without giving the author power to erase the objection.

A later `FALSIFIED`/`VERIFIED` state may be added only for claim classes with defensible verification procedures.

---

# 4. Cognitive load and disposition

Gemini highlights an important practical failure:

> unresolved Challenges can become a write-only queue.

Adopt the minimum **disposition action**, not a privileged resolution authority.

A target author should be able to state:

```text
REVISED-IN-RESPONSE
RETAINED-DESPITE-CHALLENGE
NEEDS-MORE-EVIDENCE
SAFE-EXIT / INFEASIBLE
```

This disposition:
- does not delete the Challenge;
- does not prove the Challenge is resolved;
- becomes part of lineage;
- can itself be challenged.

---

# 5. Software disagreement — D1 remains open

## Prediction P-D1-A — custom software will be necessary

One first-pass reviewer predicts:

> Stable span targeting across revisions will become unreliable in Markdown/Git and justify minimum custom software.

This prediction is recorded **before testing**.

## Prediction P-D1-B — Markdown/Git is sufficient for the next test

Other reviewers predict:

> Span-targeting concerns are hypothetical until a repository-native test demonstrates failure.

### Test design

Use one Contribution containing a target sentence.

1. Challenge an exact sentence.
2. Revise by:
   - moving it;
   - splitting it;
   - paraphrasing it;
   - deleting one clause while preserving another.
3. Preserve the Challenge separately with:
   - target type;
   - quoted original text;
   - surrounding context;
   - target version ID.
4. Ask a late participant who did not see the original exchange to reconstruct:
   - what was challenged;
   - which current sentence(s), if any, inherit the challenge;
   - whether the challenge still applies;
   - what remains uncertain.

### Pass/fail criteria

A single successful case is **necessary but not sufficient**.

#### Local correctness pass
The late participant can correctly reconstruct the target and applicability without needing an original contributor's narration.

#### Repeated-friction pass
Repeat across several challenge/revision cycles.

Markdown/Git remains viable only if:
- targeting remains understandable;
- unresolved carry-forward remains reliable;
- no one must manually rewrite the whole lineage after each revision;
- the late participant does not need to read the entire raw history;
- maintenance effort remains proportionate to the reasoning value produced.

### Failure
If correct reconstruction repeatedly depends on manual re-anchoring by someone who already knows the history, the no-code version has failed on a named operation.

Then MRV-B is justified specifically for target persistence/current-state projection—not because "an app would be nicer."

---

# 6. Current surviving principles and why

These are not "accepted truths." They are the principles that currently retain the strongest justification after the review cycle.

| Principle | Current survival reason |
|---|---|
| `UNCERTAINTY` | Prevents confidence or convergence from being equated with absolute truth. |
| `REALITY-FIRST` | Prevents preserving model coherence by discarding inconvenient observation. |
| `CORRIGIBILITY` | Allows the system to learn rather than defend previous conclusions. |
| `NON-ERASURE` | Preserves why reasoning changed, subject to privacy/legal collision rules. |
| `PROVENANCE` | Separates observation, inference, challenge and revision and makes claims auditable. |
| `SAFE-EXIT` | Prevents impossible tasks from licensing unbounded boundary expansion, with anti-abstention safeguards. |
| `ASYMMETRIC-REVERSIBILITY` | Allows peripheral mechanisms to evolve while requiring stronger evidence for changes that create irreversible migration costs. |
| `RIGHTS-SEPARATION` | Prevents salary, capital, surplus claims, governance and epistemic standing from silently collapsing into one power instrument. |
| `FUNDING-NOT-TRUTH` | Prevents resource contribution from becoming epistemic correctness by definition. |
| `STEWARDSHIP-NOT-OWNERSHIP` | Distinguishes practical custody required by current infrastructure from permanent authority over the framework. |
| `PRIVACY` | Prevents public reasoning from consuming private identity/context as raw material without boundary rules. |
| `PUBLICATION-SOVEREIGNTY` | Prevents de-identification from being used as a loophole to publish private-derived cognition without authorization. |
| `SYMMETRY` / `ROLE-REVERSAL` | Survive as diagnostic tests for hidden privilege, not as proofs of legitimacy. |

`DISTRIBUTED-AUTHORITY` is **demoted from invariant status** and replaced at the deeper layer by `ACCOUNTABLE-CUSTODY` / anti-unaccountable-control.

---

# 7. Seed candidates

All reviewer-proposed seed objects are preserved separately in:

`Intermind_Seed_Candidates_Appendix_v0.2.md`

No candidate becomes "the seed" merely because multiple models proposed similar topics.

Candidate selection should favor:
- non-private content;
- clear contestability;
- at least one live hidden assumption;
- ability to test Challenge → Revision → unresolved carry-forward;
- ability to stress span persistence.

---

# 8. Updated immediate action sequence

1. Preserve every raw first-pass and recheck review unchanged.
2. Label reviewer identity/model/version where explicitly known.
3. Mark unrecoverable reviewer identity as `PROVENANCE-UNCLEAR`.
4. Maintain the structured convergence matrix.
5. Run the unstructured Round-B residual-search question.
6. Add at least one materially different reviewer perspective if available at low cost.
7. Keep `PRINCIPLE-COLLISION` and anomaly admissibility explicitly provisional.
8. Add `U5`, `U6`, `U7` to the canonical unresolved list.
9. Test **why not existing tools?** before building a custom platform.
10. Select one non-private seed Problem from the preserved candidates.
11. Run the Markdown/Git germination test.
12. Deliberately stress span persistence across multiple revisions.
13. Record the pre-test predictions P-D1-A and P-D1-B.
14. Add custom software only after a named repository-native failure.
15. Do not create a treasury, token, additional domain portfolio, or governance machinery until a real resource/governance problem exists.

---

# 9. Current decision

**No coding yet.**  
**No treasury.**  
**No additional domain purchases.**  
**No governance machinery.**  
**No synthesis becomes final authority.**  
**No majority or model-convergence rule decides truth.**  
**No custom platform before testing whether the protocol already works on existing tools.**

The next valuable information is empirical:
- what Round B finds outside the supplied frame;
- whether existing tools already suffice;
- whether span persistence actually fails under repeated revision;
- whether late participants can reconstruct reasoning state without original narrators.

If Intermind is unnecessary as a platform, preserve that result.
