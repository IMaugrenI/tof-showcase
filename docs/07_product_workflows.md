# Product Workflows

This page explains how the public product repos can be used together in practice.

These workflows are explicit and manual.
They do **not** claim hidden automation, a combined runtime, or a merged super-tool.

## First principle

Each product works standalone.
Combination is optional.
Combination should only be used when it gives a clear practical benefit.

## Workflow 1 — Knowledge + Builder

### Use case

You want grounded input before generating a structured output.

### Start repo

Start in `tof_local_knowledge`.

### Handoff

1. search local documents
2. identify citable evidence or grounded findings
3. copy or extract the relevant evidence into the builder workflow
4. use that material as controlled input in `tof_local_builder`

### Expected result

The builder works from visible evidence instead of free-form guessing.

### What not to do

- do not feed generated output back into knowledge as truth
- do not treat builder output as evidence unless it still points back to real source material

## Workflow 2 — Builder + Organizer

### Use case

You already have reviewed builder output and want to structure it into a cleaner dossier or export path.

### Start repo

Start in `tof_local_builder`.

### Handoff

1. produce reviewed output in the builder
2. keep only the material you actually want to preserve
3. move that reviewed material into `local_case_organizer`
4. structure it there through register, timeline, or export flows

### Expected result

Generated work becomes organized, reviewable, and easier to hand off.

### What not to do

- do not use the organizer as a generator
- do not move raw, unreviewed output into structured case material without checking it first

## Workflow 3 — Knowledge + Organizer

### Use case

You want to turn evidence findings into a clearer dossier structure without a generation step.

### Start repo

Start in `tof_local_knowledge`.

### Handoff

1. search and extract grounded findings
2. keep only relevant evidence excerpts
3. move those findings into `local_case_organizer`
4. build register, timeline, or export structure from them

### Expected result

You get a more structured case space with less manual sorting.

### What not to do

- do not pretend that search hits alone are already a finished dossier
- do not collapse provenance during transfer

## Workflow 4 — Full chain

### Chain

`tof_local_knowledge` → `tof_local_builder` → `local_case_organizer`

### Use case

You want grounded material first, then controlled generation, then clean structure.

### Handoff

1. start with grounded findings in knowledge
2. pass selected findings into builder as constrained input
3. review the produced output
4. move the reviewed result into organizer
5. structure it into dossier-ready material

### Expected result

Truth stays grounded first, generation stays controlled second, and structure stays clean last.

### What not to do

- do not skip the review step between builder and organizer
- do not turn the chain into a hidden automatic loop

## Pulse

`tof_container_pulse` is not part of the working chains.

Its role is simple:

- observe host/container state
- help the user see whether the local environment looks healthy
- stay read-only and separate from the operational content flows

## Boundary rules

- no automatic Builder → Knowledge truth feedback
- no Organizer → Builder trigger path
- no Pulse control path
- no full-mesh combinations
- user decides explicitly when to hand material from one product to another
