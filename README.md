# EYAL KLAF & TFILIN LTD — website

Marketing site for EYAL KLAF & TFILIN LTD, a mobile game development and publishing company.

A single self-contained `index.html`: no build step and no dependencies beyond the Google Font it links.

## Sections

Hero · About · Services · Process · Contact

## Features

- Responsive down to phone width (CSS grid with `auto-fit`)
- Dark / light theme toggle, defaults to the system preference and remembers the choice
- Scroll-reveal animations that respect `prefers-reduced-motion`
- All colors defined as CSS custom properties on `:root`, so rebranding is a few lines

## Before going live

Replace the `your@email.com` placeholder in the contact section (it appears in the mail button and in the contact details).

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```
