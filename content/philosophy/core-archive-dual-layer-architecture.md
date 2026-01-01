---
title: "Core + Archive Dual-Layer Architecture"
date: "2025-12-26"
tags: ["architecture", "core", "archive", "scaling"]
status: "canonical"
connected: ["/protocols/archive-integration-methodology/", "/history/v7-0-overhaul-decision/"]
---

**Summary:** System scaling principle: separate the blade (Core for acting) from the library (Archive for remembering). Prevents bloat and preserves operational speed.

**Source:** Raw Transcripts: Batch 7

## v7.0 Architecture
- **Core:** The blade. For acting. Lean, operational.
- **Archive:** The library. For remembering. Complete, historical.

## Evolution to v8.0
v7.0 fragmented because Core and Archive became entangled. v8.0 breakthrough:
- **Library:** Holds everything. Lives outside AI sessions.
- **Mirror:** Shows where you are NOW. Lean, portable.
- **Third Layer:** What becomes possible when the other two work. Lived, not stored.

## Key Insight
"The thing is only good if it's not trying to be the thing; simple is what it should be."
