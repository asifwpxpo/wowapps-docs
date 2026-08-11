# WowOptions Docs — GitBook Import Pack

15 feature pages, cleaned for GitBook. Each `.md` uses real `##` / `###`
headings so GitBook's "On this page" panel populates automatically (like your
Analytics page). All 62 screenshots were extracted from the source file into
`images/` and referenced with relative paths.

## Files
- `NN-<slug>.md` — one page per feature, in order.
- `images/imageN.png` — screenshots referenced by the pages.

## Importing into GitBook
Option A — per page: open a page, ⋯ menu → Import → Markdown, pick one file.
Option B — bulk: use GitBook's Git Sync, commit this folder, and let it map
files to pages. Keep `images/` next to the `.md` files so links resolve.

## Note
`04-conditional-logic.md` matches a page you already have in your space —
skip it or use it to replace the existing one, your call.
