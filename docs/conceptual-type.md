# Pain Conceptual Type

## Definition

**Pain** is a state, experience, friction, loss, unmet need, or recurring difficulty that a subject may need to change, including pains the subject has not yet recognized as pain.

Pain is not synonymous with a complaint. A complaint is an explicit expression; Pain may be discovered from behavior, repetition, discrepancy, avoidance, or consequences.

## Conceptual type

Pain
- subject: who experiences or bears the pain
- object: what the pain concerns
- state: current undesirable situation
- desired_state: situation the subject would prefer
- gap: difference between state and desired_state
- experience: concrete episodes in which it appears
- evidence: observations supporting its existence
- awareness: explicit | recalled | suspected | inferred
- recurrence: one_off | recurring | persistent | unknown
- impact: time | cost | emotion | risk | opportunity
- trigger: event or condition that exposes it
- hypothesis: explanation of why it occurs
- confirmation: unconfirmed | acknowledged | verified | rejected
- provenance: how the Pain was formed

The type describes a **problematic state**, not its solution.

## Core invariant

Pain != Solution
Pain != Issue
Pain != Prompt
Pain != Complaint

A Pain can generate an Issue, and an Issue can generate Actions.

## Minimal JSON shape

{
  "id": "pain-001",
  "subject": "person-001",
  "statement": "同じ作業を何度もやり直している",
  "state": "rework occurs repeatedly",
  "desired_state": "first-pass completion",
  "gap": "rework",
  "awareness": "recalled",
  "evidence": [],
  "confirmation": "unconfirmed",
  "provenance": {
    "source": "experience",
    "events": []
  }
}
