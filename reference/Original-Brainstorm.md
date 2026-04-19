# AIOS Business Model Brainstorm

> **Status:** Idea stage — not a personal pursuit, but a viable model to pass on to friends entering the space.
> **Date:** 2026-04-14
> **Inspired by:** Liam Oatley's AIOS video + Ben's experience building SalesPro AI

---

## Core Thesis

The AI Operating System is **not the business** — it's the delivery layer that makes an existing business dramatically more efficient. It needs a product or service inside it. The business model is: pick a vertical, productize the AIOS setup for that vertical, and charge for setup + ongoing builds.

This is the inverse of how most AI agencies work. Instead of auditing → scoping → building point solutions one at a time, you:

1. Contextualize the AI with everything about the business (the "brain")
2. Connect it to all their systems (the "hands")
3. Build automations on top at speed (the "output")

The setup creates a development environment so powerful that ongoing builds take hours, not weeks — which makes a retainer model actually profitable for a solo operator.

---

## The Five-Layer AIOS Framework

> Based on Liam Oatley's methodology — the AIOS is built in **layers, not leaps**. Each layer wraps around the business model (which stays at the core) and adds capability. The thicker the wrapper, the more bandwidth the founder gets back.

### Layer 0 — The Foundation (Claude Code + Obsidian)
This isn't a "layer" in Liam's framework — it's the substrate everything else is built on. This is what you're actually installing during the setup session.

- **Claude Code** as the AI workspace (or Cursor for more visual learners)
- **CLAUDE.md** configured with business rules, project structure, and references
- **Obsidian vault** as the persistent knowledge base, connected via MCP
- **Skills/commands** — reusable workflows (like `/explore`, `/daily-brief`) that the founder or you can trigger
- **Telegram/mobile bridge** (optional) — so the founder can interact with their AIOS away from desk

This is the equivalent of what Ben built for SalesPro: the working directory, the CLAUDE.md, the Obsidian vault with `_context/` folders, the MCP servers. Same pattern, applied to any business.

---

### Layer 1 — Context
> *"The single biggest unlock — going from generic AI to AI that knows your entire business."*

**What it is:** The AI fully understands who the business is, what they do, and how they operate. No more copy-pasting context into ChatGPT.

**What you build:**
- Export their ChatGPT/Claude history and distill into structured Obsidian notes
- Document their business in the vault:
  - Business model, services, pricing, value proposition
  - Team members, roles, responsibilities
  - Key clients, partners, vendors
  - Brand voice, values, positioning
  - Strategy — quarterly/annual goals, OKRs, initiatives
  - SOPs, processes, playbooks
- Structure it in Obsidian so Claude Code can load any context on demand
- Configure CLAUDE.md to reference these docs automatically

**Deliverable:** The founder can open Claude Code and have a conversation about their business without explaining anything. Claude already knows.

**SalesPro parallel:** This is the KB (knowledge base) that gets transformed into agent prompts during Phase 2. Same idea — context in, intelligence out.

---

### Layer 2 — Data
> *"Not just who you are, but where you are — quantitatively — in relation to your goals."*

**What it is:** Connect the business's data sources so the AI can pull real numbers, not just qualitative context. This turns the AIOS from "smart assistant" into "business analyst."

**What you build:**
- Connect data sources via MCP servers or API integrations:
  - Revenue/payments (Stripe, Xero, QuickBooks)
  - CRM pipeline (HubSpot, GHL, Salesforce)
  - Marketing analytics (Meta Ads, Google Analytics, Bitly)
  - Project/task management (Asana, Notion, Linear)
  - Email (Gmail, Outlook)
  - Calendar (Google Calendar, Calendly)
  - Spreadsheets/dashboards (Google Sheets — many businesses run on these)
- Each integration = an MCP server or API key in the Claude Code config
- The AI can now read AND write to all their systems from one place

**Deliverable:** The founder can ask "how did we do last month vs target?" or "show me pipeline by stage" and get real answers instantly.

**SalesPro parallel:** The Supabase backend + GHL integration. All data flows through one system that Claude can query.

---

### Layer 3 — Intelligence
> *"Everything that's happening across the organization, captured and queryable."*

**What it is:** The business's ongoing activity stream — meetings, messages, communications — fed into the AIOS so it stays current, not just static.

**What you build:**
- **Meeting capture** — connect Fireflies, Otter, or similar transcription tool. Every meeting logged and searchable.
- **Communication capture** — Slack/Teams messages stored and queryable (what did X say about Y last week?)
- **Email digest** — key threads and decisions captured
- **Daily Brief** — the crown jewel of this layer:
  - Automated morning report (PDF + Telegram summary)
  - Pulls from all data sources + meeting/comms activity over past 24hrs
  - Tells a "story" of the business: key signals, stats, strategic insights, opportunities
  - Cron job runs daily, delivered before the founder starts their day

**Deliverable:** The founder wakes up to a full briefing on their business without lifting a finger. This is the first major "wow" moment and the strongest proof of ROI.

