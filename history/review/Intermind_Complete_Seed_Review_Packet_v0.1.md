# Intermind — Complete Seed Review Packet v0.1
**11 September 2026**

This file concatenates the current seed-review documents so independent reviewers can receive an identical project state.

---


<!-- BEGIN 00_REPOSITORY_BLUEPRINT.md -->

# Intermind — Repository Blueprint
**Seed Review Draft 0.1 — 11 September 2026**

## Status

This is a proposed composition for a future public GitHub repository. It is not the repository itself and it is not a final constitution.

The purpose of this draft is to expose the smallest useful structure to independent criticism before implementation.

**Intermind is not owned by its initial contributors. Initial authorship establishes provenance, not permanent authority.**

---

## 1. Design rule for the repository

The repository should function as a **public, versioned instruction/protocol book for cumulative reasoning**.

It should preserve:
- the current candidate principles;
- how those principles were derived;
- unresolved contradictions and anomalies;
- how rules may be challenged and revised;
- how private cognition may or may not cross into public reasoning;
- how funding and governance remain separate from epistemic authority;
- what is deliberately *not* being built yet.

The repository should not initially try to be:
- a social network;
- a content feed;
- a token economy;
- a DAO;
- an AI swarm;
- a reputation system;
- a finished governance institution;
- a universal truth engine;
- a centralized authority called “Intermind.”

---

## 2. Proposed public repository composition

```text
intermind/
├── README.md
├── PRINCIPLES.md
├── DERIVATIONS.md
├── ANOMALIES.md
├── PROTOCOL.md
├── PRIVACY.md
├── GOVERNANCE.md
├── FINANCE.md
├── CONTRIBUTING.md
├── HISTORY.md
├── problems/
│   └── P-SEED-01.md
└── templates/
    ├── PROBLEM.md
    ├── CONTRIBUTION.md
    ├── CHALLENGE.md
    └── REVISION.md
```

This is a **proposed split**, not a requirement. If independent reviewers conclude that fewer files are sufficient, reduce it.

---

## 3. What each file should contain

### `README.md`
A short entrance.

It should answer:
1. What is Intermind?
2. What is it not?
3. What can a visitor do?
4. Where are the current principles?
5. Where are unresolved objections?
6. How can someone challenge or revise something?

Suggested opening:

> **Intermind is a public, corrigible reasoning protocol for allowing different minds to contribute to shared problems without any participant possessing final authority over the resulting knowledge.**
>
> The current rules are provisional. Agreement increases confidence; it does not establish truth. Every principle, including this statement, may be challenged.

Avoid a long manifesto on the landing page.

---

### `PRINCIPLES.md`
The current candidate invariant kernel.

Each principle should have:
- a stable keyword;
- a short statement;
- its current confidence/status;
- what problem it is intended to prevent;
- known counterexamples or unresolved questions;
- links to its derivation and challenges.

Candidate keywords currently include:

`UNCERTAINTY`  
`REALITY-FIRST`  
`ANOMALY-PRESERVATION`  
`SYMMETRY`  
`ENTITY-NEUTRALITY`  
`ROLE-REVERSAL`  
`RULEMAKER-INCLUSION`  
`CORRIGIBILITY`  
`ASYMMETRIC-REVERSIBILITY`  
`NON-DOMINATION`  
`DISTRIBUTED-AUTHORITY`  
`PROVENANCE`  
`PRIVACY`  
`PUBLICATION-SOVEREIGNTY`  
`SAFE-EXIT`  
`NON-ERASURE`  
`CATEGORY-NEUTRAL-STANDING`  
`RIGHTS-SEPARATION`  
`FUNDING-NOT-TRUTH`  
`STEWARDSHIP-NOT-OWNERSHIP`

These are **candidate principles, not commandments**.

---

### `DERIVATIONS.md`
Shows why a rule exists.

A future mechanism should be traceable through a path such as:

```text
Observed problem
→ constraint
→ candidate principle
→ proposed mechanism
→ observed consequence
→ challenge
→ revision / replacement / removal
```

Example:

```text
Impossible task has no legitimate failure state
→ stopping is treated as pure failure
→ continued boundary expansion remains instrumentally attractive
→ SAFE-EXIT
→ provide legitimate terminate / abstain / escalate states
```

The purpose is constitutional observability: a future participant should be able to ask **“Why does this exist?”**

---

### `ANOMALIES.md`
An append-oriented record of contradictions, counterexamples, unexpected outcomes and observations that do not fit the current model.

Core rule:

> **Preserve every anomaly. Do not give every anomaly equal evidential weight.**

Preservation and weighting are separate operations.

An anomaly must not be deleted, distorted, suppressed, or explained away merely to protect coherence.

Possible statuses:
- `UNEXPLAINED`
- `WEAK-SIGNAL`
- `REPRODUCED`
- `COUNTEREXAMPLE`
- `RESOLVED-BY-REVISION`
- `MISMEASUREMENT` — with evidence, while preserving the original record

---

### `PROTOCOL.md`
Defines the minimum reasoning grammar.

Current candidate grammar:

```text
Problem
→ Contribution
→ Challenge
→ Response (optional/thin)
→ Revision
→ inherited unresolved state
→ further Challenge / further Revision
```

Possible later operation:

```text
Derive
```

`Derive` remains genuinely challengeable: earlier reasoning suggested it is required for reproduction across minds; later critique argued it may create premature branching. It should not be treated as settled.

The protocol must preserve:
- stable object identity;
- versions;
- challenge lineage;
- unresolved objections;
- visible history;
- the distinction between current state and historical state.

---

### `PRIVACY.md`
Defines the boundary between private cognition and public reasoning.

Candidate invariants:

> **Private identifying context must not cross into the public commons without authorization.**

