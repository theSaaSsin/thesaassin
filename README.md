# theSaaSsin

**I build the system that replaces your marketing team.**

UK-based operator. I ship high-converting websites, lead-recovery systems, and custom automations for SaaS founders and service businesses that want their ops running without them sitting in the middle of every handoff.

- Live work → **[thesaassin.com](https://thesaassin.com)**
- Book a consult → [calendly.com/thesaassin](https://calendly.com/thesaassin)
- Email → thesaasguy101@gmail.com

---

## What I ship

- **Landing pages and funnels** — conversion-first, no framework overhead
- **Lead-recovery systems** — retargeting, re-engagement, abandonment salvage
- **Custom automations** — internal ops, CRM sync, reporting, AI workflows
- **The Operator Panel** — in-house client-acquisition tooling

## Stack I reach for

Plain HTML / CSS / vanilla JS when a framework is overkill · Node · Express · Tauri · Cloudflare Pages · Supabase · Groq · Notion API · Puppeteer

## Currently

Building the **TheSaaSsin Operator Panel** — end-to-end lead → pitch → close studio. Phase 2 shipped: stronger intent detection, comment scraping, scoring refinements.

---

## About this repo

This repo serves **[thesaassin.com](https://thesaassin.com)** — the one-page landing site. Single-file, no framework, no build step. Auto-deploys via GitHub Pages with a custom domain via Porkbun DNS.

### Files

| File | Purpose |
|------|---------|
| `index.html` | Entire site — markup, styles, scripts inline |
| `CNAME` | GitHub Pages custom-domain config |
| `robots.txt` | Crawler directives |
| `sitemap.xml` | Search-indexing hints |

### Local preview

```bash
git clone https://github.com/theSaaSsin/thesaassin.git
cd thesaassin
python -m http.server 8000
# open http://localhost:8000
```

Or just double-click `index.html`.

### Deployment

Pushes to `main` auto-deploy via GitHub Pages. DNS: 4 A records at apex + `www` CNAME → `thesaassin.github.io`.

---

*Ship the system. Remove yourself. Scale.*