**SalesPro parallel:** The conversation events system + admin dashboard. Real-time visibility into what's happening across all clients without logging into GHL.

---

### Layer 4 — Automate
> *"Identify what's blocking your bandwidth and systematically eliminate it."*

**What it is:** With context, data, and intelligence in place, now you audit every task the founder does and start automating or augmenting them one by one.

**What you build:**
- **Task audit** — list every recurring task by category (operations, sales, marketing, finance, admin). Liam had 83 tasks across his businesses.
- **Prioritize by bandwidth impact** — which tasks eat the most time relative to their value?
- **For each task, choose:**
  - **Automate** — AI does it entirely (cron jobs, scheduled workflows)
  - **Augment** — AI does 80%, founder reviews/approves the last 20%
  - **Keep** — founder still does it (high-judgment, relationship-dependent)
- **Use `/explore` workflow** — founder describes a task, Claude Code researches solutions, proposes an approach, builds it step by step
- **Set up cron jobs** for recurring automations (reports, data pulls, content drafts, follow-ups)
- **Target: 60–70% of tasks automated or heavily augmented**

**Example automations by vertical:**

| Vertical | High-Impact Automations |
|---|---|
| Consultants/coaches | Client session prep, proposal generation, follow-up emails, content repurposing from session notes |
| Agencies | Client reporting, brief generation, campaign performance summaries, invoice prep |
| Professional services | Document drafting, research synthesis, compliance checklists, client communication |
| E-commerce | Inventory alerts, customer service drafts, ad performance reports, supplier communication |

**Deliverable:** The founder's "in the business" time drops from ~80% to ~30%. They feel the bandwidth open up.

**SalesPro parallel:** The automated onboarding pipeline (Phase 2), the drip campaigns, the tour mirror system. Each one is a task that used to be manual, now runs automatically.

---

### Layer 5 — Build
> *"Use your freed bandwidth to build new things that actually grow the business."*

**What it is:** This is the payoff. The founder now has both the bandwidth (from layers 1–4) and the workspace (Claude Code + full context + integrations) to execute on growth initiatives at speed.

**What it enables:**
- Launch new products/services in days, not months
- Spin up marketing campaigns, funnels, landing pages
- Test new channels, partnerships, markets
- Build internal tools, dashboards, client portals
- Or simply enjoy the freed time — not every founder wants to 10x, some want their weekends back

**This is where the retainer model compounds.** Each month you're not just maintaining — you're building new capability on top of an increasingly powerful base.

**SalesPro parallel:** The demo pipeline, the admin dashboard, the campaign system — all built on top of the existing AIOS foundation because the context and integrations were already there.

---

## AIOS KPIs

Three metrics to track whether the system is actually delivering value (use these in client check-ins and to justify retainer):

| KPI | What It Measures | Target |
|---|---|---|
| **Away-from-desk autonomy** | Can the founder run their business from their phone? Test periodically — go a full day without the laptop. What breaks? | 90%+ capability from mobile within 60 days |
| **Task automation %** | Of all recurring tasks audited, what % are now automated or heavily augmented? | 60–70% within 30–60 days of Layer 4 |
| **Revenue per employee** | Is the business doing more with fewer people, or same people doing more? This is the ultimate efficiency metric. | Trending up quarter over quarter |

These KPIs also double as **sales tools** — during discovery calls, ask the prospect: "What % of your time is spent IN the business vs ON it?" That frames the entire value prop.

---

## Pricing Model

| Component | Price | Layers Covered | Notes |
|---|---|---|---|
| Setup fee (in-person or remote) | $3,000–$5,000 | Foundation + L1 Context + L2 Data + first automation | The "instant ROI" session — they walk away with a working AIOS |
| Month 1 retainer | $2,000–$3,000 | L3 Intelligence (daily brief) + L4 begins (task audit) | Daily brief is the first "wow" deliverable on retainer |
| Ongoing retainer | $2,500–$5,000 | L4 Automate + L5 Build | 1–2 automations/month + new builds. Price grows as systems compound |

**Target:** 5 clients at $3k/mo = $15k/mo recurring as a solo operator. Realistic within 3–6 months.

