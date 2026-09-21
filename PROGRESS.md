# Progress

## Current state

- Phase: PHASE-01 — Foundation + Manual Production MVP
- Branch: `loop/phase-01-05-episode-research`
- Phase draft pull request: https://github.com/S09Z/hand-drawn-youtube-starter/pull/1
- LOOP-05 draft pull request: Pending creation
- Last completed loop: LOOP-05 — Episode 001 Research
- Current recommended loop: LOOP-06 — Create and approve Episode 001 script
- Loop branch: `loop/phase-01-05-episode-research`
- Next loop branch: `loop/phase-01-06-episode-script`
- Status: LOOP-05 COMPLETE — AWAITING LOOP PR MERGE
- Blockers: None. Do not start LOOP-06 until the approved LOOP-05 pull request is merged and the phase branch is updated.

## LOOP-05 — Episode 001 Research

### Goal

Select a human-approved Episode 001 topic and create a sourced research pack that can hand verified claims into scripting.

### Changes and decisions

- The human approved Margaret Knight and her flat-bottom paper-bag machinery as the Episode 001 topic.
- `episodes/EP001/research.md` records ten stable facts (`F01`–`F10`), six authoritative or primary sources, uncertainty, misconceptions, visual notes, research gaps, and a recommended story focus.
- The research distinguishes Knight's documented machinery from the overbroad claim that she invented all paper bags.
- The Annan conflict is framed as a patent-priority dispute; the script must not turn the priority ruling into an unsupported formal finding of theft.
- Exact invention and patent totals remain generalized because reputable institutional summaries differ.
- The human approved the research pack as sufficient to proceed to scripting.

### Verification completed

- All ten fact IDs use the episode-local `F` plus two digits convention and are unique.
- Primary patent records support the 1871 and 1879 machine claims; Smithsonian and National Archives sources support context and chronology.
- Uncertain claims are separated from verified facts and include explicit script handling.
- EP001 contains only its README and the research artifact; no LOOP-06 script or later artifact was created.
- No generated media, dependencies, automation, credentials, or publishing actions were introduced.
- Placeholder scan for the EP001 folder and `git diff --check` pass.

### Known issues

- Any direct quotation or close paraphrase from the interference proceeding requires inspection of the digitized case file.
- Image licensing and attribution must be checked per asset during later production work.
- The precise patent total should remain “more than twenty” unless a complete patent search is performed.

### Exact next action

After the LOOP-05 draft pull request is approved and merged into `phase/01-manual-production-mvp`, update the local phase branch. Then create `loop/phase-01-06-episode-script` and begin LOOP-06; do not start it beforehand.

## LOOP-04 — Production Template Dry Run

### Goal

Exercise every production template as one connected workflow, expose unclear handoffs or missing fields, and fix only demonstrated template defects before using the system for Episode 001.

### Scope

- Use an explicitly fictional, non-publishable historical scenario under `episodes/DRY-RUN-001/`.
- Populate every template and verify each artifact supplies the next stage's required inputs.
- Do not perform web research, create finished artwork, publish content, or choose Episode 001's real topic.

### Definition of Done

Every template has a populated sample, handoffs are traceable, demonstrated template defects are fixed, the dry-run report records results, verification passes, and the loop state is recorded.

### Verification completed

- Ten dry-run artifacts exercise every template and the full manual handoff chain.
- Research facts F01–F04 map into the script claim table.
- The 442-word narration fits its 420–460 word target and six storyboard scenes cover every beat.
- Storyboard visuals map into the drawing list; OBJ-BELL-001 remains stable through the asset and production records.
- Simulated approvals and unavailable analytics values are explicit rather than blank.
- No production media, real historical claims, external publishing, dependencies, or automation were introduced.
- `git diff --check` passes.

## LOOP-03 — Complete Visual Style

### Goal

Define a repeatable hand-drawn visual language for historical storytelling in Procreate, grounded in human-approved references and practical production limits.

### Scope

- Record 3–5 visual references with explicit adopt and avoid notes.
- Define the core look, visual grammar, accessibility rules, and reuse constraints.
- Do not run the template dry run, choose Episode 001's topic, or start later loops.

### Definition of Done

Every Visual Style field is explicit, 3–5 references are recorded, the rules are drawable and mobile-readable, the human approves the document, verification passes, and the loop state is recorded.

### Verification completed

- Every Visual Style placeholder was replaced with explicitly approved human direction.
- Four repository-local visual references resolve and include adopt and avoid notes.
- Core look, mascot grammar, motion, diagrams, text limits, reuse, and accessibility rules are actionable.
- The palette maintains a muted historical base while reserving bright accents for focus and the mascot.
- Later-loop artifacts remain untouched.

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
- Beginning with LOOP-05, every loop uses its own branch and draft pull request targeting the active phase branch. LOOP-01 through LOOP-04 remain in the existing Phase 1 history and will not be rewritten.

## Known issues

- Templates have passed a fictional dry run but have not yet been tested on a real episode.
- The recurring mascot's final original design will need to be created without copying the approved references.

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

### LOOP-03 — Complete Visual Style

- Completed: 2026-09-21
- Changed: defined the colored-pencil core look, palette, line hierarchy, mascot system, expression and motion grammar, diagram rules, mobile text limits, and four approved visual references.
- Decisions: muted historical scenes use one bright accent; the mascot uses purple, warm gold, and lime green; captions are limited to 8 words and 2 lines; diagram labels are normally 1–3 words.
- Checks: placeholder scan, reference-path validation, required-section review, accessibility and mobile-readability review, scope review, and `git diff --check`.
- Review: no meaningful findings remain for LOOP-03.
- Next action: dry-run the production templates with a small fictional sample; do not select Episode 001's real topic.

### LOOP-04 — Production Template Dry Run

- Completed: 2026-09-21
- Changed: added the fictional DRY-RUN-001 pack and added an explicit approval gate to the storyboard template.
- Checks: artifact presence, fact-ID coverage, narration word count, storyboard scene count, checklist completion, asset-ID continuity, production-media absence, placeholder scan, and `git diff --check`.
- Finding fixed: storyboard continuity checks did not include explicit human approval before drawing and production.
- Decisions: unavailable or simulated values must be written as `N/A` or clearly labeled simulated; they must not be silently left blank or represented as real completion.
- Review: no meaningful findings remain for LOOP-04.
- Next action: present candidate topics for explicit human selection before creating Episode 001's real research pack.
