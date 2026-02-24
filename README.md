# projects.kaufman.io

Simple static page that displays my public GitHub projects.

- Fetches repos via GitHub API (no auth required)
- Filters out archived and forked repos
- Shows name, description, language, last updated
- No build step — just HTML/CSS/JS

## Deploy

Push to `main` → Cloudflare Pages auto-deploys.

## Local Preview

```bash
npx serve .
# or just open index.html in a browser
```
