# Contributing

These conventions apply to every Intracodic repository unless the repository has its own `CONTRIBUTING.md`.

## Branches

- `main` is protected and always releasable. No direct pushes.
- Work happens on a branch per change:

  | Prefix | For |
  | --- | --- |
  | `feat/` | new functionality |
  | `fix/` | bug fixes |
  | `docs/` | documentation only |
  | `chore/` | build, dependencies, tooling |

  Example: `feat/order-export`, `fix/login-timeout`.

## Commits

- Summary line in the imperative, at most 72 characters: `Add CSV export for orders`.
- Body (optional) explains **why**, not what the diff already shows.
- One logical change per commit. No secrets, credentials or customer data in the history.

## Pull requests

- One topic per pull request, kept small enough to review in one sitting.
- Fill in the template: what changed, why, and how it was tested.
- At least one approving review before merging.
- Merge with **Squash and merge** unless the history of the branch matters.
- Delete the branch after merging.
