# Stage-0 empirical evaluation

**Status:** preregistered before the span-persistence test.  
**Do not rewrite these criteria after seeing a late-reader result.**

The test asks whether one Problem can become sharper through Contribution → Challenge → Revision → persistent unresolved state, such that a later participant can reconstruct what changed and why using ordinary Markdown/Git.

Reviewer count does not decide the outcome. Reality does.

## Local correctness

A late participant who did not observe the original exchange can identify:

- the original challenged claim;
- what changed;
- what survives;
- what remains unresolved.

They should be able to answer the questions in [LATE_READER_TEST.md](LATE_READER_TEST.md) once that file exists.

A single successful example is necessary for continuing this cycle. It is not sufficient to settle D1.

## Repeated-friction criterion

The protocol remains viable only if repeated Challenge → Revision cycles remain understandable without:

- manual re-anchoring by someone who remembers the discussion;
- rereading the complete raw history;
- rewriting Challenge targets after each revision;
- administrative effort greater than the reasoning value produced.

Markdown/Git remains viable only if targeting remains understandable, unresolved carry-forward remains reliable, and a late participant does not need the entire raw history.

## Failure condition

If reconstruction repeatedly depends on an original participant manually repairing lineage, record one of:

```text
MRV-A FAILURE: TARGET PERSISTENCE
MRV-A FAILURE: UNRESOLVED-STATE PROJECTION
MRV-A FAILURE: LINEAGE RECONSTRUCTION
MRV-A FAILURE: EVENT-HISTORY USABILITY
```

Do not immediately build software.

First write a minimal specification describing **exactly what primitive is missing**.

## Decision rule (from the preregistered predictions)

If Markdown/Git succeeds, do not build custom software merely for polish.

If it fails on a named recurring operation, build only the minimum primitive required for that operation.

Continue with Markdown/Git if late-reader reconstruction succeeds, Challenge carry-forward remains understandable, admin/history lineage is adequate, and process overhead remains proportionate.

Stop expanding Intermind as a project if, after one full cycle and late-reader test:

- it performs no better than a disciplined existing GitHub/RFC/wiki workflow;
- review/process overhead exceeds the external reasoning value produced;
- no distinctive failure remains that requires new infrastructure.

In that case, preserve Intermind as a protocol or convention if useful.

## What this test cannot settle

This first cycle uses designer-constructed Challenges and one Revision. It can produce local evidence. It cannot, by itself, settle D1.
