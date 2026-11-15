---
status: accepted
date: 2026-11-15
read_if:
  - designing tools or their data rows
refs:
  - art/storyboard/storyboard.html
---

# D-5YSEEY37NHL6JFEW Each tool's finiteness is set per tool in its data row

## Context
Tools are finite, but in which way was open (storyboard Q5, DESIGN.md).

## Decision
Charges, durability or consumables, chosen per tool in its content row; no single rule for every tool.

## Why
It keeps tools moddable data (D-FSULJNRFYK4Z43SE), and each tool gets its own character.

## Consequences
The tool row schema carries its kind of finiteness, and the counter and ledger need a way to show each kind.
