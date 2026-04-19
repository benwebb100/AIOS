# AIOS Agency — Master Playbook

> **What this is:** Everything you need to understand, launch, and run an AI Operating System (AIOS) agency. Read it top to bottom, then use it as a reference. This is your constitution.
>
> **Last updated:** April 2026

---

## Part 1: What You're Building

### The One-Liner
You install AI operating systems for business owners. They stop using ChatGPT like a search engine and start using AI as a system that actually knows and runs their business.

### The Core Thesis
The AI Operating System is not the business — it's the delivery layer that makes an existing business dramatically more efficient. You:

1. **Contextualise** the AI with everything about the client's business (the "brain")
2. **Connect** it to all their systems (the "hands")
3. **Build** automations on top at speed (the "output")

The setup creates a development environment so powerful that ongoing builds take hours, not weeks — which makes a retainer model actually profitable.

### Why This Works Now
1. **Claude Code + MCP** — the integration layer finally exists natively. No custom middleware needed.
2. **Development speed** — what took a team weeks now takes one person hours with a contextualised workspace.
3. **Obsidian as knowledge layer** — free, local-first, markdown-based, perfect for AI ingestion. No vendor lock-in.
4. **Retainer economics** — fast builds mean you can profitably serve 5+ clients on monthly retainers.
5. **Market timing** — business owners are actively looking for "an AI person" but don't know what to ask for. You are the concrete, deliverable answer to that.

### Why Not Voice AI
Your original path was a Voice AI agency (dental clinics). The pivot makes sense because:
- Voice AI requires a **distribution partner** — someone feeding you clients in the vertical. Ben has that for gyms (ScanWise + Steve). You don't have it for dental.
- Voice AI requires building a **platform** (backend, database, agent management, billing). AIOS is client-by-client — you don't need a product, you need a process.
- AIOS has more **upside potential** and gives you more **optionality** — you learn every client's business, you build a template library, you can eventually productise the repeatable parts.
- Everything you learned building the Voice AI setup (Claude Code, Supabase, Git, APIs, Render) transfers directly.

---

## Part 2: The Five-Layer AIOS Framework

You deliver AI operating systems in layers. Not all at once — you build up over time. Each layer adds capability and justifies the ongoing retainer.

### Layer 0 — The Foundation
**What you install:** The substrate everything else is built on.
- **Claude Code** as the AI workspace (or Cursor for more visual clients)
- **CLAUDE.md** configured with business rules, project structure, and references
- **Obsidian vault** as the persistent knowledge base, connected via MCP
- **Skills/commands** — reusable workflows the client or you can trigger (like `/daily-brief`, `/weekly-report`)
- Optional: **Telegram/mobile bridge** so the client can interact with their AIOS from their phone

**In plain English:** You set up the workbench. After this, the client has a place where AI lives for their business — not a chat window, a workspace.

### Layer 1 — Context
> "The single biggest unlock — going from generic AI to AI that knows your entire business."

**What you build:**
- Export their existing ChatGPT/Claude history and distil into structured notes
- Document their business in Obsidian:
  - Business model, services, pricing, value proposition
  - Team members, roles, responsibilities
  - Key clients, partners, vendors
  - Brand voice, values, positioning
  - Strategy — goals, OKRs, initiatives
  - SOPs, processes, playbooks
- Configure CLAUDE.md to reference these docs automatically

**Deliverable:** The client opens Claude Code and has a conversation about their business without explaining anything. Claude already knows.

**How long this takes:** 2–3 hours of discovery + 1–2 hours of structuring. Most of the time is the conversation with the client, not the setup.

### Layer 2 — Data
> "Not just who you are, but where you are — quantitatively — in relation to your goals."

