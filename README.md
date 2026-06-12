# 3 NOMADS X

Global experiential platform at the intersection of music, hospitality, travel, culture and community.

Single-page marketing site — pure HTML/CSS/JS, no build step.

## Structure

```
index.html          # entire site (markup, styles, scripts inlined)
assets/image/       # logos, event covers, hero artwork
```

## Sections

- **Hero** + animated marquee
- **Manifesto**
- **Ecosystem** — experience IPs
- **Brands** — logo marquee
- **Upcoming events** — Adam Port, Boho Sunday
- **3NOMADS in numbers**
- **Experience calendar** — 2026–2027 agenda with an animated scroll route
- **Artists** — 3D scroll parallax
- **Past events** — right-to-left auto-scrolling carousel
- **Newsletter** + footer

## Run locally

It is a static page — just open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). For GitHub Pages, enable Pages on the default branch with the root folder.
