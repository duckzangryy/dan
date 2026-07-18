# duckzangryy.github.io

Interactive mini-site **“Linh Đan”** — a playful, pink-themed question flow with photos and music. Hosted on GitHub Pages.

**Live:** [https://duckzangryy.github.io](https://duckzangryy.github.io)

## What it is

A single-page experience (`index.html`) that:

- Opens with a soft pink UI and custom heart favicon
- Guides the visitor through a short yes/no interaction
- Reveals photo / audio moments
- Shares well on social (Open Graph tags for Facebook)

Built as a personal / gifting page, not a full portfolio.

## Stack

- Static HTML + CSS + JS (no framework)
- Google Fonts (Dancing Script, Quicksand)
- Media assets: `1.jpg` … `5.jpg`, `1.mp3`

## Run locally

```bash
git clone https://github.com/duckzangryy/duckzangryy.github.io.git
cd duckzangryy.github.io
npx serve .
```

## Deploy

Repo is configured for **GitHub Pages** from the `main` branch root.

1. Push changes to `main`
2. Settings → Pages → Source: Deploy from branch `main` / `/ (root)`
3. Site updates at `https://duckzangryy.github.io`

## Customize

| Item | File |
|------|------|
| Title / OG share text | `index.html` meta tags |
| Colors | CSS variables in `<style>` (`--pink-*`) |
| Photos / audio | root image & mp3 files |
| Copy / flow | script + markup in `index.html` |

## Privacy

This page is public. Do not commit private photos or messages you are not OK sharing.

## Author

[duckzangryy](https://github.com/duckzangryy) · Vương Việt Anh
