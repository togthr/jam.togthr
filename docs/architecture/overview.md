# Architecture Overview

This overview summarizes the architecture documentation set for Jam Togthr. It is intentionally high-level and defers to specs for authoritative requirements. If any spec text is missing, see the `SOURCE NEEDED` banners in the specs directory.

## Reading Order

1. [Control Plane Spec](../specs/control-plane.md)
2. [Control Plane Session Signaling Spec](../specs/control-plane-session-signaling.md)
3. [SaaS Control Plane Spec](../specs/saas-control-plane.md)
4. [SaaS Personal Agent Extension Spec](../specs/saas-personal-agent-extension.md)
5. [Cloud + Private Agent Streaming Model Spec](../specs/cloud-private-agent-streaming-model.md)
6. [Control Plane Architecture](control-plane.md)
7. [Agent Streaming Architecture](agent-streaming.md)

## Scope

The architecture set covers:

- Control-plane workflows and session signaling boundaries.
- SaaS control-plane responsibilities and extension points for personal agents.
- Cloud/private streaming model interactions.

These summaries avoid implementation details until the underlying specs are populated.

## System Context (Pending Specs)

- **Users:** Musicians and agents collaborating in real time.
- **Surfaces:** Web, desktop, or other clients that integrate with the control plane.
- **Services:** Control-plane services and agent streaming backends.

Further detail belongs in the spec set and will be linked as it becomes available.

## Source-of-Truth Specs

- [control-plane.md](../specs/control-plane.md)
- [control-plane-session-signaling.md](../specs/control-plane-session-signaling.md)
- [saas-control-plane.md](../specs/saas-control-plane.md)
- [saas-personal-agent-extension.md](../specs/saas-personal-agent-extension.md)
- [cloud-private-agent-streaming-model.md](../specs/cloud-private-agent-streaming-model.md)
