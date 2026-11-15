---
status: accepted
date: 2026-11-15
read_if:
  - designing the shop day's time budget
  - designing the appraisal screen or the clue list
  - lighting the counter scene
refs:
  - art/moodboard/moodboard.html
---

# D-34WHPVTJ6MRKUSXM The candle is the day's clock, and unasked clues show their cost in candle

## Context
Time in the shop day is the budget every inspection spends (D-YX3IUCV2YUN7CT7X), and the player has to see that budget and weigh it against what they do not yet know.

## Decision
The day's clock is a candle on the counter. Every inspection melts it toward the next hour ring, and the room darkens as the day's options run out. The clues not yet asked for are listed, greyed, with what each would cost in candle.

## Why
A HUD timer is abstract; a candle you watch burn makes spending felt, and the darkening room carries the pressure without a number. Pricing the unasked clues in the same candle puts the real decision, what to inspect and with what, on the page, so the player weighs the unknown instead of discovering tools blind. The same candle reads as "runway" on the board's dashboard, so burn rate needs no explanation there.

## Consequences
Inspection costs are expressed in candle, and the counter's lighting follows the day's remaining time. Clue rows must be listable before they are revealed without giving away their content. This shapes S2's appraisal loop.