**What you build:** Connect the client's data sources via MCP servers or API integrations:
- Revenue/payments (Stripe, Xero, QuickBooks)
- CRM pipeline (HubSpot, GHL, Salesforce)
- Marketing analytics (Meta Ads, Google Analytics)
- Project/task management (Asana, Notion, Linear)
- Email (Gmail, Outlook)
- Calendar (Google Calendar, Calendly)
- Spreadsheets/dashboards (Google Sheets — many businesses run on these)

Each integration = an MCP server or API key in the Claude Code config.

**Deliverable:** The client can ask "how did we do last month vs target?" or "show me pipeline by stage" and get real answers from real data, instantly.

**How long this takes:** 1–3 hours depending on how many tools they use. Most MCP servers are plug-and-play — you just need the API keys.

### Layer 3 — Intelligence
Okay, can you run my strategic thinking? "Everything that's happening across the organisation, captured and queryable."

**What you build:**
- **Meeting capture** — transcription tool (Fireflies, Otter, etc.) so every meeting is logged and searchable
- **Communication capture** — Slack/Teams messages stored and queryable
- **Email digest** — key threads and decisions captured
- **Daily Brief** — the crown jewel:
  - Automated morning report (PDF + Telegram/email summary)
  - Pulls from all data sources + meeting/comms activity over past 24hrs
  - Tells a "story" of the business: key signals, stats, strategic insights, opportunities
  - Cron job runs daily, delivered before the client starts their day

**Deliverable:** The client wakes up to a full briefing on their business without lifting a finger. This is the first major "wow" moment and the strongest proof of ROI. This is what keeps clients paying.

### Layer 4 — Automate
> "Identify what's blocking their bandwidth and systematically eliminate it."

**What you build:**
- **Task audit** — list every recurring task by category (operations, sales, marketing, finance, admin)
- **Prioritise by bandwidth impact** — which tasks eat the most time relative to their value?
- **For each task, choose:**
  - **Automate** — AI does it entirely (cron jobs, scheduled workflows)
  - **Augment** — AI does 80%, client reviews/approves the last 20%
  - **Keep** — client still does it (high-judgment, relationship-dependent)
- **Target: 60–70% of tasks automated or heavily augmented**

**Example automations by business type:**

| Business Type | High-Impact Automations |
|---|---|
| Consultants/coaches | Client session prep, proposal generation, follow-up emails, content repurposing from session notes |
| Agencies | Client reporting, brief generation, campaign performance summaries, invoice prep |
| Professional services | Document drafting, research synthesis, compliance checklists, client communication |
| E-commerce | Inventory alerts, customer service drafts, ad performance reports, supplier communication |

### Layer 5 — Build
> "Use the freed bandwidth to build new things that actually grow the business."

This is the payoff. The client now has both the bandwidth (from layers 1–4) and the workspace to execute on growth initiatives at speed:
- Launch new products/services in days, not months
- Spin up marketing campaigns, funnels, landing pages
- Test new channels, partnerships, markets
- Build internal tools, dashboards, client portals
- Or simply enjoy the freed time

**This is where the retainer model compounds.** Each month you're not just maintaining — you're building new capability on top of an increasingly powerful base. The longer the client stays, the more valuable the system becomes, the harder it is to leave.

---

## Part 3: Service Delivery — The Constitution

This is your step-by-step process for every client. Follow it exactly until you've done it enough times to improvise.

### Phase 1: Discovery Call (30 minutes)

**Goal:** Understand their business well enough to scope the engagement and identify the first high-impact automation.

**Before the call:**
- Look up their business online (website, LinkedIn, social media)
- Note what tools they likely use based on their industry
- Have Claude Code open — you can ask it questions in real-time during the call

**The discovery framework — questions to ask:**

