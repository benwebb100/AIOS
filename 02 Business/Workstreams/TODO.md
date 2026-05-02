# TODO — AutoOS

> Live tracker for the parallel acquisition build. Last updated: 2026-05-02 strategy session with Ben.
> See [Workstreams/README.md](README.md) for the framing and sequencing rule.

## Active deals (highest priority)

- [ ] **Pre-draft Lou's revised proposal** based on second discovery call — so when her email lands the turnaround is hours, not days. _Bailey + Claude_
- [ ] **Decide on Jason check-in** — currently dormant. Nudge or leave him to surface? _Bailey_
- [ ] **Move Duncan from `lead` → `discovery booked`** — open the conversation, run 3-question discovery (commercial/residential split, last handover walk-through, sample O&M). _Bailey_

## Pitch Deck

- [x] Brand identity locked (`02 Business/Brand.md` — Visual Identity section)
- [x] Slide structure + copy drafted ([Pitch-Deck.md](Pitch-Deck.md))
- [x] Claude Design prompt written
- [ ] Generate v1 in Claude Design _(in progress)_
- [ ] Review + iterate
- [ ] First live use in a discovery → audit conversion conversation

## Landing Page

- [x] Brand-consistent static site built (`landing-page/`)
- [x] Hero, problem, what-it-is, how-it-works, outcomes, FAQ, book sections
- [ ] **Buy domain `autoos.com.au`** (~$15/yr) _Bailey_
- [ ] **Provide GHL audit booking URL** → replaces `REPLACE_WITH_GHL_AUDIT_BOOKING_URL` in `landing-page/index.html`
- [ ] **Provide GHL intro booking URL** → replaces `REPLACE_WITH_GHL_INTRO_BOOKING_URL` in `landing-page/index.html`
- [ ] Confirm contact email (placeholder: `hello@autoos.com.au`)
- [ ] Deploy to Render — Static Site, Root Directory `landing-page`, no build command, Publish Directory `.`
- [ ] Point DNS at Render once site is up
- [ ] _(later)_ Plausible analytics — uncomment `<script>` in `index.html`
- [ ] _(later)_ Add social proof section between FAQ and Book once Lou or Jason produces a documented win

## Paid Audit SOP (refinement)

- [x] v1 SOP exists (`02 Business/SOPs/Paid-Audit.md`)
- [x] Refinement roadmap written ([Paid-Audit-Refinement.md](Paid-Audit-Refinement.md))
- [ ] Brainstorm pricing band + cookbook depth with Ben (highest-impact first)
- [ ] Pressure-test against first real audit (Duncan candidate)

## Ad Creative Angles

- [x] 5 angles drafted in Strategy.md, roadmap ([Ad-Creative-Angles.md](Ad-Creative-Angles.md))
- [ ] **Decide: Bailey-on-camera vs voiceover** (gates everything else) _Bailey_
- [ ] Hook variants for angles 1, 2, 4 (Overwhelm / Time / FOMO)
- [ ] Film batch (3 angles in one session — don't drag across multiple shoots)
- [ ] Edit + caption
- [ ] Hold in inventory until ad spend turns on
- [ ] _(later)_ Angles 3 (ROI) + 5 (Demo) — fill when Lou/Jason produce material

## Loom Demo

- [x] Roadmap + recommendation ([Loom-Demo.md](Loom-Demo.md))
- [ ] **Decide: Version A (dogfooded — filmable now) or wait for Version B (client-shaped)** _Bailey_
- [ ] Pick the workflow to demo (suggested: ingest meeting transcript → update vault → draft action items)
- [ ] Choose tool (Loom / Screen Studio / OBS)
- [ ] Film + edit
- [ ] Embed in landing page + pitch deck

## Decisions confirmed (2026-05-02)

- ✅ Domain: `autoos.com.au`
- ✅ Front-door CTA: hybrid — audit primary, intro secondary
- ✅ Brand identity: developer-tools aesthetic; off-black `#0A0F0E` + warm off-white `#F5F2ED` + amber `#FF6B1A`; Inter + JetBrains Mono
- ✅ Pitch deck v1: 11 slides (case-study slot added when proof lands)
- ✅ Loom demo Version A recommended over waiting for Version B

## Reference

- Vault context: `02 Business/About.md`, `Brand.md`, `Strategy.md`, `Clients.md`, `Team.md`
- Workstream roadmaps: this folder
- Council verdict (dashboard timing): `reference/Council-Verdict-Dashboard-Timing.md`
- Master Playbook (full delivery framework): `reference/Master-Playbook.md`

---

_Live tracker — update checkboxes as work progresses. For per-workstream detail, see the individual `.md` files in this folder._
