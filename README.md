# Kinly data

The public archive of [Project Kinly](https://github.com/angellog/kinly), built by Vantik Systems. It holds:

- the daily and weekly reports;
- the 18-month landscape report;
- one resource page per tested repository;
- the trending snapshots needed to rebuild the Kinly database from scratch.

| Path | What |
|---|---|
| `reports/daily/YYYY-MM-DD.md` | The daily brief: top 10, five picks, repeat trenders, new entrants, picks by category |
| `reports/weekly/YYYY-Www.md` | The weekly report: top 15, top 5 per category, rising, persistence, five to test this week |
| `reports/landscape-*.md` | The 18-month landscape |
| `resources/<owner>--<repo>.md` | Resource pages for tested repositories |
| `data/snapshots/<source>/<YYYY-MM>/<date>.json` | Every trending list as observed |
| `data/repos/<shard>.json` | Repository metadata, category and Kinly's own summary. README text is never published |
| `data/user/` | The owner's profile, shortlist and ratings |
| `data/manifest.json` | What a fresh Kinly server downloads on first boot |

From 2026-10-08, the Kinly service on Railway writes this repository, one commit per run. Before that date the history was backfilled from the larsbijl trending archive; see `data/snapshots/larsbijl-archive/LICENSE`.

## Licence

[MIT](LICENSE) © Vantik Systems for Kinly-authored content: reports, summaries, scores and resource pages. Repository names and descriptions are quoted from their owners for identification and remain under their owners' terms. The larsbijl archive snapshots are © Lars van der Bijl, under MIT (`data/snapshots/larsbijl-archive/LICENSE`).
