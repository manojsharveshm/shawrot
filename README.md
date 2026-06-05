# Shawrot — Website

A production-ready single-page site for Shawrot (finance & operations automation).
Dark fintech aesthetic, brand-true (blue→navy/silver, Schibsted Grotesk + IBM Plex Mono),
with load animations, scroll reveals, animated counters, and an interactive
service-workflow viewer.

## Two versions in this package
1. `index.html` + `assets/`  — standard build (images kept as separate files; easiest to edit).
2. `shawrot-website.html`     — same site as ONE self-contained file (images embedded). Drop it anywhere.

## Deploy (pick one)
- **Netlify (fastest):** go to app.netlify.com → "Add new site" → "Deploy manually" → drag this folder in. Live in ~20s. Then point your shawrot.club domain at it.
- **Vercel:** `npx vercel` from this folder, or drag-drop in the dashboard.
- **GitHub Pages:** push these files to a repo → Settings → Pages → deploy from branch.
- **Any host / your own server:** upload `index.html` + `assets/` to the web root.
- **One-file option:** upload only `shawrot-website.html` (rename to index.html) — no assets folder needed.

## Before going fully live — quick edits
- Email: replace `hello@shawrot.club` (appears in the form, footer, mailto).
- About photo: `assets/office.jpg` is a placeholder — swap in your real headshot.
- Lead form: currently opens the visitor's email client (mailto, no backend).
  For captured leads, wire it to Formspree, your CRM, or Google Forms (one-line change in the script).
- Fonts load from Google Fonts (needs internet); self-host if you want zero external calls.

## Image credits
Photos from Unsplash (free to use, no attribution required). Replace freely with your own.
