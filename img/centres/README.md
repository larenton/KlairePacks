# Centre logos

The centres we supply — the services receiving packs, not supporters.
Supporter logos live in `img/supporters/` and are a separate list.

Drop a centre's logo here, then add the centre to the `CENTRES` array at
the foot of `impact.html`:

    { name: 'Jarrah House', logo: 'img/centres/jarrah-house.png' }

Optional fields: `note` (a line under the name, e.g. "Malabar, Sydney")
and `url` (makes the card link to the centre's own site).

The cards sit beside the heading rather than under it, to keep the page
short, and the row re-flows on its own as centres are added: one or two
sit large side by side, three or more pack tighter so the row still fits
the column instead of stacking. Nothing needs re-laying-out.

File format: same guidance as `img/supporters/README.md` — SVG if they
have one, otherwise PNG with a transparent background, around 600-900px
on the long edge. If a logo only comes as a JPEG on white, knock the
white out to transparent first, or it shows as a white box against the
cream tile.

If a file named in `impact.html` isn't here yet, the card falls back to
the centre's name — nothing breaks.
