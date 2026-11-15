---
phase: execute
parent: U-GABIZCVEAFSYLQFN
owner:
  - BR
  - claude
created: 2026-11-15
success_criteria:
  - A moodboard exists
  - A storyboard covers one shop day and the board meeting
  - Mockups exist of the counter scene and the ledger UI, and the 3D/UI split they show is agreed with the owner
---

# slice/visual-groundwork

## Purpose
Settle the mix of 3D and UI on paper before any code fixes it in place.

## Scope
In: moodboard; storyboard of one shop day and the board meeting; mockups of the counter scene and the ledger UI.
Out: any code.

## Context & constraints
S0 of the fixed slices, about day 1. Presentation is a mix: 3D where it carries the feel (the counter, the item, the customer), UI for everything else.


## Next
Storyboard one shop day and the board meeting against the moodboard and its decisions, then mock up the counter scene and the ledger UI, testing the toon outline and key light on real skelly-assets meshes. Mockups and storyboard go to the owner for review; the 3D/UI split needs their agreement.

## Evidence
<!-- Proof against success_criteria: test runs, commits, measurements. -->
- Moodboard: art/moodboard/moodboard.html (static, IM Fell from art/fonts/im-fell with its OFL), render art/moodboard/moodboard.webp. Base is the second pass (Fable) with the first pass's references and sounds folded in; owner reviewed both and chose it.
- Owner's moodboard choices recorded: D-AW7FZBF73LOHPLXO (look), D-OOYE4Y67O567LLKP (motifs), D-34WHPVTJ6MRKUSXM (candle clock), D-MHAAIXRXHKHH4G77 (tools as light), D-3ZWBI6KBBWBWWXDJ (cold rim), D-XZKESRNAOR3QIXHK (ink-blot uncertainty), D-JZVD7DBPLJP2XKT2 (haggle crossings-out), D-UB7AU7KR5QBMYH4C (knotted provenance), D-2NRZXEUWY2RFLDXF (legibility).

## Harvest
<!-- Candidates found along the way. Finalize promotes or drops every unchecked item:
     - [ ] decision: …   → record decision
     - [ ] learning: …   → record learning
     - [ ] backlog: …    → record backlog
     - [ ] process: …    → retrospective (change the process, or drop it)
-->
- [x] decision: the look, motifs, seven gameplay ideas (candle clock with unasked clues merged) and legibility rules, recorded during execute as the owner settled them
- [ ] backlog: the moodboard's sound mood (Plate VIII) as input to S6 juice-and-voice (B-MGJ5SWSBRA4IPHHQ)
- [ ] backlog: itch.io cover from the moodboard's title page, the three balls with one pastel sticker

## Log
- 2026-11-15 initialized
- 2026-11-15 phase initialize → execute
- 2026-11-15 moodboard landed in art/moodboard: second pass as base, first pass's unique bits folded in
- 2026-11-15 owner's moodboard choices recorded as nine decisions
