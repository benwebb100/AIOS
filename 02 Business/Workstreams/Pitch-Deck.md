# Workstream — Pitch Deck

> **Status:** Not started
> **Owner:** Bailey
> **Build tool:** Claude Design (Canva via MCP)
> **Case-study dependency:** Structure independent. The case-study slide is the one slot that waits for proof.

## Why now
Pitch deck is needed for: paid audit pitch, post-audit architecture proposal, ad landing page anchor, and discovery follow-up. Structure can be locked before any client testimonials exist — only the case-study slide changes when proof lands.

## Audience
Business owners $200K–$5M revenue, mid-conversation in the discovery → audit pipeline. Shown alongside live narration, not as a standalone artifact.

## Slide Structure (10–12 slides)
1. **Cover** — AutoOS, one-liner, owner photo
2. **The Problem** — "You're using ChatGPT like a search engine"
3. **What an AIOS Is** — Substrate analogy (knowledge base + Claude Code + MCP integrations + automations)
4. **Executive vs Operations** — Two value props, one install (per Strategy.md)
5. **What Gets Installed** — Layers 0–4 visual
6. **What Changes** — Outcomes (hours back, automation %, away-from-desk autonomy)
7. **Case Study** — *[CASE STUDY SLOT — fill when Lou or Jason produces a result]*
8. **The Process** — Audit → Architecture → Setup → Daily check-ins → Retainer
9. **What This Costs** — Founding pricing or standard, depending on prospect tier
10. **What Happens Next** — Sign audit scope today, kickoff this week
11. **Q&A**
12. **Appendix** — FAQs, integrations list, security/data handling

## Open Questions
- One deck or two variants (Executive-led vs Operations-led entry points)?
- Embed the Loom demo or screen-share live during the call?
- Founding-tier deck variant or unified deck with pricing as a conversation?
- Where does pricing actually live — slide 9 fixed, or pulled out into a separate proposal doc?

## Done When
- Canva file lives in a `Brand assets` folder, exportable to PDF
- Empty case-study slide is templated and clearly labelled
- Has been used in at least one live discovery → audit conversion conversation

## Inputs Needed
- Brand colours / fonts (from Brand.md or to define)
- Owner headshot
- Outcome numbers (some from playbook / projected; the case study slide needs real client data)

## Sequencing
1. Brainstorm structure with Ben (validate slide order)
2. Write copy slide-by-slide (Bailey + Claude)
3. Generate via Claude Design / Canva
4. Test in next live conversation
5. Iterate after first 3 uses

## v1 Build Decision (2026-05-02)
- Skip slide 7 (case study) entirely until Lou or Jason produces a documented win. v1 ships as **11 slides**. When proof lands, slide 7 slots in between Outcomes and Process — design system stays consistent.
- Brand identity locked: see `02 Business/Brand.md` Visual Identity section.

## Claude Design Prompt (paste-ready)

````
You are designing a pitch deck for AutoOS, an agency that installs AI operating systems for business owners. Output: 11 slides, 16:9, type-driven, premium-feeling, operator-grade.

# Brand
**Name:** AutoOS. Wordmark is `autoos` — all lowercase, set in JetBrains Mono Bold. Optional small amber filled square `▮` before the wordmark.

**Voice:** Direct, operator-to-operator, no AI hype-speak. Write like you've already solved the problem.

**Palette:**
- Primary: warm near-black `#0A0F0E` (type + primary surfaces)
- Background: warm off-white `#F5F2ED` (default canvas, not stark white)
- Accent: signal amber `#FF6B1A` (use sparingly — one element per slide max)
- Muted: soft grey `#A8A29A`

**Typography:**
- Display/headlines: Inter (or similar geometric sans), tight tracking, large weight contrast
- Body: Inter Regular
- Accent (numbers, stats, status labels): JetBrains Mono or Space Mono

