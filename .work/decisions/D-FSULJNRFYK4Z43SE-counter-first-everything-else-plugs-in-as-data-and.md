---
status: accepted
date: 2026-11-15
read_if:
  - adding a feature beyond the counter
  - deciding whether something is code or data
  - adding a mod surface
refs:
---

# D-FSULJNRFYK4Z43SE Counter first; everything else plugs in as data and panels

## Context
The game must be complete within about two weeks and then grow in place. Most of the riff's ideas (lending, the dungeon, reputation, career seasons) would each be a system of their own.

## Decision
Start simple and stay extensible: the counter comes first, and anything beyond it plugs in as data and panels, with no rewrite. Content is moddable data from day one.

## Why
A small core that works beats a broad one that does not, and data rows make each extension cheap to add and also a mod surface for players. Building the full design up front would miss the two-week bound; building a closed core would force a rewrite to extend.

## Consequences
Item kinds, traits, clues, tools, customers, investors and their terms are data rows, not code. A feature that cannot be added as data and a panel is a sign the core needs a seam first.
