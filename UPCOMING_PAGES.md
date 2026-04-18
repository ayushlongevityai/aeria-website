# Pages not yet in this export

The local project currently contains only **[index.html](index.html)** (Home V.1 content).

For later customization passes, fetch or rebuild these pages from the published Webflow site:

| Route | Suggested filename | Notes |
|-------|-------------------|--------|
| `/about` | `about/index.html` | Or `about.html` at root if you prefer flat URLs |
| `/services` | `services/index.html` | |
| `/projects` | `projects/index.html` | |
| `/projects/<slug>` | `projects/<slug>/index.html` | Case study detail pages |
| `/blogs/blog-v1` | `blogs/index.html` or `journal/index.html` | Collapse variants → one **Journal** |
| `/blog/<post>` | `blog/<slug>/index.html` | |
| `/contact/contact-v1` | `contact/index.html` | Single Contact page |
| `/location` | `location/index.html` | Optional vs folding into Contact |

**Base URL to mirror:** `https://luzen-temlis.webflow.io`

After fetching, update internal links to match your hosting structure (relative paths work well for static hosting).
