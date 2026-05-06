# asana.art

Static placeholder page for the `asana.art` domain. Hosted on GitHub Pages.

## Files

- `index.html`
- `styles.css`
- `favicon.svg`
- `CNAME` — custom domain for GitHub Pages

Pure static. No build step, no JS framework. Fonts loaded from Google Fonts.

## Deploy (GitHub Pages)

1. Push to a repo with Pages enabled.
2. **Settings → Pages**, set Source to the deployed branch.
3. The included `CNAME` handles the custom domain.
4. In your DNS provider, point the domain to GitHub Pages:
   - Apex `A` records → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` for `www` → `<github-user>.github.io`
5. Enable **Enforce HTTPS** once the cert provisions.

## To-do

- Generate `og.png` (1200×630) for social previews. The `og:image` meta tag already references `/og.png`.

## Notes

- One screen, no scrolling, no forms, no tracking.
- All motion respects `prefers-reduced-motion`.
