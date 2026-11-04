# 聖言健身歌 — workout.wordnspirit.com

Workout music website: lectionary songs for gentle exercise (elderly, children, anyone).
Live: https://workout.wordnspirit.com (backup: https://workout-a1p.pages.dev)

- Cloudflare Pages project: `workout` (production branch `main`, no build step — static files at repo root)
- Deploy: push to `main` → Cloudflare auto-deploys. Direct upload via cf.py is the emergency fallback only.
- Videos: Cloudflare R2 bucket `wordnspirit-media`, keys `workout/<slug>/video-1080p.mp4`, served at media.wordnspirit.com.
- Session order and song tables: see the working notes in the agent workspace (not in this repo).
