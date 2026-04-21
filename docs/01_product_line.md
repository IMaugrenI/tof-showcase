# Public Product Line

This repository is part of a modular local-first product line.

Each tool works standalone.
Some tools can be combined in defined ways to extend capability.
Not all combinations are supported.

> This page explains product roles and valid combinations. For the broader place of these repos inside the private/public project line, see `06_project-line.md`.

---

## Roles

| Role | Repo |
|------|------|
| Observe | tof_container_pulse |
| Structure | local_case_organizer |
| Generate | tof_local_builder |
| Ground | tof_local_knowledge |

---

## Standalone

Each tool can be used independently.

---

## Recommended pairings

- Knowledge + Builder
- Builder + Organizer
- Knowledge + Organizer

---

## Full chain

Knowledge → Builder → Organizer

---

## Special role

`tof_container_pulse` is observe-only.

- no control
- no triggering
- no integration into chains

---

## Not supported

- Organizer → Builder (automatic)
- Builder → Knowledge (feedback loop)
- Pulse controlling other tools
- full mesh combinations

---

## Design rules

- tools remain independent
- no combined runtime
- no hidden integrations
- user decides how to combine tools
