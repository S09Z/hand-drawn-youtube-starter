# Progress

## Current state

- Phase: PHASE-01 — Foundation + Manual Production MVP
- Branch: `phase/01-manual-production-mvp`
- Draft pull request: https://github.com/S09Z/hand-drawn-youtube-starter/pull/1
- Last completed loop: LOOP-02 — Complete Channel Bible
- Current recommended loop: LOOP-03 — Complete `docs/VISUAL_STYLE.md`
- Status: READY FOR HUMAN INPUT
- Blockers: Visual-style decisions are human-owned and intentionally unresolved.

## LOOP-02 — Complete Channel Bible

### Goal

Define the channel's mission, audience, content pillars, format, voice, boundaries, and early success criteria without making human-owned creative decisions by inference.

### Scope

- Replace every intentional placeholder in `docs/CHANNEL_BIBLE.md` with approved human direction.
- Check the resulting decisions for internal consistency and usefulness during topic, script, and publishing review.
- Do not define the visual style, select Episode 001's topic, or start later loops.

### Definition of Done

Every Channel Bible field is explicit, the rules are actionable, the human approves the completed document, verification passes, and the loop state is recorded.

### Verification completed

- Every Channel Bible placeholder was replaced with explicitly approved human direction.
- Mission, audience, pillars, format, voice, boundaries, and success criteria are internally consistent.
- Topic and script rules are actionable without requiring specialist audience knowledge.
- `docs/VISUAL_STYLE.md` and later-loop artifacts remain untouched.

## LOOP-01 — Repository Foundation Review

### Goal

Confirm that the starter structure is coherent, minimal, safe to place under Git, and aligned with Phase 1.

### Verification completed

- Required core files and `.gitkeep` placeholders exist and are readable.
- The EP001 artifact list maps to a template for every documented stage.
- The production log closes the Procreate/CapCut documentation gap.
- Representative secrets and generated media are ignored; source documents remain trackable.
- No credentials, generated media, runtime dependencies, or automation are tracked.
- Intentional creative `TODO` fields remain untouched.
- `git diff --check` passes.
- Phase 2 integrations remain deferred.

### Out of scope

- Final creative decisions
- Producing Episode 001 content
- Installing Obsidian or Hermes
- Connecting Telegram
- Adding automation or AI APIs

### Definition of Done

Repository inspection and review pass; any findings are fixed; `TASKS.md` and this file record LOOP-01 as complete; LOOP-02 is identified but not started.

## Decisions

- Markdown is the portable source of truth.
- `PROGRESS.md` is authoritative for operational state.
- One folder contains all artifacts for each episode.
- Asset reuse is checked before new drawings are proposed.
- Phase 1 remains manual to reveal genuine bottlenecks.

## Known issues

- Channel identity and visual language require human input.
- Templates, including the new production log and fact-ID convention, have not yet been tested on a real episode.

## Loop history

### LOOP-01 — Repository Foundation Review

- Completed: 2026-09-21
- Changed: added a production-log template, added episode-local fact IDs and a script claim map, expanded generated-audio ignore rules, and aligned workflow documentation.
- Checks: required-file presence, episode/template mapping, representative `git check-ignore` cases, tracked-file risk scan, creative-TODO preservation, runtime-manifest scan, and `git diff --check`.
- Decisions: production logs use `production-log.md`; fact IDs use `F` plus two digits and are unique within an episode; source images remain trackable.
- Review: no meaningful findings remain for LOOP-01.
- Next action: ask the human for the channel decisions required to complete `docs/CHANNEL_BIBLE.md`; do not start visual-style work.

### LOOP-02 — Complete Channel Bible

- Completed: 2026-09-21
- Changed: defined the channel mission, audience, content pillars, format, narrator voice, editorial boundaries, and first-three-episode success criteria.
- Decisions: overlooked history for curious English-speaking adults; 3–5 minute biweekly videos; warm, plain-English narration; evidence-led and respectful editorial boundaries.
- Checks: placeholder scan, document consistency review, scope review, and `git diff --check`.
- Review: no meaningful findings remain for LOOP-02.
- Next action: collect the human visual references and production constraints required for `docs/VISUAL_STYLE.md`; do not start the template dry run.
