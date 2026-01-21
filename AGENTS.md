# Agent Requirements

All agents must follow these rules:

1) Fully test your changes before submitting a PR (run the full suite or all relevant tests).
2) PR titles must be descriptive and follow Conventional Commits-style prefixes:
   - Common: `feat:`, `fix:`, `chore:`, `refactor:`, `docs:`, `test:`, `perf:`
   - Support titles: `fix(docs):`, `fix(benchmarks):`, `fix(cicd):`
3) Commit messages must follow the same Conventional Commits-style prefixes and include a short functional description plus a user-facing value proposition.
4) PR descriptions must include Summary, Rationale, and Details sections.
5) Run relevant Python tests for changes (pytest/unittest or the repo's configured runner).
6) Follow formatting/linting configured in pyproject.toml, setup.cfg, tox.ini, or ruff.toml.
7) Update dependency lockfiles when adding or removing Python dependencies.
8) If the branch you're assigned to work on is from a remote (ie origin/master or upstream/awesome-feature) you must fetch and pull from that remote branch before you begin your work so your local branch is fully up to date. For example, run `git fetch <remote> <branch>` and `git pull --ff-only <remote> <branch>` (or equivalent).

Reference: https://www.conventionalcommits.org/en/v1.0.0/
