# Intermind — Pre-Test Predictions for Stage-0 Germination Test
**Recorded:** 11 September 2026  
**Purpose:** prevent post-hoc rewriting of the no-code/software disagreement.

## P-D1-A — custom software will be necessary

Prediction:

> Stable span targeting and unresolved-state carry-forward will become unreliable or disproportionately laborious under repeated Markdown/Git revisions.

Evidence that supports P-D1-A:
- late reader cannot correctly map a Challenge from v1 onto v2;
- original contributors must manually re-anchor Challenges;
- full-history reading becomes necessary;
- repeated revision cycles create maintenance overhead greater than reasoning value.

## P-D1-B — existing tools are sufficient for the next stage

Prediction:

> Explicit version IDs, quoted targets, context, Git history, and a small protocol will be enough to preserve Challenge lineage through the initial germination test.

Evidence that supports P-D1-B:
- late reader reconstructs state correctly without narration;
- multiple Challenge/Revision cycles remain low-friction;
- current/unresolved state remains understandable;
- no custom feature is needed to preserve reasoning.

## Decision rule

Do not decide by reviewer count.

A single local success does not settle the issue.

Use repeated cycles and late-reader reconstruction.

If Markdown/Git succeeds, do not build custom software merely for polish.

If it fails on a named recurring operation, build only the minimum primitive required for that operation.
