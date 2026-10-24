# Working agreement — Lunara World legacy source

Effective 2026-10-17, by Dalton's explicit instruction. This is a legacy combined
WordPress theme/plugin source and recovery repository. The active website uses
the separate [Theme](https://github.com/Lunara-Film/lunara-theme-blocks) and
[Ledger](https://github.com/Lunara-Film/lunara-plugin-oscars-ledger) repositories.
Host connections for this legacy repository remain unverified.

## Dalton's confirmation — effective 2026-10-23

Dalton's confirmation of a website implementation task (for example "yes",
"go ahead", "do it" or "begin/create it") authorizes the requested work through
task-branch commits, PRs, passing checks, agent merge, manual deployment and
live verification. Do not ask for a second deployment confirmation or require
a new approval naming the final version. Reuse the confirmation in the current
conversation; instructions to hold, prepare only, leave a draft, or not deploy
take precedence. Ask only about a real missing decision, access, changed
destination or work beyond that confirmed scope.

Keep branch protections, required CI and exact-head PR merges. Manual
deployment means the agent uses the existing host action; it does not mean
Dalton must click it. Auto-deploy stays off unless he specifically changes it.
A confirmation never makes a merge evidence of deployment: verify and report
both states separately.

## Agent merge authority

Agents have standing permission to commit, push, open/update PRs and merge
completed, verified work within Dalton's approved task. Do not require Dalton
to click Merge or reconfirm a routine merge. An explicit instruction to hold a
particular PR takes precedence. Follow the shared
[Lunara merge policy](https://github.com/Lunara-Film/lunara-theme-blocks/blob/main/docs/AGENT-MERGE-POLICY.md).

- Branch from current `main`; never commit directly to main.
- Review the complete diff, identify the exact repository/base/PR/head SHA,
  and preserve unrelated drafts and unfinished work.
- Run relevant verification and wait for applicable CI on the final candidate.
  The protected main requires up-to-date `Lint and Validate`; resolve review
  threads and respect all current branch protections.
- This repository currently permits squash merging only. Use the PR and an
  exact-head guard with that method. Never use an administrator bypass, disable
  protections, weaken checks or force push. Verify the merged commit and main
  CI; do not merge branches back and forth to change ahead/behind counts.
- Record the result in the shared Theme `docs/SESSION-LOG.md`; preserve history.

## Recovery and deployment boundary

Keep media, written reviews, posts, Oscars records and recovery evidence intact.
Historical deployment checklists and March handoffs are not current operational
authority. Follow the active Theme agreement for current website work.

Adopting this merge policy does not reactivate this repository as a production
release source. Confirm the intended host, connection and destination before
any future runtime release. Reuse Dalton's confirmation of that scoped
release rather than asking for a second version-specific approval.
Documentation-only changes need no live deployment or smoke test.

When resuming an old branch, read the current default-branch agreement.
Feature/editorial decisions and credentials remain separate from merge authority.
