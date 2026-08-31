# ASOC 2026 — Official Conference Website

The official website for the **6th African Stroke Organization Conference (ASOC 2026)**, held jointly with the **1st Ethiopia Stroke Foundation Comprehensive Stroke Symposium**.

**November 1–4, 2026 · Addis Ababa, Ethiopia**
Theme: *Enhancing Capacity, Expanding Impact: Stroke Care Transformation in Africa*

🔗 Live site: https://asoc-africanstroke.org

---

## Pages

| File | Purpose |
|---|---|
| `index.html` | Home — hero video, about, conference history, program, call for abstracts, hosts, themes, leadership, sponsorship |
| `register.html` | Registration — embedded registration form, hybrid attendance info |
| `getting-there.html` | Travel guide — flights, visas, ride apps, money, SIM cards, altitude, weather |
| `hotels.html` | 29 Addis Ababa hotels with direct phone and email booking links |

## Assets

- `hero.mp4` / `hero-poster.jpg` — hero background video and poster frame
- `aso-logo.png`, `esf-logo.jpg` — organization logos
- `chair-mehari.jpg`, `chair-wondwossen.jpg` — conference chair portraits
- `share-card.png` — 1200×630 Open Graph image for social sharing
- `favicon.ico`, `favicon.png`, `favicon-96.png` — site icons

## SEO / verification files

- `sitemap.xml`, `robots.txt`
- `google02250dd651f95fa8.html` — Google Search Console verification (**do not delete**)
- `indexnow-key.txt` and the matching `*.txt` key file — IndexNow submission key (**do not delete**)

Structured data included: `Event`, `WebSite`, `Organization`, `FAQPage`, `BreadcrumbList`.

## Tech

Static HTML/CSS/JS. No build step, no dependencies, no framework. Every page is self-contained apart from shared images and the hero video.

## Deployment

Deployed on Vercel. Configuration lives in `vercel.json` (caching headers, clean URLs, redirects). Pushing to `main` triggers an automatic production deployment.

## Editing

Open the relevant `.html` file and edit directly — styles are in a `<style>` block at the top of each file. Key things you may want to change over time:

- **Dates and deadlines** — search for `September 6` (abstract deadline) and `September 10` (decisions)
- **Announcement bars** — search for `announce-stack` near the top of the `<body>`
- **Registration form** — the embedded form URL is in `register.html`, search for `docs.google.com/forms`

## Contact

asocconference@gmail.com
