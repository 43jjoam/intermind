# Administrative lineage

Where Git records the action sufficiently, the commit is the event record.

This log records consequential actions whose reason or classification is not obvious from Git alone, and notes the Stage-0 custody condition.

## Custody

This repository is currently a single-custodian Git repository. That fact does not decide D2. It is the Stage-0 test condition.

No GitHub remote is created as part of Stage 0. Nothing is pushed publicly as part of Stage 0.

## Pre-public sanitization

This published Git history was rewritten before the first public push. The five Stage-0 commits were recreated with the same messages and the same germination-test content. Removed from history: a local filesystem path, a local Git author identity, personal provider-account quota wording, and a specific domain locator. No late-reader answers were added.

## Events

### A-0001

```text
action: CREATE
object: Stage-0 repository
reason: authorized germination test (v0.3)
note: uploaded files were copied, not moved, into history/review/. Duplicate originals outside that directory are not part of the published tree.
```

### A-0002

```text
action: CREATE
object: history/review/* (copies of the uploaded set, later sanitized before public history)
reason: preserve historical reasoning; sanitization removed only local identity, account-quota wording, and a specific domain locator
```

### A-0003

```text
action: CREATE
object: CURRENT_STATE.md, STATE_RECONSTRUCTION.md, PROTOCOL.md, OPEN_QUESTIONS.md, README.md
reason: separate current operational state from historical reasoning
```

### A-0004

```text
action: EDIT
object: README.md and GitHub repository description
reason: public-release onboarding test showed that the existing introduction described Stage 0 before explaining what Intermind is
scope: documentation only; no Problem, Contribution, Challenge, Revision, prediction, or test criterion changed
```
