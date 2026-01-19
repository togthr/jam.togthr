# Control Plane Architecture

This document summarizes control-plane architecture at a high level. It defers to the specs for definitive requirements and avoids assumptions beyond the available sources.

## Related Specs

- [Control Plane Spec](../specs/control-plane.md)
- [Control Plane Session Signaling Spec](../specs/control-plane-session-signaling.md)
- [SaaS Control Plane Spec](../specs/saas-control-plane.md)

## Responsibilities (Pending Specs)

- Account and workspace metadata orchestration.
- Session lifecycle coordination and signaling.
- Policy, tenancy, and compliance boundaries.

Replace the placeholders above with concrete flows once the specs are available.

## Interfaces (Pending Specs)

- Client-to-control-plane APIs.
- Control-plane to session signaling pathways.
- Integrations with SaaS and extension services.

## Open Questions

- Which control-plane services are authoritative for session state?
- How are tenancy boundaries enforced across SaaS and private deployments?
