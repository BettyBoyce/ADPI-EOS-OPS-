# AI Leverage Plan: VP of Operations

> **Owner:** Betty · **Created:** 2026-11-08 · **Review:** at each quarterly pulse (next: Q1-27 planning, late Dec)
> **EOS routing:** This is **not a Rock and not a new system.** AI is a *tool* that serves the EOS tools you already run. Your learning goes in [`integrator-development.md`](integrator-development.md). Program visibility goes on the **Scorecard**. Delegation goes on the [**Delegation Ladder**](../team/delegation-ladder.md). Company-wide AI strategy is **Lorna's call** (Leadership L10, see Issues List).

## The one rule
**Learn an AI skill only when it removes a bottleneck on your Scorecard, your Rocks, or your Delegation Ladder.** If you can't name which one, it's a distraction. Park it on the Issues List as an idea.

Time box: **about 2 hours a week** on AI, and almost all of it spent *doing your job with Claude*, not studying AI. When it's working, Claude saves you more than 2 hours a week. If it doesn't by the end of Q1-27, reset.

---

## 1. What to learn, in order

You don't need to learn "AI." You need to learn how to **ask for and judge output**, the same way you'd delegate to a sharp new hire.

| # | Skill | Why it matters to your seat | You'll know you have it when… | When |
|---|---|---|---|---|
| 1 | **Run your EOS rhythm through the skills in this repo** (`/l10-prep`, `/l10-recap`, `/one-on-one`, `/leadership-update`, `/ids`, `/program-health`, `/delegate`) | They already use ClickUp + Fathom. This is about 80% of the value | L10 prep takes under 15 minutes and you walk in with a top 3 IDS list | Nov 2026, now |
| 2 | **Give good context, then check the work** (who it's for, what "done" looks like, where the data lives; then verify every number against the source link) | AI is confidently wrong sometimes. Your job is judgment, not typing | You catch a wrong number before it reaches Lorna | Nov–Dec |
| 3 | **Delegate *through* AI:** turn a recording or a messy process into an SOP + a To-Do with an owner and a date | Fastest path to capacity. Bri/Hannah/Winkle can own work once it's written down | 3 items moved down your Delegation Ladder, each with an SOP | Dec–Q1 |
| 4 | **Ask cross-system questions** ("Which program has the most off-track measurables and open IDS?") | This is the Integrator skill: seeing across departments | You answer Lorna's "how are the programs?" in one minute, with data | Q1-27 |
| 5 | **Know when to escalate a build:** spot a repeatable workflow and hand it to whoever builds (e.g., Markian on the MMA AI Brain) | Keeps you a VP, not a developer | You write a one-paragraph request instead of building it yourself | Q1-27+ |

### Deliberately *don't* learn (for now)
- How MCP/connectors work under the hood, coding, Git beyond "Claude commits for me"
- Building bots or agents yourself (the **MMA Cohort bot** and **MMA AI Brain** have owners; support them, don't build them)
- Prompt-engineering courses, comparing AI tools, chasing every new feature
- Re-organizing this repo. It's a thinking space; ClickUp stays the system of record

---

## 2. What to connect, in priority order

**Today (confirmed in this session):** ClickUp · Slack · Fathom · GitHub repos · Canva · Claude Docs.

The question isn't "what can I connect?" It's **"what number or decision am I missing?"**

| Priority | Connect | Answers the question… | Feeds | Status / next step |
|---|---|---|---|---|
| ✅ | **ClickUp** | Are Rocks, To-Dos, and IDS moving? | Scorecard, Rocks, L10 | Connected. Read-only by default |
| ✅ | **Fathom** | What did we commit to in the L10 / 1:1s? | L10 recaps, To-Dos, SOP drafts | Connected |
| ✅ | **Slack** | What's being raised outside the L10? Did the cascading message land? | Issues List, Headlines | Connected. Use it to **draft** handoffs; you send them |
| **1** | **GoHighLevel (CRM)** | How many enrolled this week, by program? Refund requests? Strategy call → enrollment handoff? | Refund measurable, Sales→Ops handoff (your Integrator stretch) | **Ask Lorna/whoever owns GHL.** If no connector exists, have Winkle drop a weekly export into ClickUp or a sheet |
| **2** | **Campus (member platform)** | Who's attending, completing onboarding, going ghost? | Scorecard #1–5, Ghost Student protocol, retention | Same: connector if one exists, otherwise a weekly export (Hannah) |
| **3** | **Program repos** (see below) | What's the current curriculum/SOP/AI Brain state of each program? | Program health, SOPs | MMA exists. Res Pro and BD don't. **Don't create more until Scorecard owners exist** |
| **4** | **Financials (P&L view)** | Cost of refunds/churn; program profitability | Integrator skill: P&L | Q1-27+. Lorna's call on access (Integrator plan) |
| Later | Calendar / email | Time audit, inbox triage | Delegation (Winkle) | Only if a Delegation Ladder item needs it |

### Program repos: what I see on your GitHub access
| Repo | Program | Note |
|---|---|---|
| `markiansich/MMA` | MMA | Probably the MMA AI Brain (company Rock). Lives on Markian's personal account. *See Issue below* |
| `BettyBoyce/ADPI-Nurture-Sequence-MMA` | MMA (marketing → enrollment) | Yours |
| `markiansich/P2P` | [confirm which program] | |
| *(none)* | Res Pro, BD Program, Force Multiplier | Program health for these comes from ClickUp + Scorecard, not a repo |

> **Key point:** repos hold a program's *knowledge* (curriculum, SOPs, AI Brain). They don't tell you if a program is *healthy*. That's the Scorecard's job. **Program visibility is a Data problem first, an AI problem second.**

---

## 3. Seeing which programs need attention

Run **`/program-health`** weekly (Friday, before your Lorna update). It grades each program 🟢/🟡/🔴 from ClickUp, the Scorecard, the Issues List, and Fathom.

**What blocks this today isn't AI. It's missing data** (from [`../eos/scorecard.md`](../eos/scorecard.md)):
- **MMA Retention (#21)** and **RES Retention (#20)** have no owner and no goal
- **BD Program** has no measurables at all ([`../programs/bd-program/README.md`](../programs/bd-program/README.md) is blank)
- Most measurables show `[#]` instead of a numeric goal
- **Force Multiplier** has no measurables yet (it's a Q1 Rock candidate)

**Fix those in the next L10 and the program view largely builds itself.** Until then `/program-health` will flag them as ⚪ "no data."

---

## 4. Delegating faster

Run **`/delegate <task>`**. Claude will:
1. Place it on the [Delegation Ladder](../team/delegation-ladder.md) (keep / delegate / delegate now)
2. Name the seat from the [Accountability Chart](../eos/accountability-chart.md) (Bri / Hannah / Winkle)
3. Draft the SOP from your notes or a Fathom recording (into `sops/`)
4. Draft the handoff: a To-Do with owner + due date, and a Slack message **as a draft for you to send**

**Your rule:** if you've done it twice and it isn't Integrator work, `/delegate` it. Aim for **one handoff a week** through Q1-27. That's about 12 tasks off your plate by March.

---

## 5. Your weekly AI rhythm (about 2 hrs)
| When | Run | Output |
|---|---|---|
| Monday before the Ops L10 | `/l10-prep` | Agenda + top 3 IDS |
| Monday after the L10 | `/l10-recap` | To-Dos with owners/dates, IDS outcomes |
| Before each 1:1 | `/one-on-one <name>` | Prep notes |
| Once a week | `/delegate <one task>` | One item handed off |
| Friday | `/program-health` → `/leadership-update` | Program grades → brief for Lorna |
| Any time | `/ids`, `/log-win` | |

---

## 6. 30 / 60 / 90 (aligned to the EOS cadence)
| By | Result (not activity) |
|---|---|
| **2026-12-08** (30 days) | Every Ops L10 prepped and recapped with Claude. First 4 `/delegate` handoffs done. Retention measurables (#20, #21) have owners (L10 IDS) |
| **2027-01-07** (60 days, Q1 planning) | `/program-health` runs weekly with real numbers for MMA + Res Pro. BD measurables defined. GHL + Campus data path decided. **Your own Q1 Rock set** (suggested below) |
| **2027-02-06** (90 days) | 8+ tasks off your plate. You answer "how are the programs?" in a minute. One Integrator responsibility moved from Lorna to "Co-own" |

**Suggested Q1-27 Rock (Betty):** *"Program Health live: MMA, Res Pro, BD, and Force Multiplier each have 2–3 owned, numeric weekly measurables, reported in a weekly program-health brief to Lorna by 3/31/27."* It's a Data result, and AI is just how it gets done.

---

## Guardrails
- **ClickUp is read-only** unless you ask in the conversation. Slack messages are **drafts** unless you say "send."
- **Never commit transcripts** or member payment details. Summaries only.
- **Verify numbers** against the source link before they go to Lorna or the CEO. Never invent a number. Use `[TBD]`.
- ⚠️ **This repo is public on GitHub** and holds coaching notes on your team (`team/`, `eos/people-analyzer.md`). *See Issue below. Make it private.*
