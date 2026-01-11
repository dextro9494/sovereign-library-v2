---
title: "v2 Rework Control Panel"
date: "2026-01-01"
status: "canonical"
tags: ["v2", "rework", "architecture", "drift-control"]
---

# v2 Rework Control Panel (freeze-frame)

This page is the **governor** for the v2 rebuild: vocabulary, non-negotiables, and intake rules.
It prevents drift while we ingest Codex + sessions + raw batches.

## Current state
- **v1 is live** (published snapshot).
- **v2 is live** (staging lane), currently a scaffold copy of v1.
- We do **not overwrite v1** until v2 is coherent and complete.

## Core philosophy (v8 breakthrough)
**“Simple is what it should be.”**  
The system is only useful if it doesn’t try to become the system.

## The three layers (canonical)
### 1) Library (this site)
- Holds everything: philosophy, history, patterns, protocols, receipts.
- Lives outside AI sessions.
- Does **not** tell you what to do: it holds what you know.

### 2) Mirror (operational reflection)
- Shows **current state**: where you are RIGHT NOW.
- Lean, current, portable, pasteable into sessions.

**Decision boundary for v2:**
- **Mirror Instance** (daily truth) is paste-only (offsite).
- **Mirror Template** (schema + paste block) may be stored on the site.

> Note: some session saves say “Mirror will eventually be added to the website.”
> To avoid future regret, v2 should publish the **template**, not the live instance.

### 3) Third Layer (lived proof)
- The lived layer: enjoyment, formation, real-world expansion.
- “Not stored, not reflected — LIVED.”
- Made real through **receipts** (milestones, outcomes, evidence).

## Why v7 fragmented (drift trap to avoid)
v7 became operationally heavy:
- 33 Canonical Stories + Council intelligence + Field tests + raw transcripts + protocol logs
- Retrieval under crisis became slow.
- “Patch layering” created more surface area, not more speed.

**Trap name:** Monolith re-formation  
**Anti-trap:** separation + retrieval discipline.

## Vocabulary locks (canonical terms)
- **Library** = durable knowledge store (public).
- **Mirror** = current operational truth (pasteable).
- **Mirror Template vs Instance** = template can be public, instance stays private/paste-only.
- **Third Layer** = lived proof layer (receipts).
- **RCP (Real-World Connection Protocol/Filter)** = system must connect to real-world sovereignty.
- **Throttle Clause** = consultation must not replace execution.

## Deprecated / high-risk labels (use sparingly or deprecate)
- **Dark Council** (early-era framing; easily becomes performative).
- Over-identity with **Builder/Survivor** (use as navigation tool, not a prison).
- Any architecture that collapses back into a single “master file.”

## Intake rules for v2 (how we rebuild without losing anything)
1) **Structure before content**
   - Create containers/hubs first.
2) **No orphan facts**
   - Everything extracted must land in: Library node, Field Test, Daily Capsule, or Third Layer receipt.
3) **Evidence over aspiration**
   - Third Layer entries require a receipt or they remain “forming.”
4) **Connections are first-class**
   - Preserve explicit `connected:` links; add backlinks later (optional).
5) **Public by default (per István)**
   - Everything shared may go to the site; still flag accidental doxx-risk items.

## What’s missing (must exist in v2)
- Meta entries (self-explaining hubs):
  - **What is the Library?**
  - **What is the Mirror?**
  - **What is the Third Layer?**
- Under-defined concepts:
  - **Success Dance** (operational indicators)
  - **Pleasure Architecture** (real enjoyment vs substitution)
  - **Council role map** (canonical “who does what, when”)
- Optional but strong:
  - “Normal day vs crisis” usage page.

## Ingestion status
- Codex versions v1→v7.1: ✅ received
- Claude session recaps (this zip): ✅ received
- Raw legacy batches (7): ⏳ next

## Next step (the smart one)
Extract a **Decision Map** from the Claude session recaps:
- What is locked (non-negotiables)
- What is implied (but not written)
- What is still open (true blockers)

Then ingest the 7 raw batches into the containers without drift.
