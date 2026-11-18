# Contributing

Thanks for helping out. Speed matters here, so the rules are few and enforced by tooling.

## Workflow

1. **Branch from `main`**: `feat/<short-name>`, `fix/<short-name>`, `chore/<short-name>`.
2. **Keep it small.** Aim for PRs under ~400 changed lines. Split big work behind a feature flag.
3. **Commit with [Conventional Commits](https://www.conventionalcommits.org/)**: `feat: add stripe webhook`, `fix(auth): handle expired session`.
4. **Open a PR** using the template. CI must be green.
5. **Squash‑merge** to `main`. The PR title becomes the commit, so it must also follow Conventional Commits.
6. `main` is always deployable. If something breaks, revert first, investigate second.

## Definition of done

- [ ] Lint, type-check and tests pass locally (`make check` or the repo's equivalent)
- [ ] New behaviour has a test, or the PR says why not
- [ ] No secrets, tokens or `.env` files committed
- [ ] User-facing change noted in `CHANGELOG.md` (or via the PR title for release tooling)
- [ ] README updated if setup or env vars changed

## Code style

- Formatters and linters are the source of truth. Don't argue with them in review.
- Prefer boring, well-known libraries. A micro‑SaaS should not need novel infrastructure.
- Configuration through environment variables, documented in `.env.example`.

## Issues

Use the issue forms (bug, feature, idea). Ideas for new products go in the **💡 Product idea** form.
