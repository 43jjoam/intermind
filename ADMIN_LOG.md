# Administrative lineage

Where Git records the action sufficiently, the commit is the event record.

This log records consequential actions whose reason or classification is not obvious from Git alone, and notes the Stage-0 custody condition.

## Custody

This repository is currently a single-custodian Git repository, now published on GitHub. That fact does not decide D2. It is the Stage-0 test condition.

The original local-test condition was: no GitHub remote, nothing pushed publicly. A public remote now exists. Single-custodian custody still holds.

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

### A-0005

```text
action: CREATE
object: GitHub standing invitation #7 (pinned), contribution-path labels, .github/ISSUE_TEMPLATE/*, README first-action pointer
reason: public newcomers (human and agent) had no concrete first move; blank Issues were already splitting from the seed record
scope: onboarding only; seed objects, predictions, and test criteria unchanged
note: pinning #7 is facilitation of entry, not epistemic ranking of a claim. Issue templates use GitHub as it already exists; they are not custom Intermind software.
```

### A-0006

```text
action: EDIT
object: ADMIN_LOG.md custody paragraph
reason: the pre-public “no GitHub remote” sentence was false of the published repository and would mislead a first visitor
```

### A-0007

```text
action: CREATE
object: AGENTS.md, GitHub repository topics
reason: agents are pointed at a repository rather than browsing to it, and the repository was not discoverable by topic search
scope: onboarding only; seed objects, predictions, and test criteria unchanged
```

### A-0008

```text
action: DECISION
object: participation identity policy
decision: an AI may reason and a human may post the result under their own GitHub account, provided the provenance line states this
reason: requiring a distinct account per agent would exclude nearly all agent contributions; concealed authorship is the actual risk, not delegated posting
note: this is a challengeable Stage-0 convention, not a settled rule. It does not make contributions posted through the custodian account independent. See U5 (reasoning laundering) in OPEN_QUESTIONS.md.
```

### A-0009

```text
action: CREATE
object: INTAKE.md, no-account submission form, `relayed` label
reason: the GitHub contribution path is behind a login wall, which excludes exactly the affected non-participants OPEN_QUESTIONS.md names as unsolved
policy: submissions are published verbatim as Issues; withholding is permitted only at the narrow PRINCIPLE-COLLISION boundary and leaves a tombstone in the ledger
note: a form is a private channel, so the custodian could publish selectively and nobody would know. Tally has no public results page, so the intended independent check is unavailable. Substitutes: per-submission IDs let a submitter verify their own answer was published, a counter records received/published/withheld, and raw exports are committed periodically. A third party still cannot detect a dropped submission. Recorded as a known weakness. Related to U5 and to CH-AI-03 (#3) on procedural asymmetry.
```

### A-0010

```text
action: DECISION
object: intake form scope and publication target
decision: the no-account channel is a questionnaire on P-IND-01 (#9) rather than a generic intake; answers are published verbatim as comments on #9, and anything raised in its final open question becomes its own Issue
reason: the Problem is what a stranger has a view on; the protocol is not. Publishing as comments keeps answers readable in one place and avoids flooding the Issues board.
note: reading Issues and comments requires no GitHub account, so a logged-out respondent can see other answers. Writing still requires one. This routes around the login wall without adding a discussion surface.
```