**Visual treatment:**
- Generous white space — every slide breathes
- One idea per slide
- No stock photos, no gradients, no robot/circuit/brain imagery, no glassmorphism, no drop shadows
- Numbers and stats are HUGE (60–100pt monospace)
- Grid-based, deliberate, almost editorial layout

**Reference looks:** linear.app, vercel.com, cursor.com, railway.app. NOT typical AI startup decks.

# Slides

## 1 — Cover
- Wordmark `autoos` centered, large
- Beneath: "We install AI operating systems for businesses."
- Bottom-left small mono caption: `[Founder Name] · [Date]`

## 2 — The Problem
- Headline (huge): "You're using AI like a search engine."
- Body (smaller, off to the side or below): "ChatGPT helps with the next 10 minutes. It doesn't know your business, your team, your clients, your numbers, or your processes. Every conversation starts from zero."
- No imagery. Type-only.

## 3 — What an AIOS Is
- Headline: "An AI operating system that actually knows your business."
- 4-tile grid (2x2 or horizontal row), each tile with a one-line label in mono:
  - `knowledge base` — your business as context
  - `claude code` — the brain
  - `mcp integrations` — your tools, connected
  - `automations` — the work runs itself
- Tiles are simple bordered rectangles, no icons.

## 4 — Executive vs Operations
- Headline: "Two value props. One install."
- Two columns:
  - Left: **Executive** (personal). Sub: "Changes the owner's life." List: Email triage · Scheduling · Decision support · Daily brief
  - Right: **Operations** (company). Sub: "Changes the business." List: Reporting · Team workflows · Client management · Process automation
- Single amber dividing line between the columns.

## 5 — What Gets Installed
- Headline: "Built once. Compounds forever."
- Vertical stack of 5 layers, each a row with mono label + plain-English description:
  - `layer 0 — foundation` — accounts, repos, vault structure
  - `layer 1 — knowledge` — your business as living context
  - `layer 2 — integrations` — your tools, connected via MCP
  - `layer 3 — workflows` — your processes automated
  - `layer 4 — reporting` — visibility on demand
- Each row is clean, generous spacing.

## 6 — What Changes
- Headline: "What this actually does."
- Three huge mono numbers across the slide:
  - `90%+` — away-from-desk autonomy within 60 days
  - `60-70%` — recurring tasks automated within 30-60 days
  - `15-20 hrs` — back per week
- Numbers in primary near-black, one (e.g. middle) in amber.

## 7 — The Process
- Headline: "How we install."
- Horizontal 5-step flow:
  1. `audit` — interviews + cookbook + demo ($500)
  2. `architecture` — what we'll install, in what order
  3. `setup` — 2-4 hrs to install layers 0-2
  4. `daily check-ins` — first week of fine-tuning
  5. `retainer` — monthly builds, audits, automations
- Step labels in mono. Connecting line is amber.

## 8 — Pricing
- Headline: "What this costs."
- Two large blocks:
  - Setup: `$1,500` (mono, huge)
  - Retainer: `$1,000/mo` (mono, huge)
- Below in muted grey: "Founding pricing — locked for our first 3 clients."

## 9 — What Happens Next
- Headline: "If this lands."
- Three-step list with amber numerals:
  1. Sign the audit scope today
  2. Schedule kickoff this week
  3. First cookbook in your hands within 2 weeks
- Bottom-right: amber CTA button-style: `start the audit →`

## 10 — Q&A
- Single huge word centered: `questions.`
- Wordmark bottom-left.

## 11 — Contact
- Wordmark large
- Beneath in mono: email + phone
- Bottom in muted grey: "Built and run from an AutoOS workspace."

# Critical do-NOTs
- No purple/blue gradients
- No AI startup imagery (robots, circuits, brains, neural networks)
- No stock photos
- No drop shadows or glass effects
- No more than one amber accent per slide
- No emojis

Make every slide feel like a page from a serious infrastructure company's pitch deck — Linear, Vercel, Cursor — not an AI agency.
````
