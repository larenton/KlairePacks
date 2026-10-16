# Centre logos

The centres we supply — the services receiving packs, not supporters.
Supporter logos live in `img/supporters/` and are a separate list.

Drop a centre's logo here, then add the centre to the `CENTRES` array at
the foot of `impact.html`:

    { name: 'Jarrah House', logo: 'img/centres/jarrah-house.png' }

Optional fields: `note` (a line under the name, e.g. "Malabar, Sydney")
and `url` (makes the card link to the centre's own site).

The row is sized to hold all five centres and stays centred at any
count, so nothing needs re-laying-out as centres two to five arrive.

File format: same guidance as `img/supporters/README.md` — SVG if they
have one, otherwise PNG with a transparent background, around 600-900px
on the long edge. If a logo only comes as a JPEG on white, knock the
white out to transparent first, or it shows as a white box against the
cream tile.

If a file named in `impact.html` isn't here yet, the card falls back to
the centre's name — nothing breaks.
