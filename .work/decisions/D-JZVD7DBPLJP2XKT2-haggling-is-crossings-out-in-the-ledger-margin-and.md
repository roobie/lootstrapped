---
status: accepted
date: 2026-11-15
read_if:
  - designing haggling or offers
  - designing undo or corrections in the ledger
refs:
  - art/moodboard/moodboard.html
---

# D-JZVD7DBPLJP2XKT2 Haggling is crossings-out in the ledger margin, and they are the undo history

## Context
Haggling reads people through offers and tells (project design, Two sides of the counter), and the ledger is the shop's interface (D-H574L6YSCOZIDEGL).

## Decision
Haggling is written as crossings-out in the ledger margin, and the same strikes are the undo history.

## Why
A bookkeeper strikes through rather than erases, so the haggle's whole history stays readable at a glance, and a customer's tells sit beside the numbers they explain. One mechanism then serves both the haggle record and undo, and undo that keeps the mistake visible suits the grim-comic ledger.

## Consequences
Offers are ledger entries, and undo strikes an entry instead of deleting it, which fits a season that replays from its inputs (D-2Q5ZKHIVF2C6ZP2C).
