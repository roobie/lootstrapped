# Lootstrapped

Work runs through dev-proc (`.work/`); start from its `status`.

- Until v1.0-BETA, tests pin logic invariants only (determinism, ledger arithmetic, data-row schemas, state transitions), never gameplay or balance values, because playtests have to stay free to change the tuning: D-2H4SJGQLQ72BWTKE.
- The sim is deterministic: a seed plus the player's inputs replay a season exactly, so sim code never calls `Math.random` or reads the wall clock: D-2Q5ZKHIVF2C6ZP2C.
- Code is logic; content is moddable data, as Jsonnet rows with CEL expressions, so a feature beyond the counter plugs in as data and panels: D-FSULJNRFYK4Z43SE.
- The stack is TypeScript, Jsonnet evaluated in the browser and CEL, as in skelly and deadvox; `~/devel/skelly/packages/deadvox` is the reference and `~/devel/skelly-assets` the source of meshes: D-T7MNEN4NJXAJ3P56.
- Player-facing text is grim-comic: D-IGZD65FTBWFT5FBJ.
- Durable docs (decisions, learnings) hold only the why; the code is the how and what.
- After a fresh clone: `mise trust`. Setup, check and test commands arrive with the skeleton slice (S1).

## Drive
- parallel: 1
- setup: `mise trust` (more arrives with S1)
- test: none yet; arrives with S1
- owner-only: feel, visuals, the S0 moodboard and mockup choices, balance taste, and reshaping the flexible slices after each playtest
- review: the unit's `## Evidence`
- integrate: merge to main after review; push only with the owner's say-so
