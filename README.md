# Klaire Packs website

Static site. No build step — open `index.html` or serve the folder.

## Pages

| File | Page |
| --- | --- |
| index.html | Home |
| packs.html | The packs |
| for-centres.html | For centres |
| screening-rules.html | Screening rules |
| order.html | Order packs (centres) |
| impact.html | Impact |
| donate.html | Donate |
| sponsor.html | Sponsor a pack |
| transparency.html | Transparency |
| thank-you.html | Thank you |

Every page is plain, self-contained HTML — no runtime, no build step. Edit any file directly and refresh. All pages are mobile responsive (hamburger nav, stacked layout, collapsed embeds) via the shared `mobile.css`.

## Other files

- `mobile.css` — responsive rules shared by every page. Must sit next to the HTML files.
- `img/` — pack photography and favicon.

## Deploying to GitHub Pages

Push these files to the repository root (or a `docs/` folder) and enable Pages on that branch. `index.html` is served at the site root.

## Third-party embeds

- Donation and sponsorship forms are Zeffy embeds; they load from zeffy.com and need a live domain to render.
- The Transparency page embeds a Google Sheet, which must be shared as "Anyone with the link — Viewer".
