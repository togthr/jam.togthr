# Codex Home

Set `CODEX_HOME` to point at this directory when running Codex-based tooling:

```bash
export CODEX_HOME="$(pwd)/.codex"
```

## AGENTS Layering
Codex resolves instructions in the following order (deepest scope wins):

1. Repository root `AGENTS.md`
2. Nested `AGENTS.md` files within subdirectories
3. Optional overrides via `AGENTS.override.md` for local, uncommitted changes
