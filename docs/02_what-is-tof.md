# Technical Architecture — What ToF Means

**ToF** names the technical structuring approach within the wider **ToF Systems** work. It is not synonymous with a Discord bot, a particular chat interface, or a language model.

The central idea is a modular design with clear treatment of processing, authorization, protection, state, and historical records.

## Technical priorities

- Explicit processing stages and responsibilities.
- Boundaries between services and data spaces.
- Governance and protection before consequential actions.
- Separation of live state, retained history, and governed reference material.
- Platform-independent core logic with adapters at the boundaries.

These describe **architecture principles**, not a claim that every detail is implemented by each public repository.

## What the name does not imply

The technical approach is not defined by a single chatbot, LLM wrapper, monolithic bot, or platform-specific implementation. The public tools are independently usable and do not require the private assistant runtime.

## Historical naming: ToF and V’eth

Earlier architecture documents distinguish **ToF (technical structure)** from **V’eth (identity and expression)**. The distinction protects system decisions from being silently influenced by a persona or symbolic presentation.

For today's public orientation, **ToF Systems** is the common project identity. The two older terms remain here only where they explain a meaningful architectural boundary.

[Read about separation of responsibilities](03_layer-separation.md)
