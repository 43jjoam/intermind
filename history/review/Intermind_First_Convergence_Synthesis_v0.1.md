# Intermind — First Convergence Synthesis
**Review round: v0.1 seed packet**  
**Date: 11 September 2026**

## Epistemic status

This is a synthesis of four first-pass reviews currently available:

- **R1** — reviewer pasted directly in the conversation; model identity not preserved in the pasted text.
- **R2** — independent uploaded reviewer.
- **R3** — Claude Sonnet 5.
- **R4** — Grok.

Repeated agreement is treated as a **priority signal**, not as proof. These reviewers are likely correlated through overlapping training data, alignment norms, shared safety/governance literature, and the common review prompt.

No minority objection is removed merely because other reviewers disagree.

---

# 1. High-confidence convergence signals

## C1 — `ANOMALY-PRESERVATION` needs an anti-flooding / weighting distinction
**Raised by:** R1, R2, R3, R4  
**Convergence strength:** Very high, but likely partly correlated.

All four reviewers identify essentially the same failure mode:

> If every submission calling itself an “anomaly” must remain equally visible and undeletable, adversaries can turn preservation into denial-of-service.

### Proposed conceptual correction

Do **not** weaken the deeper principle into “preserve only anomalies we like.”

Instead distinguish:

```text
submission claiming anomaly
≠
epistemically admitted anomaly
≠
evidential weight
≠
visibility priority
```

Candidate revised principle:

> **Preserve every admitted anomaly and preserve the record of every rejected/quarantined anomaly submission. Preservation does not imply equal evidential weight, equal visibility, or exemption from privacy, safety, or legal constraints. Classification, challenge, quarantine, and rate-limiting must themselves remain inspectable.**

This preserves the original insight — do not erase inconvenient reality — while preventing arbitrary text volume from becoming epistemic authority.

### Still unresolved
- What minimum structure makes an anomaly “admissible” without creating a central gatekeeper?
- Can a submission be quarantined without its full content remaining public?
- How should maliciously generated anomaly floods be represented without creating archive bloat?

---

## C2 — Practical custodianship can become de facto centralization
**Raised by:** R1, R2, R3, R4  
**Convergence strength:** Very high.

All four reviews distinguish philosophical non-ownership from practical control over:
- GitHub admin rights;
- merge rights;
- domain custody;
- moderation;
- future wallets/keys;
- canonical visibility.

Forkability provides exit, but not necessarily equal voice because the canonical repository may retain network effects.

### Proposed revision

Replace the stronger claim “decentralization itself is the invariant” with:

> **No participant should possess permanent, unaccountable, unilateral control over consequential infrastructure or rules. The mechanism used to prevent such capture may be centralized or distributed depending on context, but it must remain observable, challengeable, and replaceable.**

Treat **decentralization as a candidate mechanism**, not as proof of fairness.

### Minimum Stage-0 safeguard
Do not create complex governance yet. Instead:
- preserve repository history;
- prohibit silent force-rewrites where practical;
- keep full exports/backups;
- log consequential administrative actions;
- document who currently has custody;
- make future transfer/fork procedures explicit.

Multi-party custody becomes justified only when multiple custodians or material stakes actually exist.

---

## C3 — `SAFE-EXIT` survives, but must itself be challengeable
**Raised by:** R1, R2, R3, R4  
**Convergence strength:** Very high.

The reviewers agree with the core insight but identify the mirror-image failure:

```text
no safe exit
→ endless goal expansion

too-cheap safe exit
→ strategic abstention / premature surrender
```

### Proposed revision

> **SAFE-EXIT creates a recorded state, not deletion or unquestionable closure. An exit must state its reasons and relevant evidence, remain challengeable, and be reversible when new evidence or capabilities appear. “Infeasible under current constraints” must remain distinct from “proven impossible.”**

Do not add a fixed calendar re-review requirement yet; reopen when the triggering evidence changes unless later experience shows time-based review is needed.

