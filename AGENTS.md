# AGENTS

## Mission
Build an agent-ready, low-latency collaboration platform for real-time music jams.

## Commands (placeholders)
- `scripts/verify.sh` — project checks (T001)
- `scripts/dev.sh` — local dev (T002)
- `scripts/test.sh` — tests (T003)

## Hard Constraints
- Never commit secrets or credentials.
- Do not access real-time audio or control-plane systems from this repo.
- Real-time or audio-thread code must avoid blocking calls, heap allocations, and logging in the hot path.

## Docs
- [`docs/README.md`](docs/README.md)
- [`docs/agent/STATUS.md`](docs/agent/STATUS.md)
- [`docs/agent/CODEX_CUSTOM_INSTRUCTIONS.md`](docs/agent/CODEX_CUSTOM_INSTRUCTIONS.md)
