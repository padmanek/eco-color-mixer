# Eco Powder Color Matcher

Static single-page app intended for GitHub Pages hosting.

## What it does

- Accepts a target hex color or a mouse-driven color wheel picker.
- Searches combinations of Eco's 8 paint colorants up to a user-selected total powder limit.
- Lets users choose max total powders per recipe (default 8), capped to the in-game mixing limit (100).
- Returns top approximate mixes sorted by RGB distance.

## Local run

```bash
python3 -m http.server 4173 --directory docs
```

Then open: <http://localhost:4173/powder-color-mixer/>
