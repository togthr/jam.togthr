# Summary

## Checklist
- [ ] `./scripts/verify.sh` run (or not applicable with explanation).
- [ ] Docs updated (or not applicable).
- [ ] Tests added/updated and run (if applicable).
- [ ] No secrets or credentials included.

## Risk Areas
- [ ] Real-time or audio-thread paths touched (confirm no blocking/alloc/logging in hot path).
- [ ] Networking/protocol changes.
- [ ] Security/privacy impact.

## Rollout
Describe rollout/rollback plan or why none is needed.
