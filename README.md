# EvolutionPad 🧬

A local, single-file notepad with built-in **version control style history** — write, commit snapshots, and branch off into new variants of your text, visualized as a family tree.

No installs, no server, no accounts. Just open `index.html` in your browser.

## Features

- **Plain-text editor** with word/character count and optional line numbers.
- **Commits** — save named snapshots of your writing at any point, with an optional description and add/remove line stats.
- **Variants ("Evolve")** — branch off from your current draft (or any past commit) to explore a different direction, without losing the original. Each variant gets its own independent, linear commit history.
- **Visual evolution tree** — an SVG family tree of all your variants, color-coded, showing how each one branched from another.
- **Multiple projects** — manage several independent notepads/trees, switch between them, rename, or delete.
- **Read-only history view** — click any past commit to view it, then evolve a new variant from that exact point or delete it.
- **Import / Export** — save your project (including full history) as a JSON file, or load one back in.
- **Persistent** — everything is saved automatically to your browser's `localStorage`.

## Usage

1. Download `index.html`.
2. Open it in any modern browser (Chrome, Edge, Firefox).
3. Start writing. Use **+ Commit** to save a snapshot, and **🌿 New Variant** to branch off and explore a new direction.

## Tech

A single static HTML file using React 18, Babel Standalone, and vanilla CSS — no build step, no dependencies to install.

## Notes

- Data is stored in your browser's `localStorage`, scoped to wherever `index.html` is opened from. Use Export regularly to back up important work.
