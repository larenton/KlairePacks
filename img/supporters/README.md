# Supporter logos

Drop supporter logo files in this folder, then point the matching entry in
the `SUPPORTERS` array at the foot of `supporters.html` at the file:

    { name: 'Claypool', logo: 'img/supporters/claypool.svg', ... }

What works best:

- **SVG** if the supporter has one — it stays sharp at any size.
- Otherwise **PNG with a transparent background**, at least 600px on the
  long edge (the tiles render up to 130px tall, so 600px covers retina).
- Any orientation — wide, tall or square. The tile contains the logo
  without cropping or stretching it.
- A dark or single-colour version reads best on the cream `#FBF8F1` tile.

What to avoid: JPEGs (the white box shows as a rectangle on the tile),
screenshots of a logo, and favicon-sized files.

Name files in lowercase with hyphens, e.g. `sweet-william-chocolate.png`.

If a file named in `supporters.html` isn't here yet, the card falls back
to the supporter's name as a wordmark — nothing breaks.
