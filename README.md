# HullPatch — Website

Promo site for [HullPatch](https://github.com/hibikipr/hullpatch), served by GitHub Pages at
[hullpatch.townsville.cc](https://hullpatch.townsville.cc) (custom domain on the
`townsville.cc` Cloudflare zone).

- `index.html` — landing page
- `styles.css` — shared tokens and base type (townsville.cc theme)
- `assets/` — icons copied from the app repo's `public/`
- `CNAME` — pins the custom domain; don't delete unless you mean to detach it

Plain static HTML/CSS, no build step. Deploys automatically on push to `main`.

## If the HTTPS certificate ever gets stuck

Remove the `CNAME` file, let Pages rebuild, then add it back to re-trigger certificate issuance.

## Related repos

- [hullpatch](https://github.com/hibikipr/hullpatch) — the app itself
