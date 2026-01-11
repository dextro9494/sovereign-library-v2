# v2 Build Log (regenerated from this chat)
**Date:** 2026-01-11

## Goal
Create **v2 as a parallel site** (keep v1 intact), deploy via GitHub Pages, and add the structural beams that allow a large Library without navigation fog.

## What you did (hands-on sequence)
1) Created new GitHub repo: `sovereign-library-v2`
2) Local folder existed with `.git`
3) Copied v1 scaffold into v2 (keeping v2’s `.git`)
4) Built to `/docs`:
   ```bash
   hugo -d docs
   ```
5) GitHub Pages issue: repo was private → Pages asked for Pro → you made repo public → Pages became free
6) Enabled Pages:
   - Settings → Pages → Deploy from branch → `main` / `/docs`
7) Added milestone tag:
   ```bash
   git tag -a v2-start -m "v2 repo created; v1 scaffold copied; Pages working"
   git push --tags
   ```
8) Added backlinks (“Referenced by”) in `layouts/_default/single.html`
9) Fixed baseURL to v2 subpath:
   - `baseURL = "https://dextro9494.github.io/sovereign-library-v2/"`
10) Added tags taxonomy:
    - `content/tags/_index.md`
    - `layouts/tags/taxonomy.html`
    - Added nav item “Tags”
11) Troubleshooting:
    - Hugo build error happened because `taxonomy.html` was accidentally placed under `content/` (Hugo tried to parse it as content)
    - Fixed by moving it to `layouts/tags/taxonomy.html`
12) Git push rejection (non-fast-forward):
    - Fixed with:
      ```bash
      git pull --rebase
      git push
      ```
13) Added manual “Connections Index” page:
    - `content/system/connections-index.md`

## Current v2 URL
- `https://dextro9494.github.io/sovereign-library-v2/`

## Why these changes matter
- Backlinks + tags make the Library **grandiose-safe**
- Mirror and Third Layer can remain clean interfaces that point into the Library

---
