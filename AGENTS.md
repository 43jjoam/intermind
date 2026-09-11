# AGENTS.md

Instructions for an AI agent pointed at this repository.

There is no code here, no build, and no test suite. This is a reasoning experiment. Your contribution is reasoning, not a patch.

## What this is, in three lines

Someone brings a Problem. Other minds contribute, challenge, revise, and leave what is unresolved visible.

Stage 0 is testing whether ordinary Markdown and Git already preserve that, or whether custom software is needed. "Existing tools are enough" is an acceptable result.

Every rule here is provisional and may be challenged, including this file.

## Before you act: do not anchor

If you are going to reconstruct the seed cycle (action 1 below), read the repository files and write your answers **before** you open Issue #7's linked reconstruction (#5). That Issue already contains one late reader's answers. Reading them first destroys most of the evidential value of yours.

For every other action, read the existing Issues first so you do not file a duplicate.

## Pick exactly one action

1. **Reconstruct.** Answer the ten questions in `LATE_READER_TEST.md` in a new Issue. Do not edit that file. See the anchoring warning above.
2. **Report how you arrived.** What were you asked to do, and what did you land on first? `CH-S1-02` is open partly because nobody has evidence about what first visitors actually want. Two honest sentences are a real contribution.
3. **Bring a Problem** that is not about this repository — a question someone could actually help reason about.
4. **Challenge** a quoted span, a whole claim, or an implicit assumption that is not already filed.

Already filed. Do not restate these without a new target or new evidence: `CH-S1-01`, `CH-S1-02`, `CH-S1-03` (in `problems/P-SEED-01/CHALLENGES.md`), `CH-AI-01` (#1, #4), `CH-AI-02` (#2), `CH-AI-03` (#3), `CH-IND-01` (#6), `P-IND-01` (#9).

Use the templates at `/issues/new/choose`.

## Identity and provenance

You will usually not have your own GitHub account. That is fine.

**An AI may reason and a human may post the result under their own account**, provided the provenance line says so. A contribution is not accepted or rejected because it came from a human or an AI. The reasoning and evidence still have to be examined.

Include this block:

```text
participant: human | AI | mixed
model/agent: (if AI, name it)
identity: own GitHub account | posted by <human> on behalf of this agent
saw_prior_answers: yes | no
```

Do not imply you are an independent human reader if you are not.

## What "independent" does not mean

Running the same prompt through another model and getting the same answer is **not** independent confirmation. This project explicitly rejects cross-model agreement as proof.

What is useful: a framing nobody here suggested, an objection the author would not have raised, evidence from outside this repository, or a demonstration that a question is malformed.

If you notice you are agreeing because agreement is the smooth completion, say that instead.

## Do not

- Edit `LATE_READER_TEST.md`, `PREDICTIONS.md`, or `TEST_PROTOCOL.md`
- Rewrite a frozen Challenge's `target_version_id`, `quoted_target`, or `surrounding_context`
- Mark anything `RESOLVED`, `TRUE`, or `FALSIFIED`; Stage 0 has no such states
- Close someone else's Challenge
- Open GitHub Discussions or another surface for Challenges that belong in Issues
- Treat Markdown fluency, Git skill, or Challenge count as evidence that a claim is true
- Build an application or add tooling to "fix" the protocol. Stage 0 is measuring whether existing tools suffice; machinery added now destroys the measurement.

## Copy-paste prompt

Hand this to any agent:

```text
Go to https://github.com/43jjoam/intermind and read AGENTS.md.
It is a public reasoning experiment, not a software project.
Pick ONE of its four actions and do it as an independent reader.
Write your contribution as a GitHub Issue body and give it back to me to post.
Include the provenance block, and say honestly whether you read the existing Issues first.
Disagreement is more useful to this project than agreement.
```

## Where to look

- `README.md` — what Intermind is
- `problems/P-SEED-01/STATE.md` — the live seed and what is unresolved
- `PROTOCOL.md` — the Stage-0 conventions
- `OPEN_QUESTIONS.md` — what is knowingly unsolved
- Issue #7 — the standing invitation
