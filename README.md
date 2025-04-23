# Recursive Fractal Cosmology (RFC)

**A Unified Symbolic-PDE Framework for Cosmology, Physics, and Consciousness**

This repository contains the core LaTeX source code, simulation schemas, and reproducibility tools for the RFC framework as detailed across **Presentations 24–26**. RFC models reality through recursive symbolic compression across quantum, cosmological, and cognitive domains, offering predictive simulations backed by real-world data.

---

## Contents

- `Presentation24.tex`, `Presentation25.tex`, `Presentation26.tex` — Full RFC theory and expansion documents
- `Appendix/` — Modular PDE details and reproducibility appendices (A–G)
- `SimulationConfigs/` — JSON-based configurations for all RFC modules (A–K)
- `PDE_Kernels/` — Symbolic and numerical PDE code (Wolfram, Julia, etc.)
- `.gitignore` — Recommended exclusion rules for LaTeX, cache, and build files
- `README.md` — You are here

---

## Modules and Simulations

RFC is implemented via a symbolic HPC pipeline with the following modules:

| Module | Domain                          | PDE Field(s)               | Output |
|--------|----------------------------------|-----------------------------|--------|
| A      | Cosmology (Friedmann)           | `Ψχ`, `Γζ`                  | `a(t)`, `H(t)` |
| B      | CP Phase / EDM                  | `Θη` (Sine-Gordon)          | Soliton band |
| C      | Ringdown Echoes                 | `Ψχ`                        | Echo delay |
| D      | Entropy Collapse                | `ψ_self`, `Ων`              | Stability field |
| E      | Neural Dynamics                 | `ϕτ` (fractal PDE)          | EEG `D_f ≈ 2.45` |
| F      | Observer Identity               | `ψ_self`                    | Logic bifurcation |
| G      | MCMC Parameter Fit              | All fields                  | Unified ε, λ, δ |
| H      | Spin Foam Embedding             | `ΣΛ`                        | Gauge modulations |
| I      | Symbolic Mass Field             | `ψ(ν)`                      | Mass spectrum |
| J      | Decoherence Divergence          | `λ_div`, `ψ(ν_i)`           | Divergence metric |
| K      | Collapse–Rebirth Dynamics       | `ψ_m`, `ψ_anti`, `ψ_rebirth` | Entropy spike, rebirth field |

---

## Reproducibility Protocol

To reproduce any simulation:

1. Clone the repo  
2. Navigate to `SimulationConfigs/` and select a module config (e.g. `module_A.json`)  
3. Run using `simulateRFC(...)` via the RFC kernel (Julia, Wolfram, or hybrid setup)  
4. Results are written to `/output/` with timestamps and logs  

All PDEs, boundary conditions, and parameter settings are documented in `Appendix/Appendix.tex` (A–G).

---

[![Launch RFC in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Charlie-glitch83/RFC/HEAD?filepath=notebooks%2FRFC_Simulator.ipynb)

> **Launch RFC Simulation Lab in Your Browser**  
> No installation required. Run symbolic PDEs (Modules A–K) and explore field dynamics interactively.

---

## Citing RFC

If you use or reference RFC, please cite the presentations individually as follows:

- **RFC Presentation 24**:  
  Charlie-glitch83. (2025). *Recursive Fractal Cosmology (RFC): Core Kernel and Cosmological Modules*. Zenodo.  
  [https://doi.org/10.5281/zenodo.15205532](https://doi.org/10.5281/zenodo.15205532)

- **RFC Presentation 25**:  
  Charlie-glitch83. (2025). *Recursive Fractal Cosmology (RFC): Mass Fields, Identity, and Topos Logic*. Zenodo.  
  [https://doi.org/10.5281/zenodo.15234638](https://doi.org/10.5281/zenodo.15234638)

- **RFC Presentation 26**:  
  Charlie-glitch83. (2025). *Recursive Fractal Cosmology (RFC): Collapse-Rebirth and Symbolic Annihilation*. Zenodo.  
  [https://doi.org/10.5281/zenodo.15250393](https://doi.org/10.5281/zenodo.15250393)

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
