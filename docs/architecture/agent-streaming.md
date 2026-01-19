# Agent Streaming Architecture

This document summarizes the agent streaming model at a high level. It does not introduce new requirements beyond the specs.

## Related Specs

- [Cloud + Private Agent Streaming Model Spec](../specs/cloud-private-agent-streaming-model.md)
- [SaaS Personal Agent Extension Spec](../specs/saas-personal-agent-extension.md)

## Streaming Topology (Pending Specs)

- Cloud-hosted agents and private agents operate in coordinated sessions.
- Streaming transport, authentication, and session boundaries are defined in the specs.

## Data Flow (Pending Specs)

- Session initiation and authorization.
- Stream negotiation and lifecycle events.
- Observability and auditing hooks.

## Open Questions

- How are cloud and private agents composed within a single session?
- Which components own stream quality-of-service policies?
