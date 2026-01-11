---
title: "Decision Map"
---

# Decision Map

## Locked (do not drift)
- Parallel build: v1 preserved, v2 staged.
- Library may expand; Mirror + Third Layer remain executable.
- Retrieval beams: backlinks + tags are required.
- Publishing flow: local build → `/docs` → push.

## Open (decide later)
- Mirror instance: public or paste-only (default paste-only).
- Third Layer implementation style (cards vs logs vs board).
- Automated “connections index” (top referenced pages).

## Technical notes (from build)
- If push rejected: `git pull --rebase` then `git push`.
- Hugo taxonomy templates belong in `layouts/`, not `content/`.
- Menu changes may require hard refresh (Ctrl+F5).