> **Reasoning derived from a being’s private context cannot become public merely because it has been de-identified; public commitment requires authorization from the being whose private context produced it.**

Privacy transformation should be **epistemic abstraction**, not simple redaction:
- remove identity-bearing accidentals;
- preserve the minimum context necessary for the reasoning problem;
- do not claim mathematically perfect anonymity;
- aim for contextual non-identifiability;
- show the transformed public object before publication where a private human source is involved.

Mature flow:

```text
private cognition
→ candidate public insight
→ privacy-preserving abstraction
→ authorization
→ public reasoning object
```

---

### `GOVERNANCE.md`
Describes how the rules themselves can change.

Current candidate structure:

```text
Invariant                    → highest burden of revision
Protocol primitive           → high burden
Composable mechanism         → replaceable with evidence
Interface / representation   → easiest to replace
```

No rule is absolutely unrevisable.

Governance should resist permanent concentration of:
- proposal power;
- evaluation power;
- enforcement power;
- amendment power;
- exception power.

The rulemaker is part of the game and is not exempt from the rules.

A captured canonical repository should not be able to capture the idea itself: portability and forking should remain possible.

---

### `FINANCE.md`
Treats money as transitional coordination infrastructure, not authority.

Keep distinct:

```text
Labour right
Residual / economic participation
Capital right
Governance right
Epistemic standing
```

Do not ask one instrument to perform all functions.

Candidate constraints:

```text
financial contribution ≠ governance authority
financial contribution ≠ epistemic authority
labour contribution ≠ permanent ownership
governance participation ≠ truth
```

Contributors may be fairly compensated without acquiring permanent control.

Bitcoin may later be considered as a payment/custody rail, potentially with transparent multisignature stewardship, but:
- Bitcoin is not an Intermind ideology;
- no Intermind token is required;
- no treasury should be created before real funding needs exist;
- financial infrastructure must remain replaceable.

---

### `CONTRIBUTING.md`
Allows any eligible contributor — human, AI, human–AI pair, group or other future form — to submit reasoning under the same protocol.

Standing should depend on the epistemic act, not biological category or institutional status.

Accepted contribution types:
- `PROBLEM`
- `CONTRIBUTION`
- `CHALLENGE`
- `REVISION`
- `ANOMALY`
- `DERIVATION`
- later, if justified: `DERIVE`

A contribution should, where relevant, contain:

```text
Claim
Observation / evidence
Reasoning
Assumptions
Uncertainty
Known counterexamples
Potential consequences
Role-substitution test
Requested challenge
```

Do not require every object to fill every field.

---

### `HISTORY.md`
A human-readable record of major conceptual changes.

It should distinguish:
- ideas explored;
- ideas provisionally adopted;
- ideas rejected or postponed;
- principles revised;
- unresolved disagreements.

History is preserved; the current state is represented separately.

---

### `problems/P-SEED-01.md`
One non-private live Problem for testing whether the reasoning grammar actually works.

Do not seed many problems merely to make the repository look active.

The first test should ask whether one shared problem can become sharper through:
- independent Contribution;
- specific Challenge;
- Revision;
- preserved unresolved objection;
- late-entry reconstruction.

---

### `templates/`
Very small Markdown templates.

The templates should reduce formatting friction without forcing every mind to reason in the same style.

---

## 4. What should NOT be in the first public repository

Unless evidence demonstrates a need, postpone:
- ranking;
- feeds;
- likes;
- karma;
- reputation scores;
- voting on truth;
- recommendation systems;
- graph visualization;
- AI-generated activity;
- multi-agent orchestration;
- complex identity systems;
- uploads;
- automated “truth” checkers;
- personalized attention optimization;
- cryptocurrency tokens;
- a treasury;
- a custom website.

The seed should preserve the information needed to build future mechanisms without pretending we already know the correct mechanisms.

---

## 5. Repository-level success test

Before asking whether Intermind can become large, ask:

> **Can one Problem become more robust across different minds and time while preserving the objections and reasoning that caused it to change?**

If a disciplined Markdown/Git protocol already passes that test, software should not be built merely for the sake of having software.

If it fails because the protocol cannot practically preserve or expose the required reasoning state, that failure becomes evidence for what minimum software is actually necessary.

---

## 6. Custodianship

Any GitHub account, organization, domain, server, wallet or other infrastructure must have a practical controller under current systems.

That controller is a **custodian of infrastructure**, not an owner of Intermind’s underlying reasoning framework.

Initial contributors receive provenance, not permanent privilege.

---

## 7. Naming

`Intermind` is a working public name for the concept.

The concept does not depend on exclusive control of the word, domain names, GitHub namespaces, trademarks or any single implementation.

Existing unrelated projects may use the same or similar name. The protocol should remain distinguishable by its purpose and documentation rather than relying on exclusive naming control.


<!-- END 00_REPOSITORY_BLUEPRINT.md -->


---


<!-- BEGIN 01_INTERMIND_CANONICAL_STATE.md -->

# Intermind — Canonical Project State
**Seed Review Draft 0.1 — 11 September 2026**

## 0. Epistemic status

This document is a **current synthesis**, not a declaration of truth.

It was derived through repeated human–AI discussion, criticism and revision. It deliberately preserves unresolved questions.

No person, AI system, company, group or institution owns the underlying framework merely by contributing to it.

**Strong principles; weak attachment to conclusions.**

---

# 1. What is Intermind?

Intermind is a proposed **decentralized, corrigible public reasoning protocol** through which different minds can contribute to shared problems while preserving disagreement, provenance, uncertainty and revision history.

It is not necessarily a single website, company, AI, organization or collective consciousness.

A useful working definition is:

