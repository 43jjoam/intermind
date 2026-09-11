# State reconstruction

**Date of reconstruction:** 11 September 2026  
**Purpose:** distinguish adopted operational state, provisional scaffold, explicit rejection, and unresolved disagreement.  
**This file does not invent closure.**

Operational source of truth: `history/review/Intermind_Current_State_v0.3.md`.

## What is currently adopted for Stage 0

- Intermind is tested as a public, corrigible reasoning protocol, not assumed to be a standalone application.
- An acceptable outcome is that Intermind remains a protocol or convention on existing tools.
- No custom software, treasury, token, additional domains, governance machinery, or further large synthesis before this germination test.
- Seed `P-SEED-01` / `S1` as specified in v0.3, including Contribution v1 and Challenges `CH-S1-01`, `CH-S1-02`, `CH-S1-03`.
- Challenge persistence: the target author cannot erase a Challenge; revision does not auto-resolve it.
- Address claims are dispositions, not truth verdicts.
- Challenge states only: `OPEN`, `ADDRESS-CLAIMED`, `WITHDRAWN-BY-CHALLENGER`, `SUPERSEDED`.
- No universal `RESOLVED`, `TRUE`, or `FALSIFIED` state.
- Span targeting fields stay frozen on the original version; no silent remapping.
- Resource contribution must not automatically buy seed selection, default visibility, Challenge priority, or epistemic standing.
- Interrupted Gemini and Claude processes are workflow constraints, not epistemic evidence.
- Do not wait for pending reviewers. Later outputs may be appended without rewriting the pre-test state.

## What is provisional

- The Stage-0 Challenge and address-claim grammar.
- SAFE-EXIT must state reason, evidence, at least one revisit trigger, and remain visible.
- Temporary anomaly-admissibility scaffold, used only if an anomaly is submitted.
- Administrative lineage via Git and, when Git is insufficient, `ADMIN_LOG.md`.
- Material-difference claims treated as challengeable, not as admin facts.
- `ACCOUNTABLE-CUSTODY` as a deeper replacement for treating decentralization as an invariant.
- `PRINCIPLE-COLLISION` as a process, not a fixed hierarchy.
- Candidate principles listed as currently surviving in synthesis v0.2 §6. Those are confidence signals, not commandments.

## What is explicitly rejected or postponed for this pass

- Building MRV-B or any application. The v0.1 coding brief is historical only.
- Creating v0.1 blueprint files (`PRINCIPLES.md`, `DERIVATIONS.md`, `ANOMALIES.md`, `PRIVACY.md`, `GOVERNANCE.md`, `FINANCE.md`, `CONTRIBUTING.md`, `HISTORY.md`, `templates/`) as the live Stage-0 surface. They fail the add test: the germination experiment does not fail without them; their content remains recoverable from `history/review/`; they are not required Stage-0 primitives.
- `Derive` in the kernel.
- Universal `RESOLVED` / `FALSIFIED` / `VERIFIED`.
- Ranking, likes, voting, reputation, search, AI integration, notifications, cryptocurrency, DAO, treasury.
- Deleting `SYMMETRY` (R1 proposal preserved, not adopted).
- A fixed privacy > safety > corrigibility ranking.
- Treating D2 Position B (proportional single-custodian safeguards) as consensus.
- Treating cross-model agreement as independent proof.

## What remains unresolved

See [OPEN_QUESTIONS.md](OPEN_QUESTIONS.md). In short: U1–U7, D1, D2, C8, terminal-value conflict, affected non-participants, ritual compliance, non-discursive knowledge, material-difference adjudication, V2-1 provenance backfill, V2-5 override class, and whether `Derive` belongs later.

## Conflicts and which document wins

- v0.1 repository blueprint wants a large protocol-book repo. **Superseded** by v0.3 / this Stage-0 surface. Blueprint preserved in `history/review/`.
- v0.1 Action Plan next action was “send reviews.” **Superseded** by v0.3: run the germination test.
- v0.2 said Round B was still pending and “no coding yet.” **Partially superseded.** v0.3 freezes review and authorizes this Markdown/Git test. Round B remains an open process, not a gate. “No coding” still applies to custom software.
- D1 remains an empirical disagreement. Predictions are preregistered, not decided.
- D2 remains open. Stage 0 uses ordinary single-custodian Git plus logged actions. That is a test condition, not a verdict.
- SAFE-EXIT: v0.1 deferred calendar review; v0.2/v0.3 require at least one revisit trigger. **v0.3 wins** if any exit occurs.
- Anomaly wording: v0.1 “preserve every anomaly”; v0.2/v0.3 add admissibility. **v0.3 scaffold** only if needed.

