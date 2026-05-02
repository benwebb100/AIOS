# Workstream — Landing Page

> **Status:** Not started
> **Owner:** Claude (build) + Bailey (deploy)
> **Stack:** Static site → Render
> **Case-study dependency:** Hero, problem, what-it-is, how-it-works, FAQ, audit CTA all independent. Social proof / testimonials section waits.

## Why now
- Anchor for any cold traffic (LinkedIn, ads, referral DMs)
- The "where do I learn more" answer in discovery conversations
- Required before paid acquisition can switch on (no point sending traffic with nowhere to land)

## Page Sections
1. **Hero** — One-liner from Brand.md + sub-headline + audit CTA
2. **Problem** — "AI is everywhere and you're still copy-pasting" framing (lift from Brand.md voice)
3. **What an AIOS is** — 3-tile breakdown (Brain, Hands, Voice — or whichever decomposition lands)
4. **How it works** — Audit → Architecture → Install → Retainer (4 steps, visual)
5. **What changes** — Outcomes block (hours saved, automation %, away-from-desk autonomy)
6. **[Social proof block — empty until Lou/Jason produce results]**
7. **FAQ** — Pricing transparency, "is this just ChatGPT?", "what about my data?", "what if I stop?"
8. **CTA** — Book a free 30-min intro OR pay for the audit (decide which is the front door)

## Open Questions
- Domain — `autoos.com.au`? `autoos.ai`? Something else?
- Front-door CTA — free intro call (lower friction, higher volume) or audit-direct (higher commit, better lead quality)?
- Email capture vs Calendly embed?
- Single page or multi-page (separate /audit, /pricing, /faq routes)?
- Brand voice level — peer-to-peer operator (per Brand.md) or slightly polished?

## Done When
- Live at the chosen domain
- Mobile-responsive
- CTA wired to Calendly + Stripe checkout (or whichever flow we land on)
- Analytics installed (Plausible or GA — Plausible preferred for privacy story)

## Build Plan
1. Bailey decides domain + purchases
2. Claude generates static HTML/CSS skeleton with placeholder copy
3. Bailey reviews structure, requests revisions
4. Bailey deploys to Render as static site
5. Iterate copy section-by-section
6. Wire CTA flows
7. Plug in social proof when Lou/Jason results land

## Inputs Needed
- Domain decision
- Owner headshot, brand colours/fonts
- Calendly link for intro / Stripe product for audit
- Decision on front-door CTA (gates the conversion architecture)
