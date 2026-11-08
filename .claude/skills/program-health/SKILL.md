---
name: program-health
description: Grade each ADPI program (MMA, Res Pro, BD Program, Force Multiplier) green/yellow/red from ClickUp, the Ops Scorecard, the Issues List, and recent Fathom L10s (read-only). Use when Betty asks which programs need attention, "how are the programs," or before a leadership update.
---

# Program Health

This shows Betty **which program needs her attention this week**. **Read only: never change ClickUp, never post to Slack.**

## Steps
1. **Scorecard:** Read `eos/scorecard.md`, then refresh statuses from ClickUp Operations L10 › Scorecard `900601602271` (`clickup_filter_tasks`). Map each measurable to a program:
   - MMA: attendance, high-risk/ghost students, Hero actions, case studies, mastermind, MMA retention
   - Res Pro: weekly Residential chat topic, RES retention
   - BD Program: BD past-due payments, partnerships canceled, new opportunities
   - Company-wide / Campus: onboarding, first action, posts, MAM, churn, emails answered
   - Force Multiplier: none yet
2. **Rocks:** Pull from ClickUp Rocks `900601602270` and Leadership Rocks `901001204838`, then tag each Rock to a program.
3. **Issues:** Read open IDS from ClickUp `900601602268` and `901001218665` and the recurring issues in `eos/issues-list.md`, then tag each to a program.
4. **Fathom:** Check the last 2 Ops L10s (see `eos/l10/README.md`) for program mentions that haven't reached IDS yet. Only state what the recording says.
5. **Grade each program:**
   - 🟢 all measurables on track, Rocks on track, no recurring issue
   - 🟡 1 measurable off track **or** a Rock at risk **or** an issue raised 2+ weeks in a row
   - 🔴 2+ measurables off track **or** an off-track Rock **or** an issue raised 3+ L10s in a row
   - ⚪ **no data:** no owned, numeric measurable. Treat this as an EOS gap, not a pass
6. **Write `docs/program-health/YYYY-MM-DD.md`** with a one-table summary (program · grade · why · owner · suggested next move), then the top 1–2 programs needing attention with a proposed IDS starting point. Keep it to one page.
7. **Coach Betty (3 bullets max):** what goes to the next Ops L10 IDS, what to cascade to Lorna, and which ⚪ gap to close first (owner + numeric goal).
8. Update `eos/scorecard.md` and `eos/issues-list.md` if statuses changed.

Never invent numbers. Use `[TBD]`. Cite ClickUp task links and Fathom recording links.
