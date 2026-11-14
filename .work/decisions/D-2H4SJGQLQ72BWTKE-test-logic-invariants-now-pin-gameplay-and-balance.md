---
status: accepted
date: 2026-11-15
read_if:
  - writing or changing tests
  - pinning a price, odds, threshold or session length
refs:
---

# D-2H4SJGQLQ72BWTKE Test logic invariants now; pin gameplay and balance only near v1.0-BETA

## Context
The design is expected to move a lot until playtests settle it, but the code under it still needs protection.

## Decision
From the start, tests cover logic invariants only: determinism under a seed, ledger arithmetic, data-row schemas and state transitions. Gameplay and balance (prices, odds, investor thresholds, session length) are pinned in tests only when approaching v1.0-BETA.

## Why
Invariants hold whatever the tuning, so they protect the code without resisting design change. Pinning balance earlier would freeze tuning that the playtests are supposed to change, and every tweak would start with fixing tests.

## Consequences
A test that asserts a tuned number is premature until the beta-hardening slice. Balance values belong in data, where they can change without touching tests.
