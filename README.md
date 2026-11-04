# Serie A • Historical Points Explorer

How unusual is this table? Compare Serie A points `P` at position `n` after each club's first `M` completed matches, across all seasons using 3 points for a win.

## Live site

This repository is configured as a GitHub Pages site. Push the default branch to your repo, then enable Pages (Settings → Pages → deploy from branch → `main` / root).

## What's inside

- `index.html` — a single self-contained HTML file (CSS + embedded dataset + app logic). No build step needed; host it as-is on static hosting.
- Embedded dataset: 2025–26 and earlier seasons plus a current-season snapshot.

## Data provenance

Historical seasons (to 2025–26): [engsoccerdata](https://github.com/jalapic/engsoccerdata) (James P. Curley; non-commercial), with 2025–26 from [Openfootball](https://github.com/openfootball/italy). Current season (2026–27): [Open Matchday contributors](https://github.com/oladeeayo/open-matchday), fetched on load and hourly (jsDelivr fallback); third-party results, not an official feed.

## Editing guide

See the comments at the top of `index.html`:
1. Appearance — edit the CSS block.
2. Visible descriptions and labels — edit the HTML below.
3. Embedded dataset — leave unchanged when editing descriptions.
4. App logic — generated wording lives in `textContent` assignments.

Keep element IDs unchanged. The file remains a single standalone HTML page suitable for static hosting.
