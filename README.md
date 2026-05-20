# Backed

Static marketing site for **Backed** — risk-free, retainer-and-commission marketing infrastructure for brands and creators.

## Pages
- `index.html` — landing page (the engine, live campaigns, sign-up bonus, FAQ, CTA)
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `financials.html` — interactive Backed Financials model (password-gated, client-side)

## Hosting
Built as a static site. Served via GitHub Pages from the `main` branch root.

Custom domain is configured via:
- 4 A records on the apex pointing to GitHub Pages' IPs
- 1 CNAME on `www` pointing to `<username>.github.io`

## Stack
- Plain HTML
- Tailwind CSS via CDN
- Vanilla JS for interactivity (engine calculator, marketplace tabs, signup / sign-in / contact modals, financials portfolio, chart)
- No build step required
