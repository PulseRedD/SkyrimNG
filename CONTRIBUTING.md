# Contribution and Change-Control Policy

## Absolute rule: no direct changes to `main`

**Every change must be committed to a non-main branch and submitted through a pull request targeting `main`. Zero exceptions.** This includes documentation, automation, emergency fixes, and all AI-assisted work. Do not merge PRs without explicit project-owner approval. Never force-push or rewrite `main` history.

## Required workflow
1. Read `PROJECT_STATE.md`, `sessions/LATEST_HANDOFF.md`, and applicable directory READMEs before work.
2. Create a purpose-specific branch from `main` (for example `docs/compatibility-taxonomy`).
3. Make scoped commits with descriptive messages (`docs(separators): document priority groups and naming rules`).
4. Open a PR with motivation, changed directories, verification, risks, and links to decisions/issues.
5. Wait for owner review and approval. Do not self-merge.
6. Update project state and handoff through the same PR when appropriate.

## AI agent guardrails
- Treat the repository as authoritative; never replace entire files or directories based only on chat memory.
- Inspect current files and the proposed diff before editing.
- Make minimal targeted changes; preserve unrelated content.
- No bulk rewrites, deletion, force-push, or branch-protection changes without explicit approval.
- If instructions conflict, stop and ask rather than changing `main`.

## GitHub enforcement
Configure a ruleset/branch protection for `main`: require PR before merging, require at least one approval where supported, block force pushes and deletions, restrict bypass permissions, and enable relevant status checks when available. Ruleset activation must be independently verified; this document alone does not enforce access controls.
