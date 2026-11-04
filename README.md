# www

Static files for Sajjad Industries, served by GitHub Pages at
`https://assets.sajjadindustries.com/` (custom domain, see `CNAME`). It will later move to
Cloudflare Pages with the same URLs.

Everything under `brand/`, and the favicon set in the root, is **copied from the company
repository's `brand/exports`** (built there by `brand/scripts/`). Never edit those files here:
change the source in the company repository, rebuild, and copy the exports over.

| Path | Source in the company repo |
|---|---|
| `brand/email-header.png` | `brand/exports/email/header-on-black-1200.png` |
| `brand/mark-96.png` | `brand/exports/email/mark-on-white-96.png` |
| `favicon.ico`, `favicon.svg`, `favicon-16.png`, `favicon-32.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `site.webmanifest` | `brand/exports/favicon/` |

`index.html` is a placeholder (black page, horizontal lockup, legal line) until the website exists.
