# Alibaba Cloud CDN Homework — GitHub Pages Origin

This repository is the **origin** website for an Alibaba Cloud CDN homework.

- Origin (GitHub Pages): `https://YOUR-USERNAME.github.io`
- Accelerated CDN hostname: `https://cdn.YOUR-DOMAIN`

Files:

| Path | Purpose | CDN cache TTL |
|---|---|---|
| `index.html` | Main page (shows Version + verification token) | 10 minutes |
| `css/style.css` | Styles | 1 day |
| `js/app.js` | Loads `api/news.json` | 1 day |
| `images/logo.png` | Logo image | 7 days |
| `api/news.json` | Frequently updated data | 1 minute / no-cache |
| `downloads/guide.pdf` | Downloadable guide | 3 days |
