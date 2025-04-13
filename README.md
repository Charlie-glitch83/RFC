# Recursive Fractal Cosmology (RFC)

**A Unified Symbolic-PDE Framework for Cosmology, Physics, and Consciousness**

This repository contains the core LaTeX source code, simulation schemas, and reproducibility tools for the RFC framework as detailed in **Presentation 23**. RFC models reality through recursive symbolic compression across quantum, cosmological, and cognitive domains, offering predictive simulations backed by real-world data.

---

## Contents

- `Presentation23.tex` — LaTeX source of the full RFC theory document
- `Appendix/` — Modular PDE details and reproducibility appendices
- `SimulationConfigs/` — JSON-based configurations for all RFC modules (A–H)
- `PDE_Kernels/` — Symbolic and numerical PDE code (Wolfram, Julia, etc.)
- `.gitignore` — Recommended exclusion rules for LaTeX, cache, and build files
- `README.md` — You are here

---

## Modules and Simulations

RFC is implemented via a symbolic HPC pipeline with the following modules:

| Module | Domain                     | PDE Field(s)           | Output |
|--------|----------------------------|-------------------------|--------|
| A      | Cosmology (Friedmann)      | `Ψχ`, `Γζ`              | `a(t)`, `H(t)` |
| B      | CP Phase / EDM             | `Θη` (Sine-Gordon)      | Soliton band |
| C      | Ringdown Echoes            | `Ψχ`                    | Echo delay |
| D      | Entropy Collapse           | `ψ_self`, `Ων`          | Stability field |
| E      | Neural Dynamics            | `ϕτ` (fractal PDE)      | EEG `D_f ≈ 2.45` |
| F      | Observer Identity          | `ψ_self`                | Logic bifurcation |
| G      | MCMC Parameter Fit         | All fields              | Unified ε, λ, δ |
| H      | Spin Foam Embedding        | `ΣΛ`                    | Gauge modulations |

---

## Reproducibility Protocol

To reproduce any simulation:

1. Clone the repo
2. Navigate to `SimulationConfigs/` and select a module config (e.g. `friedmann_A.json`)
3. Run using `simulateRFC(...)` via the RFC kernel (Julia, Wolfram, or hybrid setup)
4. Results are written to `/output/` with timestamps and logs

All PDEs, boundary conditions, and parameter settings are listed in `Appendix A` and `Appendix H`.

---

## Citing RFC

If you use or reference this theory, cite it using the DOI:

> Charlie-glitch83. (2025). *Recursive Fractal Cosmology (RFC)*. Zenodo. https://doi.org/10.5281/zenodo.15205532

---

## License

This repository is made available for open research and collaboration under the [MIT License](LICENSE).

---

## Contact

For correspondence, questions, or collaboration proposals:

- **Author:** Allan Edward  
- **Email:** charlieaws@yahoo.com

---

> “Structure, law, identity, and time are not givens—they are recursive outcomes.” — RFC
