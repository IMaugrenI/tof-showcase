# Design Principles and Public Documentation

These principles describe the **architecture direction** of the ToF Systems development work. They are useful for evaluating designs but are not guarantees about the maturity of every public tool.

## Engineering principles

- Separate responsibilities and interfaces explicitly.
- Prefer modular components over an uninspectable monolith.
- Make the movement of information traceable.
- Treat authorization, privacy, and protection as architecture concerns.
- Distinguish an LLM's generated answer from verified state or accepted evidence.
- Keep current runtime behavior, archived material, and plans clearly labeled.
- Keep operational boundaries visible even when documenting only a reduced model.

## Public documentation principles

- Publish examples and explanations that can be understood without private system access.
- Exclude credentials, real private identifiers, sensitive paths, logs, and operator controls.
- Say whether material is a design, prototype, working tool, or verified runtime evidence.
- Link to the individual product repository for actual commands, capabilities, and limitations.

## Practical interpretation

The public documentation is meant to show *what problem a principle solves*, not only repeat that a system has boundaries. Architecture references establish intentions and distinctions; runnable repositories provide the relevant implementation evidence.

[Projects](../README.md) · [Public disclosure limits](09_boundaries.md)
