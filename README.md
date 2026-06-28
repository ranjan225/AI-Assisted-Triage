# Sentriage — Marketing Site (Phase 1)

A single-file, self-contained landing page for the on-prem AI triage product. No
build step, no dependencies — it's pure HTML/CSS with a few lines of JS.

> **Overview only.** This page sells the *value and outcomes* (cut the noise,
> on-prem, data sovereignty). It deliberately reveals **none** of the
> implementation — no dataset, models, scoring approach, or pipeline.

## View it
Open `index.html` in any browser (double-click it), or serve locally:

```bash
cd "Phase 1"
python -m http.server 8080      # then open http://localhost:8080
```

## Deploy it (free options)
Drag the folder onto **Netlify Drop** (app.netlify.com/drop), or push to a repo
and enable **GitHub Pages** / **Cloudflare Pages** / **Vercel**. It's a static
site, so any host works.

## Before you publish — quick edits
- **Brand name:** "Sentriage" is a placeholder — find/replace it across
  `index.html` (logo, `<title>`, footer) with your chosen name.
- **Contact email:** currently `ranjan12574@gmail.com` in the nav, hero, CTA,
  and footer `mailto:` links — swap if needed.
- **Copy:** tune the headlines to taste; nothing here is technical or sensitive.

## Sections
Hero · Problem · How it works · Why on-prem · Who it's for · Pilot CTA · Footer.
Fully responsive (desktop + mobile nav).
