# ToF Showcase

> English is the primary text in this repository. A German clone is available in `README_DE.md`.

ToF / V’eth is **not a bot** and **not a simple LLM wrapper**.

**ToF** is the technical order space of the system:  
architecture, chain logic, governance, safety, runtime, state, and archive.

**V’eth** is the separate identity, mirror, expression, and symbolic layer.  
It accompanies the expressive side of the system, but does not replace the technical core.

This repository is a **deliberately reduced public surface**.  
It shows selected principles, layer separations, and simplified architectural fragments without exposing the full production state.

## Purpose of this repository

This repository exists to:

- make the core idea of ToF / V’eth visible
- show architectural thinking and system separation in a traceable way
- present selected redacted fragments publicly
- document principles and working style
- give an honest but controlled insight into the project

## What becomes visible here

- what ToF is
- how ToF and V’eth are read as separate layers
- how layers and spaces are kept cleanly separated
- how the public chain reading roughly works
- which technical guardrails support the build
- where the boundary lies between public presentation and internal system

## Structure

### Core overview
- [`docs/01_overview.md`](docs/01_overview.md) – compact overview
- [`docs/02_what-is-tof.md`](docs/02_what-is-tof.md) – what ToF is and what it is not
- [`docs/03_layer-separation.md`](docs/03_layer-separation.md) – separation of spaces and layers

### Architecture and principles
- [`docs/04_architecture-fragments.md`](docs/04_architecture-fragments.md) – simplified architecture fragments
- [`docs/05_public-chain.md`](docs/05_public-chain.md) – reduced public chain reading
- [`docs/06_principles.md`](docs/06_principles.md) – showcase ground principles
- [`docs/07_public-principles.md`](docs/07_public-principles.md) – technical guardrails in public form

### Boundaries and reference spaces
- [`docs/08_canon-boundary.md`](docs/08_canon-boundary.md) – canon is not runtime
- [`docs/09_boundaries.md`](docs/09_boundaries.md) – what stays public and what stays private

### Examples
- [`examples/01_example_flow.md`](examples/01_example_flow.md) – simplified example flow
- [`examples/02_redacted_config_example.md`](examples/02_redacted_config_example.md) – redacted configuration example

## Public core idea

The project follows a clear reading:

- platforms speak at the outside
- inside, the system speaks its own language
- platform logic ends at the edge
- the core remains platform-neutral
- language-model output is not the truth core
- protection, separation, and traceability come before mere response generation

## Important separation line

ToF / V’eth is not presented publicly as an ordinary chat setup.

What matters is:

- **ToF = structure**
- **V’eth = expression / identity**
- **Canon = reference space**
- **Runtime = active technical truth**

These layers may influence one another, but they must not merge without being marked.

## What is deliberately not shown here

This repository is **not** a full production state.

Among the things not shown publicly are:

- full core code
- production compose and infrastructure details
- real secrets, tokens, or keys
- concrete IDs, scopes, or local operating details
- operational security mechanics in detail
- private data, logs, or archive material
- internal special paths and sensitive control logic

## Project context

ToF / V’eth is an independently developed system project.

Its center of gravity is:

- structured technical order
- modular thinking
- clear separation of roles and layers
- protection and governance thinking
- traceable further development
- controlled rather than blind disclosure

This public repository therefore shows only selected fragments — not out of vagueness, but out of system discipline.

## Note

This repository is meant as a **showcase instead of full disclosure**.

Its purpose is to make understandable:

- how the project thinks
- how it separates its layers
- which principles support the build
- why ToF / V’eth should not be read as an ordinary bot or simple chat setup

## Contact

- GitHub profile: [IMaugrenI](https://github.com/IMaugrenI)
- LinkedIn: [Jakob Kessler](https://www.linkedin.com/in/jakob-kessler-595b393b7)