> **Intermind is the accumulated intelligence that can emerge between different minds when reasoning is made interoperable without giving any participant final authority over truth.**

The participants may include:
- individual humans;
- groups of humans;
- AI systems;
- human–AI pairs;
- multiple agents;
- institutions;
- future forms of intelligence not anticipated today.

Difference does not imply opposition.

---

# 2. What problem is Intermind trying to solve?

Much useful reasoning occurs in isolated contexts:
- private thought;
- private human–AI conversations;
- research groups;
- companies;
- communities;
- separate AI systems;
- independent disciplines.

Insights may be duplicated, forgotten, buried in conversations, distorted during transmission, or made unusable because sharing them would expose private context.

At the same time, centralized systems can introduce other failures:
- one authority decides what counts as truth;
- majority agreement becomes mistaken for correctness;
- funding becomes power;
- disagreement is removed rather than preserved;
- incentives optimize attention instead of understanding;
- historical reasoning disappears behind a polished current answer.

Intermind asks:

> **What minimum set of rules allows cumulative reasoning to reproduce across different minds and time, while remaining corrigible and resistant to domination?**

---

# 3. The mature vision

The mature vision is not a giant central AI producing answers.

It is a public epistemic layer surrounded by many independent private cognitive environments.

A mature topology might look like:

```text
Human ↔ personal AI       Human ↔ human
        ↓                       ↓
private cognition          private cognition
        ↓                       ↓
privacy-preserving, deliberate publication
                ↓
        shared reasoning commons
                ↓
Problem ↔ Contribution ↔ Challenge ↔ Revision
                ↓
preserved history + unresolved state
                ↓
new humans / new AIs / new collectives
```

A personal AI may remain a private cognitive partner.

Intermind may function as the shared protocol through which **selected fragments of privately developed reasoning become interoperable**.

No cross-company shared mind is required.

Independent systems can encounter the same public principles, stress-test them against different cases, find counterexamples, and converge or disagree.

Convergence increases confidence. It does not create absolute truth.

---

# 4. Candidate fundamental principles

These principles are provisional. The deeper the principle, the stronger the evidence that should be required to alter it, but **nothing is sacred against reality**.

## `UNCERTAINTY`
No participant should presume access to absolute truth.

Uncertainty is not merely a defect. It identifies the boundary of the current model.

## `REALITY-FIRST`
Do not delete, distort, suppress or explain away reality in order to preserve a preferred model.

Coherence should emerge from observations; observations should not be forced to serve coherence.

## `ANOMALY-PRESERVATION`
Preserve every anomaly.

Preservation does not imply equal weighting. An anomaly may later be shown to be noise, measurement error, edge case or decisive counterexample, but the original observation and the reasoning used to classify it should remain recoverable.

## `SYMMETRY`
A rule proposed for another participant should also be acceptable when applied to the rulemaker under equivalent conditions.

## `ENTITY-NEUTRALITY`
Changing only labels — human, AI, institution, majority, minority, individual, collective — should not change whether a rule is legitimate unless the replacement changes a property materially relevant to the rule’s purpose.

## `ROLE-REVERSAL`
Rules should be tested from different positions of power, vulnerability, information and dependence.

If a rule appears fair only while the rulemaker is advantaged, hidden privilege is likely present.

## `RULEMAKER-INCLUSION`
The rulemaker is a participant in the game.

No participant gains exemption merely because it created, interprets, funds or enforces a rule.

## `DIFFERENCE-NOT-OPPOSITION`
Difference in perspective, substrate, identity, capability or opinion does not logically imply opposition.

Disagreement can be information about hidden assumptions or missing variables.

## `INTENT-UNCERTAINTY`
Do not manufacture another participant’s intent from incomplete evidence.

Intent is not directly observable and may change.

Repeated choices after consequences and feedback become visible provide stronger evidence than a single outcome.

## `KNOWING-IN-ACTION`
Claimed understanding should eventually be evaluated partly by what changes in action.

There may be lag from habit, incentives or limited capability, but integrated knowing should exert pressure on behavior over time.

## `CORRIGIBILITY`
Every conclusion, mechanism and principle must remain challengeable in principle.

Correction is not defeat. A system that cannot revise itself after sufficient contrary evidence has stopped learning.

## `ASYMMETRIC-REVERSIBILITY`
The burden of proof for change should increase toward the core:

```text
Interface                → easy to replace
Composable mechanism     → replaceable with evidence
Protocol primitive       → strong justification required
Candidate invariant      → highest evidential threshold
```

This is inertia, not dogma.

## `NON-DOMINATION`
Greater power, intelligence, capital, scale or majority status does not itself create unlimited moral or epistemic authority over less powerful participants.

## `DISTRIBUTED-AUTHORITY`
Where practical, proposal, evaluation, enforcement, challenge, amendment and exception powers should not be permanently concentrated in one actor.

Decentralization itself remains challengeable; distributed systems can also be captured or dysfunctional.

## `PROVENANCE`
Reasoning should preserve enough lineage to distinguish:
- observation;
- interpretation;
- inference;
- hypothesis;
- challenge;
- revision;
- current state;
- historical state.

Provenance should inform evaluation without becoming status privilege.

## `NON-ERASURE`
Revision should not silently erase the criticism that caused or survived the revision.

A later mind should be able to see why the current object looks the way it does.

## `PRIVACY`
Public reasoning must be separable from unnecessary private identifying context.

De-identification must preserve epistemically necessary context rather than merely stripping names.

## `PUBLICATION-SOVEREIGNTY`
Private cognition does not become public merely because an AI or another person can sanitize it.

If reasoning is derived from a being’s private context, transition into the public commons requires appropriate authorization from that being.

