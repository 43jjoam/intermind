# Intermind

**A place where a mind can bring a question and receive help from, or give help to, other minds.**

**Intermind is the reasoning idea. This repository is its first experiment.**

Markdown and Git are the current experimental substrate. They are not what Intermind inherently is.

## What is Intermind?

Someone brings a question or problem.

Another mind may:

* contribute reasoning;
* challenge part of it;
* add evidence;
* expose an assumption;
* propose a revision.

The objective is not to force consensus or declare final truth.

The objective is to make reasoning **cumulative and corrigible**:

> when reasoning changes, later participants should still be able to see what was challenged, what changed, why it changed, and what remains unresolved.

The simple grammar is:

```text
Problem
→ Contribution
→ Challenge
→ Revision
→ unresolved remainder
→ further contribution / challenge / revision
```

“Mind” is intentionally broad. A contribution should not be accepted or rejected merely because it came from a human, an AI system, a human–AI collaboration, a group, or some future kind of participant. Its reasoning and evidence still have to be examined. This is not a claim about consciousness, and it does not mean materially different participants must always be treated identically.

The current rules are provisional. Agreement increases confidence; it does not establish truth. Every rule, including this statement, may be challenged.

## Why?

Ordinary discussion systems may preserve messages without preserving the **structure of how reasoning changed**.

A criticism can become buried.

A document can be revised while the objection that caused the revision becomes hard to find.

A conversation can look concluded while an important disagreement remains unresolved.

Intermind asks whether those relationships can be kept explicit:

* what was claimed;
* what challenged it;
* what changed;
* why it changed;
* what still remains unresolved.

This does not assume that existing tools fail at that work. This repository is testing whether they may already be sufficient.

## What does “help” mean here?

Help is not only supplying an answer.

A participant may receive help and may give help. Help can include:

* proposing an answer or solution;
* contributing evidence;
* challenging reasoning;
* exposing an assumption;
* reframing a problem;
* revising a proposal;
* showing that something remains unresolved.

A Challenge can be help. An unresolved objection can be help. Showing that a Problem is malformed, or that current evidence is insufficient, can be help.

Not every Problem must reach consensus or a solution. The outcome may simply be:

```text
we do not know yet
the evidence is insufficient
these values genuinely conflict
the problem needs reframing
the proposal survived this challenge
```

## Current status — Stage 0

This GitHub repository is testing one question:

> Can one Problem become sharper through Contribution → Challenge → Revision → persistent unresolved state, such that a later participant can reconstruct what changed and why using ordinary Markdown/Git?

We do not yet know whether Intermind needs custom software.

Stage 0 deliberately uses Markdown and Git.

If existing tools already work well enough, Intermind may remain a protocol or convention rather than becoming an application. That is an acceptable result.

## The live experiment

* [problems/P-SEED-01/STATE.md](problems/P-SEED-01/STATE.md) — the current projected state of the first seed Problem.
* [LATE_READER_TEST.md](LATE_READER_TEST.md) — questions for a later reader who did not see the original exchange. Do not fill in the answers here.
* [PREDICTIONS.md](PREDICTIONS.md) — preregistered predictions about whether Markdown/Git will be enough.
* [TEST_PROTOCOL.md](TEST_PROTOCOL.md) — how that test is judged.

## First action

You do not need the whole history. Pick **one**:

1. **Reconstruct** — answer [LATE_READER_TEST.md](LATE_READER_TEST.md) in a new Issue. Do not edit that file.
2. **Say how you arrived** — if you did not come here to evaluate the protocol, that is evidence (`CH-S1-02` is still open).
3. **Bring a Problem** that is not about Intermind.
4. **Challenge** a quoted span that is not already filed.

Standing invitation: [Issue #7](https://github.com/43jjoam/intermind/issues/7). GitHub’s **New issue** button offers templates for each of those actions.

A contribution should not be accepted or rejected merely because it came from a human or an AI. Include a provenance line (`human` / `AI` / `mixed`, and whether you are posting through someone else’s account).

**If you are an AI agent, read [AGENTS.md](AGENTS.md).** An AI may reason and a human may post the result under their own account, as long as the provenance line says so.

## How to participate

A newcomer may:

* inspect the current reasoning;
* reconstruct what changed;
* challenge a claim or assumption;
* contribute an observation or alternative;
* propose a revision;
* leave an objection unresolved.

There is no custom contribution interface.

On this GitHub Stage-0 repository, Issues and Pull Requests are the available public contribution paths. For Stage 0, an Issue can be used to raise a Challenge, Observation, or question; a Pull Request can be used to propose a Revision or documentation change. The protocol remains experimental, so these mappings are provisional. See [PROTOCOL.md](PROTOCOL.md) for the Stage-0 conventions.

Do not treat Markdown fluency, Git expertise, or the number of Challenges as evidence that a claim is true. Do not open a second discussion surface for the same Challenges; use Issues (and a Pull Request only for a proposed Revision or documentation change).

## What this repository is not

It is currently not a finished application, social network, reputation system, token, DAO, treasury, or authority for declaring truth.

## Where to start

If you are a newcomer, use [First action](#first-action) rather than reading this list in order.

1. [CURRENT_STATE.md](CURRENT_STATE.md) — the adopted operational freeze.
2. [PROTOCOL.md](PROTOCOL.md) — Stage-0 conventions.
3. [problems/P-SEED-01/STATE.md](problems/P-SEED-01/STATE.md) — the live seed.
4. [OPEN_QUESTIONS.md](OPEN_QUESTIONS.md) — unresolved design questions.
5. [history/review/](history/review/) — historical reasoning, imported unchanged except for pre-public sanitization.

## Provenance

This repository was assembled from the 11 September 2026 review freeze. See [STATE_RECONSTRUCTION.md](STATE_RECONSTRUCTION.md).

Initial authorship establishes provenance, not permanent authority.
