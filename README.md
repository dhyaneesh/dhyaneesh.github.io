# Dhyaneesh DS — personal site & writing

Static site for [dhyaneesh.github.io](https://dhyaneesh.github.io): a home page plus long-form **field reports** on AI systems, agents, and related tooling.

## What’s here

- **`index.html`** — Landing page (bio, latest report, archive of older pieces, links).
- **`openclaw-article.html`**, **`ao-symphony.html`** — Standalone articles (shared typography, light/dark theme, responsive layout).
- **`favicon.ico`** — Site icon.

No build step: plain HTML, CSS, and a little JavaScript for theme toggling and scroll reveals.

## Local preview

Open `index.html` in a browser, or from the repo root:

```bash
npx --yes serve .
```

Then visit the URL the CLI prints (often `http://localhost:3000`).

## Publishing

Hosted with **GitHub Pages** from this repository. Push to the default branch; GitHub serves the site from the root (adjust branch/folder in the repo’s Pages settings if you use something else).
