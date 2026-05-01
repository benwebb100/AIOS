# SOP — Paid Audit

> Paid discovery engagement that replaces the old free 30-min scope. Outputs a "cookbook" document and a live demo. The audit *is* the close.
> Source: Bledsoe webinar synthesis (April 2026), adapted for AU founding pricing.

## Pricing

- **Founding tier (first ~3 audits):** $250–500 flat
- **Standard tier (after track record):** $500–1,500 flat
- **Per-conversation pricing (premium / multi-stakeholder):** $1,000–1,500 per 90-min interview, max 3/day

The audit price is a filter. If they baulk at $250, they will baulk at every later number. Don't negotiate down.

## Audit Proposal (one-pager)

Send within 24 hrs of the initial conversation:

```
PAID AUDIT — [Business Name]
DATE: [Date]

WHAT IT IS
A structured discovery of your business: stakeholder interviews,
workflow mapping, opportunity analysis, and a working AIOS prototype
loaded with your context.

WHAT YOU GET
1. Cookbook document — plain-English summary on top, technical detail
   below. Maps your current state, future state, and prioritised
   automations. Yours to keep regardless of what we do next.
2. Live demo of an AIOS contextualised to your business — you can
   interact with it during the presentation and after.
3. Architecture proposal (if it makes sense after the audit).

WHAT'S INVOLVED
- 1 owner interview (90 min, recorded)
- 1–2 key stakeholder interviews (60–90 min each, recorded)
- 1 presentation (45–60 min, demo + cookbook walkthrough)

INVESTMENT
$[250–500] flat. Payable on signed scope.
Timeline: ~1–2 weeks from kickoff.

NEXT STEPS
1. Sign and pay
2. Schedule interviews
3. Audit kicks off
```

## Audit Process

### 1. Kickoff (after payment)
- Schedule interviews
- Send pre-interview prep email: what to think about, what docs to send through
- Open a project folder under `03 Meetings/<Client>/`

### 2. Interviews (1–3 sessions)

**Owner interview (90 min, recorded — Granola, Otter, or phone recorder)**
- Business model + current state
- Where the owner spends their time vs where they want to spend it
- The "if you cloned yourself" question
- Current tools and systems
- What breaks when they're on holiday
- 12-month vision

**Key stakeholder interviews (60–90 min each, recorded)**
- One per critical role (operations lead, head of sales, key admin, etc.)
- Same broad arc but role-specific pain points
- "What would you do differently if you had a clone?"
- Where their workflow breaks
- What they wish the owner knew

**Discipline:** Max 3 interviews per day. Process transcripts in the afternoon — don't let them stack.

### 3. Processing

- Transcripts → Claude Code with prompt: *"This is an audit interview transcript for [client]. Extract: business context, current workflows, pain points, opportunities for AI augmentation, risk-ranked automation candidates."*
- Cross-reference across stakeholders — what do they all complain about? What does the owner not know?
- Build the cookbook (see template below).

### 4. Cookbook Document

Two-section structure:

```
# [CLIENT] — AIOS Audit Cookbook

## Executive Summary (Plain English)
[1–2 pages anyone can read. What we found, what we'd build, why.]

### What we heard
- [Top 3 pains across stakeholders]

### What we'd build (in priority order)
1. [Highest-leverage automation — usually owner-personal]
2. [Operations-side automation that compounds]
3. [Reporting/visibility piece]
4. [Modular add-ons available later]

### Expected outcomes
- Hours saved per week (per role)
- Pain points eliminated
- New visibility unlocked
- Revenue / opportunity unlocked

## Technical Detail (Project Spec)
[Becomes the project requirements doc if they sign on.]

### Current state
- Tools, data sources, workflows mapped
- Integration points
- Data quality assessment

### Future state
- AIOS architecture (Layers 0–4 mapped to client)
- Required MCP servers / integrations
- Context files needed
- Sequencing

### Risk-ranked automation list
| Automation | Value | Effort | Risk | Priority |
|---|---|---|---|---|
| ... | ... | ... | ... | ... |
```

### 5. Presentation (45–60 min)

- Handful of slides covering the executive summary
- **Live demo** — Claude desktop app pre-loaded with their context, run a real query in front of them ("show me my last week's revenue", "draft a follow-up to [actual stakeholder]")
- **Puppy-dog close** — leave them logged in, let them try it themselves, leave it accessible afterwards
- End with the architecture proposal (see `Sales-Process.md` Step 4)

> By presentation day, the architecture sale should be a formality. If you've done the audit well, they're already sold.

## Filter at every step

If the prospect ghosts during interview scheduling, slow-pays the audit invoice, or keeps trying to scope-creep "what would you do if I gave you this for free" — they will not be a good long-term client. The audit is doing its job: filtering.

## Time Budget per Audit

- Interviews: 3–6 hrs (recorded)
- Processing: 4–6 hrs (transcript → cookbook)
- Presentation prep + demo build: 3–4 hrs
- Presentation: 1 hr

**Total: ~12–17 hrs.** At founding $500, that's $30–40/hr — under-priced on labour, but the audit's job is to *win the architecture sale*, not to be profitable on its own.
