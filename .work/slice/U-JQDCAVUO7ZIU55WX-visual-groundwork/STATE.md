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
Storyboard awaits owner review, chiefly its open questions Q1–Q15 (art/storyboard/storyboard.html, end of page). Next: mock up the counter scene and the ledger UI, testing the toon outline and key light on real skelly-assets meshes and where the ledger sits beside the 3D counter (Q2). Mockups and storyboard go to the owner; the 3D/UI split needs their agreement.

## Evidence
<!-- Proof against success_criteria: test runs, commits, measurements. -->
- Moodboard: art/moodboard/moodboard.html (static, IM Fell from art/fonts/im-fell with its OFL), render art/moodboard/moodboard.webp. Base is the second pass (Fable) with the first pass's references and sounds folded in; owner reviewed both and chose it.
- Owner's moodboard choices recorded: D-AW7FZBF73LOHPLXO (look), D-OOYE4Y67O567LLKP (motifs), D-34WHPVTJ6MRKUSXM (candle clock), D-MHAAIXRXHKHH4G77 (tools as light), D-3ZWBI6KBBWBWWXDJ (cold rim), D-XZKESRNAOR3QIXHK (ink-blot uncertainty), D-JZVD7DBPLJP2XKT2 (haggle crossings-out), D-UB7AU7KR5QBMYH4C (knotted provenance), D-2NRZXEUWY2RFLDXF (legibility).
- Storyboard: art/storyboard/storyboard.html (static, moodboard's look and IM Fell), render art/storyboard/storyboard.webp. Fifteen panels: one shop day (open, seller, inspect, loupe, curse candle, haggle, sale, investor toast, candle gutters, tally) then Closing Day (cut, dashboard, three angels, graded verdict, shuttered shop with stickers); each caption names what the player sees and does, what is 3D and what UI, and the light/sound beat, with the decisions it rests on. Fifteen open questions tagged on their panels and listed at the end for the owner.

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
- [ ] decision: where the ledger sits while the counter is in view (storyboard Q2), once the mockups settle it
- [ ] decision: the shop day's structure: phased by customer kind or one queue, and what an hour ring does (storyboard Q4, Q9), before S2
- [ ] decision: how an offer is entered and where tells and patience show (storyboard Q6), before S2's haggle
- [ ] decision: how each angel's judgement is made legible, whether the player acts in the meeting, and whether fired is a fourth outcome (storyboard Q12–Q14), before S3
- [ ] backlog: investor messages during shop days and tool restocking at night (storyboard Q8, Q10), if the owner keeps them out of S2–S3

## Log
- 2026-11-15 initialized
- 2026-11-15 phase initialize → execute
- 2026-11-15 moodboard landed in art/moodboard: second pass as base, first pass's unique bits folded in
- 2026-11-15 owner's moodboard choices recorded as nine decisions
- 2026-11-15 storyboard of one shop day and the board meeting landed in art/storyboard, with fifteen open questions for the owner
- 2026-11-15 storyboard contradictions fixed after the second opinion: no percentage in the shop, offers in upright figures, the buyer's request on vellum, the day's candle and a tool's charge told apart on clue rows
