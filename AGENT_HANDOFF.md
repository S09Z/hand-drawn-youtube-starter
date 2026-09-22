# Agent Handoff

## Project

AI-assisted hand-drawn YouTube storytelling system.

## Current goal

Establish a minimal, repeatable manual workflow:

Research → Script → Storyboard → Drawing List → Procreate → CapCut → Publish → Analytics

## Current state

- Starter repository created.
- Current phase: `PHASE-01`.
- Current branch: `loop/phase-01-07-storyboard-drawing-list`.
- Phase draft pull request: https://github.com/S09Z/hand-drawn-youtube-starter/pull/1
- LOOP-05 draft pull request: Pending creation
- `LOOP-01 — Repository Foundation Review` is complete.
- `LOOP-02 — Complete Channel Bible` is complete.
- `LOOP-03 — Complete Visual Style` is complete with four approved repository-local references.
- `LOOP-04 — Production Template Dry Run` is complete using the fictional, non-publishable `DRY-RUN-001` pack.
- `LOOP-05 — Episode 001 Research` is complete with human-approved topic and research pack; Margaret Knight's flat-bottom paper-bag machinery is EP001.
- `LOOP-06 — Episode 001 Script` is complete with a 507-word human-approved script and full `F01`–`F10` claim mapping.
- `LOOP-07 — Episode 001 Storyboard and Drawing List` is complete with 15 approved scenes and 15 approved modular assets.
- Current recommended work: `LOOP-08 — Complete Procreate and CapCut production manually`, but do not begin until LOOP-05, LOOP-06, and LOOP-07 are merged in order and the local Phase 1 branch is updated.
- Reserved next branch: `loop/phase-01-08-manual-production`.
- Workflow exception: the human explicitly directed LOOP-07 to continue before the earlier loop branches were merged. This branch starts from approved LOOP-06 commit `8388333`; preserve the merge order LOOP-05 → LOOP-06 → LOOP-07.
- Authoritative current loop and state live in `PROGRESS.md`.
- Episode templates intentionally retain fill-in placeholders until they are used.

## Latest verification

- Required foundation files and episode/template mappings pass.
- Git ignore checks cover secrets, generated video, and common generated audio formats.
- No production media, credentials, runtime dependencies, or automation are tracked; four approved visual-reference images are intentionally versioned under `docs/references/`.
- The production-log and fact-ID conventions passed the fictional dry run; real-episode validation remains pending.
- EP001 research contains unique fact IDs F01–F10, separates disputed claims from verified facts, and was approved by the human for script handoff.
- EP001 script contains 507 narrated words, preserves the research cautions, maps all factual claims to F01–F10, and has human approval for voice, length, and final wording.
- EP001 storyboard covers 0:00–4:10 in 15 scenes; its drawing list caps production at 15 modular assets after confirming the asset library contains only placeholders. Both artifacts have human approval.

## Working philosophy

Use Loop Engineering: Inspect → Plan → Implement → Verify → Review → Record → Next Loop.

- One small loop at a time.
- Beginning with LOOP-05, each loop is isolated on its own branch and draft pull request into the phase branch.
- Prefer minimal implementation.
- Verify every change.
- Do not introduce infrastructure for hypothetical future needs.
- Keep this file concise; history belongs in `PROGRESS.md` and Git.

## Technology direction

Current: Claude/GPT for assistance, Procreate for drawing, CapCut for editing, Markdown files for durable state.

Phase 2 candidates: Obsidian, Hermes Agent, Telegram. Potential later options: local LLM and ElevenLabs.

Avoid unless a real bottleneck justifies them: n8n, LangChain, Qdrant, Kubernetes, complex RAG, complex multi-agent systems, custom dashboards, and ComfyUI pipelines.

## New-session report

Before changing anything, report:

- Last completed loop
- Current loop
- Relevant files
- Documentation/repository mismatches
- Blockers
- Smallest useful next action
- Verification approach

Do not implement until the current loop is approved.
