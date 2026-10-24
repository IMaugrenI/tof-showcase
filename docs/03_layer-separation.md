# Architecture Boundaries — Responsibilities and Data Spaces

A central idea in the earlier ToF architecture is that different responsibilities must not quietly collapse into one another.

## Areas and responsibilities

| Area | Responsibility | Important boundary |
| --- | --- | --- |
| Technical core (ToF) | Processing and operational structure | Not governed by style or persona |
| Identity and expression (historically V’eth) | How the assistant presents and expresses itself | No implicit permission to change system state |
| Runtime | Actual active services and operational state | Not equivalent to plans or documentation |
| Workbench (Werkbank) | Inspecting, separating, and preparing older material | Not automatically released to runtime |
| Archive (Archiv) | Retained history and provenance | Not automatically the current truth |
| Canon (Kanon) | Governed reference material | Not the same as live runtime state |

These are **conceptual boundaries** in the public architecture reference. Their presence in documentation does not establish the deployment status of any implementation.

## Why the separation matters

Archived facts should not silently become current state. Planning candidates must not automatically become executable changes. Expression and identity cannot grant themselves authorization. A technical decision needs explicit sources, authority, and review.

## Public scope

The public repository explains these relationships without exposing private paths, credentials, internal operator details, or full runtime mechanisms.

[Public processing model](05_public-chain.md) · [Reference and identity boundaries](08_canon-boundary.md)
