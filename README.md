# thesaassin.com

The official landing page for **TheSaaSsin** — SaaS consulting and lead-acquisition systems for founders who'd rather ship than fiddle with funnels.

**Live:** https://thesaassin.com

---

## What this repo is

A single-file, hand-built static landing page. No framework, no build step, no bundler. Just HTML, CSS, and vanilla JavaScript in one self-contained `index.html`, served by GitHub Pages at a custom domain.

## Stack

- Static HTML / CSS / vanilla JS (all inline)
- Calendly embed for booking consults
- Scroll-reveal animations
- Responsive down to 320px

## Files

| File | Purpose |
|------|---------|
| `index.html` | Entire site (markup, styles, scripts inline) |
| `CNAME` | Custom domain config for GitHub Pages |
| `robots.txt` | Crawler directives |
| `sitemap.xml` | Search-indexing hints |

## Local preview

```bash
git clone https://github.com/theSaaSsin/thesaassin.git
cd thesaassin
python -m http.server 8000
# open http://localhost:8000
```

Or just double-click `index.html`.

## Deployment

Pushes to `main` auto-deploy via GitHub Pages. Custom domain `thesaassin.com` resolves via Porkbun DNS — A records to GitHub's edge IPs and a `www` CNAME.

---

Built and maintained by [@theSaaSsin](https://github.com/theSaaSsin).
