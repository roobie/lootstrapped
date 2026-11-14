---
phase: initialize
parent: U-GABIZCVEAFSYLQFN
owner:
  - BR
  - claude
created: 2026-11-15
success_criteria:
  - A browser build loads moddable data rows (items, traits, clues, tools, customers, investors)
  - Randomness comes from a seeded RNG, and the same seed gives the same rolls
  - A skelly-assets item sits on the counter, and the player can turn and inspect it
  - The Jsonnet evaluator question (one evaluator for build and runtime; precompiled base content with a lazily loaded evaluator for mods, or not) is decided from measured download weight and startup time
---

# slice/skeleton

## Purpose
The first running build: data, randomness and the counter's 3D item in place, so every later slice adds play rather than plumbing.

## Scope
In: a browser build; data rows loaded from Jsonnet; a seeded RNG; one skelly-assets item on the counter that can be turned and inspected; the evaluator measurement.
Out: gameplay (haggling, appraisal, the ledger).

## Context & constraints
S1 of the fixed slices, about days 2–3; starts after visual-groundwork. Tests from here on cover logic invariants only (determinism under a seed, data-row schemas).


## Next
<!-- The cursor of the unit being worked: what is about to happen, and for a held unit the reason first.
     Rewrite it freely. A unit with open children keeps none: its present is its children. -->

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
