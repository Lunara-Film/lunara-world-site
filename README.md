# Lunara World Site Repository

This repository preserves earlier combined WordPress source for recovery and
reference. The active Lunara website is maintained in separate repositories,
including [Theme](https://github.com/Lunara-Film/lunara-theme-blocks) and
[Oscars Ledger](https://github.com/Lunara-Film/lunara-plugin-oscars-ledger).
See the current [repository alignment](https://github.com/Lunara-Film/lunara-theme-blocks/blob/main/docs/REPOSITORY-ALIGNMENT.md)
and this repository's [working agreement](AGENTS.md). Existing host connections
for this legacy source have not been verified; do not treat it as the current
website deployment source.

## What is in this repo

- `wordpress/wp-content/themes/lunara-film-premium`
  - Historical Lunara child theme (presentation/editorial layer)
- `wordpress/wp-content/plugins/academy-awards-table-optimized`
  - Historical Oscars plugin (data/query/presentation layer)
- `docs/`
  - Continuity and handoff documents for safe recovery and collaboration

## What is intentionally NOT in this repo

- WordPress core files
- Uploads/media library
- Database dumps
- Local recovery/temp folders
- Release zips and backups

## Why this structure is proper

- Keeps version control focused on custom code only.
- Makes deployments safer (theme/plugin scoped).
- Keeps history readable when multiple agents/people contribute.

## Suggested workflow

1. Create a feature branch for each change.
2. Keep changes within the approved source/documentation scope.
3. Commit with clear messages.
4. Push and open a Pull Request.
5. The integrating agent merges the reviewed, verified PR with an exact-head
   guard after `Lint and Validate` passes. Use the supported squash method;
   do not ask Dalton to perform a routine merge.
6. Record the merged commit. Deployment is a separate authorized action and
   requires confirming the actual host/source before reusing this legacy code.

## Safety rails in this repo

- PR template: `.github/pull_request_template.md`
- CI check: `.github/workflows/lint-and-validate.yml`
- Current merge/deployment boundary: `AGENTS.md`
- Historical deployment reference: `docs/DEPLOY_CHECKLIST.md`

## Protected assets (project rule)

Do not delete or structurally alter:

- Media files
- Written reviews
- Posts
- Oscars database records
