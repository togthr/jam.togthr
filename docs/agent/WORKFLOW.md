# Workflow

## Trunk-based development

- Keep branches short-lived and focused.
- Rebase or merge frequently to stay close to trunk.
- Prefer small, reviewable pull requests that land quickly.

## Definition of Done

- `./scripts/verify.sh` is green (or documented as not applicable).
- Requirements are implemented and reviewed.
- Documentation is updated when behavior or usage changes.

## AGENTS.md layering

- Follow the closest `AGENTS.md` to the file you are changing.
- More-specific `AGENTS.md` files override higher-level ones.
- System and developer instructions always take precedence.
