# Library v1.0 — Structural Audit (regenerated from this chat)
**Date:** 2026-01-11  
**Scope:** This recreates the analysis we did in this chat about your **current public v1** and the reasons for a **parallel v2 rebuild**.

> Note on evidence: earlier in the chat you uploaded a v1 repo snapshot zip, which I used to count sections/pages and inspect templates. That uploaded snapshot is not currently present in this environment now, so the concrete counts below are reproduced from the earlier in-chat audit (not re-measured again today).

---

## What v1 is (as audited)
- Hugo site with content under `content/`
- Single-page template renders:
  - title, optional tags, optional date, content
  - **Connected to** list driven by frontmatter `connected: [...]`
  - missing targets are displayed explicitly as **Missing:** (good drift detector)

---

## Navigation and section inventory (from the earlier v1 snapshot audit)
Top-level sections in nav:
- Patterns
- Protocols
- History (includes Daily Capsules)
- Philosophy
- Field Tests
- Relationships
- Council
- Home

Content totals (earlier snapshot):
- Total pages: **84**
- Patterns: **13**
- Protocols: **15**
- History: **21** (Daily Capsules: **4** days + index)
- Philosophy: **11**
- Field Tests: **15**
- Relationships: **5**
- Council: **3**
- Home: 1

---

## What v1 could not support cleanly (why v2 rebuild was smart)
You want:
- **Library:** can be grand, hold everything, grow big
- **Mirror:** clean executable “session bootloader”
- **Third Layer:** lived formation, proof/receipts, not aspirational planning

v1 could store content, but was missing structural beams needed for “grand Library without fog”:
- No rendered **backlinks** (reverse connections)
- No first-class **tags index** you can navigate from
- No “governor” meta layer that locks vocabulary and prevents drift across rewrites

---

## Rebuild principle we locked
- Do **not** overwrite v1 while building v2.
- Build v2 as a parallel repo/site.
- Cutover only when v2 coheres.

---

## v2 beams we implemented
- Backlinks: **Referenced by** (computed from `connected:`)
- Tags taxonomy index (`/tags/`) + navbar link
- baseURL corrected for v2 subpath
- A manual starter **Connections Index** page (`content/system/connections-index.md`)

---
