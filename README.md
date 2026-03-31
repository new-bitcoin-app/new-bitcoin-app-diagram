# New Bitcoin App — GitHub Pages Diagram Demo

This is a polished GitHub Pages demo for a **stable architecture diagram URL**.

## Why this setup

Instead of generating a new Mermaid Live link every time the diagram changes, this repo keeps one permanent URL:

```text
https://<owner>.github.io/new-bitcoin-app-diagram/
```

The page at that URL renders `diagram.mmd`, so updating the architecture is as simple as changing one file and pushing to `main`.

## Files

- `index.html` — the GitHub Pages viewer
- `diagram.mmd` — the Mermaid source I can keep updating during our discussion
- `.github/workflows/pages.yml` — auto-deploys the site on every push

## Publishing

1. Create a GitHub repo named `new-bitcoin-app-diagram`
2. Push these files to the `main` branch
3. Enable GitHub Pages via the workflow (or let Actions deploy it automatically)
4. Open:
   - `https://<owner>.github.io/new-bitcoin-app-diagram/`

## Update flow

1. We talk
2. I edit `diagram.mmd`
3. I commit + push
4. Same URL, updated diagram

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```
