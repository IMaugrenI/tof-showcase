# Technical Guardrails — Scope and Interpretation

The following are **publicly describable design constraints from the earlier ToF system architecture**:

- Docker-first deployment direction
- Postgres-only database direction within that architecture
- explicit service and responsibility boundaries
- fail-closed handling instead of silent bypasses
- audit- and provenance-aware designs
- append-only-oriented traceability where appropriate
- platform-neutral core with external adapters
- language-model output late in the processing model, not as the authority source
- privacy and consent as cross-cutting concerns

## Scope matters

These constraints belong to the **referenced architecture**, not automatically to every standalone public product. For example, a read-only static status generator can be useful without requiring Postgres; the public tool's own README describes its actual dependencies.

Terms such as *fail-closed*, *audit-first*, and *Postgres-only* describe **intended architectural choices**, not independently verified guarantees of the complete private runtime.

## Where to look for evidence

For actual running behavior, dependencies, and supported platforms, use the [product repository](../README.md), its quickstart, checks, and documented limitations. This document intentionally does not reveal private security implementation details.
