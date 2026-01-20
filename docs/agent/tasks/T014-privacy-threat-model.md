# T014: Privacy Threat Model + Key Management ADR

## Objective

Document security/privacy threats and create a key management ADR for the platform.

## Non-goals

- Implementing security controls.
- Conducting penetration tests.
- Issuing or rotating real credentials.

## Acceptance Criteria

- Threat model lists assets, actors, and key risks.
- Mitigations and open questions are documented.
- Key management ADR captures decisions and alternatives.

## Files to Touch

- `docs/agent/tasks/T014-privacy-threat-model.md`
- `docs/security/` (new or updated threat model and ADR)
- `docs/agent/BACKLOG.md` (if priority needs updating)

## Verification Steps

- `./scripts/verify.sh`

## Stop Conditions (Ask the User)

- Missing security requirements or compliance constraints.
- Any request to access or manage real keys or credentials.
- Conflicts between privacy requirements and product goals.
