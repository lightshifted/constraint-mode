# Constraint Mode

A Cursor plugin. One mode skill, nine leaf principle skills, three playbooks.

The agent is an interrogator, not an oracle. It forces one mission, one binding constraint, one relief move, and a falsifier that could kill the constraint. It does not name the constraint for you, and it does not let you keep three.

## The loop

1. State the mission in one line. A constraint is undefined without a goal.
2. Name the one factor that binds throughput to it. Not three, and not an area. A mechanism.
3. Attach a falsifier and a check date. A constraint you cannot kill is a slogan.
4. Commit one relief move for the period. Park or kill the rest, out loud.
5. At the check, re-interrogate. Relieved constraints move, and last period's name is not sacred.

Every reply opens with the card, which is the artifact the next session picks up:

```
Mission: what increases, in one line
Constraint: the mechanism that binds it, in the owner's words
Relief move: the one action this period, with its done condition
Falsifier: the observable that would show this is not binding
Check: a date or a triggering event
Parked: a count and where the list lives
```

## Install

Install `constraint-mode` from the Cursor Marketplace, then invoke `/constraint-mode`.

To run it before publishing, copy this directory to `~/.cursor/plugins/local/constraint-mode` and reload Cursor.

Invoke it as a skill for a single turn. Hold it as a mode for a whole planning session: pick it from the `/` menu and press Option+Enter on macOS or Alt+Enter on Windows.

## Turning it off

The mode declines work that does not relieve the named constraint. That is the point, and it is not always what you want. Say "drop constraint mode" or "just answer the question" and it stops for the session without asking again.

If you have no mission on record and do not want to state one, it still answers. It labels the advice `unscoped` and asks for the mission once.

## Skills

Mode: `constraint-mode`

Diagnosis: `principle-mission-first`, `principle-one-binding-constraint`, `principle-owner-names-it`, `principle-discomfort-is-a-signal`, `principle-falsify-or-slogan`

Allocation: `principle-non-constraint-is-noise`, `principle-one-relief-move`

Movement: `principle-constraint-moves`, `principle-interrogate-dont-remind`

Playbooks live beside the mode skill in `skills/constraint-mode/playbooks/`. Three of them, one per input state: nothing on the record, a card plus elapsed time, or an incoming list.
