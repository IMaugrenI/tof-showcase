# Processing Chain — Reduced Architecture Model

This reference shows a **conceptual ordering of responsibilities** from earlier ToF architecture work. It is not a verified map of a running deployment or a specification for every public tool.

## Simplified sequence

1. Input
2. Edge / intake
3. Check
4. Governance / decision
5. Safety / protection
6. Analysis
7. Processing
8. State
9. Retention
10. Archive
11. Vector / coherence space
12. Output preparation
13. Output

The list retains the historical architecture's distinctions. It should not be interpreted as proof of thirteen separate containers, a fixed real-time sequence for all messages, or fully implemented behavior.

## Why the order matters

The intended principle is that incoming information is checked and governed before a system makes decisions or produces answers. Historical records and current state have different roles. An LLM can support later processing or wording, but its output is **not** automatically a trusted source or authorization decision.

## What is not shown

Internal routing rules, operator controls, production addresses, and full security mechanisms remain outside this public summary.

[Architecture overview](04_architecture-fragments.md) · [Technical guardrails](07_public-principles.md)
