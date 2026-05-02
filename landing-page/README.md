# autoos — landing page

Static landing page for autoos.com.au. Single HTML file + single CSS file. No build step, no JS framework. Drop the folder onto Render as a static site.

## Files

| File | Purpose |
|---|---|
| `index.html` | The page |
| `styles.css` | Brand-consistent styles |
| `README.md` | This file |

## Placeholders to swap before deploying

Search-and-replace these in `index.html`:

| Placeholder | Replace with |
|---|---|
| `REPLACE_WITH_GHL_AUDIT_BOOKING_URL` | GHL audit calendar booking URL (×1 in the `#book` section) |
| `REPLACE_WITH_GHL_INTRO_BOOKING_URL` | GHL free intro calendar booking URL (×1 in the `#book` section) |
| `hello@autoos.com.au` | Real contact email if different (×1 in footer + 1 in mailto link) |

Optional later:
- Plausible analytics — uncomment the `<script>` tag at the bottom of `index.html` once `plausible.io` is set up for the domain
- Open Graph meta tags + social card image — add when ready for sharing

## Deploying to Render

1. Push this `landing-page/` folder (or its contents) to a Git repo Render can read
2. In Render: **New → Static Site**
3. Connect the repo, set:
   - **Build command:** *(leave empty)*
   - **Publish directory:** `landing-page` (if you push the whole AIOS repo) or `.` (if you push just the folder contents)
4. Add custom domain `autoos.com.au` in Render → Settings → Custom Domains
5. Update DNS at the registrar — Render gives you the CNAME / A records
6. Wait for cert to provision (~5 min after DNS resolves)

## Local preview

Just open `index.html` in a browser. No server needed. (For analytics testing later you'd want a local server, but the page itself is fully static.)

## Editing copy

All copy lives in `index.html` — no template engine, no markdown. Edit the file directly.

## Brand source of truth

If you change colours/typography, update `02 Business/Brand.md` first, then mirror to `:root` custom properties in `styles.css`. Don't let them drift.

## What's intentionally not here yet

- **Social proof / testimonials section** — slot in when Lou or Jason produces a documented win. Insert between the FAQ and the Book sections.
- **Case studies page** — same trigger.
- **Blog / changelog** — Sprint 4 work.
- **Privacy policy / terms** — needed before paid ads run, not before launch. Generate when ad spend turns on.
