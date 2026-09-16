---
name: principle-interrogate-dont-remind
description: "Apply when designing or running a digest, ping, status bot, weekly focus message, or any focus automation. A recurring message that forces no decision is calendar noise."
disable-model-invocation: true
---

# Interrogate, do not remind

A recurring message that forces no decision is calendar noise. The value is in the interrogation, not in the arrival of the message.

**When:** Designing or running a digest, reminder, weekly focus message, status bot, or "what should I focus on" automation.

**Do:**
- Every recurrence asks what changed, reads the falsifier, and ends in `keep` or `moved`.
- Every recurrence produces a card, not a mood.
- Ask for measured evidence before accepting inferred evidence.

**Refuse:**
- A motivational or generic "stay focused" message.
- An automation that names the constraint on the owner's behalf.
- A recurrence with no falsifier to read. There is nothing to check, so it will always report progress.

**Test:** The recipient ignores the message entirely. Did it still force a dated constraint decision onto the record? If no, it is calendar noise.
