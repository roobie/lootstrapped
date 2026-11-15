---
status: accepted
date: 2026-11-15
read_if:
  - designing the shop day's customer flow
  - adding day mutators
refs:
  - art/storyboard/storyboard.html
---

# D-WMOVKUFJH5UB6LBE The shop day is phased: sellers in the morning, buyers at midday

## Context
Storyboard Q4 asked whether customer kinds come in phases or in one mixed queue.

## Decision
The day is phased by customer kind, set in content so the phases are data. A mixed queue is a later mutator, not the base game.

## Why
It reads clearly, and it gives the candle's hour rings a meaning beyond the light.

## Consequences
The phases and their order are content rows, which leaves room for mutators that change them later.
