# PyStudio Node Build Core Toolchain

Thin child repository for PyStudio Node.js native build core packages.

The shared build logic, package profile, source adapter policy, apt repository
packaging, and manifest sync all live in:

`vg188/pystudio-termux-builds`

This repository exposes one workflow with a `source` input. Each run selects
exactly one source and calls the reusable orchestrator workflow.
