# Public Documentation and Private-System Boundaries

**ToF Systems publishes both runnable tools and architecture references.** The two must not be confused: public code can be inspected directly, while private runtime behavior is not established by a public architecture document.

## What this showcase may present

- High-level architecture and responsibility models.
- Public technical principles and reduced processing examples.
- Links to source code, demos, and checks **in the separate public product repositories**.
- Historical terminology where it is needed to explain architectural decisions.
- The scope and limitations of the public project family.

## What remains outside this showcase

- Complete private-system source and production infrastructure.
- Sensitive Compose or runtime configuration, host paths, and network details.
- Credentials, private IDs, secrets, raw logs, and personal data.
- Private security controls, operator access details, and unapproved internal evidence.

## Reading rule

**Design intent is not deployment evidence.** A public example should state whether it illustrates a concept, shows a working public tool, or is supported by a specific runtime check. The individual repository remains the source for its real features and dependencies.

The goal is a useful, understandable public explanation — not excessive secrecy, and not the disclosure of sensitive private operations.

[Project family](../README.md)
