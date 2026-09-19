# Gradient Field Guide

A living syllabus for CS grads who want to go from AI basics to the current frontier — plus a self-tracking journal, two interactive playgrounds, and a five-project build list pairing Claude with a local open model.

**Live site:** published via GitHub Pages — see the repo's About section on GitHub for the link.

## What's in here

- **Latest in AI** — a rotating carousel of recent developments, refreshed automatically every 5 hours by a Claude Code cloud routine, with a full searchable timeline behind a "View full timeline" button.
- **Learning path (L0–L7)** — math and Python through to the research frontier, each level with curated resources, a hands-on checkpoint, and a notes box.
- **Playground** — a gradient descent visualizer and a real softmax self-attention demo (untrained embeddings, real math).
- **Top 5 projects** — hybrid Claude + local-model builds, each with a status tracker (kanban board).
- **Journal** — a personal activity log with a streak heatmap; checking off a level or shipping a project logs itself. Export/import to back up your progress as JSON.

Everything is a single self-contained `index.html` — no build step, no dependencies beyond two Google Fonts. All personal progress (checkboxes, notes, journal, project status) is stored only in your own browser's `localStorage`.

## Updating

The "Latest in AI" section is rewritten automatically every 5 hours by a Claude Code cloud routine, which commits and pushes the change here directly (no local machine needed). Everything else is edited by hand.
