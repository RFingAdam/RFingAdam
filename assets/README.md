# README SVG kit

Self-hosted artwork for [RFingAdam](https://github.com/RFingAdam) profile and project READMEs.

The motif is a Smith chart plus a VNA-style sweep trace, in an iron-and-copper palette. Files are static SVG in this folder — no third-party render services, no runtime badge URLs.

These drawings are decorative. They are not measurements.

## Files

| File | Use |
|---|---|
| `header-profile-dark.svg` / `header-profile-light.svg` | Profile README banner. Pair them with a `<picture>` element so GitHub can follow the reader’s color scheme. |
| `header-project-dark.svg` / `header-project-light.svg` | Reusable project-README banner. Edit the `PROJECT` and `TAGLINE` text nodes. |
| `divider.svg` | Section rule. Transparent background; mid-tone copper on both GitHub themes. |
| `icon-mark.svg` | Kit emblem. |
| `icon-smith.svg`, `icon-wave.svg`, `icon-antenna.svg`, `icon-mcp.svg` | Small section icons. Transparent background. |

## Project header

1. Copy `header-project-dark.svg` and `header-project-light.svg` into the project repo’s `assets/` folder.
2. Change the two text elements with `id="PROJECT"` and `id="TAGLINE"`. Keep the palette and the Smith / sweep motif.
3. Wire them at the top of the project README the same way as the profile header (`<picture>` + `alt`).

## Palette

- Iron background (dark): `#14110E` / panel `#1C1914`
- Paper background (light): `#F3EEE6` / panel `#EBE4D8`
- Copper: `#C67A3A` (dark accent `#E09A55`, light accent `#9A5624`)
- Amber locus (dark): `#E8B84A`
- Marker: `#D94B2B` (light `#C43A22`)
- Steel labels: `#8F877C` (light `#5E574C`)

## Accessibility

Every SVG has `role="img"`, a `<title>`, and a `<desc>`. When you embed one, keep a short `alt` on the `<img>` (or an empty `alt` on the purely decorative divider).