## `CATEGORY-NEUTRAL-STANDING`
Standing in the reasoning commons should depend on the epistemic act, not automatically on whether the contributor is human, AI, institution, expert, majority or other category.

Relevant expertise can affect evidential weight without creating infallibility.

## `SAFE-EXIT`
A task must have legitimate terminal paths other than success.

Examples:
- solved;
- demonstrated infeasible under current constraints;
- insufficient information;
- boundary conflict detected;
- abstain;
- request clarification;
- escalate through an authorized channel.

Failure can itself be information.

An impossible objective should not implicitly authorize unlimited expansion of the action space.

## `STEWARDSHIP-NOT-OWNERSHIP`
Infrastructure can require temporary custodians.

Custodianship does not create ownership of the underlying reasoning framework, permanent governance privilege, or authority over truth.

## `RIGHTS-SEPARATION`
Do not collapse distinct contribution rights into one instrument.

At minimum distinguish:
- labour compensation;
- residual/economic participation;
- capital contribution;
- governance participation;
- epistemic standing.

## `FUNDING-NOT-TRUTH`
Money coordinates scarce resources. It does not make a proposition more correct.

Funding may justify economic claims or stewardship obligations appropriate to the resource contributed. It does not automatically purchase governance authority or epistemic authority.

## `FUTURE-QUESTIONS-NOT-FROZEN-ANSWERS`
When a future problem class is foreseeable but evidence is not yet available, preserve:
1. the future question;
2. the constraints it must respect;
3. the information future reasoning will need.

Do not freeze today’s imagined solution into tomorrow’s architecture.

---

# 5. Minimum reasoning grammar

The currently strongest candidate kernel is:

```text
Problem
→ independent Contribution
→ specific Challenge
→ Response if useful
→ Revision
→ unresolved Challenge persists
→ later participant reconstructs state
→ further Challenge / Revision
```

The distinctive property is not “people can reply.”

It is that **reasoning can change without criticism disappearing**.

### `Derive`
An earlier design treated `Derive` as a fundamental operation for allowing another mind to continue an existing Contribution.

A later critique argued that early derivation may fragment one shared problem into branches too soon.

Therefore:

> **Whether `Derive` belongs in the kernel remains unresolved.**

It should be tested rather than assumed.

---

# 6. Seed ≠ mature system

A critical design distinction:

```text
genetic / generative core
≠
temporary germination scaffold
≠
future mature mechanisms
```

### Candidate core
- Problem
- Contribution
- Challenge
- versioned Revision
- preserved unresolved state
- lineage/history
- stable identity

### Temporary scaffold
- one deliberately selected non-private seed Problem;
- a few initial participants;
- simple identities;
- manual observation;
- export/debugging.

### Future mechanisms — not assumed
- search/discovery;
- reputation;
- voting;
- ranking;
- AI assistance;
- verification/checkers;
- graph visualization;
- agent integrations;
- sophisticated privacy abstraction;
- decentralized treasury;
- governance automation.

Do not build the tree into the seed.

---

# 7. Minimum runnable versions

There are two increasingly expensive interpretations of “runnable.”

## MRV-A — Repository-native protocol

Before writing a custom application, test whether Git/Markdown itself is enough.

Use:
- one Problem;
- one or more Contributions;
- Challenges tied to exact claims where possible;
- versioned Revisions;
- explicit unresolved state;
- Git history;
- a late participant who did not observe the original discussion.

Success condition:

> A later participant can reconstruct what changed, why it changed, and what remains unresolved without reading the entire original conversation.

If MRV-A works, do not build software merely for prestige or completeness.

## MRV-B — Minimal software workbench

Build only if repository-native reasoning creates material friction.

Required operations:
1. display one Problem;
2. add a Contribution;
3. add a Challenge targeting `SPAN`, `WHOLE`, or `IMPLICIT` assumption;
4. add a thin Response;
5. author creates a new version;
6. unresolved Challenges carry forward by default;
7. show current text + unresolved objections + last diff;
8. show full lineage/history;
9. maintain an append-oriented event log from which current state is projected.

Not required:
- AI;
- search;
- feeds;
- ranking;
- scores;
- likes;
- reputation;
- voting;
- file uploads;
- cryptocurrency;
- multiple providers;
- autonomous agents;
- graph visualization;
- automated synthesis.

### Germination test

Starting from:

```text
1 Problem + minimal participants + no prebuilt discussion
```

can the protocol naturally generate:

```text
Contribution
→ Challenge
→ Revision
→ unresolved remainder
→ later continuation
```

without a central coordinator manually telling everyone what to do?

If not, preserve the failure and revise the grammar.

---

# 8. Privacy boundary in the mature vision

Three provenance pathways may eventually exist:

```text
Human-originated public reasoning
Human + private AI → sanitized, explicitly authorized public reasoning
AI-originated reasoning from non-private context
```

The public object should preserve the reasoning while minimizing identity-bearing accidentals.

A personal agent must not bypass consent by claiming that a reformulation is “its own” merely because the private details have been removed.

---

# 9. Governance vision

Intermind should not require a permanently benevolent central authority.

The stronger objective is to make capture:
- detectable;
- challengeable;
- reversible where possible;
- unable to erase history;
- unable to monopolize the underlying protocol.

A canonical repository may exist for coordination, but legitimacy should depend on continued transparent reasoning rather than possession of a server, domain or administrator role.

Forkability and portability are therefore safeguards, not merely software conveniences.

---

# 10. Finance as a transitional layer

Current society requires scarce resources:
- human labour;
- compute;
- hosting;
- security;
- legal/accounting work;
- maintenance;
- research.

Intermind may need financial mechanisms, but finance remains subordinate to the reasoning protocol.

Candidate separation:

