# ToF Systems — Architecture Overview

**ToF Systems** brings together independent local-first software tools, AI-assisted development workflows, and architecture work focused on clear responsibilities, controlled data flows, and inspectable results.

This document describes the **architectural ideas** behind the wider development work. For runnable public examples, begin with the [project overview](../README.md).

## Two different concerns in the earlier architecture

Some older ToF documents use the name **ToF / V’eth**. In that architecture, the names refer to different responsibilities:

- **ToF:** technical structure, processing, separation of system responsibilities, and operational controls.
- **V’eth:** identity, mirroring, and expression — how a system presents or expresses itself.

The distinction matters: a conversational identity or presentation style must not gain technical authority simply because it is part of the same assistant. These historical terms are not prerequisites for understanding today's public projects.

## Design principles

- Separate responsibilities rather than mixing all features into one component.
- Make data movement and decisions traceable.
- Keep platform-specific adapters at the edge.
- Distinguish stored references, historical evidence, and current runtime state.
- Apply consent, authorization, and safety checks through explicit mechanisms.
- Keep public descriptions separate from proof of implemented or deployed behavior.

## What this documentation shows

The showcase provides architecture explanations, design principles, and reduced examples. It does **not** publish the complete private system or prove that every design idea has been deployed.

The public tools — [Container Pulse](https://github.com/IMaugrenI/tof_container_pulse), [Local Knowledge](https://github.com/IMaugrenI/tof_local_knowledge), [Local Builder](https://github.com/IMaugrenI/tof_local_builder), and [Local Case Organizer](https://github.com/IMaugrenI/local_case_organizer) — each document their own real capabilities and setup procedures.

[Next: Technical architecture](02_what-is-tof.md) · [Project context](06_project-line.md)
