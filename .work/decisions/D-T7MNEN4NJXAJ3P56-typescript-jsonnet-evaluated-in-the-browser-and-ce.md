---
status: accepted
date: 2026-11-15
read_if:
  - choosing languages, libraries or the content pipeline
  - touching the Jsonnet evaluator or mod loading
  - deciding whether base content ships precompiled
refs:
---

# D-T7MNEN4NJXAJ3P56 TypeScript, Jsonnet evaluated in the browser, and CEL

## Context
skelly and deadvox already use TypeScript, Jsonnet and CEL for browser games, and their tooling and lessons are available. Players on itch.io should be able to mod without installing a toolchain.

## Decision
The stack is TypeScript, Jsonnet and CEL as in skelly and deadvox, with Jsonnet evaluated in the browser. Build and runtime use the same Jsonnet evaluator.

## Why
Reusing the stack carries the earlier projects' lessons straight over. Evaluating Jsonnet in the browser is what "content is moddable" means for a player: mods need no toolchain. skelly compiles with the go-jsonnet binary at build time, so a different browser evaluator would let build and runtime drift apart; one evaluator for both (for example go-jsonnet compiled to wasm) prevents that.

## Consequences
A wasm evaluator adds download weight and startup time. Whether base content ships precompiled with the evaluator loaded lazily for mods is decided in S1 by measuring, not up front.
