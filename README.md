# Trek 970 → City Build

A single-page, Blue Lug–style field manual for converting a 1990s Trek 970
mountain bike into a considered city bike — what each part is, what to change,
and what to buy.

**Live site:** https://julienvarin.github.io/bike-project/

## Deploying (GitHub Pages)
This is a static site served straight from the repo root. To publish it:
**Settings → Pages → Build and deployment → Source: “Deploy from a branch”
→ Branch: `claude/github-pages-deploy-yu731y` / `/(root)` → Save.**
Pages rebuilds automatically on every push to that branch.

## Contents
- `index.html` — the whole site, self-contained (HTML + CSS + a little JS).
- `images/` — line-art SVG illustrations for each part and its options. Swap
  any `<img>` in `index.html` for your own photo to personalise it.

## Local preview
Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```
