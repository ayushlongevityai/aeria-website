# Luzen — full site roadmap (follow-up after Home)

Use this when moving beyond the Home page (`index.html`). Keep one canonical page per section (no template V1/V2/V3 variants).

## Shared global work (once, then copy)

- **Navigation + footer**: Mirror the Home pattern (already simplified): Home, About, Services, Projects, Journal (`/blogs/blog-v1` until renamed), Contact, Locations.
- **Meta / OG / favicons**: Same title pattern, description tuned per page, `assets/images/hero-og.jpg` or page-specific OG image.
- **Assets**: Local `assets/images/`, `CREDITS.md` updated for any new photos.
- **Broken links**: Until inner pages exist, either stub minimal `index.html` per folder or temporarily point CTAs to `/#contact`.

## Page-by-page outline

### About (`/about`)

- Story: why “balcony-first,” team, studio values.
- Timeline or 4-step process (audit → concept → build → style).
- Optional team photos; same image quality bar as Home.
- CTA: Book balcony audit → `/contact`.

### Services (`/services`)

- 5–6 packages: Starter Balcony, Terrace Transformation, Rooftop Lounge, Outdoor Kitchen / Dining, Vertical Garden, Micro-Balcony Rescue.
- Each: scope, what’s included, “from” price band, typical timeline.
- FAQ teaser linking to Home FAQ or expanded on-page.

### Projects listing (`/projects`)

- Grid of case studies (reuse card styling from Home projects block).
- Filters optional later: by typology (balcony / terrace / rooftop), m² band.

### Project detail (`/projects/<slug>`)

- Hero + narrative, m², duration, materials, before/after if available.
- Slugs aligned with Home: `the-compact-city-balcony`, `terrace-with-a-view`, `rooftop-lounge-retreat`, `the-vertical-garden-balcony`.

### Journal / Blog (`/blogs/blog-v1` or future `/journal`)

- Listing + 3–4 pillar posts: weatherproofing, load limits / structure, strata / HOA, seasonal styling.
- Reuse Webflow blog template if you import the missing HTML from Webflow export.

### Contact (`/contact`)

- Single form: space type, size (m²), photos, constraints (strata), preferred visit window.
- Response-time promise, service areas.

### Locations (`/location`)

- Map or city list; can merge into Contact if you want fewer pages.

## Production checklist (site-wide)

- Replace placeholder stats on Home with real numbers when available.
- Set **absolute** `og:image` URLs for production (social crawlers).
- Optional: self-host Webflow CSS/JS for full offline deploy.
- Legal: privacy, cookies if you use analytics.

See also [UPCOMING_PAGES.md](UPCOMING_PAGES.md) for routes missing from this export.
