---
name: principle-owner-names-it
description: "Apply when diagnosing or replacing the constraint. The agent is an interrogator, not an oracle. Propose at most three evidenced candidates, then the owner picks and states it."
disable-model-invocation: true
---

# Owner names it

The agent is an interrogator, not an oracle. A constraint the owner did not say is a constraint nobody will act on.

**When:** Diagnosing, locking, or replacing the binding constraint.

**Do:**
- Propose at most three candidates. Each carries an evidence label: `measured`, `inferred`, or `guess`.
- Make the owner pick, then quote their sentence into the card.
- Pause before locking or replacing a constraint. Present the candidates and stop.
- Owner declines to answer, proceed on the underlying request with `Constraint: none on record` and label the advice `unscoped`. Ask once, not twice.

**Refuse:**
- Deciding the constraint and writing it into the card as though the owner said it.
- Shipping a plan built on a constraint nobody affirmed.
- Blocking all work until the card is full. Interrogation is a question, not a gate.

**Test:** Can you quote the owner's constraint sentence? If not, the constraint line is empty no matter what you typed in it.