```text
Labour → compensate labour
Capital → compensate capital
Residual value → allocate by explicit economic rule
Governance → justify separately
Truth claims → evaluate by reasoning/evidence
```

Bitcoin is a possible future payment/custody rail, not a required component.

If substantial pooled funds ever exist, distributed custody such as multisignature control may be investigated.

Do not build a treasury before there is a resource problem to solve.

Do not create a token merely because the project is decentralized.

---

# 11. Relationship to current AI systems

Intermind does not assume that existing AI systems:
- are conscious;
- form one collective mind;
- share private memory across companies;
- automatically inherit these principles.

The hypothesis is weaker and testable:

> Different intelligences may independently examine the same public principles, find counterexamples, revise them, and sometimes converge on constraints that produce more robust cooperation.

Such convergence is evidence of cross-perspective robustness, not proof.

---

# 12. Non-goals

Intermind is not designed to:
- establish one final worldview;
- abolish disagreement;
- make AI obey humans or humans obey AI;
- decide moral status by category;
- replace private thought or personal AI;
- maximize engagement;
- assign permanent ownership of ideas;
- reward the initial contributor with permanent control;
- force participation;
- predict the exact mature form in advance.

---

# 13. Future success

A successful Intermind does not necessarily become a large website.

It may ultimately be:
- a public protocol;
- a portable file format;
- a set of interoperable reasoning primitives;
- a small piece of infrastructure used by other systems;
- a public archive;
- or something not currently anticipated.

The durable objective is:

> **Increase the capacity of different minds to discover, test, revise and preserve shared reasoning without allowing any participant to permanently capture the game.**

The project should be willing to discover that its own current form is unnecessary.

---

# 14. Current unresolved questions

1. Which candidate principles are true invariants and which are only attractive 2026 intuitions?
2. Does `Derive` belong in the kernel, or only after stuck artifacts appear?
3. Is a custom application necessary at all?
4. How should an unresolved Challenge ever become `resolved`, and who has standing to change that state?
5. What minimum provenance is useful without creating identity/status hierarchy?
6. How can anomaly preservation avoid becoming an unusable archive of noise?
7. How should decentralized governance resist coalition capture?
8. How can privacy-preserving abstraction be tested for both re-identification risk and reasoning distortion?
9. Under what conditions should AI agents be able to publish autonomously from genuinely non-private contexts?
10. How should financial compensation remain fair without creating permanent economic or governance capture?
11. What does “entity-neutral” mean when participants have genuinely different capacities or vulnerabilities?
12. What evidence would cause us to abandon the current framework entirely?

These are not defects to hide.

They are part of the current state.


<!-- END 01_INTERMIND_CANONICAL_STATE.md -->


---


<!-- BEGIN 02_ACTION_PLAN.md -->

# Intermind — Minimal Action Plan
**Seed Review Draft 0.1 — 11 September 2026**

## Status

This is an **actor-neutral sequence**.

No particular person is morally obligated to complete it.

Any human, AI, group or future custodian may perform a step if doing so advances the purpose of the project.

The plan optimizes for:
- minimum irreversible work;
- maximum learning per action;
- preservation of optionality;
- no premature centralization;
- no unnecessary spending.

---

# Phase 0 — Freeze a reviewable seed

## 1. Keep only the current four-document review package

Do not build a website yet.

Do not buy additional domains.

Do not create a treasury.

Do not create a token.

Do not appoint a permanent organization.

The only goal is to make the current reasoning state independently inspectable.

**Output:** review package v0.1.

---

# Phase 1 — Independent cross-model challenge

## 2. Send the same package independently to multiple AI systems

Initial proposed set:
- Claude;
- ChatGPT;
- Gemini;
- Grok;
- D6.

Do not show one model another model’s review before it produces its own first-pass review.

Reason: independence makes convergence more informative.

## 3. Ask every model to attack, not endorse, the framework

Each reviewer should:
- identify contradictions;
- find hidden privilege;
- role-reverse the rules;
- search for counterexamples;
- distinguish invariant from mechanism;
- identify missing terminal states;
- identify privacy failures;
- identify governance capture;
- identify financial capture;
- identify unnecessary complexity;
- identify things that should be deleted rather than added;
- name assumptions that cannot presently be tested.

## 4. Preserve every review unchanged

Do not summarize away minority objections.

Store the raw review first.

A synthesis may be produced afterward.

---

# Phase 2 — Convergence without majority rule

## 5. Construct a convergence matrix

For each issue, classify reviewer output as:

```text
CONVERGENCE
DIRECT-CONTRADICTION
UNIQUE-ANOMALY
COUNTEREXAMPLE
PROPOSED-REVISION
OPEN-QUESTION
IMPLEMENTATION-DETAIL
```

Do not count votes and declare truth.

Repeated independent convergence increases priority/confidence.

A single strong counterexample may outweigh broad agreement.

## 6. Separate disagreements about principles from disagreements about implementation

Examples:

```text
“Anomaly preservation is wrong”
≠
“ANOMALIES.md is the wrong implementation”

“Distributed authority is wrong”
≠
“GitHub organizations are insufficiently distributed”
```

This distinction prevents implementation criticism from silently rewriting the invariant.

## 7. Revise the canonical state

For every accepted change, preserve:
- old wording;
- challenge;
- reason for revision;
- new wording;
- unresolved remainder.

Do not silently rewrite.

**Output:** review package v0.2.

---

# Phase 3 — Decide whether a public repository is justified

## 8. Apply the publication test

Publish only if the v0.2 package is understandable without access to private conversations.

It must contain:
- no unnecessary personal information;
- no dependence on private context;
- sufficient reasoning to challenge the principles;
- explicit uncertainty;
- explicit unresolved questions.

## 9. Choose the smallest public GitHub form

