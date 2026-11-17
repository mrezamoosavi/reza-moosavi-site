# reza-moosavi-site

Personal website of Reza Moosavi, AI and data science leader in financial services.

## What's here

| File | Purpose |
|---|---|
| `index.html` | The whole site: a single static page, no build step |
| `photo.jpg` | Hero photo (800×800, optimized) |
| `netlify.toml` | Netlify deploy settings and security headers |

## How it's built and updated

- Content and design are edited in a Claude design canvas, which is the source of truth.
- `index.html` is generated from that canvas, then committed here.
- Netlify watches the `main` branch, so every push goes live within about a minute.

## Content rules

The site is public, so it never shows:

- dollar figures or per-project metrics (value is described as "8-figure")
- team headcount
- internal tool, team or vendor names, or vendor decisions

## Run locally

Open `index.html` in a browser. No server or dependencies are needed.
