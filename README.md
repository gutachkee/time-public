# time — website

Public marketing and legal pages for **time**, a local-only focus timer for iPhone and iPad.

Served with GitHub Pages from the `main` branch, `/` (root).

| Page | Path | URL once Pages is enabled |
|---|---|---|
| Landing | `index.html` | `/` |
| Privacy Policy | `privacy/index.html` | `/privacy` |
| Terms of Use | `terms/index.html` | `/terms` |

Static HTML with one shared stylesheet (`assets/site.css`). No build step — edit and push.

## Screenshots

`assets/shots/*.webp` are real screenshots of the app, captured on an **iPhone 17 Pro simulator**
(iOS 26.5) from a `Debug` build seeded with a sample day of focus data, then resized to 720px wide
and encoded with `cwebp -q 84`. The status bar is pinned to 9:41 with `simctl status_bar override`.

| File | Screen |
|---|---|
| `home-light` / `home-harbor` / `home-dark` | Home — Blush Day, Harbor Day, Lagoon Night |
| `home-stats` | Today's stats + the weekly card |
| `home-break` | Home with the break nudge |
| `weekly` | Weekly history |
| `items` | Focus items editor |
| `settings` / `settings-dark` | Settings (Pro + Appearance) |
| `setup` / `welcome` | Onboarding and the welcome flow |
| `paywall` | The Pro sheet |

The Lock Screen, Dynamic Island and Home Screen widget cards in the "Outside the app" section are
CSS illustrations, not screenshots — those surfaces can't be captured from the command line.

Colors, type and the arc-timer mark mirror the app's own design tokens
(`TrackerCore/Sources/TrackerCore/PaletteTokens.swift`, Blush palette).

`Privacy Policy.md` and `Terms of Use.md` are the original text drafts the HTML pages were built from.
