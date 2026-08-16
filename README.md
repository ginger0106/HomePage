# Jingyan Jiang — Academic Homepage

A bilingual, responsive academic homepage for Jingyan Jiang, built as a dependency-free static site for GitHub Pages.

## Pages

- `/` — English homepage
- `/zh/` — 中文主页
- `/publications/` — complete English publication archive
- `/zh/publications/` — 中文论文档案

## Local preview

Run any static web server from this directory, for example:

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## GitHub Pages

In the repository settings, choose **Pages → Deploy from a branch**, then publish the repository root from the default branch. The `.nojekyll` file keeps the static structure unchanged.

Publication records live in `assets/js/publications.js`; update that single file to keep both language versions synchronized.
