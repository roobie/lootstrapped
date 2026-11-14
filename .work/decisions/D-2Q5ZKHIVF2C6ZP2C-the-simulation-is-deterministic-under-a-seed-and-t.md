---
status: accepted
date: 2026-11-15
read_if:
  - writing simulation code that uses randomness or time
  - reproducing a bug
  - adding replays
refs:
---

# D-2Q5ZKHIVF2C6ZP2C The simulation is deterministic under a seed and the player's inputs

## Context
The game has seeded randomness everywhere (items, traits, customers, the offscreen dungeon), and bugs in a 30-minute season are hard to reproduce by hand.

## Decision
The simulation is deterministic: a seed plus the player's inputs reproduce a season exactly.

## Why
Determinism makes every bug replayable and makes the logic tests meaningful, at little cost when it is held from the start. Retrofitting it later is far harder than never losing it.

## Consequences
Simulation code draws randomness only from the seeded generator and never reads the wall clock. Presentation may use real time; the simulation may not depend on it.
