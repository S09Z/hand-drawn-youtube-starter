# Project Plan

## Vision

Build a simple, repeatable system for short, hand-drawn YouTube stories. AI reduces research and planning effort without replacing human creative judgment.

## Core production flow

Research → Script → Storyboard → Drawing List → Procreate → CapCut → Publish → Analytics

## Principles

- Make one real video before automating the workflow.
- Keep Markdown files portable across Codex, Claude Code, ChatGPT, and Obsidian.
- Separate verified facts, uncertain claims, and creative interpretation.
- Reuse drawings before proposing new assets.
- Preserve human approval at topic, script, visuals, edit, and publish stages.
- Add technology only for a measured bottleneck.

## Phase 1 — Foundation + Manual Production MVP

Goal: define the channel and successfully produce at least one episode using a documented manual workflow.

Deliverables:

- Repository foundation and state files
- Channel Bible and visual style
- Research, script, storyboard, drawing-list, publishing, and analytics templates
- Reusable asset catalog
- One complete episode content pack
- A recorded retrospective after publication

Exit criteria:

- One episode moves through every production stage.
- Sources and uncertain claims are visible.
- Required drawings are clear before Procreate begins.
- Post-publish metrics and lessons can be recorded.
- The next bottleneck is supported by evidence, not speculation.

## Phase 2 — Lightweight Wiki + Selective Assistance

Goal: add memory and carefully chosen assistance only after Phase 1 is proven.

Potential deliverables:

- Obsidian-compatible wiki conventions and links
- Searchable episode and asset index
- Hermes read-only workspace access, then controlled writes
- Optional Telegram status/research commands
- Optional scheduled topic report

Exit criteria:

- Each integration has a narrow purpose and verification.
- Secrets stay outside Git.
- Workspace access follows least privilege.
- Human approval remains required for publishing and risky actions.

## Deferred until justified

- Vector database or complex RAG
- n8n, LangChain, Qdrant, Kubernetes
- Complex multi-agent systems or custom dashboards
- Automated image/video generation pipeline
- Automatic YouTube publishing
- Local LLM routing and ElevenLabs
