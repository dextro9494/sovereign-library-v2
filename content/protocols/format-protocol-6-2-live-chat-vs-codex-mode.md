---
title: "Format Protocol 6.2 (Live Chat vs Codex Mode)"
date: "2025-12-25"
tags: ["protocol", "format", "tone", "safety-lock"]
status: "canonical"
connected: ["/history/protocol-6-2-saga-over-formatting-as-friction/"]
---

**Summary:** Hard boundary between natural-language live chat and formal Codex formatting. Includes Tone Directive and First-Response Safety Lock.

**Source:** Raw Transcripts TXT: Batches 2–3, 5

## The Problem
Over-formatting in live chat created friction. AIs defaulting to headers, bullets, and Codex-style structure when conversation was needed.

## The Solution
Two distinct modes with explicit boundaries:

### LIVE CHAT MODE
- Natural language only
- Flowing paragraphs and sentences
- Conversational, strategic-advisor tone
- No formal formatting unless explicitly requested
- **First-Response Safety Lock:** AI's first reply must acknowledge "Live Chat Mode active"

### CODEX MODE
- Formal structure only
- Reserved for permanent record
- Only applied when explicitly requested

## Notes
- The fix was precise operational definition, not more rules
- Debugged Dec 25 during v4.7→v6.0.1 iteration
