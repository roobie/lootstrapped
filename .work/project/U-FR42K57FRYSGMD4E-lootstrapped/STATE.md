---
phase: execute
owner:
  - BR
  - claude
created: 2026-11-15
success_criteria:
  - A v1.0-BETA build is published on itch.io in which a session of about 30 minutes plays one season and ends in a graded charter verdict (clean, with terms, or probation)
  - The same seed and the same player inputs replay a season to an identical end state
  - The owner judges the game fun in playtests
---

# project/lootstrapped

## Purpose
A grim-comic pawnshop game for an adventuring guild, complete within about two weeks of AI-assisted development and then extended and polished in place: you appraise, haggle, sell and lend what parties bring back, and a board of angel investors judges each season.

## Scope
In: the counter (buy with haggling, appraise by clues with finite tools, sell, close the day's ledger), a season of shop days ending in the board meeting, and the later layers (lending, the offscreen dungeon, provenance, reputation, pressure, polish) as playtests justify them; content as moddable data rows.
Out: rendering the dungeon; shopkeeper stats; anything that needs a rewrite to plug in rather than new data and panels.

## Context & constraints
Promoted from riff 2026-11-14 #1, which is now DESIGN.md (what is decided, and what is still a bounce). Builds on skelly-assets (weapons, armour and props as `.glb`, and its showcase turntable) and on the TypeScript, Jsonnet and CEL tooling and browser-game lessons of skelly and deadvox. Ships to itch.io. The simulation stays deterministic. The two-week plan's first four slices are fixed; what comes after them is decided by playtests. Nothing is built yet.

## Next

## Evidence
<!-- Proof against success_criteria: test runs, commits, measurements. -->

## Harvest
<!-- Candidates found along the way. Finalize promotes or drops every unchecked item:
     - [ ] decision: …   → record decision
     - [ ] learning: …   → record learning
     - [ ] backlog: …    → record backlog
     - [ ] process: …    → retrospective (change the process, or drop it)
-->

## Log
- 2026-11-15 initialized
- 2026-11-15 phase initialize → execute
- 2026-11-15 riff-261114-1 moved in as DESIGN.md
- 2026-11-15 bounce added: Wyrm Combinator is a dragon's fund, the angels its LPs
- 2026-11-15 milestone/first-season spawned with slices S0–S3
- 2026-11-15 flexible slices S4–S7 recorded as provisional backlog items
- 2026-11-15 decision records for the riff's decided items; DESIGN.md points at them
