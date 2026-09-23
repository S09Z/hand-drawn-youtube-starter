# Agent Handoff

## Project

AI-assisted hand-drawn YouTube storytelling system.

## Current goal

Establish a minimal, repeatable manual workflow:

Research → Script → Storyboard → Drawing List → Procreate → CapCut → Publish → Analytics

## Current state

- Phase: PHASE-01 — Foundation + Manual Production MVP
- Branch: `loop/phase-01-07-storyboard-drawing-list`
- Phase draft pull request: https://github.com/S09Z/hand-drawn-youtube-starter/pull/1
- LOOP-05 pull request: https://github.com/S09Z/hand-drawn-youtube-starter/pull/4 — merged
- Last completed loop: LOOP-05 — Episode 001 Research
- Current loop: LOOP-07 — Storyboard reconciliation; dependent on revised LOOP-06 approval
- Script pull request: https://github.com/S09Z/hand-drawn-youtube-starter/pull/2 (targets the Phase 1 branch)
- Status: Research corrections integrated; revised script requires renewed human approval.
- Existing LOOP-07 storyboard PR #3 depends on PR #2 and must carry the same research restrictions.
- Next action: review revised script and storyboard, then merge the dependent PRs in order before production.
- Earlier completion and approval records below describe the versions before the 2026-09-23 correction.

## Latest verification

- Required foundation files and episode/template mappings pass.
- Git ignore checks cover secrets, generated video, and common generated audio formats.
- No production media, credentials, runtime dependencies, or automation are tracked; four approved visual-reference images are intentionally versioned under `docs/references/`.
- The production-log and fact-ID conventions passed the fictional dry run; real-episode validation remains pending.
- Review follow-up: the exact dispute chronology and case-to-patent link remain unresolved; research now restricts scripting to the broad priority outcome and separately verified machine patent.
- Remote script/storyboard PRs #2 and #3 exist; reconcile their claims and dependencies before continuing later loops.
- EP001 research contains unique fact IDs F01–F10, separates disputed claims from verified facts, and was approved by the human for script handoff.
- EP001 script contains 507 narrated words, preserves the research cautions, maps all factual claims to F01–F10, and has human approval for voice, length, and final wording.

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
