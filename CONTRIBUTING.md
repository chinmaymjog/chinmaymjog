# Contributing

Use this repository to maintain profile content, links, and public-facing project references.

## Workflow

1. Create a short-lived branch from `main` using `feature/*`, `bugfix/*`, or `docs/*`.
2. Keep the branch focused on one profile or content improvement.
3. Use Conventional Commits such as `docs: refresh featured projects`.
4. Validate links, assets, and rendered profile content before opening a Pull Request.
5. Open a Pull Request with summary and validation notes.

## Repo-Specific Guidance

- Keep profile content current and factually accurate.
- Prefer focused updates to featured projects, links, or branding assets.
- Check image and external link references after edits.

## Guardrails

- Do not commit directly to `main`.
- Do not commit secrets, tokens, or personal environment files.
- Keep profile content accurate and current.
- Avoid bundling unrelated profile refreshes into one PR.

## Validation

Before opening a Pull Request:

- review the diff for scope
- verify links and assets
- update docs or content references when needed

## Documentation Updates

- Update README when featured repositories, contact links, or profile positioning changes.
- Keep asset references under `docs/assets/` valid.