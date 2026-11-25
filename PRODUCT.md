# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

static zero-dependency HTML/CSS/JavaScript (served directly from the repository root on GitHub Pages main branch)

## Users

Melvin. Personal second brain and knowledge repository accessed across desktop and mobile devices for rapid thought retrieval, model lookup, and synthesis.

## Product Purpose

Deliver an interactive, client-side digital garden web application that renders the Obsidian vault directly on GitHub Pages without requiring static site generators, build steps, or server-side pipelines.

## Positioning

A zero-build Obsidian web environment: instant search, responsive folder tree navigation, bidirectional wikilink navigation, and an interactive physics-driven node graph running entirely in the browser.

## Operating Context

Obsidian markdown vault tracked in git, hosted on GitHub, and served via GitHub Pages pointing to `/` (root) on `main`.

## Capabilities and Constraints

- Zero external build step: runs as a standalone `index.html` at the vault root.
- Interactive vault file tree mirroring exact directories: `Philosophy & Mind`, `Books & Learning`, `Science & Technology`, `Projects & Work`.
- Real-time markdown parser supporting headings, lists, blockquotes, and `[[Wikilinks]]`.
- Interactive force-directed canvas/SVG graph visualization mapping connections between notes.
- Client-side search indexing note titles, tags, and content.
- Theme support: Dark/Light or calibrated high-legibility Obsidian palette.

## Evidence on Hand

Real markdown files in the repository:
- `_Knowledge Base Index.md`
- `Philosophy & Mind/Janusian Thinking.md`
- `Philosophy & Mind/Survivorship Bias.md`
- `Philosophy & Mind/12 Japanese Wisdoms.md`
- `Philosophy & Mind/The Hawthorne Effect.md`
- `Philosophy & Mind/Metacognition.md`
- `Philosophy & Mind/Maladaptive Daydreaming.md`
- `Philosophy & Mind/Main Character Energy.md`
- `Books & Learning/Can't Hurt Me - David Goggins.md`

## Product Principles

1. Vault Fidelity: Accurately parse and present the user's authentic notes and link relations.
2. Instantaneous Responsiveness: Fast note switching, zero latency searching, smooth graph physics.
3. Impeccable Typography & Craft: Strict typographic contrast, calibrated spacing scale, and keyboard accessibility.
