# AI-Assisted Triage — Website

The landing page for **AI-Assisted Triage** — an on-prem AI engine that helps
security teams cut through the noise in their vulnerability-report queue.

## What it does

Security teams aren't drowning in vulnerabilities — they're drowning in *reports*
about them: duplicates, low-effort submissions, and a rising tide of
AI-generated noise. AI-Assisted Triage scores every incoming bug-bounty /
vulnerability-disclosure report in seconds, across seven dimensions:

- **Report quality**
- **Duplicate risk**
- **AI-generated likelihood**
- **Evidence completeness**
- **Technical accuracy**
- **Severity**
- **Suggested CWE**

…each with a short rationale — so analysts triage the real findings first and the
noise last.

Two principles it's built on:

- 🔒 **Self-hosted.** It runs entirely on your own infrastructure. No report ever
  leaves your environment. Bring your own model.
- 🤝 **Recommend, don't decide.** Every score comes with reasoning, and a human
  always makes the final call.

Built for the teams who *can't* put their reports in someone else's cloud —
government, defense, financial services, healthcare, and enterprise security
programs running their own disclosure programs.

## About this repository

This repo contains the **marketing landing page** — a single, self-contained
static site (`index.html`). No build step, no dependencies, just HTML/CSS with a
little JavaScript. It presents the product's value only; it contains none of the
engine, models, datasets, or implementation.

## View locally

Open `index.html` in any browser, or serve it:

```bash
python -m http.server 8080      # then open http://localhost:8080
```

## Deploy

It's a static site — host it anywhere:

- Drag the folder onto **Netlify Drop** (app.netlify.com/drop), or
- Enable **GitHub Pages**, **Cloudflare Pages**, or **Vercel**.

## Contact

Demos, pilots, and licensing: **ranjan12574@gmail.com**
