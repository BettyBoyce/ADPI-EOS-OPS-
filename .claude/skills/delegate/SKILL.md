---
name: delegate
description: Hand a task off from Betty to the right seat (Bri, Hannah, Winkle) using EOS Delegate & Elevate. Places it on the Delegation Ladder, drafts the SOP, and drafts the To-Do and Slack handoff. Use when Betty says "delegate this," "hand this off," "who should own this," or describes a task she keeps doing herself.
---

# Delegate & Elevate

The goal is to move work out of Betty's seat so she has capacity for Integrator work. **Draft only: create nothing in ClickUp and send nothing in Slack unless Betty says so in this conversation.**

## Steps
1. **Identify.** Ask, if not given: what the task is, how often it happens, and roughly how long it takes. If it's really a problem rather than a task, stop and route to `/ids`.
2. **Quadrant.** Place it on `team/delegation-ladder.md`: Love/great (keep) · Like/good (keep for now) · Don't like/good (delegate) · Don't like/not good (delegate now). Push back kindly if Betty is keeping something that isn't VP/Integrator work.
3. **Seat.** Pick one owner from `eos/accountability-chart.md` by matching the task to that seat's 5 roles. Check `team/<seat>.md` and `eos/people-analyzer.md` for **GWC** (Get it, Want it, Capacity). If no seat fits, flag it as an Accountability Chart issue rather than forcing it.
4. **Process.** If no SOP exists, draft `sops/<area>-<task>.md` from `sops/_template.md` using Betty's notes, or a Fathom recording if she names one (summaries only, never transcripts). Mark steps you're unsure about `[confirm]`.
5. **Handoff draft:**
   - **To-Do:** owner, due date within 7 days (first run done with Betty watching or reviewing), and the definition of done
   - **Slack message draft** to the owner: what, why it matters (Core Value / program), link to the SOP, first due date, and how Betty will check in. Use `slack_send_message_draft` only if Betty asks; otherwise show the text
   - **Scorecard hook:** if the task produces a number, suggest the measurable
6. **Update** `team/delegation-ladder.md` (handoff status: Drafted → Handed off → Owned) and the owner's `team/<seat>.md`.
7. **Elevate prompt (one line):** what Integrator responsibility from `growth/integrator-development.md` this freed time could go toward.
