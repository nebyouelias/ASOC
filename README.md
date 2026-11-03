# ASOC 2026 — Official Conference Website

The official website for the **6th African Stroke Organization Conference (ASOC 2026)**.

**December 16–17, 2026 · Online**
Theme: *Enhancing Capacity, Expanding Impact: Stroke Care Transformation in Africa*

🔗 Live site: https://asoc-africanstroke.org

---

## Pages

| File | Purpose |
|---|---|
| `index.html` | Home — hero, about, conference history, program, attending online, hosts, themes, leadership, sponsorship |
| `register.html` | Registration — "opening soon" notice, what to have ready, joining details |

## Assets

- `aso-logo.png` — African Stroke Organization logo
- `chair-mehari.jpg`, `chair-sarfo.png` — conference chair portraits
- `share-card.png` — 1200×630 Open Graph image for social sharing
- `favicon.ico`, `favicon.png`, `favicon-96.png` — site icons

## SEO / verification files

- `sitemap.xml`, `robots.txt`
- `google02250dd651f95fa8.html` — Google Search Console verification (**do not delete**)
- `indexnow-key.txt` and the matching `*.txt` key file — IndexNow submission key (**do not delete**)

Structured data included: `Event` (online, `VirtualLocation`), `WebSite`, `Organization`, `FAQPage`, `BreadcrumbList`.

## Tech

Static HTML/CSS/JS. No build step, no dependencies, no framework. Every page is self-contained apart from shared images.

## Deployment

Deployed on Vercel. Configuration lives in `vercel.json` (caching headers, clean URLs, redirects). Pushing to `main` triggers an automatic production deployment. `vercel.json` also redirects the retired `donate.html`, `getting-there.html` and `hotels.html` URLs to the home page.

## Editing

Open the relevant `.html` file and edit directly — styles are in a `<style>` block at the top of each file. Key things you may want to change over time:

- **Conference dates** — search for `December 16` (and `20261216` for the Google Calendar link and `2026-12-16` for the countdown target and structured data)
- **Joining details** — the "Attend Online" section is `#online` in `index.html`; the platform and session times are stated as "to be announced" and need filling in once known
- **Announcement bar** — search for `announce-stack` near the top of the `<body>`
- **Registration form** — the form is not live yet. `register.html` carries an "opening soon" notice in the `#form` section; drop the embed back in there when the form is ready

## Contact

asocconference@gmail.com
