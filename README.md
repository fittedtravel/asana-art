# asana.art

Coming-soon page for **asana.art** — a creative home for yoga, nutrition & holistic living.

## What's on the page

Two text elements over an ambient sunrise bloom:

1. **`asana.art`** — the wordmark, Lora 300, tracked tight.
2. **`asana.art/@you`** — a handwritten teaser (Caveat 500), hinting that personal profile URLs are coming. Decorative copy, not a real link.

That's it. No nav, no links, no forms, no tagline, no "coming soon" text.

## Files

- `index.html`
- `styles.css` — palette, type, motion (sunrise bloom drift + wordmark breath)
- `favicon.svg` — lowercase `a` in Lora 300 on canvas
- `CNAME` — `asana.art` for the GitHub Pages custom domain

Pure static. No build step, no JS framework. Fonts loaded from Google Fonts (Lora + Caveat).

## Deploy (GitHub Pages)

1. Push to a repo with Pages enabled.
2. **Settings → Pages**, set Source to the deployed branch.
3. The included `CNAME` points the custom domain at `asana.art`.
4. In your DNS provider, point `asana.art` to GitHub Pages:
   - Apex `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` for `www` → `<github-user>.github.io`
5. Enable **Enforce HTTPS** once the cert provisions.

## To-do before launch

- Generate `og.png` (1200×630) — screenshot the wordmark + bloom on canvas, no teaser. The `og:image` meta tag already points to `https://asana.art/og.png`.

## Notes

- All motion respects `prefers-reduced-motion`.
- One screen, no scrolling, no forms, no tracking.
