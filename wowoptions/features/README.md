# WowOptions Docs — GitBook Import Pack

15 feature pages, cleaned for GitBook. Each `.md` uses real `##` / `###`
headings so GitBook's "On this page" panel populates automatically.

## Files
- `<feature>.md` — one page per feature. The filename becomes the GitBook URL
  (e.g. `quantity-selector.md` → /quantity-selector), so no numbers in names.
- `SUMMARY.md` — defines page order/nav for GitBook Git Sync.
- `images/<feature>-<context>.png` — screenshots named by section and step
  (e.g. `quantity-selector-step-2.png`), original resolution, with alt text.

## Importing into GitBook
- Bulk (keeps order): use Git Sync and commit this whole folder. GitBook reads
  `SUMMARY.md` for the page order and `images/` for the pictures.
- Per page: page ⋯ menu → Import → Markdown → pick one file.

## Notes
- `conditional-logic.md` matches a page already in your space — skip or replace.
- Three screenshots were low-res in the source doc; re-shoot from your dashboard
  if you want them crisp: `switch-step-1.png`, `pop-up-step-1.png`, `collapse-step-1.png`.
