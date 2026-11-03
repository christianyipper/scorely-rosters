# scorely-rosters

Daily JPHL roster and player-stat data for [Scorely](https://github.com/christianyipper).

A GitHub Action (`.github/workflows/update-rosters.yml`) runs `scrape.mjs` every day at 09:00 UTC and commits `rosters.json` when the rosters or stats have changed. The app downloads it from:

https://raw.githubusercontent.com/christianyipper/scorely-rosters/main/rosters.json

Run it locally with `npm ci && npx playwright install chromium && npm run scrape`.
