# Curator Ledger: Website

A production-ready single-page site for Curator Ledger (finance & operations automation for Indian lenders, NBFCs and investment firms).
Live at https://curatorledger.vercel.app
Dark fintech aesthetic, brand-true (blue→navy/silver, Schibsted Grotesk + IBM Plex Mono),
with load animations, scroll reveals, animated counters, and an interactive
service-workflow viewer.

## Files
`index.html` + `assets/`: single-page site, images kept as separate files.

## Deploy (pick one)
- **Netlify (fastest):** go to app.netlify.com → "Add new site" → "Deploy manually" → drag this folder in. Live in ~20s.
- **Vercel:** `npx vercel` from this folder, or drag-drop in the dashboard.
- **GitHub Pages:** push these files to a repo → Settings → Pages → deploy from branch.
- **Any host / your own server:** upload `index.html` + `assets/` to the web root.

## Before going fully live: quick edits
- Email: no contact email is published yet. Add one to the footer once the inbox exists.
- Lead form: not connected to any inbox. Submissions show a holding note and are not stored.
  Wire it to Formspree, Supabase or your CRM before relying on it (see the script at the bottom of index.html).
- Fonts load from Google Fonts (needs internet); self-host if you want zero external calls.

## Image credits
Photos from Unsplash (free to use, no attribution required). Replace freely with your own.
