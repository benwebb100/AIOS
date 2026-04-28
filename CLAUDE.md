# AutoOS — Workspace Context

## What This Repo Is
The operating workspace for **AutoOS** — the agency that installs AI Operating Systems (AIOS) for business owners. This repo serves two purposes simultaneously:
1. **Live business operations** — sales, delivery, client work, strategy
2. **Demo / sandbox** — this workspace mirrors the AIOS we install for clients, so we dogfood every workflow before it ships

## The Team
- **Bailey** — Managing Director. Owns the business, makes the calls.
- **Claude Code** — Developer. Pairs on every build, drafts everything, maintains the workspace.
- **Ben** — External strategic advisor (async, weekly sync). Not on delivery.

Full working mode: `02 Business/Team.md`.

## Vault Structure
This workspace follows the Obsidian vault layout from the Master Playbook — the same layout we install for clients.

```
01 Inbox/             — capture zone (notes, ideas, transcripts to triage)
02 Business/          — business context (the "brain")
  About.md            — what the agency is, business model, tech stack
  Team.md             — Bailey, Claude, Ben
  Clients.md          — pipeline (prospects, active, churned)
  Brand.md            — name, positioning, voice
  Strategy.md         — goals, KPIs, acquisition plan
  SOPs/               — operating procedures
    Discovery-Call.md
    Sales-Process.md
03 Meetings/          — meeting notes and transcripts (YYYY-MM-DD - Party - Topic.md)
04 Archive/           — retired material, kept for reference
reference/            — agency-level reference (not the day-to-day workspace)
  Master-Playbook.md  — the constitution
  Original-Brainstorm.md
  Council-Verdict-Dashboard-Timing.md
```

## Rules
- **Load business context on relevant sessions.** When working on AIOS strategy, sales, delivery, or content, read `02 Business/About.md`, `Brand.md`, and `Strategy.md` first. Pull `Team.md` and `Clients.md` if the task touches people or pipeline.
- **The Master Playbook (`reference/Master-Playbook.md`) is the constitution.** It contains the full delivery framework, all SOPs in long form, and templates. SOPs in `02 Business/SOPs/` are working quick-reference distillations — the playbook is the source of truth they derive from.
- **Update `02 Business/` docs in place when business decisions change** (pricing, positioning, new verticals, team, etc.). Don't append chronologically.
- **Keep docs concise.** If a doc gets long, split it or move detail into the playbook.
- **New meeting notes go in `03 Meetings/`** named `YYYY-MM-DD - [Counterparty] - [Topic].md`.
- **Skills/commands live in `.claude/`** (foundation Layer 0 work — to be built out).

## What Lives Outside This Repo
- **Sibling client workspaces** under `c:\Users\Monkey\Documents\AIOS Projects\` (e.g. `Lou/`, `Jason/`) — each client has their own AIOS workspace
- **AIOSWIKI** — the cross-cutting wiki shared across workspaces (sync skill targets it)
