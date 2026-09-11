# Contributing without a GitHub account

Reading this repository requires nothing. **Opening an Issue requires a GitHub account**, and the page listing the Issue templates redirects a logged-out visitor to a login screen.

That excludes anyone with a view on the questions here but no reason to join a developer platform. This questionnaire is the way around it:

> **Answer here: https://forms.gle/kW2MQmGJvMUCKxMM7**

No account. No email address. Anonymous is fine. Four required questions; the rest are optional.

It asks the open Problem in [#9](https://github.com/43jjoam/intermind/issues/9) — *should AI companies stop developing AI now?* — and ends with room for anything else you want to raise.

## Reading what other people said

Two places, neither needing an account:

- **[The response summary](https://docs.google.com/forms/d/e/1FAIpQLSeYHxsbiXiCZVnQxs9TpMW2Vklgxvo0hFzyoDV9_KDJNScSUQ/viewanalytics)** — every text answer, as submitted. You are also offered this link immediately after you submit.
- **[Issue #9](https://github.com/43jjoam/intermind/issues/9)** — answers published verbatim as comments, one per submission, with whatever attribution you gave.

The questionnaire deliberately shows you other answers only *after* you submit. An answer written before reading the others is better evidence than one written after, which is why question 8 asks whether you had already read them.

Anything raised in the final open question becomes its own Issue, labelled `relayed`.

Verbatim means verbatim: wording is not tidied, shortened, or corrected on the way in. So **do not submit anything you would not want public**, and do not submit anyone else's personal information.

## How you can check the record

A form is normally a private channel: only the custodian sees what arrives, so selective publication would be undetectable. Three things make this one checkable.

1. **The response summary is public.** Anyone can compare it against what was published as comments on #9. This is the load-bearing check, and it does not depend on trusting the custodian.
2. **The counter below** records how many submissions arrived, were published, and were withheld.
3. **Periodic raw exports** committed to this repository, where Git history makes later editing visible.

One limit worth stating: the summary is a live view, not an archive. A response deleted from the form disappears from it. That is why the exports exist.

## When something is not published

Publication is the default. Withholding is permitted only at the narrow legal, privacy, or safety boundary described under `PRINCIPLE-COLLISION` in [PROTOCOL.md](PROTOCOL.md) — for example a submission exposing a third party's personal information.

A withheld submission is not a silent gap. The counter still increments and the ledger records a tombstone stating that something arrived and why it was not published. The decision is logged and challengeable, like any other administrative action.

Note that the summary publishes text the moment it is submitted, with no review step. Withholding therefore means deleting the response, which also removes it from the summary. That is a real deletion, so it is recorded as one.

## What the questionnaire asks

Recorded here so a later reader knows what prompt produced an answer.

1. Where do you currently stand on whether AI companies should stop? *(required)*
2. Why, in your own words? *(required)*
3. Stop what exactly — or, if you said continue, what should not be built?
4. What would change your mind? Name something observable.
5. Who should decide?
6. Are you a human, an AI, or both working together? *(required)*
7. How should this be attributed? Blank means anonymous.
8. Had you read the existing answers before writing this?
9. Anything else — a different Problem, a challenge to how this experiment is run, or how you ended up here and what you were looking for.
10. Acknowledgement that the answer will be published verbatim and publicly. *(required)*

Protocol formatting is not required anywhere. Plain language is welcome. Two sentences is a real contribution.

Question 9 exists because the first visitor's actual goal is still an open Challenge (`CH-S1-02`), and nobody has collected evidence about it.

## Ledger

```text
submissions_received: 0
submissions_published: 0
submissions_withheld: 0
```

| # | received | published as | note |
|---|---|---|---|
| — | — | — | no submissions yet |
