# Pain Tools

Pain should be treated as a discovery problem, not merely an input form.

## Tool set

### Recall
Re-present prior experiences.

Input:
- subject
- time range
- experiences

Output:
- candidate pains
- supporting evidence
- questions

### Detect
Find patterns that may indicate unrecognized Pain.

Signals:
- repeat
- rework
- wait
- abort
- avoid
- fail
- complain
- handoff
- manual
- mismatch
- drop

Output is always a **Pain candidate**, not a confirmed Pain.

### Ask
Convert a candidate into a question that the subject can answer.

Good:
「この作業を毎週繰り返すことを、負担だと感じていますか？」

Bad:
「この作業は問題ですよね？」

The latter leads the subject.

### Confirm
Let the subject acknowledge, reject, or revise the candidate.

### Trace
Navigate:

Pain → Experience → Observation → Evidence

and:

Pain → Issue → Action → Result

### Compete
Let multiple Agents independently discover or interpret Pain candidates.

Experience
  ├── Agent A → candidate A
  ├── Agent B → candidate B
  └── Agent C → candidate C
                 ↓
             evaluation
                 ↓
          candidate set
                 ↓
             human check

Competition compares evidence and explanations; it must not force a Pain to exist.

## Suggested API concepts

POST /pains/recall
POST /pains/detect
POST /pains/ask
POST /pains/{id}/confirm
GET  /pains/{id}/trace
POST /pains/competition

These are conceptual interfaces. Implementation may live in bons.ai or another runtime; pain remains the canonical conceptual model.

## Data loop

Experience
   ↓
Pain Discovery
   ↓
Pain
   ↓
Issue
   ↓
Action
   ↓
Result
   ↓
Evaluation
   ↓
Experience

Pain is therefore a continuously discoverable object, not a one-time form field.
