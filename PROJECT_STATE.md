# Aleron MD Quality of Life Project State

Last updated: 2026-05-17 07:10 PDT

## Current repo

- Repo: `qol-three-slider`
- Remote: `https://github.com/yimjason01-blip/qol-three-slider.git`
- Branch: `main`
- Current HEAD: `d53bee7` (`Vitality gradient: green->yellow-green->tan->mauve`)
- Deploy target: GitHub Pages static site

## Current product state

This repo hosts the Aleron MD Quality of Life teaching tool.

The current canonical tool file is `aleron.html`.

The tool is linked from the Aleron MD landing workspace in the sibling repo `../meridian-landing`.

## Important files

- `aleron.html`: canonical Quality of Life tool
- `index.html`: root entry for the GitHub Pages repo
- `logic.html`: logic/calculator reference
- `spec.html`: model/spec reference
- `.nojekyll`: GitHub Pages behavior marker
- `handoffs/`: task handoffs for Codex, Hermes, or other agents

## Collaboration state

This repo is now prepared for Codex-style collaboration through:

- `AGENTS.md`
- `PROJECT_STATE.md`
- `handoffs/README.md`

The repo itself is the shared context boundary. Do not rely on chat memory as the source of truth.

## Open questions

- Whether this tool should remain a separate GitHub Pages repo or be moved under the landing repo.
- Whether `index.html` should redirect to or duplicate `aleron.html`.

## Verification baseline

No build step is required for the current static site.

Before declaring changes done:

1. Search changed files for em dashes.
2. Verify links and asset paths.
3. Open the changed HTML locally or on GitHub Pages.
4. If model logic changed, verify example outputs before claiming correctness.