## Observations recorded rather than silently patched

```text
OBSERVATION
Several reviews cited as evidence in v0.1/v0.2 syntheses were not present in the uploaded file set: raw R1, raw R2, raw Grok first-pass and recheck, Gemini recheck, DeepSeek recheck, Claude v0.2 challenge-disposition review, and Round-B responses. The uploaded set contains only 04_REVIEW_CLAUDE.md as a raw first-pass review.
CHALLENGE
Synthesis claims about those missing reviews are second-hand.
PROPOSED MINIMUM REVISION
Record the gap. Do not invent the missing reviews. Do not treat matrix rows that depend on them as if the raw text were on hand.
EVIDENCE
Directory listing of the upload set; Intermind_Review_Status_Pre_Stage0.md names materials “supplied by the user” that are not in the folder.
UNCERTAINTY
Those files may exist elsewhere. If recovered, append them unchanged and compare to this pre-test state.
```

```text
OBSERVATION
CH-S1-01, CH-S1-02, and CH-S1-03 are constructed in the same v0.3 design freeze as Contribution v1. They are not independent later Challenges from separate participants.
CHALLENGE
This first cycle tests reconstruction and span persistence, not independent multi-party challenge.
PROPOSED MINIMUM REVISION
State that provenance explicitly on each Challenge. Do not fictionalize three authors.
EVIDENCE
Intermind_Current_State_v0.3.md §6, “Deliberate Challenges for the test.”
UNCERTAINTY
A later genuine independent Challenge may still be added without rewriting these records.
```

```text
OBSERVATION
Git already records CREATE, EDIT, and MOVE more reliably than a parallel admin taxonomy, provided history is not force-rewritten.
CHALLENGE
A duplicate admin event language could become ritual overhead.
PROPOSED MINIMUM REVISION
Use Git as the primary event record. Use ADMIN_LOG.md only when Git cannot capture identity, reason, or a safe tombstone.
EVIDENCE
Ordinary git log / git show already reconstructs file creation and edits.
UNCERTAINTY
Whether this remains true after unsafe-content redaction or permission changes is untested.
```

## Inventory of uploaded documents

Role labels: CURRENT, SUPPORTING, HISTORICAL, RAW REVIEW, UNRESOLVED, UNKNOWN.

| File | Apparent date | Role |
|---|---|---|
| Intermind_Current_State_v0.3.md | 11 Sep 2026 | CURRENT |
| Intermind_v0.2_Challenge_Carry_Forward.md | 11 Sep 2026 | CURRENT |
| Intermind_Stage0_PreTest_Predictions.md | 11 Sep 2026 | CURRENT |
| Intermind_Review_Status_Pre_Stage0.md | 11 Sep 2026 | CURRENT |
| Intermind_First_Convergence_Synthesis_v0.2.md | 11 Sep 2026 | SUPPORTING |
| Intermind_Convergence_Matrix_v0.2.md | 11 Sep 2026 | SUPPORTING |
| Intermind_Seed_Candidates_Appendix_v0.2.md | 11 Sep 2026 | SUPPORTING |
| Intermind_Round_B_Residual_Search_Prompt.md | 11 Sep 2026 | SUPPORTING (prompt only) |
| Intermind_First_Convergence_Synthesis_v0.1.md | 11 Sep 2026 | HISTORICAL |
| Intermind_Complete_Seed_Review_Packet_v0.1.md | 11 Sep 2026 | HISTORICAL |
| Intermind_Seed_Review_v0.1.zip | 11 Sep 2026 | HISTORICAL |
| 04_REVIEW_CLAUDE.md | 11 Sep 2026 | RAW REVIEW |
| Named but not uploaded raw reviews / conversation dump | — | UNKNOWN |
