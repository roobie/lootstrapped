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
Record the decisions the owner took on the moodboard (visual direction, the gameplay ideas, legibility), then storyboard one shop day and the board meeting.

## Evidence
<!-- Proof against success_criteria: test runs, commits, measurements. -->
- Moodboard: art/moodboard/moodboard.html (static, IM Fell from art/fonts/im-fell with its OFL), render art/moodboard/moodboard.webp. Base is the second pass (Fable) with the first pass's references and sounds folded in; owner reviewed both and chose it.

## Harvest
<!-- Candidates found along the way. Finalize promotes or drops every unchecked item:
     - [ ] decision: …   → record decision
     - [ ] learning: …   → record learning
     - [ ] backlog: …    → record backlog
     - [ ] process: …    → retrospective (change the process, or drop it)
-->

## Log
- 2026-11-15 initialized
- 2026-11-15 phase initialize → execute
- 2026-11-15 moodboard landed in art/moodboard: second pass as base, first pass's unique bits folded in
