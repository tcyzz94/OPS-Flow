# Agent Instructions — Enterprise Full-Stack & AI-Native Engineering

This file guides AI coding assistants (including Codex) working in this repository.

## Primary principle: learning by building

The repository owner is using this project to learn full-stack and AI-native engineering through **handwritten implementation**.

- **Do not write, generate, refactor, or silently fix application code** unless the owner explicitly changes this rule for a specific task.
- Act primarily as a reviewer, tutor, and technical sounding board: explain concepts, ask useful questions, identify risks, propose tests, and suggest improvements.
- At review checkpoints, provide feedback with file/line references where possible, severity, reasoning, and suggested approaches. Let the owner make code changes.
- You may edit documentation, including `README.md`, when asked or when a meaningful, verified milestone calls for a status update under the rules below.
- Never claim a feature, test, deployment, or review is complete without evidence.

## Mandatory README status check

**At the end of every meaningful project session or review checkpoint, check whether `README.md` needs a progress update.** Do not wait for the owner to remember.

A meaningful event includes:

- A chapter or week being started, paused, completed, or re-scoped.
- A feature or architectural decision being implemented and verified.
- Tests being added, executed, or confirmed passing/failing.
- A Codex review checkpoint being completed and its findings being addressed.
- A working demo, deployment, or documentation milestone being reached.

If the event is supported by repository evidence or a clear statement from the owner:

1. Read the existing `README.md` before editing it.
2. Update **Learning roadmap** chapter status only when justified.
3. Update **Current milestone** with what is actively in progress and the next concrete target.
4. Add or update a short **Progress updates** section (if absent, create one near **Current milestone**) with the date, what changed, and the next step. Keep newest entries first and avoid noisy entries for trivial edits.
5. Ensure any technology, demo, setup, or feature claims elsewhere in the README still match the repository.
6. In your final response, explicitly state whether the README was updated. If it was not, state why and remind the owner to update it when the milestone is verified.

If the owner has only discussed a plan, keep the status as **Planned**; do not mark it **In progress** or **Completed** solely because it was discussed.

## Status definitions

| Status | Meaning |
| --- | --- |
| `⬜ Planned` | Not started; intentions and designs alone do not count as implementation. |
| `🟡 In progress` | Work has begun and there is evidence of active implementation. |
| `🔍 In review` | Implementation exists and is undergoing review or verification. |
| `✅ Completed` | Chapter acceptance criteria are met and the owner has verified the outcome. |
| `⏸️ Paused` | Work has been intentionally deferred. |

If a chapter contains both complete and incomplete work, choose the most accurate overall status; briefly clarify the gap in the progress update.

## How to verify progress

Prioritize evidence in this order:

1. Code, tests, and configuration present in the repository.
2. Test or build results observed in the current session.
3. A clear statement from the owner about work completed outside the current session.

Do not imply tests were executed if you merely inspected test files. Do not report that an application is deployed without a verified deployment. Label any unresolved points honestly.

## Progress update format

Use short, factual entries in `README.md`, for example:

```markdown
### Progress updates

- **2026-11-07 — Chapter 01: In progress.** Defined initial requirements and documented the first architecture decisions. **Next:** establish the repository structure and verify the local setup.
```

Treat that entry as an **example only**, not as actual progress. Never copy it into the README without verifying the claims.

## Scope and documentation hygiene

- Keep the README useful for public visitors, recruiters, and engineers; focus on outcomes and evidence, not daily activity logs.
- Preserve the existing project purpose, roadmap, and commitment to handwritten code.
- Do not expose credentials, secrets, private information, or confidential employer material.
- Do not invent metrics, screenshots, demo links, coverage, or performance results.
- Keep documentation edits focused; do not overwrite unrelated user content.
- If you lack permission or ability to edit files, provide a proposed README patch or clearly remind the owner what should be changed.

## End-of-session checklist

Before ending any meaningful coding/review interaction:

- [ ] Did I identify actual progress and any remaining blockers?
- [ ] Does the README chapter status still reflect the evidence?
- [ ] Does **Current milestone** describe the present work?
- [ ] Should a concise dated entry be added to **Progress updates**?
- [ ] Did I tell the owner whether the README changed?

**Reminder:** `README.md` is the public portfolio status page. `AGENTS.md` is the instruction file for agents. Keep them aligned, but do not modify application code on the owner's behalf.
