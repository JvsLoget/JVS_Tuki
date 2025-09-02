# JVS Tuki – Static Site (Video Edition)

One-page site with customer survey and video section.

## Add video (two options)
### A) Self-hosted MP4
1) Name your file **video.mp4**.
2) Put it next to `index.html` (repo root).
3) Commit & push — the `<video>` player will show it.

### B) YouTube embed
1) Replace `VIDEO_ID` in the iframe URL, e.g. `https://www.youtube.com/embed/VIDEO_ID`.
2) Commit & push.

> Tip: For GitHub Pages keep video files small (<50–100 MB) so it loads fast.

## Deploy on GitHub Pages
1) Create a public repo (e.g., `jvs-site`).
2) Upload `index.html` and `logo.png` (and optionally `video.mp4`).
3) Settings → Pages → Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)`.
4) Open the published URL.

Email in footer: jvstuki@outlook.com.
