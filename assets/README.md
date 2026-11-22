# README SVG kit

Self-hosted artwork for the [RFingAdam](https://github.com/RFingAdam) profile README, and a reusable project-header template.

The brand anchor is the official [rfpro.dev](https://rfpro.dev) Smith-chart mark (a two-step L-match into 50 Ω) and that site’s palette: navy `#0f172a`, teal `#2dd4bf`, copper `#c17f59`. Files are static SVG in this folder — no third-party render services.

## Files

| File | Use |
|---|---|
| `logo.svg` | Official mark, transparent background. |
| `logo-badge.svg` | Official mark on a navy disc (favicon-style). |
| `header-profile-dark.svg` / `header-profile-light.svg` | Profile banner. Pair with a `<picture>` element. |
| `header-project-dark.svg` / `header-project-light.svg` | Reusable project-README banner. Edit the `PROJECT` and `TAGLINE` text nodes. |
| `card-*.svg` | Profile project cards. Same size, one literal icon each. |

## Project header

1. Copy the `header-project-*.svg` pair into the project repo’s `assets/` folder.
2. Change the text elements with `id="PROJECT"` and `id="TAGLINE"`.
3. Optionally swap the logo for that project’s own mark, keeping the typography and navy/teal/copper palette.
4. Wire them at the top of the project README with a `<picture>` element and short `alt` text.

## Accessibility

Every SVG has `role="img"`, a `<title>`, and a `<desc>`. Keep a short `alt` on the `<img>` when you embed one.
