# barthcap.io

The Barth Capital site. Plain HTML, CSS and JS. No build step, no framework.

## What's here

    wrangler.jsonc          Cloudflare config. Publishes ./public only
    public/index.html       the entire one-page site, CSS inlined
    public/img/             logos (SVG where the brand supplied one), case study and content thumbnails, headshot
    public/og.png           social share image, 1200x630
    public/favicon.png      browser tab icon

## How it goes live

GitHub Pages serves the site from the `gh-pages` branch, which holds only
the contents of ./public. After committing to `main`, publish with:

    git push origin main && git subtree push --prefix public origin gh-pages

Pages rebuilds within a minute or two.

DNS stays at Squarespace (Google Workspace domain). The website uses only
four A records on `@` and a `www` CNAME to barthelemypb.github.io. Never
touch the MX, SPF or DKIM records: they carry aaron@barthcap.io email.

`public/CNAME` tells GitHub Pages the custom domain. Do not delete it.
`wrangler.jsonc` is left from a Cloudflare Workers test deploy and is unused.

## House rules for this site

- Barth Capital engagements are Aartoo, Fuzzland and Redefine only.
- CertiK, BitGo, Novo Protocol and BEN are Aaron's experience. They live in the Experience
  section and never appear in a client grid or next to engagement work.
- Case study figures are client results from case studies Aaron wrote. Label them that way.
- No em dashes or en dashes anywhere in the copy.
- No dates on engagements, roles or content tiles (Aaron's call). No invented metrics or outcomes.
- Every tile and logo links to its source.
- Barth Reach is a Barth Capital practice. It gets its own "Also from Barth Capital" block, never a spot among the engagements.

## Brand

Dark only. Near-black #09090b, electric blue accent #5b9dff.
Geist for text, Geist Mono for labels. Barth the dog, inverted to off-white.
