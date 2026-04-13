# AGENTS.md

## Repo Snapshot
- Repository: `jtgsystems/the-dainer-coming-soon`
- Default branch: `main`
- Visibility: `public`
- Summary: Public deployment repo for The Dainer Coming Soon page
- Detected stack: static site

## Read First
- `README.md`

## Key Paths
- `assets/`

## Working Rules
- Keep changes focused on the task and match the existing file layout and naming patterns.
- Update tests and docs when behavior changes or public interfaces move.
- Do not commit secrets, credentials, ad-hoc exports, or large generated artifacts unless the repository already tracks them intentionally.
- Prefer the existing automation and CI workflow over one-off commands when both paths exist.

## Verified Commands
- No reliable build or test command was detected from the repo root manifests.
- Check the files in `Read First` and `.github/workflows/` before changing code or release logic.

## Change Checklist
- Run the relevant tests or static checks for the files you changed before finishing.
- Keep human-facing docs aligned with behavior changes.
- If the repo has specialized areas later, add nested `AGENTS.md` files close to that code instead of overloading the root file.

## Notes
- No build tool was detected at the repo root; treat this like a static site unless repo docs say otherwise.

This file should stay short, specific, and current. Update it whenever the repo's real setup or verification steps change.
