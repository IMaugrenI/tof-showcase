# Documentation Index

This page is the compact public entry map for the `tof-showcase` documentation.

The goal is orientation, not full internal disclosure. Start here when you want to understand what the public repo family shows, what each document is for, and where to go next.

## Fast path

1. [`01_overview.md`](01_overview.md) — broad public overview of ToF / V’eth
2. [`01_product_line.md`](01_product_line.md) — public product roles and valid combinations
3. [`07_product_workflows.md`](07_product_workflows.md) — explicit manual workflows between product repos
4. [`06_project-line.md`](06_project-line.md) — how the public repos relate to the larger private project line
5. [`05_public-chain.md`](05_public-chain.md) — reduced public reading of the system chain

## Architecture reading

- [`01_overview.md`](01_overview.md) — the public starting frame
- [`02_what-is-tof.md`](02_what-is-tof.md) — what ToF is and what it is not
- [`03_layer-separation.md`](03_layer-separation.md) — separation between ToF, V’eth, runtime, workbench, archive, canon, and public surface
- [`05_public-chain.md`](05_public-chain.md) — simplified processing chain, with LLM/output late in the path
- [`06_project-line.md`](06_project-line.md) — public slices versus the larger private ToF / V’eth line

## Product-line reading

- [`01_product_line.md`](01_product_line.md) — Observe / Ground / Generate / Structure roles
- [`07_product_workflows.md`](07_product_workflows.md) — valid manual handoffs and boundary rules

## Public repositories

### Product line

- [`tof_container_pulse`](https://github.com/IMaugrenI/tof_container_pulse) — Observe: local Docker host status at a glance
- [`tof_local_knowledge`](https://github.com/IMaugrenI/tof_local_knowledge) — Ground: local document indexing, evidence search, grounded answers
- [`tof_local_builder`](https://github.com/IMaugrenI/tof_local_builder) — Generate: controlled local AI builder with read-only source and sandboxed output
- [`local_case_organizer`](https://github.com/IMaugrenI/local_case_organizer) — Structure: local dossier building, timelines, and export packages

### Architecture / framing

- [`tof-v7-public-frame`](https://github.com/IMaugrenI/tof-v7-public-frame) — tighter public boundary reading for V7

### Method / transition

- [`tof-legacy-recovery-workbench`](https://github.com/IMaugrenI/tof-legacy-recovery-workbench) — recovery discipline for older mixed material
- [`tof-bridge-planning-method`](https://github.com/IMaugrenI/tof-bridge-planning-method) — structured bridge from prepared blocks into candidates
- [`tof-module-ideas`](https://github.com/IMaugrenI/tof-module-ideas) — public-safe space for module candidates before runtime

## Boundary notes

This documentation index does not claim that the public repositories expose the full private system.

The intended reading is deliberately bounded:

- public repos are safe slices, not the whole runtime
- product repos stay standalone
- workflows are explicit and manual
- there is no hidden combined runtime
- the showcase explains structure without exposing private operational details

## Recommended next click

For product behavior, start with [`01_product_line.md`](01_product_line.md).

For system context, start with [`06_project-line.md`](06_project-line.md).

For the strictest public boundary frame, go to [`tof-v7-public-frame`](https://github.com/IMaugrenI/tof-v7-public-frame).