**In-person flyout model (Tyler's approach):** Add travel cost to setup fee. In-person builds trust fast, justifies premium pricing, and you get the context right because you're sitting with them.

---

## Ideal Verticals

The sweet spot is **businesses where the owner's knowledge/time is the bottleneck** — not businesses that need more appointment bookings (saturated with point solutions already).

### Tier 1 — Highest ROI, Easiest Sell
| Vertical | Why It Works | Key Automations |
|---|---|---|
| **Management consultants / coaches** | Owner IS the product. Brain full of frameworks, client context, methodologies that are trapped in their head or scattered across tools. Huge leverage from contextualizing all of it. | Client prep, proposal generation, session notes → action items, IP systematization, content from expertise |
| **Professional services (lawyers, accountants, advisors)** | Knowledge-heavy, high hourly rates, tons of repetitive research and document work. Even small time savings = big dollar ROI. | Document drafting, client communication, research synthesis, compliance checklists |
| **Agency owners (marketing, creative, dev)** | Already tech-savvy (easier sell), juggling multiple clients and tools, need systematization. | Client reporting, project management, brief generation, campaign analysis |

### Tier 2 — Good Fit, Needs More Positioning
| Vertical | Why It Works | Consideration |
|---|---|---|
| **Real estate agents/teams** | High transaction values, lots of CRM/follow-up work, relationship-driven | Some overlap with existing AI tools, need to differentiate |
| **Recruiters / staffing firms** | Candidate matching, outreach, pipeline management all benefit from context | Market is competitive but most solutions are point-based |
| **E-commerce operators** | Multi-channel, data-heavy, lots of repetitive operational work | Alice (from Liam's video) already doing this — proven model |

### Tier 3 — Possible but Harder Sell
| Vertical | Challenge |
|---|---|
| Dental / chiro / medical | ROI harder to quantify, regulated, already saturated with booking/recall AI |
| Retail / hospitality | Lower margins, less knowledge-work, harder to justify $3k/mo |
| Trades / construction | Less digitally native, longer sales cycle |

---

## Why This Works Now (and Didn't Before)

1. **Claude Code + MCP** — the integration layer finally exists natively. No custom middleware needed.
2. **Development speed** — what took a team weeks now takes one person hours with a contextualized workspace.
3. **Obsidian as knowledge layer** — free, local-first, markdown-based, perfect for AI ingestion. No vendor lock-in.
4. **Retainer economics** — fast builds mean a solo operator can profitably serve 5+ clients on monthly retainers.
5. **Market timing** — early adopter business owners are actively looking for "an AI person" but don't know what to ask for. This is a concrete, deliverable offer.

---

## Competitive Moat

The generic "I'll set up Claude Code for you" offer commoditizes fast (Liam's "teach them to fish" problem). Defensibility comes from:

1. **Vertical expertise** — deep knowledge of one industry's tools, workflows, and pain points
2. **Template library** — pre-built CLAUDE.md configs, MCP setups, Obsidian structures, and automation playbooks per vertical
3. **Ongoing relationship** — you hold the dev environment, client gets a chat interface. Tyler's separation of "builder vs user" creates dependency.
4. **Compounding context** — the longer you work with a client, the more their AI knows, the harder it is to switch

---

## Go-To-Market

### Acquisition
- **Facebook/Instagram ads** targeting business owners in chosen vertical
  - Hook: "Get a full AI operating system set up for your business"
  - This is a new offer — cuts through the noise of generic "AI automation" ads
  - Will attract early adopters and tech-curious owners (that's fine — they're the ideal first clients)
- **LinkedIn content** showing before/after of real client setups
- **In-person events** — local business meetups, industry conferences
- **Referrals** — once one consultant sees it, they tell their consultant friends

### Sales Process
1. Discovery call — understand their tech stack, pain points, how they currently use AI
2. Demo — show a real AIOS in action (use your own or a case study)
3. Propose setup + first automation targeting their biggest time sink
4. In-person or remote setup session
5. Monthly retainer kicks in

---

## Risk & Considerations

- **Client dependency on you** — if you disappear, their system stagnates. Mitigate: document everything in their Obsidian vault, keep CLAUDE.md files clean.
- **API/tool changes** — MCP servers, Claude Code, integrations all evolve fast. Maintenance is real overhead.
- **Scope creep** — "can you also just..." is the retainer killer. Clear deliverable count per month (1 big or 2 small automations).
- **Privacy/security** — you have access to everything. Need clear agreements, possibly separate API keys, and data handling policies.
- **Scaling past solo** — at 8–10 clients you hit capacity. Options: raise prices, hire junior builders, or productize (build a SaaS layer like SalesPro did).

---

## Connection to SalesPro AI

SalesPro is proof this model works at the **product** end of the spectrum:
- Vertical: gyms
- Context: KB → prompts → agent config (automated)
- Integrations: GHL, calendar APIs, Retell, SMS, Supabase
- Automations: voice agents, drip campaigns, tour mirroring, onboarding pipeline

The difference: SalesPro productized the entire stack so clients don't need Claude Code at all — they get a dashboard. This AIOS business model is the **services** version of the same pattern, suited for a solo operator getting started.

The natural evolution: start with services (setup + retainer), identify the most common builds across clients, then productize the repeatable parts into a SaaS.

---

## Action Items (for whoever picks this up)

- [ ] Choose a vertical (consulting/coaching is the obvious first pick — test with Ben's mum)
- [ ] Build a template AIOS setup for that vertical (CLAUDE.md, Obsidian structure, MCP config, first 3 automations)
- [ ] Set up a case study by doing 1–2 free/discounted installs
- [ ] Create a simple landing page + Facebook ad creative
- [ ] Price at $5k setup + $2.5k/mo retainer, adjust based on market response
- [ ] Document the setup process so it's repeatable in 3–4 hours per client
