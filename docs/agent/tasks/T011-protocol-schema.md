# T011: Protocol/Schema Doc

## Objective

Document the wire protocol and schema boundaries needed for real-time collaboration.

## Non-goals

- Implementing serialization code.
- Defining final production API endpoints.
- Locking in versioning beyond documented assumptions.

## Acceptance Criteria

- Protocol message categories and schema fields are listed.
- Versioning approach and compatibility expectations are documented.
- Open questions and assumptions are clearly marked.

## Files to Touch

- `docs/agent/tasks/T011-protocol-schema.md`
- `docs/protocol/` (new or updated protocol doc)
- `docs/agent/BACKLOG.md` (if priority needs updating)

## Verification Steps

- `./scripts/verify.sh`

## Stop Conditions (Ask the User)

- Required protocol details are missing or contradictory.
- Security/privacy constraints need confirmation before documenting fields.
- Any request to finalize API details without approval.
