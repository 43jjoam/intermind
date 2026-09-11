# Challenges against C-S1-01

Original Challenge records are frozen. Do not rewrite `target_version_id`, `quoted_target`, or `surrounding_context` after a later Revision.

These three Challenges were constructed in the same v0.3 design freeze as Contribution v1. They are not independent later Challenges from separate participants. This cycle tests reconstruction and span persistence, not independent multi-party challenge.

---

## CH-S1-01

```text
challenge_id: CH-S1-01
target_object_id: C-S1-01
target_version_id: C-S1-01.v1
target_kind: SPAN
quoted_target: Search into mostly empty territory rewards founding new questions
surrounding_context: Ship the already-challenged Problem first. Search into mostly empty territory rewards founding new questions, while the scarce epistemic event is a specific objection that survives revision and remains visible to a later participant.
challenge_body: This assumes publishing a new Problem is a low-value or cheap act. In some domains, identifying the right Problem is the scarce intellectual contribution. A search-first interface might surface genuinely independent problem formation rather than vanity expansion.
author/provenance: Intermind_Current_State_v0.3.md (deliberate seed-test Challenge; not an independent external challenger)
state: OPEN
```

---

## CH-S1-02

```text
challenge_id: CH-S1-02
target_object_id: C-S1-01
target_version_id: C-S1-01.v1
target_kind: WHOLE
quoted_target: [WHOLE — the entire body of C-S1-01.v1]
surrounding_context: C-S1-01.v1 argues that a first visitor should land on one already-challenged Problem, that search into mostly empty territory rewards founding new questions, and that search can wait until there is enough territory to navigate.
challenge_body: The Contribution assumes a first visitor's goal is to evaluate the protocol. A visitor may instead arrive with a concrete Problem and no interest in the seeded example. Making the seed the default may privilege the founders' framing.
author/provenance: Intermind_Current_State_v0.3.md (deliberate seed-test Challenge; not an independent external challenger)
state: OPEN
```

---

## CH-S1-03

```text
challenge_id: CH-S1-03
target_object_id: C-S1-01
target_version_id: C-S1-01.v1
target_kind: IMPLICIT
quoted_target: [IMPLICIT — v1 does not state this assumption in so many words]
surrounding_context: v1 presents a forced choice between empty-territory search and one already-challenged Problem as the greeting, then concludes a first visitor should land on one live Problem.
challenge_body: The Contribution assumes there must be one default entry path. A two-mode entry ("inspect a live reasoning cycle" / "bring a Problem") may avoid the forced choice.
author/provenance: Intermind_Current_State_v0.3.md (deliberate seed-test Challenge; not an independent external challenger)
state: OPEN
```

---

## Address claims

These records do not alter the original `target_version_id`, `quoted_target`, or `surrounding_context` fields above.

### AC-S1-01

```text
address_claim_id: AC-S1-01
challenge_id: CH-S1-01
made_by: author of C-S1-01
in_response_to_version: C-S1-01.v1
claimed_in_version: C-S1-01.v2
disposition: REVISED-IN-RESPONSE
resulting_challenge_state: ADDRESS-CLAIMED
claim: v2 moves, splits, paraphrases, and qualifies the targeted clause. Unqualified “rewards founding new questions” is no longer asserted. Residual: v2 still says empty-territory search can make starting a new question the most obvious available action.
```

### AC-S1-02

```text
address_claim_id: AC-S1-02
challenge_id: CH-S1-02
made_by: author of C-S1-01
in_response_to_version: C-S1-01.v1
claimed_in_version: C-S1-01.v2
disposition: NEEDS-MORE-EVIDENCE
resulting_challenge_state: OPEN
claim: v2 acknowledges that a visitor may arrive with a concrete Problem and ignore the seed. That acknowledgment is not evidence about what first visitors actually want, nor a demonstration that a default seed does not privilege founder framing. CH-S1-02 therefore remains OPEN.
```

### AC-S1-03

```text
address_claim_id: AC-S1-03
challenge_id: CH-S1-03
made_by: author of C-S1-01
in_response_to_version: C-S1-01.v1
claimed_in_version: C-S1-01.v2
disposition: RETAINED-DESPITE-CHALLENGE
resulting_challenge_state: ADDRESS-CLAIMED
claim: v2 names a two-mode entry and makes the one-default assumption explicit. It still ships one default for this experiment. The implicit assumption is now stated; it is not abandoned.
```
