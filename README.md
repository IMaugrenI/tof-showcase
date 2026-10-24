# ToF Systems — Projects & Architecture

<p align="center">
  <img src="https://raw.githubusercontent.com/IMaugrenI/IMaugrenI/main/assets/banner/ToF_Banner.png" alt="ToF Systems banner" width="100%" />
</p>

**Local-first software, self-hosted AI, and clearly bounded systems.**

This repository is the public guide to the ToF Systems project family. It explains what each public tool does, how the architectural ideas connect, and where to find runnable examples. It is an **overview**, not a product installation or a mirror of any private runtime.

[Deutsch](README_DE.md) · [Start here](START_HERE.md) · [Documentation index](docs/INDEX.md)

## Start with something concrete

| Public project | Role | Practical use |
| --- | --- | --- |
| [Container Pulse](https://github.com/IMaugrenI/tof_container_pulse) | **Observe** | Generate local, read-only dashboards for Docker and host signals. |
| [Local Knowledge](https://github.com/IMaugrenI/tof_local_knowledge) | **Ground** | Index local documents, search evidence, and answer with supporting context. |
| [Local Builder](https://github.com/IMaugrenI/tof_local_builder) | **Generate** | Use local models with controlled source access and separated output. |
| [Local Case Organizer](https://github.com/IMaugrenI/local_case_organizer) | **Structure** | Organize files into registers, timelines, and reviewable export packages. |

Each project has its own README and `START_HERE.md` for supported platforms, current features, and limits.

## One approach, independent tools

**Observe → Ground → Generate → Structure** is a way to explain complementary responsibilities — **not** a claim that all repositories are bundled into one finished application or already automatically connected.

The shared design direction is practical: run locally when possible, separate trusted sources from generated output, make evidence visible, and require explicit authority for consequential actions.

## Architecture and methods

| Reference | Purpose |
| --- | --- |
| [Architecture Reference (V7)](https://github.com/IMaugrenI/tof-v7-public-frame) | A version-tagged public account of service and data boundaries. The V7 label belongs to the project history; visitors do not need to know the internal version sequence. |
| [Module Ideas](https://github.com/IMaugrenI/tof-module-ideas) | Describe and classify larger module candidates before implementation. |
| [Legacy Recovery Workbench](https://github.com/IMaugrenI/tof-legacy-recovery-workbench) | Separate older mixed material into evidence, hypotheses, and review steps. |
| [Bridge Planning Method](https://github.com/IMaugrenI/tof-bridge-planning-method) | Move prepared material into reviewable planning candidates without silently promoting it to running code. |

These are **method and reference repositories**. They are not interchangeable with the runnable product tools.

## Navigate the documentation

- [Start here](START_HERE.md) — short reading path for new visitors.
- [Documentation index](docs/INDEX.md) — overview of public documentation.
- [Project roles](docs/01_product_line.md) — capabilities and useful combinations.
- [Practical workflows](docs/07_product_workflows.md) — public examples with stated boundaries.
- [Project context](docs/06_project-line.md) — how the public work relates to broader private development.

## What this work demonstrates

- Local-first architecture and self-hosted operating practices.
- Clear responsibilities between input, knowledge, generation, and output.
- Human-directed AI implementation with reviewable results.
- Architecture and documentation that distinguish design intent from implemented behavior.
- Public examples that do not require disclosure of private environments.

**Accuracy matters:** a public architecture diagram is not proof of a deployed feature. Each runnable repository is the authority for its own implementation, setup, supported platforms, and maturity. No production readiness or end-to-end integration is implied across the whole project family.

[Back to Jakob Kessler's GitHub profile](https://github.com/IMaugrenI)
