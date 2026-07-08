# HQ Signals — Public Track Record

Static site auto-published hourly from the HQ Signals paper trading database.
`stats.json`, `leaderboard.json`, and `signals.json` are regenerated and pushed
by `hq-phase8/src/publish/publishStatic.js` (runs under the `hq-public-publisher`
pm2 process). Do not hand-edit the JSON files — they get overwritten on the next
publish cycle.
