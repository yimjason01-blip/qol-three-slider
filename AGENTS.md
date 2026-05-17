# Aleron MD Quality of Life Agent Guide

This repo contains the Aleron MD Quality of Life teaching tool.

## Source of truth order

1. `PROJECT_STATE.md` for current state.
2. `AGENTS.md` for collaboration rules.
3. The current git commit.
4. `handoffs/` for task-specific notes.
5. Existing HTML files.

## Product boundary

This is a companion tool for Aleron MD. It is not the main landing repo.

The primary landing workspace is the sibling repo:

- local sibling: `../meridian-landing`
- landing files: `index.html` and `v2.html`

If a task changes how the tool is introduced, linked, or framed from the landing page, inspect the sibling repo too.

## Canonical files

- `aleron.html`: canonical Quality of Life teaching tool
- `logic.html`: calculator or logic reference page
- `spec.html`: explanatory spec/reference page
- `index.html`: root entry for the GitHub Pages repo

## Writing rules

- No em dashes in user-facing prose.
- Keep standard units explicit where clinical values appear.
- Do not overstate precision. This is a teaching model, not a clinical diagnosis.
- Keep Aleron MD framing aligned with the landing page.

## Codex handoff contract

For every non-trivial task:

1. Read `AGENTS.md` and `PROJECT_STATE.md` first.
2. Check git status before editing.
3. Confirm whether the task also requires the sibling landing repo.
4. Make the smallest coherent change.
5. Search changed HTML/MD files for em dashes.
6. Open the changed page locally when behavior or layout changed.
7. Add a task handoff in `handoffs/` for substantial work.
8. Commit code and handoff together.

## Deployment notes

This is a GitHub Pages static site with no build step.
