# barthcap.io

The Barth Capital site. Plain HTML, CSS and JS. No build step, no framework.

## What's here

    wrangler.jsonc          Cloudflare config. Publishes ./public only
    public/index.html       the entire one-page site, CSS inlined
    public/img/             logos (SVG where the brand supplied one), case study and content thumbnails, headshot
    public/og.png           social share image, 1200x630
    public/favicon.png      browser tab icon

## How it goes live

Cloudflare Workers Builds watches this repo. Push to `main` and it deploys.
Push any other branch and Cloudflare gives you a preview URL instead.
Do not drag files into the Cloudflare dashboard.

## House rules for this site

- Barth Capital engagements are Aartoo, Fuzzland and Redefine only.
- CertiK and BitGo were full-time roles. They live in the founder background
  section and never appear in a client grid or next to engagement work.
- Case study figures are client results from case studies Aaron wrote. Label them that way.
- No em dashes or en dashes anywhere in the copy.
- No invented dates, metrics or outcomes.
- Barth Reach is a Barth Capital practice. It gets its own "Also from Barth Capital" block, never a spot among the engagements.

## Brand

Dark only. Near-black #09090b, electric blue accent #5b9dff.
Geist for text, Geist Mono for labels. Barth the dog, inverted to off-white.
