# System Architecture — Public Overview

The earlier ToF architecture describes **separate responsibilities** rather than a single bot process. This document is a deliberately reduced conceptual view, not a complete deployment diagram.

## Processing responsibilities

- **Input and intake:** receive material through controlled entry points.
- **Checking and filtering:** establish basic validity and context.
- **Governance and safety:** apply permissions, protection, and decision boundaries.
- **Analysis and processing:** interpret and work with accepted input.
- **State and retention:** distinguish current state from retained records.
- **Archiving:** preserve historical material and provenance.
- **Output preparation and delivery:** prepare a response without making generated text the system's source of truth.

These are responsibility categories. Their presentation does not assert that each category is one service, one container, or one universally deployed step.

## Keep platform behavior at the edge

External platforms have their own events and message formats. Adapters translate those inputs into internal representations, so platform-specific behavior need not define the system core.

## Evidence and scope

This architecture sketch deliberately omits private runtime paths, operator procedures, service configuration, and security-sensitive details. Use [the public product repositories](../README.md) to inspect working implementations, not this conceptual sketch.

[Processing chain](05_public-chain.md) · [Layer responsibilities](03_layer-separation.md)
