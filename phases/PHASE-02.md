# PHASE-02 — Lightweight Wiki + Selective Assistance

## Objective

Turn accumulated Markdown into useful channel memory and automate only high-value, low-risk work demonstrated by Phase 1.

## Candidate scope

- Obsidian-compatible links between topics, episodes, assets, and lessons
- Duplicate-topic and asset-reuse checks
- Hermes read-only research/wiki access
- Carefully controlled wiki writes
- Optional Telegram commands such as status, research, asset lookup, and wiki search
- Optional scheduled story report

## Required order

1. Define and validate the Markdown schema.
2. Prove manual search/linking value.
3. Introduce Hermes read-only.
4. Verify permissions and workspace boundaries.
5. Add narrow write actions only after review.
6. Evaluate Telegram last, with user allowlist and least privilege.

## Security boundaries

- Secrets are never stored in the repository or returned through Telegram.
- Agent access is limited to the creator workspace.
- Imported/web content is treated as untrusted.
- External publishing and dangerous commands always require human approval.
- Telegram is a remote controller, not a trust boundary.

## Non-goals

- Direct production-system access
- Arbitrary shell execution through chat
- Fully autonomous content creation and publishing
- Infrastructure added without measured value

## Entry criteria

Phase 1 is complete and its retrospective identifies a problem that this phase can solve.
