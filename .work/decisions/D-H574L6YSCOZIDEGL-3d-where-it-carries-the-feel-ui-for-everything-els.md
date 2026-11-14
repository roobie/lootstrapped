---
status: accepted
date: 2026-11-15
read_if:
  - deciding whether a feature is a 3D scene or UI
  - designing the counter scene or the ledger
refs:
---

# D-H574L6YSCOZIDEGL 3D where it carries the feel, UI for everything else

## Context
The game builds on skelly-assets' 3D meshes and turntable, but most of what a shopkeeper does is reading numbers, lists and the ledger.

## Decision
The presentation is a mix: a 3D scene where it carries the feel (the counter, the item, the customer) and UI for everything else.

## Why
Fully 3D would spend the two-week budget on scenes that add little to bookkeeping, and fully 2D would waste the asset pipeline and the tactile pleasure of turning an item over. The mix puts 3D only where touch and presence matter.

## Consequences
The counter scene and the ledger UI are designed together, which is why the split is settled in S0 before code fixes it. New features default to UI unless they need the feel of the counter.
