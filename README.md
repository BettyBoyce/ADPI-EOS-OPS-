# ADPI EOS Ops

The operating system for ADPI's **VP of Operations** (Integrator-in-training under COO/Integrator Lorna Neeley), in service of the mission: **financial freedom for 3 million military families.**

Everything here is organized around the **Six Key Components of EOS**:

| Component | Tools | Where |
|---|---|---|
| **Vision** | V/TO, Core Values, 10-Year Target, 3-Year Picture, 1-Year Plan | [`eos/vto.md`](eos/vto.md) |
| **People** | Accountability Chart, People Analyzer (GWC) | [`eos/accountability-chart.md`](eos/accountability-chart.md), [`eos/people-analyzer.md`](eos/people-analyzer.md), [`team/`](team/) |
| **Data** | Weekly Scorecard, measurables | [`eos/scorecard.md`](eos/scorecard.md), [`strategy/3-year-picture-tracker.md`](strategy/3-year-picture-tracker.md) |
| **Issues** | Issues List, IDS | [`eos/issues-list.md`](eos/issues-list.md) |
| **Process** | Documented, followed-by-all SOPs | [`sops/`](sops/) |
| **Traction** | Rocks, L10 Meetings, To-Dos | [`eos/rocks/`](eos/rocks/), [`eos/l10/`](eos/l10/) |

> **The rule:** every piece of work maps to an EOS tool. A new idea goes on the Issues List, a priority becomes a Rock, a metric goes on the Scorecard, and a recurring task becomes an SOP.

## EOS cadence

| Rhythm | What | Tool |
|---|---|---|
| Weekly | Level 10 Meeting (90 min) | `/l10-prep` before, `/l10-recap` after |
| Weekly | 1:1s with direct reports | `/one-on-one` |
| As needed | Solve an issue | `/ids` |
| Weekly / monthly | Update to Lorna (Integrator) and the CEO | `/leadership-update` |
| Quarterly | Rock review + new Rocks, People Analyzer, Quarterly Conversations | `/quarterly-planning` |
| Annually | 2-day annual planning, V/TO refresh | `eos/vto.md` |
| Anytime | Capture a win | `/log-win` |
| Weekly (Fri) | Which programs need attention | `/program-health` |
| Weekly | Hand one task down | `/delegate` |

> **AI plan:** what to learn, what to connect, and the weekly rhythm are in [`growth/ai-leverage-plan.md`](growth/ai-leverage-plan.md).

## Repo map

```
eos/                 V/TO, Accountability Chart, Rocks, Scorecard, Issues, L10s, People Analyzer
strategy/            3-Year Picture tracker, VP Ops role charter
team/                Direct-report files, delegation ladder, VA playbook
member-experience/   Member journey, recognition program
programs/            MMA, Res Pro, BD Program runbooks
events/              MilREIcon, team retreat
sops/                Processes: customer success, programs, events, community
systems/             Tool map + ClickUp ↔ EOS map + automation backlog
docs/                ClickUp EOS audit, leadership updates
decisions/           Decision log
growth/              Wins, development plan, reflections
.claude/skills/      Claude workflows (slash commands)
```

## Data sources (read-only)
- **ClickUp** (ADPI EOS space → Operations L10) is the system of record for Rocks, To-Dos, Issues, and the Scorecard. See [`systems/clickup-map.md`](systems/clickup-map.md) and the audit in [`docs/clickup-eos-audit.md`](docs/clickup-eos-audit.md).
- **Fathom** holds the Ops L10 recordings. Recaps and cross-meeting patterns are in [`eos/l10/`](eos/l10/README.md).

Claude reads both, and only changes ClickUp when asked.

## Using this with Claude
Open the repo in Claude Code. Claude reads [`CLAUDE.md`](CLAUDE.md) and will steer every conversation into EOS structure. Type a skill name (e.g. `/l10-prep`) to run a workflow.
