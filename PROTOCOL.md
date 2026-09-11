# Stage-0 protocol

These conventions exist only to make the germination test runnable. They are not a constitution.

Process competence is not epistemic competence. Do not reward verbosity, Markdown fluency, Git expertise, Challenge count, commit count, or stylistic sophistication.

## Problem

A Problem has a stable identity.

Required fields:

```text
problem_id
title
body
author/provenance
```

## Contribution

A Contribution has a stable identity and versioned bodies.

Required fields:

```text
contribution_id
version_id
problem_id
author/provenance
body
```

Earlier versions remain readable. A later version does not delete an earlier one.

## Challenge

Required fields:

```text
challenge_id
target_object_id
target_version_id
target_kind: SPAN | WHOLE | IMPLICIT
quoted_target
surrounding_context
challenge_body
author/provenance
state
```

For `SPAN`, preserve the original exact quotation.

Do not silently remap a Challenge onto a later version. A later reader decides, from lineage, whether the Challenge still applies.

### Persistence

The author of the target cannot erase another participant's Challenge.

Revision does not automatically resolve a Challenge.

### States (Stage 0 only)

```text
OPEN
ADDRESS-CLAIMED
WITHDRAWN-BY-CHALLENGER
SUPERSEDED
```

- `OPEN`: default.
- `ADDRESS-CLAIMED`: the target author states that a Response or Revision addresses it.
- `WITHDRAWN-BY-CHALLENGER`: only the challenger may set this for their own Challenge.
- `SUPERSEDED`: a new Challenge explicitly replaces the old one; both remain in lineage.

Do not use a universal `RESOLVED`, `TRUE`, or `FALSIFIED` state in Stage 0.

Original Challenge targeting fields (`target_version_id`, `quoted_target`, `surrounding_context`) are not rewritten after Revision. Later dispositions are appended.

## Address claims

The target author may record a disposition. This is an **address claim**, not a truth verdict.

```text
REVISED-IN-RESPONSE
RETAINED-DESPITE-CHALLENGE
NEEDS-MORE-EVIDENCE
SAFE-EXIT
```

The Challenge remains visible. The claim can itself be challenged.

## Safe exit

An exit must:

- state a reason;
- state relevant evidence;
- specify at least one revisit trigger;
- remain visible in the unresolved or terminal-state view.

An exit is a state, not deletion.

## Anomaly submission

Stage 0 is not testing large-scale anomaly moderation.

If an anomaly is submitted during the test, a temporary facilitator applies this minimum rule. An admitted anomaly includes:

1. observation or discrepancy;
2. provenance;
3. the expectation or model it conflicts with;
4. sufficient non-private context.

The decision is logged and challengeable. This is a temporary scaffold, not permanent authority.

## Administrative lineage

Consequential actions should remain reconstructible through Git and, when Git is not enough, [ADMIN_LOG.md](ADMIN_LOG.md):

```text
CREATE
EDIT
MOVE
ARCHIVE
DELETE/REMOVE-CONTENT
RESTORE
PERMISSION-CHANGE
```

Where Git records the action sufficiently, the commit is the event record.

Do not silently rewrite history. If private or unsafe content must be removed, preserve a safe tombstone where possible.

## Material-difference claims

Claims that a participant should receive different procedural treatment because of scale, capacity, or vulnerability are **not admin facts**. They are challengeable claims.

No Stage-0 participant receives special standing merely by asserting greater relevant capacity.

## Attention constraint

Resource contribution must not automatically buy seed selection, default visibility, Challenge priority, or epistemic standing.

## What Stage 0 does not decide

Disagreement may remain because of missing evidence, different models, hidden assumptions, or incompatible terminal values. The protocol may only make the disagreement legible, preserve why it exists, and identify consequences.

Affected people who cannot or do not participate remain a design constraint. Stage 0 does not solve representation of non-participants.
