# Agent Handoff

## Project

AI-assisted hand-drawn YouTube storytelling system.

## Current goal

Establish a minimal, repeatable manual workflow:

Research → Script → Storyboard → Drawing List → Procreate → CapCut → Publish → Analytics

## Current state

- Starter repository created.
- Current phase: `PHASE-01`.
- Current branch: `phase/01-manual-production-mvp`.
- Draft pull request: https://github.com/S09Z/hand-drawn-youtube-starter/pull/1
- `LOOP-01 — Repository Foundation Review` is complete.
- `LOOP-02 — Complete Channel Bible` is complete.
- `LOOP-03 — Complete Visual Style` is complete with four approved repository-local references.
- Current recommended work: `LOOP-04 — Validate all production templates with a dry run`.
- Authoritative current loop and state live in `PROGRESS.md`.
- Episode templates intentionally retain fill-in placeholders until they are used.

## Latest verification

- Required foundation files and episode/template mappings pass.
- Git ignore checks cover secrets, generated video, and common generated audio formats.
- No production media, credentials, runtime dependencies, or automation are tracked; four approved visual-reference images are intentionally versioned under `docs/references/`.
- The production-log and fact-ID conventions await validation during the template dry run in LOOP-04.

## Working philosophy

Use Loop Engineering: Inspect → Plan → Implement → Verify → Review → Record → Next Loop.

- One small loop at a time.
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