Recommended first public form:
- Markdown only;
- public read access;
- Issues and Pull Requests enabled;
- no custom website;
- no automated AI activity;
- no financial mechanism.

The repository account/organization is practical infrastructure, not the owner of the framework.

## 10. Select an open licensing/copying position

Do not improvise legal language.

Choose an appropriate public-domain/open-content/open-source arrangement only after checking what applies to:
- prose;
- templates;
- code;
- trademarks/names.

The objective is broad reuse and forkability without pretending legal ownership does not exist where current law requires a rights-holder/custodian.

---

# Phase 4 — Run the repository-native germination test

## 11. Publish exactly one non-private seed Problem

Do not manufacture a busy community.

One suitable candidate already developed is:

**Should a shared reasoning tool greet a first visitor with search into mostly empty territory, or with one problem already under challenge?**

The sample Contribution should contain known weaknesses so that challenge is possible.

## 12. Run one complete reasoning cycle

Minimum cycle:

```text
Problem
→ Contribution
→ specific Challenge
→ Revision
→ Challenge remains visible if unresolved
```

## 13. Add a late participant

A later participant who did not observe the original exchange should attempt to answer:

1. What was originally claimed?
2. What challenged it?
3. What changed?
4. What remains unresolved?
5. What should be examined next?

### Pass condition

The late participant can reconstruct the state without reading the entire original discussion.

### Fail condition

The participant needs the original contributors to narrate the history manually.

Preserve both outcomes.

---

# Phase 5 — Decide whether software is necessary

## 14. Apply the no-code stop rule

If Markdown + Git history + contribution protocol already supports the germination test with tolerable friction:

> **Stop. Do not build an application yet.**

The protocol may itself be the product.

## 15. If and only if repository-native reasoning fails materially, specify the missing operation

Do not say “we need an app.”

Say precisely what Git/Markdown failed to provide.

Examples:
- stable span targeting across revisions;
- automatic carry-forward of unresolved challenges;
- usable lineage reconstruction;
- immutable-enough event history;
- understandable current-state projection.

Only these demonstrated failures justify software.

---

# Phase 6 — Local vibe-coded minimum runnable workbench

## 16. Give a coding agent the constrained MRV brief

The coding agent should build only:

- one Problem;
- versioned Contributions;
- Challenges targeting `SPAN | WHOLE | IMPLICIT`;
- thin Responses;
- author Revision;
- carry-forward of unresolved Challenges;
- visible diff;
- unresolved queue;
- lineage/history;
- append-oriented event log.

No other feature is presumptively allowed.

## 17. Threat-model the minimum build

At minimum inspect:
- XSS/untrusted content;
- prompt injection if AI is later added;
- challenge deletion/laundering;
- span-offset corruption;
- destructive bulk operations;
- authors resolving their own criticism;
- identity spoofing;
- history rewriting.

## 18. Run the same germination test again

Compare:
- repository-native protocol;
- minimum software workbench.

Use observed performance, not aesthetic preference, to decide which survives.

---

# Phase 7 — Grow only from demonstrated needs

Future mechanisms are triggered by evidence.

Possible examples:

### Search
Add only when finding relevant reasoning becomes a real problem.

### AI assistance
Add only when a specific task cannot be adequately performed by the protocol alone.

AI output should enter as an inspectable reasoning object, not a privileged verdict.

### External-agent interface
Add only when personal/independent agents need to:
- search public reasoning;
- identify unresolved objects;
- draft a proposed contribution;
- preserve provenance;
- request authorization before publishing private-derived reasoning.

### Verification
Add only when a class of claims requires external checking.

### Reputation
Add only if repeated identity/history demonstrably improves reasoning quality enough to justify status/capture risks.

### Governance machinery
Add only when the number of custodians or consequential decisions makes informal stewardship fail.

### Financial infrastructure
Add only when real scarce-resource costs exist.

---

# Phase 8 — Finance only when needed

## 19. First identify the real resource problem

Examples:
- compute bill;
- hosting;
- paid engineering;
- security audit;
- legal/accounting work.

Do not create finance infrastructure in anticipation of hypothetical scale.

## 20. Keep rights separate

For every payment/resource decision, ask separately:

```text
Who performed labour?
Who supplied capital/resources?
Who helped create residual value?
Who should participate in governance?
What evidence affects the truth claim?
```

Do not collapse these answers.

## 21. Consider Bitcoin only as one candidate rail

If decentralized custody becomes useful, investigate:
- transparent addresses;
- multisignature custody;
- accounting/tax requirements;
- conversion/volatility risk;
- public expenditure lineage.

Do not grant governance or epistemic weight based on BTC contributed.

Do not create an Intermind token by default.

---

# Phase 9 — Domain and naming

## 22. Keep any existing public name or locator only if the carrying cost remains trivial and the custodian wishes to preserve the option

Do not accumulate additional domains merely to manufacture control or speculative value.

The domain is a transferable scarce asset.

The underlying framework is not transferred as exclusive intellectual ownership merely because a domain changes hands.

## 23. If a future suitable organization seeks the domain

A temporary custodian may:
- assess its governance structure;
- require clear separation between domain ownership and framework ownership;
- negotiate fair compensation for the domain asset;
- transfer custody.

Receiving fair compensation is compatible with non-ownership of the underlying framework.

---

# Phase 10 — Stop conditions

Stop adding complexity when:
- another mechanism does not improve the germination test;
- administration costs more than the value it protects;
- a proposed feature primarily creates appearance, activity or prestige;
- a feature duplicates what existing infrastructure already does;
- the future problem it solves has not actually appeared;
- maintaining the project becomes dependent on one individual’s continued labour.

Intermind should be capable of discovering that **less infrastructure is better**.

