# Repository Working Agreement

## Authority and evidence

- Read `README.md`, `docs/README.md`, `report/README.md` and the relevant
  academic source before changing report semantics.
- Accepted Nexa Product, Domain, architecture and design decisions remain the
  semantic authority. This repository projects academic Web evidence and does
  not redefine Product authority.
- Preserve the distinction between planned, designed, implemented, verified,
  accepted and production-ready. Do not turn a report outline into Product or
  implementation acceptance.
- Keep academic claims traceable to versioned report sources. Do not invent
  interviews, screenshots, tests, metrics, sprint completion, deployment or
  export results.

## Repository state

- Inspect the actual branch, worktree, remote metadata and working tree before
  editing.
- Fetch remote metadata before creating new work when permitted; do not merge
  fetched changes into a user's working branch.
- Preserve unrelated local work and use an isolated worktree when the checkout
  is dirty.

## Report quality

- Keep submitted prose polished, professional and neutral.
- Do not expose private rubric analysis, evaluator-directed language, internal
  workflow details, credentials, local paths or temporary placeholders in
  public artifacts.
- Keep report chapters and evidence assets separate from repository governance.
- Preserve relative-link, asset, citation and source integrity.

## Tooling and validation

- The current CI workflow provides a whitespace gate through `git diff --check`.
- Do not claim Markdown linting, PDF export, visual review or academic
  acceptance unless the corresponding command and evidence were actually run.
- Add export or validation tooling only in a separately scoped task; a README
  change must not introduce dependencies or alter report content.

## SCM and artifacts

- Follow the repository's current contribution and release conventions.
- Use Conventional Commits and preserve real authorship and signatures.
- Do not force-push, rewrite shared history, merge automatically, create
  releases or create tags for this governance/documentation change.
- Repository-facing artifacts must remain neutral, professional and free of
  internal orchestration residue.

## Final handoff

Report factual result, files changed, checks actually executed, commit and push
state, remaining risks, open decisions and unverified evidence.
