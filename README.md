# w0nderful666.github.io

Minimal terminal-style personal homepage for **w0nderful666**. English, dark by default, with a light/dark toggle that remembers your choice. No build step, no external APIs, no external fonts — one `index.html` holds everything.

## Content

Three hand-picked projects, summarized from their public READMEs (snapshot 2026-09-27):

- [AeMusic](https://github.com/w0nderful666/AeMusic) — Android music player (Jetpack Compose / Media3)
- [WF-1000XM5 Spatial Audio](https://github.com/w0nderful666/wf1000xm5-spatial-audio-android) — head-tracked audio experiment on Android
- [FxxKPDF](https://github.com/w0nderful666/FxxKPDF) — local-first PDF toolkit in the browser ([live demo](https://w0nderful666.github.io/FxxKPDF/))

Projects are curated manually — nothing auto-syncs from GitHub.

## Preview

Open `index.html` directly in a browser, or run the local preview server:

```bash
python3 preview_server.py
```

Serves `/` and `/index.html` on port 8080. The preview server is a local tool only; it is not part of the deployed site.

## Deploy

Published with GitHub Pages via the `Deploy personal homepage` Actions workflow. Pushing to `main` triggers a deploy automatically; only `index.html` is packaged into the site artifact.

To add a project later, edit the `#projects` section in `index.html` (copy an `<article class="project">` block), then push.