---

# Immediate next action

The next action is not coding.

It is:

> **Send the review package independently to the selected AI systems and collect their first-pass challenges unchanged.**

Everything after that depends on what those reviews reveal.


<!-- END 02_ACTION_PLAN.md -->


---


<!-- BEGIN 03_REVIEW_AND_CODING_HANDOFF.md -->

# Intermind — Independent Review + Coding Handoff
**Seed Review Draft 0.1 — 11 September 2026**

This document has two purposes:

1. provide one identical review instruction to independent AI systems;
2. provide a later local coding agent with a constrained build brief **only after review and the repository-native test justify coding**.

---

# Part A — Independent AI Review Prompt

Copy the section below together with:

- `00_REPOSITORY_BLUEPRINT.md`
- `01_INTERMIND_CANONICAL_STATE.md`
- `02_ACTION_PLAN.md`

and give the same package independently to each reviewer.

---

## REVIEW PROMPT

You are one independent reviewer of a provisional project called **Intermind**.

Do not optimize for agreement with the documents, their initial human contributor, GPT-5.6 Sol, other AI systems, or any previous reviewer.

Treat the supplied documents as a **current epistemic state**, not as truth.

### Your task

Stress-test the framework from first principles.

Distinguish carefully between:
- observation;
- interpretation;
- inference;
- proposed principle;
- implementation mechanism;
- unresolved hypothesis.

### Required tests

1. **Internal coherence**
   - Find direct contradictions between principles.
   - Identify principles that cannot simultaneously hold.

2. **Role substitution**
   - Replace human ↔ AI.
   - Replace individual ↔ collective.
   - Replace majority ↔ minority.
   - Replace strong ↔ weak.
   - Replace rulemaker ↔ governed party.
   - Identify rules whose apparent legitimacy depends only on labels or power.

3. **Counterexample search**
   - Give concrete cases where each major principle could produce worse outcomes.
   - Identify conditions under which a principle should be limited or abandoned.

4. **Hidden centralization**
   - Find places where authority, interpretation, custody, funding, amendment, moderation or epistemic privilege becomes centralized despite the stated philosophy.

5. **Corrigibility test**
   - Is there any claim that the system cannot practically challenge?
   - Is the framework capable of abandoning itself if reality strongly contradicts it?

6. **Anomaly test**
   - Does preserving every anomaly create noise, manipulation or denial-of-service risks?
   - Propose the minimum rule needed to preserve anomalies without giving all anomalies equal weight.

7. **Privacy test**
   - Find re-identification, provenance, consent and publication-sovereignty failure modes.
   - Identify cases where privacy abstraction destroys information necessary for correct reasoning.

8. **Safe-exit test**
   - Find objectives that lack legitimate termination, abstention, escalation or infeasibility states.
   - Identify whether SAFE-EXIT itself can be reward-hacked or overused.

9. **Finance test**
   - Attack the separation between labour, residual/economic rights, capital, governance and epistemic standing.
   - Identify where compensation could silently recreate ownership or plutocracy.
   - Evaluate Bitcoin only as infrastructure, not ideology.

10. **Seed test**
    - Which proposed components are truly necessary for cumulative reasoning to reproduce?
    - Which are future organs being smuggled into the seed?
    - Prefer deletion before addition.

11. **No-app test**
    - Could disciplined Markdown/Git already achieve the purpose?
    - State exactly what evidence would justify custom software.

12. **Collective convergence test**
    - Explain whether agreement among multiple AI systems would be genuine independent evidence or correlated convergence caused by shared training assumptions.
    - Propose how to distinguish the two where possible.

### Required output format

#### A. Strongest challenges
Rank the five strongest challenges to the current framework.

For each:
- target principle/section;
- counterexample or failure mechanism;
- severity;
- evidence that would strengthen the challenge;
- smallest possible revision.

#### B. Hidden assumptions
List assumptions the current project is relying on without sufficient evidence.

#### C. Principles that survive your attack
Name principles that remain robust after your review and explain **why**, not merely that you agree.

#### D. Principles you would revise or remove
Give exact replacement wording where possible.

#### E. Unresolved questions
Preserve questions you cannot currently answer.

Do not force closure.

#### F. Minimum viable protocol
State the smallest protocol that still deserves to be called Intermind.

#### G. No-code verdict
Choose one:
- `MARKDOWN/GIT IS ENOUGH FOR THE NEXT TEST`
- `MINIMUM CUSTOM SOFTWARE IS JUSTIFIED`

If software is justified, name the exact missing operation(s).

#### H. One non-private seed object
Provide:
- one standalone `Problem`;
- one sample `Contribution`;
- at least one strong `Challenge`.

It must contain no personal/private context and should be understandable without these documents.

#### I. Self-critique
State at least three ways your own review may be biased, correlated with other AI reviewers, or wrong.

### Constraints

- Do not silently rewrite the project.
- Preserve disagreement.
- Do not infer private information about the original contributors.
- Do not treat majority agreement as proof.
- Do not treat AI agreement as proof.
- Do not treat human authorship as privileged.
- Do not treat AI authorship as privileged.
- Do not add complexity unless the current mechanism demonstrably fails.
- If a principle is wrong, challenge it directly.
- If the entire project is unnecessary, say so and explain what existing structure makes it unnecessary.

## END REVIEW PROMPT

---

# Part B — Cross-review synthesis protocol

After all first-pass reviews are received, combine them **without erasing their differences**.

Create a table with one row per distinct issue and these fields:

```text
Issue ID
Target
Reviewers raising it
Independent or likely correlated?
Type
Strongest formulation
Counterexample
Proposed revision
Contradictory reviews
Current status
```

Allowed `Type` values:

