# Storage Corner app assets

Public brand assets (icons) used by Storage Corner's internal Google Apps Script web apps. Apps Script
can only show a favicon from a public image URL, so they're hosted here.

| Path | Used by |
|---|---|
| `dd-checklist/favicon-64.png` (+ 32, 180, svg) | Due Diligence Checklist app (`favicon_url` setting) |
| `ca-database/favicon-64.png` (+ 32, 180, svg) | CA Database UI app: roll-up storage door |
| `ca-database/favicon-search-64.png` (+ 32, 180, svg) | CA Database UI app: the same door with a magnifying glass (alternative) |
| `microfiche-pipeline/favicon-64.png` (+ 32, 180, svg) | Microfiche Pipeline app (`FAVICON_URL` in `src/Config.js`) |
| `ssd-dashboard/favicon-64.png` (+ 32, 180, svg) | Same-Store Sales Dashboard app: rising bars on purple (`favicon_url` setting) |

Nothing in this repo is confidential. The source of truth for these files is each app's own repo
(e.g. `src/client/brand/` in the Due Diligence Checklist, CA Database UI and Same-Store Sales Dashboard apps, `assets/` in the Microfiche Pipeline).
