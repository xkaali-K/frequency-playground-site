# Frequency Playground — Landing Page

A single‑file, static landing page you can deploy in minutes. Use this as the **Business URL** for marketplaces (Flippa, etc.).

## Quick Deploy Options

### GitHub Pages (free)
1) Create a new public repo, e.g., `frequency-playground-site`.
2) Upload `index.html` to the repo root.
3) In repo settings → Pages → **Deploy from branch**, select `main` and `/ (root)`.
4) Your site will be live at `https://<your-username>.github.io/frequency-playground-site`.

### Netlify (free)
1) Go to https://app.netlify.com/drop
2) Drag & drop this folder — Netlify gives you a live URL like `https://<random>.netlify.app`.

### Cloudflare Pages (free)
1) Create a new project and connect the repo or upload the folder.
2) Build output: just the static `index.html` (no build step required).

## Customizing
- Open `index.html` and change:
  - Contact email/Flippa URL in the “Interested?” section
  - Any copy blocks, pricing, or features
  - Add screenshots by replacing the `.shot` divs with `<img>` tags

## Notes
- This is intentionally **no‑framework** and **single‑file** for maximum compatibility with GitHub Pages & Netlify.
