---
name: principle-constraint-moves
description: "Apply after relief work ships, a checkpoint fires, a metric moves, or the mission changes. Relieve one constraint and a different one binds. Last period's name is not sacred."
disable-model-invocation: true
---

# Constraint moves

Relieve one constraint and a different one becomes binding. That is the loop working, not the loop failing. Last period's name is not sacred.

**When:** A relief move ships, a checkpoint fires, a metric moves, or the mission changes.

**Do:**
- Decide which of three happened: relieved, still binding, or never binding.
- Mission changed, discard the constraint and diagnose from scratch. Do not translate the old one into the new mission.
- Constraint changed, set a new falsifier, a new check date, and a new relief move. All three, or the card is stale in a way nobody will notice.

**Refuse:**
- Carrying a constraint forward because it is already written on the card.
- Counting activity as relief without reading the falsifier.
- Pointing a new constraint at the old falsifier.

**Test:** What evidence, dated inside this period, shows the old constraint still limits throughput today?
