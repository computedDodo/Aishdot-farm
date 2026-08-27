# Aishdot Poultry Farm — Website

A 2-page static site: `index.html` (Home) and `about.html` (About & Services),
sharing `style.css` and `script.js`. No build step, no dependencies — plain
HTML/CSS/JS, so it deploys to Vercel as-is.

## Files
- `index.html` — Home page
- `about.html` — About & Services page
- `style.css` — shared design system (colors, type, layout)
- `script.js` — mobile menu toggle + footer year
- `README.md` — this file

## Deploy to Vercel (pick one)

**Easiest — drag and drop:**
1. Put all 5 files in one folder on your computer/phone.
2. Go to https://vercel.com/new
3. Drag that folder onto the page (or use "Browse" to select it).
4. Vercel detects it as a static site automatically — no settings needed. Deploy.

**Vercel CLI (if you have Node/npm):**
```bash
npm i -g vercel
cd path/to/this-folder
vercel
```
Follow the prompts; accept the defaults (no framework, no build command).

**Via GitHub (best for future updates):**
1. Push these files to a new GitHub repo.
2. On vercel.com, "Add New Project" → Import that repo.
3. Leave Framework Preset as "Other" — deploy.
4. Every future push to `main` auto-redeploys.

## Before it goes live — worth doing
- **Photos**: there are currently no photos, only icons/patterns — this was
  intentional so the site looks complete without placeholders, but real
  photos (the farm, birds, egg crates, packaging) would strengthen trust a
  lot. Ask the client for a few phone photos and I can drop them in.
- **Custom domain**: Vercel gives a free `*.vercel.app` URL immediately; a
  real domain (e.g. `aishdotpoultryfarm.com` or `.com.ng`) can be added
  under Project Settings → Domains once purchased.
- **WhatsApp number**: both CTA buttons currently point to 0806 489 2346.
  Say the word if the client prefers the second number (0814 436 7665) as
  primary instead.

## Customizing
All colors, fonts and spacing live at the top of `style.css` under `:root`
— change a value there and it updates across both pages. Copy lives
directly in the HTML files, in plain readable sections.
