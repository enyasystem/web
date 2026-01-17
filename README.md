# Website Sections — Local Preview

This repository contains a small static demo of website sections (header, hero, about, services, etc.).

What's included

- `index.html` — single-file demo with styles and scripts.
- `assets/hero-landscape.svg` — extracted hero background (lazy-loaded).

Quick preview (Python)

1. Open a terminal in the project root (where `index.html` lives).
2. Run a simple static server:

```bash
# Python 3
python -m http.server 8000
```

3. Open your browser to http://localhost:8000

Notes

- The hero background is an SVG at `assets/hero-landscape.svg`. Social preview cards use this image; for production, consider replacing with a raster `png`/`jpg` fallback for broader social network compatibility.
- Meta tags (Open Graph / Twitter) were added to `index.html` for better sharing previews.
- For development, edit `index.html` directly and refresh the browser to see changes.

Want me to:
- Generate a PNG fallback for social cards and wire a `picture`/`og:image` update?
- Run an accessibility audit and fix issues?
