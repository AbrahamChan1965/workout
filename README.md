# 聖言健身歌 — workout.wordnspirit.com

Workout music website: lectionary songs for gentle exercise (elderly, children, anyone).
Live: https://workout.wordnspirit.com (backup: https://workout-music.pages.dev)

- Cloudflare Pages project: `workout-music` (**Git-connected to this repo**, production branch `main`, no build step — static files at repo root)
- Deploy: push to `main` → Cloudflare auto-deploys from GitHub. Direct upload is NOT used for this site.
- The old Direct Uploads project `workout` (workout-a1p.pages.dev) was retired and deleted 2026-11-04 on Abe's order — GitHub is now the only deploy route.
- Videos: Cloudflare R2 bucket `wordnspirit-media`, keys `workout/<slug>/video-1080p.mp4`, served at media.wordnspirit.com.
- Session order and song tables: see the working notes in the agent workspace (not in this repo).

---

四站共用契約：見 [UNIVERSE.md](./UNIVERSE.md)（WNS Universe：devotions、sermon、music、workout 四站共用的聯動契約；改共用的東西先改那份文件）。
