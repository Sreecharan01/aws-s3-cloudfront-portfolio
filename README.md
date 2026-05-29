# aws-s3-cloudfront-portfolio

A minimal static landing page built with plain HTML and CSS.

## Overview

This repository contains a simple single-page site with a responsive layout and a modern glassy aesthetic. It's designed as a small personal or portfolio landing page.

## Files

- `index.html` — the page markup.
- `style.css` — all styles, including CSS variables for easy theming.

## Quick start

1. Open `index.html` in your browser (double-click the file).
2. Or serve the folder locally for a better development experience:

```bash
# Python 3
python -m http.server 8000

# or with Node (http-server)
npx http-server .
```

Then visit `http://localhost:8000`.

## Development

- Edit `index.html` to update content.
- Edit `style.css` to change layout, colors, and spacing.
- Theme variables live in the `:root` selector at the top of `style.css` — change `--accent`, `--bg`, etc.
- Toggle the alternate accent palette by adding/removing the `accent-on` class on the `body` element.

## Customization

- Fonts: the stylesheet references `Aptos` with sensible fallbacks — update the font stack if needed.
- Colors and spacing are controlled with CSS variables for easy tweaks.

## License

Add a license file if you want to publish this project publicly.

---

If you'd like, I can:

- add a `LICENSE` file (MIT recommended),
- create a small CI or preview script, or
- scaffold an optimized production build pipeline.

Tell me what you'd like next.