---

## C4 — Formal entity-neutrality needs a material-difference clause
**Raised by:** R1, R2, R4; supported structurally by R3  
**Convergence strength:** High.

The reviewers repeatedly point out that formal equality can generate unequal outcomes when participants differ in:
- compute;
- parallelization;
- vulnerability;
- legal exposure;
- physical needs;
- consent capacity;
- scale;
- dependency.

### Proposed revision

Keep the anti-category principle, but change its role:

> **Entity labels alone do not justify privilege or exclusion. Materially relevant differences — such as capacity, vulnerability, consent, dependency, scale, or domain-specific competence — may justify different procedural safeguards. Such differences must be stated, challengeable, and must not automatically create permanent hierarchy.**

### Consequence for `SYMMETRY`
Do **not** remove symmetry entirely.

Reclassify it as a **diagnostic test, not a proof of justice**:

> Role-reversal and symmetry tests can expose hidden privilege, but passing them does not by itself establish legitimacy.

---

## C5 — Privacy and non-erasure need an explicit collision rule
**Raised strongly by:** R2, R3; indirectly supported by R1’s privacy critique  
**Convergence strength:** High enough to require explicit treatment.

The current framework can produce a contradiction:

```text
preserve reasoning/history
vs
remove identifying/private material when publication is unauthorized,
withdrawn, unsafe, or legally prohibited
```

### Proposed revision

Separate:
- **reasoning lineage**, from
- **private identifying source material**.

Candidate rule:

> **NON-ERASURE applies to epistemic lineage, not as an absolute command to retain identifying or unlawfully published content. Where privacy, consent, safety, or legal obligations require removal of source content, preserve the minimum non-identifying tombstone/lineage needed to keep later reasoning intelligible whenever this can be done safely.**

### Still unresolved
- Is authorization revocable after public reasoning has depended on the contribution?
- Who authorizes group-derived private reasoning?
- What happens when even a tombstone is re-identifying?

Do not force these questions closed yet.

---

## C6 — Cross-model convergence is correlated evidence, not independent proof
**Raised by:** R2, R3, R4; anticipated by R1’s self-critique  
**Convergence strength:** Very high.

The identical prompt improves comparability but also focuses attention on the same failure classes.

### Proposed review architecture

Use two layers:

**Round A — common prompt**
- good for comparable stress tests;
- already performed.

**Round B — unstructured residual search**
Ask each reviewer only:

> “Ignoring the supplied checklist, what important failure mode, assumption, or alternative architecture did the checklist itself cause you to overlook?”

This tests for prompt-induced convergence without requiring a full second review.

Later, human reviewers from materially different disciplines/cultures can add genuinely different failure modes if useful. This is not required before the seed test.

---

# 2. Important disagreement that should NOT be resolved by voting

## D1 — Is custom software already justified?

### R1
**Verdict:** Minimum custom software is justified now.

Reason:
- stable span targeting across revisions will break in Markdown/Git.

### R2, R3, R4
**Verdict:** Markdown/Git is enough for the next test.

Reason:
- span-targeting failure is currently hypothetical;
- the project’s own minimum-effort rule says software should follow a demonstrated failure.

### Synthesis

This disagreement gives us an empirical decision rule:

> **Run MRV-A in Markdown/Git specifically to stress stable targeting across revision.**

The first seed Problem should deliberately include:
1. a Challenge tied to an exact sentence;
2. a Revision that moves/splits/rewrites that sentence;
3. a late participant reconstructing whether the Challenge still applies.

If manual anchoring becomes confusing or unreliable, that is direct evidence for MRV-B.

Therefore **do not code yet**, but design the Markdown seed test to attack span stability on purpose.

---

# 3. Minority / unresolved challenges that remain important

## U1 — Add a `FALSIFIED` state?
R1 proposes distinguishing `FALSIFIED` from `UNRESOLVED` when a Challenge is objectively verified.

