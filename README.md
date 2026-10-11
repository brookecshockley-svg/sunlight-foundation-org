# Sunlight Foundation static site

Static GitHub Pages copy of the previous Lovable-hosted site for `sunlight-foundation.org`.

This repo vendors the built static assets so the website no longer depends on Lovable hosting or a Lovable subscription.

## Files

- `index.html` — clean GitHub Pages entrypoint with Sunlight metadata and no Lovable badge
- `assets/` — downloaded JS, CSS, and image assets from the existing site
- `CNAME` — custom domain for GitHub Pages
- `.nojekyll` — disables Jekyll processing

## DNS target

For IONOS, point the domain to GitHub Pages:

- Apex/root A records:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `www` CNAME: `brookecshockley-svg.github.io`

Keep IONOS mail/MX records intact.
