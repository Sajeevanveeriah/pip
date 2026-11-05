# pip handoff

Maintain this account's fork of the Python package installer.

## Work at 5 November 2026

Source baseline: [main at 6154f119](https://github.com/Sajeevanveeriah/pip/commit/6154f1191dcc7c4bc32f69e4ad10602a1de4d098). Use the linked revision to distinguish these changes from later work.

- refactor: Use Requirement directly for preparer normalization (#14279) ([6154f119](https://github.com/Sajeevanveeriah/pip/commit/6154f1191dcc7c4bc32f69e4ad10602a1de4d098), 24 Aug 2026).
- test: Pin default git branch to master (#14263) ([6d309205](https://github.com/Sajeevanveeriah/pip/commit/6d309205789d368b2749d93fd6193d584811efd5), 21 Aug 2026).

## Resume here

Keep fork maintenance on this repository. Read AI_POLICY.md before considering a separate upstream contribution. Preserve vendored code and test fixture READMEs.

GitHub showed no open pull requests or issues at this revision. Check the [work queue](https://github.com/Sajeevanveeriah/pip/pulls) and any local changes before choosing a task.

## Files and checks

[README.rst](README.rst), [AI_POLICY.md](AI_POLICY.md), [docs/html/getting-started.md](docs/html/getting-started.md).

Start with [.github/workflows/ci.yml](.github/workflows/ci.yml) for hosted check definitions. Confirm the run belongs to the commit under review.

GitHub returned no check results for this source revision. Runtime verification is unconfirmed in this snapshot.

## Next handoff

When pausing, replace the dated snapshot with the active branch or revision, what changed, the checks actually run and their results, and the first unfinished action. Record any blocker or decision the next person needs. Keep private data and credentials out of this file.