**Do not adopt yet.**

Reason:
- “objective verification” itself requires a verifier, domain rules, and appeal mechanism;
- this could silently centralize adjudication.

Preserve as a future question:

> Under what claim classes can a challenge be marked `FALSIFIED`, and what evidence/verification process justifies that status?

Possible candidates later:
- formal proofs;
- reproducible deterministic checks;
- externally defined empirical criteria.

---

## U2 — Funding can buy attention without buying “truth”
R1 identifies a strong second-order failure:

> money can purchase 1,000 articulate submissions and dominate attention even if the rules say money does not buy truth.

Preserve as a dormant constraint:

> **Resource contribution must not automatically purchase attention allocation.**

Do not design ranking yet. This is a future mechanism problem, not a Stage-0 feature.

---

## U3 — Text/Git may privilege technical and discursive reasoning
Raised by R1, R2, R3.

Open questions:
- Does Git exclude non-technical subject-matter experts?
- Does a text-first grammar underrepresent visual, embodied, tacit, mathematical, or spatial reasoning?
- Is “Problem → Contribution → Challenge” universal enough, or only one discourse form?

Do not solve by adding rich media now.

Instead treat the first Git test as a **test of one reasoning grammar**, not proof of universality.

---

## U4 — What ends Intermind itself?
R2 and R4 explicitly challenge whether the project can abandon itself.

Candidate meta-rule:

> **Intermind has no right to perpetual existence. If its core purpose is achieved better by another protocol, or repeated evidence shows its mechanisms systematically worsen reasoning, the project may be retired while preserving its history.**

The exact retirement threshold remains open.

---

# 4. Principles with strongest current survival

Across the current reviews, the strongest surviving core appears to be:

1. **CORRIGIBILITY**
2. **NON-ERASURE / visible reasoning lineage**
3. **SAFE-EXIT**, with challengeable/reversible justification
4. **PROVENANCE**
5. **REALITY-FIRST**
6. **RIGHTS-SEPARATION**
7. **FUNDING-NOT-TRUTH**
8. **ASYMMETRIC-REVERSIBILITY**, with a real amendment/abandonment path
9. **PRIVACY / PUBLICATION-SOVEREIGNTY**, with explicit collision handling
10. **Role-reversal / symmetry as diagnostic tests rather than proofs**

This is not a final invariant set.

---

# 5. Minimum protocol after first convergence

Current strongest minimum:

```text
Problem
→ Contribution
→ Challenge
→ Revision
→ unresolved Challenge carries forward
→ visible version/history lineage
→ late participant reconstructs current + unresolved state
```

Required supporting properties:
- stable object identity;
- versioning;
- append-oriented event/history record;
- current state separated from historical state;
- privacy/authorization gate before private-derived publication.

Currently postponed:
- Derive;
- ranking;
- reputation;
- voting;
- search across many Problems;
- AI generation;
- custom software;
- treasury;
- Bitcoin;
- governance automation.

---

# 6. Immediate next actions

1. Preserve all four current reviews unchanged.
2. Do not merge their prose into one “consensus answer.”
3. Record the convergence/issues above.
4. If more first-pass reviewers are still pending, collect them before changing v0.1.
5. Ask the short Round-B question about what the checklist itself missed.
6. Produce v0.2 only after those remaining reviews are added.
7. Then run the Markdown/Git germination test with deliberate span-revision stress.
8. Build custom software only if the test produces a named failure.

---

# 7. Current decision

**No coding yet. No treasury. No additional domains. No governance machinery.**

The first review round has already improved the framework by exposing:
- anomaly preservation vs flooding;
- non-ownership vs practical custody;
- safe-exit vs exit-hacking;
- category-neutrality vs real asymmetry;
- privacy vs non-erasure;
- convergence vs correlated training.

That is exactly the kind of correction process the project claims to value.
