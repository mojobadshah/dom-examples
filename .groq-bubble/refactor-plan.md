# Groq Public Poly Auto-Fork Refactor Plan

- Source repo: `mdn/dom-examples`
- Target repo: `mojobadshah/dom-examples`
- Branch: `groq-poly-refactor-dom-examples-2026-04-25t19-41-44-524z`
- Risk: `low`
- Safe apply mode: `true`

## Important

AI-generated code changes are staged under `groq-bubble-safe-changes/` instead of being written directly to arbitrary repository paths.
This prevents GitHub 409 path conflicts and blocks unsafe writes like `.env`.

## Original Plan

### Refactor Plan

Prefer docs, demo, workflow, or minimal frontend staging changes. Always preserve behavior and do not include secrets.

1. Update `.github/dependabot.yml` to use a different package-ecosystem or adjust the schedule for dependabot.

## Staged AI Changes

- `.github/dependabot.yml` → `groq-bubble-safe-changes/01-github-dependabot-yml.yml`
- `.github/workflows/pr-merge-conflicts.yml` → `groq-bubble-safe-changes/02-github-workflows-pr-merge-conflicts-yml.yml`
- `.github/workflows/pr-merge-conflicts.yml` → `groq-bubble-safe-changes/03-github-workflows-pr-merge-conflicts-yml.yml`
- `.github/workflows/pr-merge-conflicts.yml` → `groq-bubble-safe-changes/04-github-workflows-pr-merge-conflicts-yml.yml`
- `docs/staging/index.html` → `groq-bubble-safe-changes/05-docs-staging-index-html.html`
- `docs/staging/README.md` → `groq-bubble-safe-changes/06-docs-staging-readme-md.md`
- `.prettierrc.json` → `groq-bubble-safe-changes/07-prettierrc-json.json`
- `.github/ISSUE_TEMPLATE/bug.yml` → `groq-bubble-safe-changes/08-github-issue-template-bug-yml.yml`

