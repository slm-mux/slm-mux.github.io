# SLM-MUX Project Page

This repository hosts a minimal static website for the SLM-MUX paper/code release, inspired by the `nerfies.github.io` template.

## Quick start

- Put your paper PDF at `ICLR_SLM_MUX.pdf` (already present).
- Open `index.html` and update:
  - Title, authors, affiliations
  - GitHub code link
  - Abstract text
  - Replace placeholder images in `assets/img/` when ready (logo, teaser, favicon)

## Local preview

Use any static web server. Examples:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
# then open http://127.0.0.1:8000
```

or with Node:

```bash
npx serve --listen 8000 .
```

## Deploy (GitHub Pages)

1. Push this repo to GitHub as `slm-mux.github.io` or enable Pages on the `main` branch.
2. Pages will serve the site at `https://slm-mux.github.io/`.

## Customize

- Favicon: `assets/img/favicon.svg`
- Logo: `assets/img/logo.svg`
- Teaser image: `assets/img/teaser.svg` (also referenced in Open Graph tags as `.jpg` — swap when you have a raster image)
- Colors and layout: `assets/css/styles.css`
- Lightweight behavior (smooth scroll, BibTeX copy): `assets/js/main.js`

## Cite

Edit `bibtex.bib` and the page will load it automatically into the BibTeX section.