**About the business (5 min):**
- "Walk me through what your business does and who you serve."
- "How many people on the team? What does each person handle?"
- "What's your approximate revenue? Where does it come from?" (if they're comfortable sharing)

**About their tools (5 min):**
- "What software do you use day-to-day? CRM, accounting, project management, email, calendar?"
- "Where does your client/customer data live?"
- "Do you use any AI tools currently? ChatGPT, Claude, anything else?"

**About their pain (10 min) — this is the most important part:**
- "What takes up most of your time on a weekly basis?"
- "What's the thing you keep saying you'll get to but never do?"
- "If you could clone yourself, what would the clone do all day?"
- "What breaks when you go on holiday for a week?"
- "What information do you wish you had at your fingertips but don't?"

**About their goals (5 min):**
- "Where do you want the business to be in 12 months?"
- "What's the main thing standing between here and there?"
- "If we could free up 15 hours a week of your time, what would you spend it on?"

**Closing (5 min):**
- Summarise back what you heard: "So the biggest pain points are X, Y, and Z. The tools you're working with are A, B, and C. And ideally you want to get to [goal]."
- "Here's what I'd recommend for the setup: [quick scope]. I'll send you a proposal today."

**After the call:**
- Record the call (use Fireflies, Otter, or the built-in meeting recorder)
- Feed the transcript to Claude Code: "Here's a discovery call transcript. Extract the key business context, tools used, pain points, and recommended first automations."
- Draft the proposal (Claude Code can do this — give it a template)

### Phase 2: Setup Session (2–4 hours, remote or in-person)

**This is where you install Layers 0–2.** Do this in a single session.

**Prep (before the session):**
- [ ] Create their Obsidian vault structure (use the template below)
- [ ] Identify which MCP servers you'll need based on their tools
- [ ] Have their API keys / login credentials ready (ask them to prep these before the session)

**During the session:**

**Step 1 — Install the foundation (30 min):**
- Set up Claude Code on their machine (or yours if you're managing it for them)
- Create their project directory and CLAUDE.md
- Install Obsidian and create their vault with the standard structure:
  ```
  01 Inbox/
  02 Business/
    About.md          — business model, services, pricing
    Team.md           — people, roles, responsibilities
    Clients.md        — key clients, partners, vendors
    Brand.md          — voice, values, positioning
    Strategy.md       — goals, OKRs, current initiatives
    SOPs/             — processes and playbooks
  03 Meetings/
  04 Archive/
  ```
- Connect Obsidian to Claude Code via MCP

**Step 2 — Load context (60–90 min):**
- Work through each vault document with the client, filling them in together
- This is a structured conversation — you're interviewing them and typing as you go
- Don't try to be perfect. Get 80% of the context captured. You'll refine over the first month.
- Export and distil any existing ChatGPT/Claude history they have

**Step 3 — Connect tools (30–60 min):**
- Install MCP servers for their key tools (start with the 2–3 most important)
- Common ones: Gmail, Google Calendar, Slack, Google Sheets, Stripe, HubSpot
- Test each connection: "Show me my last 5 emails" / "What's on my calendar this week?"
- Add API keys to the Claude Code config

**Step 4 — First automation (30 min):**
- Pick the single highest-impact automation from the discovery call
- Build it live with the client watching — this is your "wow" moment
- Good first automations:
  - Daily brief (cron job pulling from their data sources)
  - Weekly client report auto-generation
  - Meeting prep (pull context before each calendar event)
  - Email draft assistance with full business context
  - Pipeline/revenue summary on demand

**End of session:** The client should be able to open Claude Code, ask a question about their business, and get a genuinely useful answer. That's the bar.

### Phase 3: First Week

- **Day 1–2:** Daily brief goes live (if that was the first automation). Check in with the client — is it useful? What's missing?
- **Day 3–5:** Refine the context based on what you're learning. Add missing SOPs, update team info, fix any integration issues.
- **Day 7:** First weekly check-in call (15 min). Ask: "What was useful? What surprised you? What do you wish it could do?"

### Phase 4: Ongoing Retainer (Monthly)

Each month you deliver:
- **1–2 new automations or augmented workflows** (from the task audit, or client requests)
- **Context updates** — keep the vault current as the business evolves
- **Integration maintenance** — fix anything that broke, add new tools if needed
- **Monthly check-in** (30 min) — review usage, discuss what to build next, capture new context

### Scope Management

This is critical. Without boundaries, you'll burn out.

**Included in retainer:**
- 1–2 automations per month
- Context updates and maintenance
- Monthly strategy call
- Async support (Slack/email, respond within 24 hours on business days)

**Not included (charge separately or say no):**
- Custom software development (building apps, websites, dashboards from scratch)
- Marketing execution (running their ads, writing all their content)
- Being on-call 24/7
- Anything that requires more than 8–10 hours/month per client

If a client asks for something big, scope it as a separate project with a separate fee. Don't let it creep into the retainer.

---

## Part 4: AIOS KPIs

Three metrics that prove the system is delivering value. Use these in monthly check-ins and to justify the retainer.

| KPI | What It Measures | Target |
|---|---|---|
| **Away-from-desk autonomy** | Can the client run their business from their phone? Test periodically. | 90%+ capability from mobile within 60 days |
| **Task automation %** | Of all recurring tasks audited, what % are now automated or augmented? | 60–70% within 30–60 days of Layer 4 |
| **Revenue per employee** | Is the business doing more with fewer people, or same people doing more? | Trending up quarter over quarter |

These also double as **sales tools** — during discovery calls, ask: "What percentage of your time is spent IN the business vs ON it?" That frames the entire value prop.

---

## Part 5: Pricing

### Founding Clients (First 3)
| Component | Price | What They Get |
|---|---|---|
| Setup | $1,500 | Full AIOS install (Layers 0–2 + first automation) |
| Monthly retainer | $1,000/mo | 1–2 automations/month, context maintenance, monthly call |

Frame this explicitly: "You're one of our first three clients. You get founding pricing in exchange for being a case study and giving us feedback."

### Standard Pricing (After 3 Clients)
| Component | Price | What They Get |
|---|---|---|
| Setup | $3,000–5,000 | Full AIOS install |
| Monthly retainer | $2,000–3,000/mo | 1–2 automations/month, daily brief, ongoing builds |

### Premium (In-Person Setup)
- Add $1,000–2,000 to setup fee for travel + in-person delivery
- In-person builds trust fast, justifies premium pricing, and you get the context right because you're sitting with them

### Revenue Target
5 clients at $2,500/mo avg = **$12,500/mo recurring**. Realistic within 6 months.

---

## Part 6: Go-to-Market

### The Offer in One Sentence
"We set up an AI operating system that knows your entire business — your team, your clients, your numbers, your processes — so AI actually works for you instead of you working for it."

### Why People Will Care (Right Now)
There is a massive market of business owners who:
- Use ChatGPT daily but know they're barely scratching the surface
- Feel overwhelmed by the pace of AI and don't know where to start
- Would pay for someone to just set it all up properly
- Have heard about AI automations but only seen point solutions (chatbots, Zapier workflows)

You're not selling AI. You're selling **the setup** — the thing they can't do themselves.

### Meta Ads Strategy

**Targeting:**
- Business owners, founders, entrepreneurs, consultants, agency owners
- Interest: AI tools, productivity, business coaching, entrepreneurship
- Age: 28–55
- Geography: Start AU, expand to UK/US

**Ad Angles to Test:**

1. **The overwhelm angle:**
   "AI is everywhere and you're still copy-pasting into ChatGPT. There's a better way. We set up an AI operating system that actually knows your business — your clients, your numbers, your processes — and works on it with you. Book a free strategy call."

2. **The time angle:**
   "What if AI could prep for your meetings, brief you every morning, and handle half your recurring tasks — because it actually knows your business? That's what an AI operating system does. We set it up for you."

3. **The demo angle:**
   Screen recording of a real AIOS in action. Show the daily brief. Show a data pull. Show an automation running. "This is what an AI operating system looks like. We build these for business owners. Book a call."

4. **The FOMO angle:**
   "Your competitors are setting up AI systems that run their businesses while they sleep. You're still writing prompts in ChatGPT. Let's fix that."

**Ad Format:**
- Short-form video (30–60 sec), talking to camera or screen recording
- Hook in first 3 seconds (pattern interrupt, bold claim, or question)
- CTA: "Book a free strategy call" → landing page → Calendly

**Budget:**
- Start with $30–50/day
- Test 3–4 ad angles for 7 days each
- Kill anything above $50 cost per lead, scale anything below $20

### Landing Page

Keep it simple. One page. Above the fold:
- Headline: "Get an AI Operating System Set Up for Your Business"
- Subhead: "Stop using ChatGPT like a search engine. We install AI that actually knows and runs your business."
- CTA button: "Book a Free Strategy Call"
- Below the fold: 3–4 bullet points on what the AIOS does, pricing overview, FAQ
- Build it on Carrd ($19/year), Framer, or a simple static page on Render

### Content Strategy (After First 3 Clients)
- LinkedIn posts documenting real setups (anonymised if needed) — before/after format
- Screen recordings of AIOS features in action
- Client testimonials (video > text)
- "Day in the life" content — what it looks like to have an AIOS running

### Referrals
$500 credit toward next month's retainer for each referred client who signs up. Tell every client about this during onboarding.

---

## Part 7: Ideal Verticals

You're starting broad — no niche yet. But some business types will get more value than others. Here's the landscape so you know what you're looking at when leads come in.

### Tier 1 — Highest ROI, Easiest Sell
| Vertical | Why It Works | Key Automations |
|---|---|---|
| **Consultants / coaches** | Owner IS the product. Brain full of frameworks and client context trapped in their head. Huge leverage from contextualising all of it. | Client prep, proposal gen, session notes → action items, content from expertise |
| **Professional services (lawyers, accountants, advisors)** | Knowledge-heavy, high hourly rates, tons of repetitive research and document work. Even small time savings = big dollar ROI. | Document drafting, client comms, research synthesis, compliance checklists |
| **Agency owners (marketing, creative, dev)** | Already tech-savvy, juggling multiple clients and tools, need systematisation. | Client reporting, project management, brief generation, campaign analysis |

### Tier 2 — Good Fit, Needs More Positioning
| Vertical | Why It Works | Consideration |
|---|---|---|
| **Real estate agents/teams** | High transaction values, lots of CRM/follow-up work | Some overlap with existing AI tools |
| **Recruiters / staffing firms** | Candidate matching, outreach, pipeline management | Competitive market but most solutions are point-based |
| **E-commerce operators** | Multi-channel, data-heavy, lots of repetitive ops | Proven model (others are doing it) |

### Tier 3 — Possible but Harder Sell
| Vertical | Challenge |
|---|---|
| Medical / dental / chiro | Harder to quantify ROI, regulated, already saturated with booking AI |
| Retail / hospitality | Lower margins, less knowledge-work |
| Trades / construction | Less digitally native, longer sales cycle |

**Don't pick a niche yet.** Take the first 5 clients from wherever they come. The niche will reveal itself based on which clients get the most value and which ones you enjoy working with.

---

## Part 8: Competitive Moat

The generic "I'll set up Claude Code for you" offer will commoditise. Here's how you stay ahead:

1. **Template library** — every client you do, you save reusable configs: CLAUDE.md templates, Obsidian structures, MCP setups, automation playbooks. Client #10 is 3x faster to set up than client #1.
2. **Compounding context** — the longer you work with a client, the more their AI knows, the harder it is to switch. This is natural lock-in, not artificial.
3. **Vertical expertise** (when you eventually niche) — deep knowledge of one industry's tools, workflows, and pain points makes you the obvious choice.
4. **Builder vs user separation** — you hold the dev environment, the client gets the output. They depend on you for new builds, not just maintenance.

---

## Part 9: Your Boot Camp Curriculum

Before you take your first client, work through this. It should take 1–2 days.

### Day 1: Understanding Businesses as Systems

**Session 1 (2 hours): How businesses work**
Open Claude Code and work through these prompts:

- "Explain to me how a consulting business operates day-to-day. What are all the recurring tasks, who does what, what tools do they typically use?"
- "Now do the same for a marketing agency."
- "Now do the same for an e-commerce business."
- "What are the most common SaaS tools business owners use, grouped by category (CRM, accounting, project management, communication, marketing, etc.)?"

The goal: develop an instinct for what a business looks like on the inside — the tools, the processes, the pain points.

**Session 2 (2 hours): MCP servers and integrations**
- Research what MCP servers are available: `claude mcp list` or search GitHub for "MCP server [tool name]"
- Set up 3–4 MCP servers for tools you're likely to encounter:
  - Gmail
  - Google Calendar
  - Google Sheets
  - Slack or similar
- Test each one — connect it to Claude Code, pull real data, understand what it can and can't do
- Document what you learn: which servers work well, which are janky, what API keys are needed

**Session 3 (1 hour): Obsidian as a knowledge layer**
- Install Obsidian if you haven't already
- Create a sample vault using the client template structure (see Phase 2 above)
- Connect it to Claude Code via MCP
- Test: "What does this business do?" / "Who are the key team members?" / "What's the current strategy?"
- Understand how CLAUDE.md references vault files

### Day 2: Building a Practice AIOS

**Session 4 (3–4 hours): End-to-end practice build**
Pick a business you know (a friend's, a family member's, or make one up) and do the full setup:

1. Create the Obsidian vault with all the context documents filled in
2. Set up CLAUDE.md with references to the vault
3. Connect 2–3 MCP servers (even if simulated — Gmail + Calendar + Sheets is enough)
4. Build a daily brief automation
5. Build one more automation (meeting prep, report generation, whatever fits)
6. Test everything end-to-end

**Session 5 (1–2 hours): Practice discovery call**
- Get a friend or family member to pretend to be a business owner
- Run through the full discovery framework from Part 3
- Record it, play it back, notice what you missed
- Feed the recording to Claude Code and practice extracting the key info

**Session 6 (1 hour): Practice proposal**
- Based on your practice discovery call, create a proposal using Claude Code
- Include: what you heard, what you'd build, timeline, pricing
- Get feedback from Ben

### After the Boot Camp
You should be able to:
- [ ] Explain what an AIOS is in 30 seconds
- [ ] Run a discovery call using the framework
- [ ] Set up a full AIOS (Layers 0–2) in under 4 hours
- [ ] Build a basic daily brief automation
- [ ] Identify the top 3 automations for any business after a discovery call
- [ ] Create a proposal and send it same-day

---

## Part 10: Risk and Scope Management

### Things That Will Go Wrong (and How to Handle Them)

**"Can you also just..."** — Scope creep is the retainer killer. Every request that's not in the agreed scope gets logged and quoted separately. Be friendly but firm: "Love that idea. That's outside this month's scope — want me to quote it as an add-on?"

**Client dependency on you** — If you disappear, their system stagnates. Mitigate: document everything in their Obsidian vault, keep CLAUDE.md files clean. They should be able to hand the system to another builder if needed.

**API/tool changes** — MCP servers, Claude Code, and integrations all evolve fast. Budget 1–2 hours/month for maintenance per client. Flag this in your retainer scope.

**Privacy/security** — You have access to everything. Get a simple agreement in place covering data handling. Use separate API keys where possible. Never store client credentials in plain text.

**Scaling past solo** — At 8–10 clients you hit capacity. Options: raise prices, hire a junior builder, or productise (build a SaaS layer on top of repeatable setups). That's a future problem — don't optimise for it now.

**A client doesn't "get it"** — Some people will sign up thinking they're getting a chatbot. The discovery call should filter this out — if someone just wants "ChatGPT but for my business," they're not the right client. You're looking for people who want systems, not a toy.

---

## Part 11: Sprint Plan

### Sprint 0: Boot Camp (Days 1–2)
- [ ] Work through the curriculum in Part 9
- [ ] Set up your own AIOS (practice what you preach — your agency should run on one)
- [ ] Practice discovery call with a friend
- [ ] Practice end-to-end setup on a fake or real business

### Sprint 1: Go-to-Market Setup (Days 3–5)
- [ ] Build landing page (Carrd or Framer — keep it simple)
- [ ] Record 2–3 ad creatives (talking to camera + screen recordings)
- [ ] Set up Meta Ads account and create first campaign
- [ ] Set up Calendly for discovery call bookings
- [ ] Create a proposal template in Claude Code
- [ ] Write and practise your discovery call script

### Sprint 2: First Clients (Days 6–21)
- [ ] Launch ads ($30–50/day)
- [ ] Take discovery calls as they come in
- [ ] Close first 1–2 clients at founding pricing
- [ ] Deliver setup sessions
- [ ] Daily check-ins with clients during their first week
- [ ] Document everything — what worked, what was hard, what to improve
- [ ] Debrief with Ben after each setup

### Sprint 3: Refine and Scale (Days 22–45)
- [ ] Close client #3 at founding pricing
- [ ] Build your template library from the first 3 setups
- [ ] Collect testimonials / case studies
- [ ] Raise prices to standard tier
- [ ] Start content marketing (LinkedIn posts documenting setups)
- [ ] Refine ad creatives based on what's working
- [ ] First monthly retainer check-ins with clients

### Sprint 4: Systematise (Month 2–3)
- [ ] Onboarding process documented and repeatable
- [ ] Template vault and CLAUDE.md configs for common business types
- [ ] Proposal generation takes < 30 minutes
- [ ] Setup sessions take < 3 hours
- [ ] Evaluate: which verticals are working best? Time to niche?
- [ ] Explore partnership channels (coaches, accountants)
- [ ] Target: 5 paying clients, $8–12K MRR

---

## Part 12: Your Tech Stack

| Tool | What It's For | Cost |
|---|---|---|
| **Claude Code** | Your main tool — builds everything for clients | Covered by Ben |
| **Obsidian** | Knowledge base for each client's business | Free |
| **GitHub** | Version control for any code/config | Free |
| **Supabase** | Database if clients need dashboards or data layers | Free tier to start |
| **Render** | Hosting if clients need anything deployed | Free tier to start |
| **Carrd or Framer** | Your landing page | $19–30/year |
| **Calendly** | Discovery call booking | Free tier |
| **Meta Ads** | Primary acquisition channel | $30–50/day |
| **Fireflies / Otter** | Meeting recording + transcription | Free tier to start |
| **Loom** | Screen recordings for proposals and demos | Free tier |

### What You Already Know (From the Voice AI Build)
All of this transfers directly:
- Git (push, commit, version control)
- Supabase (tables, SQL, dashboard)
- Render (deploying services)
- Claude Code (the core workflow)
- APIs and environment variables
- How services connect to each other via webhooks and API calls

You are not starting from zero. You're starting from a solid foundation with a new application.

---

## Part 13: Working with Ben

### How This Relationship Works
- This is **your business**. You own it, you run it, you build it.
- Ben is your **strategic advisor**. He's done this before (SalesPro AI, ScanWise) and will help you avoid the mistakes he's already made.
- He is not doing delivery. He is not taking calls. He is not building client systems.

### Communication Cadence
- **Weekly call (30 min):** Bring your questions, blockers, and wins. Ben will help you think through strategy and next moves.
- **Async (Slack/messages):** For urgent questions or quick strategy checks between calls.
- **After each new client setup:** Debrief with Ben — what went well, what was hard, what to change.

### What to Ask Ben About
- Pricing decisions
- Scope management ("client wants X — should I include it?")
- Technical architecture ("what's the best way to set up Y?")
- Sales strategy ("how should I handle this objection?")
- When you're stuck and Claude Code isn't enough

### What NOT to Escalate to Ben
- Technical debugging (use Claude Code)
- Client communication (you handle all of it)
- Day-to-day decisions (you're the operator)
- Things you can figure out by spending 30 minutes in Claude Code researching

---

## Appendix A: Discovery Call Cheat Sheet

Print this out or have it on a second screen during calls.

```
OPENING (2 min)
- "Thanks for booking. Tell me a bit about your business."

TOOLS (5 min)
- "What software do you use day-to-day?"
- "Where does your client/customer data live?"
- "Do you use any AI tools currently?"

PAIN (10 min) — LET THEM TALK
- "What takes up most of your time weekly?"
- "What's the thing you keep saying you'll get to but never do?"
- "If you could clone yourself, what would the clone do?"
- "What breaks when you go on holiday?"
- "What info do you wish you had at your fingertips?"

GOALS (5 min)
- "Where do you want the business in 12 months?"
- "What's the main thing standing between here and there?"

CLOSE (5 min)
- Summarise pain + tools + goals back to them
- "Here's what I'd recommend for the setup..."
- "I'll send you a proposal today."
```

## Appendix B: Proposal Template

```
PROPOSAL FOR: [Business Name]
DATE: [Date]
PREPARED BY: Bailey — [Agency Name]

WHAT I HEARD
- [Pain point 1]
- [Pain point 2]
- [Pain point 3]

WHAT I'D BUILD
Phase 1 — Setup (Week 1):
- Full business context loaded into AI operating system
- Connected tools: [list their tools]
- First automation: [specific automation targeting their #1 pain point]

Phase 2 — Ongoing (Monthly):
- Daily business brief
- [Automation 2 based on their pain points]
- [Automation 3]
- Monthly strategy call + async support

INVESTMENT
- Setup: $[X] (one-time)
- Monthly: $[X]/month
- Includes: [scope summary]
- Founding client pricing — locked in for 6 months

NEXT STEPS
1. Sign off on this proposal
2. Share tool logins / API keys (I'll send you a checklist)
3. We schedule the setup session (2-3 hours, remote)
4. Your AI operating system is live within 48 hours
```

## Appendix C: Objection Handling

**"What even is an AI operating system?"**
"You know how you use ChatGPT and have to explain your business every time? Imagine if AI already knew everything — your team, your clients, your numbers, your processes — and could actually do work in your business, not just answer questions. That's what I set up."

**"I already use ChatGPT / Claude"**
"That's great — you're ahead of most people. The difference is you're using it like a search engine. What I set up is more like hiring a team member who knows your entire business and can access all your tools. It's the difference between googling a recipe and having a chef in your kitchen."

**"That sounds expensive"**
"I hear you. Let me put it this way — if it saves you even 10 hours a week, and your time is worth $100/hour, that's $4,000/month in recovered time for a fraction of that cost. Most clients see the ROI within the first week when their daily brief starts landing."

**"Can't I just set this up myself?"**
"You absolutely could — everything I use is available to anyone. It's like asking 'can I do my own accounting?' Technically yes. But it'd take you weeks to figure out what I can set up in a few hours, and you'd miss things I know from having done it for other businesses. Your time is better spent running your business."

**"I need to think about it"**
"Totally fair. I'll send the proposal over and you can sit with it. One thing worth mentioning — I only take on 5 clients at a time so I can give everyone proper attention. If you decide to go ahead, just let me know and I'll lock in your spot."

**"What happens if I stop paying?"**
"Everything I build lives in your systems — your Obsidian vault, your Claude Code setup, your integrations. You own all of it. If we stop working together, you keep everything. It just won't get new automations or maintenance updates."
