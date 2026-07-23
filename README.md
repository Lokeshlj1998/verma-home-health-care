# Verma Home Health Care Services — Website

A modern, responsive, multi-page website for **Verma Home Health Care Services**, built with plain HTML, CSS, and JavaScript. Content is bilingual (English + Hindi) and mirrors the branding, services and care tips from the company flyer.

Serving: **Indore · Bhopal · Jabalpur · Gwalior**
Contact: **Mr. Akhilesh Verma — +91 93292 15182, +91 89659 77473**

## Pages

- `index.html` — Home (hero, highlighted services, featured tips, CTA)
- `services.html` — Full list of services + how it works
- `tips.html` — 7 important care tips for bed patients (from the flyer)
- `about.html` — Who we are, mission, values, stats
- `contact.html` — Contact details, service cities, callback form

## Project Structure

```
verma-home-health-care/
├── index.html
├── services.html
├── tips.html
├── about.html
├── contact.html
├── css/
│   └── style.css       # Shared styles, responsive design, brand palette
├── js/
│   └── script.js       # Mobile nav toggle, form UX, footer year
└── README.md
```

## How to Run

No build step required — it's plain HTML/CSS/JS.

**Option 1 — Just open the file**

```bash
xdg-open index.html   # Linux
open index.html       # macOS
start index.html      # Windows
```

**Option 2 — Serve locally (recommended)**

Using Python (already on most systems):

```bash
cd verma-home-health-care
python3 -m http.server 8080
```

Then open http://localhost:8080 in your browser.

Or using Node's `serve`:

```bash
npx serve .
```

## Customising

- **Colors / branding** — edit CSS variables in `css/style.css` (`:root { ... }`)
- **Phone numbers / cities** — search and replace in the HTML files
- **Add a real logo** — replace the `.brand-logo` `V` block with an `<img>` tag
- **Contact form** — currently client-side only; connect the `<form>` in `contact.html` to a backend (e.g. Formspree, Netlify Forms, or your own server)

## Deploy

The site is static, so it can be hosted on any static host for free:

- **Netlify** — drag the folder into netlify.com/drop
- **Vercel** — `vercel` in the folder
- **GitHub Pages** — push to a repo and enable Pages
- **Cloudflare Pages** — connect the repo

## License

© Verma Home Health Care Services. All content and branding belong to the business.