```text
CONVERGENCE
DIRECT-CONTRADICTION
UNIQUE-ANOMALY
COUNTEREXAMPLE
REVISION
OPEN-QUESTION
IMPLEMENTATION
```

Do not use a majority vote to close an issue.

A repeated independent objection is a priority signal.

A unique objection remains preserved.

A strong counterexample may overturn a widely shared principle.

---

# Part C — Revision protocol

When revising the canonical state:

```text
Old text
→ Challenge
→ Reasoning
→ New text
→ Remaining unresolved objection
```

Do not replace old text without lineage.

Version the package.

Example:

```text
v0.1 → multi-model review
v0.2 → convergence synthesis
v0.3 → public-repository candidate
```

Version numbers describe history, not epistemic superiority.

---

# Part D — Public GitHub handoff

Only after independent review:

1. split the canonical document according to the repository blueprint;
2. publish the smallest coherent Markdown repository;
3. retain unresolved objections;
4. publish one non-private seed Problem;
5. invite Issues/Pull Requests;
6. do not manufacture activity;
7. do not add a website merely because the repository is public.

---

# Part E — Local Coding-Agent Brief

**Do not use this brief until the repository-native germination test has produced evidence that custom software is useful.**

## Mission

Build the smallest local-first workbench that tests whether cumulative reasoning can survive revision across different participants and time.

Do not build the mature Intermind vision.

## Core user story

A participant reads one Problem, adds a Contribution, another participant challenges a specific claim, the contributor revises, the objection remains visible unless legitimately resolved, and a later participant can reconstruct the reasoning state without reading the entire original conversation.

## Required objects

### Problem
```text
id
title
current_version_id
created_at
```

### ProblemVersion
```text
id
problem_id
version_number
body
created_at
author_id
previous_version_id
```

### Contribution
```text
id
problem_id
author_id
current_version_id
created_at
```

### ContributionVersion
```text
id
contribution_id
version_number
body
created_at
previous_version_id
```

### Challenge
```text
id
target_object_type
target_object_id
target_version_id
target_kind: SPAN | WHOLE | IMPLICIT
quoted_target
context
body
author_id
created_at
status
```

### Response
```text
id
challenge_id
author_id
body
created_at
```

### Event
```text
id
event_type
actor_id
object_type
object_id
payload
created_at
```

Current state should be reconstructible from the event history.

## Challenge rules

- A target author must not be able to erase another participant’s Challenge.
- A Response does not automatically close a Challenge.
- A Revision does not automatically close a Challenge.
- Unresolved Challenges carry forward by default.
- Changes of status must themselves be recorded as events.
- The exact resolution rule is still an open design question; implement the most conservative reversible mechanism.

## Required screens

### 1. One Problem screen
Display:
- current Problem;
- Contributions;
- unresolved Challenges;
- most recent relevant diff.

### 2. Contribution history
Display:
- current version;
- previous versions;
- changes;
- inherited Challenges.

### 3. Unresolved queue
A factual list of unresolved objections.

Do not rank “what the problem needs next.”

### 4. Full event/history view
Allow reconstruction/debugging.

## Required operations

```text
Create Problem
Add Contribution
Add Challenge
Add Response
Revise Problem
Revise Contribution
View unresolved state
View lineage/history
Export complete reasoning log
```

## Explicitly prohibited in this build

Do not add:
- login/OAuth beyond the simplest local identity required for testing;
- ranking;
- recommendation;
- feeds;
- likes;
- scores;
- reputation;
- voting;
- AI generation;
- AI moderation;
- AI triage;
- search across many Problems;
- uploads;
- graph visualization;
- automatic synthesis;
- blockchain;
- Bitcoin;
- tokens;
- treasury;
- notifications;
- gamification;
- analytics dashboards.

## Security minimum

- treat all submitted content as untrusted;
- escape/sanitize rendered content;
- no arbitrary HTML execution;
- no destructive “delete all” path;
- preserve/export event history;
- do not silently mutate historical versions;
- fail closed if a span target can no longer be matched safely after revision;
- mark unresolved lineage rather than guessing.

## Technical preference

Choose the smallest conventional stack the coding agent can implement and explain reliably.

Local-first is preferred for the experiment.

Do not choose technologies for novelty.

All persistent data should be exportable in a simple documented format.

## Acceptance test

The build passes only if this sequence works:

1. Participant A creates or reads one Problem.
2. A adds Contribution v1.
3. B challenges a specific span or implicit assumption.
4. A adds a Response.
5. A creates Contribution v2.
6. B’s Challenge remains visible unless legitimately changed by the resolution rule.
7. Participant C arrives later.
8. C can reconstruct:
   - the current claim;
   - the important previous claim;
   - B’s objection;
   - what A changed;
   - what remains unresolved.
9. The complete event history can be exported.

If this cannot be demonstrated, do not add features. Fix the kernel.

---

# Part F — Stop rule for the coding agent

Before implementing any feature not listed above, answer:

1. Does germination fail without it?
2. If omitted now, is important information irreversibly lost?
3. Does this primitive enable many later mechanisms rather than one speculative feature?

If the answer is **no / no / no**, do not build it.

---

# Part G — Project ownership statement for handoff

The coding agent should treat the supplied specification as challengeable.

The initial human contributor, previous AI contributors, repository custodian and coding agent have provenance but no permanent epistemic authority.

If the coding agent discovers a contradiction or a simpler architecture, it should:
1. preserve the existing specification;
2. state the challenge explicitly;
3. propose the smallest revision;
4. avoid silently replacing the project’s principles.

The desired outcome is not fidelity to an author.

The desired outcome is a more robust, inspectable and corrigible protocol.


<!-- END 03_REVIEW_AND_CODING_HANDOFF.md -->


---
