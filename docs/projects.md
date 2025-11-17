# 🛰️ SUNCAST Projects

This page provides an evolving overview of key tools and workflows associated with the SUNCAST ecosystem. Many of these live in separate repositories under the [SUNCAST GitHub organization](https://github.com/suncast-org).

---

## Core Tools

### pyGSFIT

- **Purpose:** Microwave spectral fitting and forward modeling of solar emission.
- **Highlights:**
  - Modern Python implementation of legacy spectral fitting workflows.
  - Supports multi-frequency microwave observations.
  - Designed for reproducibility and integration into training environments.

### pyAMPP

- **Purpose:** NLFFF-based magnetic modeling and data-constrained field reconstruction.
- **Highlights:**
  - Bridges observational data and 3D magnetic models.
  - Targets cloud/HPC-ready workflows.
  - Serves as a foundation for tomography extensions.

### pyGSK

- **Purpose:** Generalized Spectral Kurtosis (GSK) toolkit for radio data analysis.
- **Highlights:**
  - Implements the Nita & Gary GSK estimator.
  - Supports both simulation and real-data workflows.
  - Forms the basis for RFI detection and quality control pipelines.

---

## Community Workflows (Examples)

SUNCAST will host and showcase real-data and training workflows, such as:

- **OVRO–LWA Spectral Kurtosis Pipelines** (e.g., SK-based quality control and RFI detection),
- **Tomographic Reconstruction Workflows** that combine EUV, radio, and other diagnostics,
- **Educational Notebooks and Training Modules** for workshops and summer schools.

As these workflows mature, they will be documented and linked from this page.

---

## Contributing New Projects

If you are developing a tool or workflow that aligns with SUNCAST goals, you can:

1. Develop it independently in your personal GitHub space.
2. Reach out to the SUNCAST team when it is ready for broader use.
3. Propose a **repository transfer** into the SUNCAST organization.

See the **[Contributing Guide](contributing.md)** and **[Governance Model](governance.md)** for details on top-down and bottom-up project integration paths.
