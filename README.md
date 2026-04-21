# ToF Showcase

> English is the primary text in this repository. A German clone is available in `README_DE.md`.

Public architecture entry point for the broader ToF / Veth project line.

I use this repo to explain the structure publicly without exposing private runtime details.
It is the best place to understand how the visible repo family fits together.

This repository is public proof of architecture and reading-rule work under AI-assisted build conditions. It is not meant to present classic line-by-line coding proof. It is meant to show how public system framing, separation logic, and controlled explanation can be shaped under human direction.

Read this repo if you want the architecture view of the project, not the runnable product view.

## Product Line

The visible public repos also form a modular product line.

Each tool works standalone.
Some tools can be combined in defined ways.
Not all combinations are supported.

→ See: [`docs/01_product_line.md`](docs/01_product_line.md)

## Start here

- [`docs/01_overview.md`](docs/01_overview.md) — compact overview
- [`docs/01_product_line.md`](docs/01_product_line.md) — standalone tools, valid pairings, and supported chain logic
- [`docs/02_what-is-tof.md`](docs/02_what-is-tof.md) — what ToF is and what it is not
- [`docs/03_layer-separation.md`](docs/03_layer-separation.md) — separation of spaces and layers
- [`docs/05_public-chain.md`](docs/05_public-chain.md) — reduced public chain reading
- [`docs/06_project-line.md`](docs/06_project-line.md) — how the public repo family fits together

## Scale

The public frame shown here sits in front of a private production system built and operated solo — 52 containerized services on a self-hosted Linux server, running since early 2025. What is shown publicly is deliberately reduced. The underlying system is not.

## My role in this repo

My role here is mainly:

1. architecture and separation logic
2. public framing and reading rules
3. scope reduction and review
4. AI-assisted implementation under my direction

## What this repo shows

1. ToF as technical structure, chain logic, governance, safety, runtime, state, and archive thinking
2. Veth as a separate identity, mirror, and expression layer
3. why public explanation must stay separate from private runtime truth
4. how boundaries and reading rules keep the public frame honest
5. how the public tools stay modular instead of collapsing into one monolith

## Why this repo exists

1. to give a traceable public entry point into the broader project line
2. to prevent the project from being read as only a bot surface
3. to show architecture thinking, separation logic, and documentation discipline
4. to keep public and private layers clearly distinct

## What this repo is not

1. not the private production state
2. not the full runtime code
3. not the full compose or infrastructure setup
4. not a hidden internal dump
5. not a merged super-app of all public tools

## For employers

This repo is useful if you want to see how I think about:

1. system boundaries
2. layered architecture
3. public-safe documentation
4. separating explanation from implementation truth
5. modular tool families with constrained combinations

## Related public repos

### Public runnable product line

- [`tof_container_pulse`](https://github.com/IMaugrenI/tof_container_pulse) — lightweight Docker host status viewer with one-glance monitoring and optional multi-host mode
- [`local_case_organizer`](https://github.com/IMaugrenI/local_case_organizer) — local dossier builder for sensitive case files, timelines, and export packages
- [`tof_local_builder`](https://github.com/IMaugrenI/tof_local_builder) — runnable local builder stack
- [`tof_local_knowledge`](https://github.com/IMaugrenI/tof_local_knowledge) — on-prem local knowledge system

### Public architecture and framing line

- [`tof_v7_public_frame`](https://github.com/IMaugrenI/tof-v7-public-frame) — reduced public frame for V7 boundaries

### Public method and transition line

- [`tof-module-ideas`](https://github.com/IMaugrenI/tof-module-ideas) — public-safe candidate space for larger module ideas
- [`tof-legacy-recovery-workbench`](https://github.com/IMaugrenI/tof-legacy-recovery-workbench) — recovery workbench for older mixed material
- [`tof-bridge-planning-method`](https://github.com/IMaugrenI/tof-bridge-planning-method) — bridge-planning layer for structured translation work
