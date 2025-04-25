# Recursive Fractal Cosmology (RFC)

**A Unified Symbolic-PDE Framework for Cosmology, Physics, and Consciousness**

This repository contains the core LaTeX source code, simulation schemas, and reproducibility tools for the RFC framework as detailed across **Presentations 24–26**. RFC models reality through recursive symbolic compression across quantum, cosmological, and cognitive domains, offering predictive simulations backed by real-world data.

---

## Contents

- `Presentation24.tex`, `Presentation25.tex`, `Presentation26.tex` — Full RFC theory and expansion documents  
- `Appendix/` — Modular PDE details and reproducibility appendices (A–G)  
- `notebooks/SimulationConfigs.json` — JSON-based configurations for all RFC modules (A–Q)  
- `PDE_Kernels/` — Symbolic and numerical PDE code (Wolfram, Julia, Python)  
- `notebooks/RFC_Simulator.ipynb` — Interactive browser-ready simulation notebook  
- `.gitignore` — Recommended exclusion rules for LaTeX, cache, and build files  
- `README.md` — You are here  

---

## Modules and Simulations

RFC is implemented via a symbolic HPC pipeline with the following modules:

| Module | Domain                              | PDE Field(s)                    | Output                                  |
|--------|-------------------------------------|----------------------------------|-----------------------------------------|
| A      | Cosmology (Friedmann)               | `Ψχ`, `Γζ`                       | `a(t)`, `H(t)`                          |
| B      | CP Phase / EDM                      | `Θη` (Sine-Gordon)               | Soliton band                            |
| C      | Ringdown Echoes                     | `Ψχ`                             | Echo delay                              |
| D      | Entropy Collapse                    | `ψ_self`, `Ων`                   | Stability field                         |
| E      | Neural Dynamics                     | `ϕτ` (fractal PDE)               | EEG `D_f ≈ 2.45`                        |
| F      | Observer Identity                   | `ψ_self`                         | Logic bifurcation                       |
| G      | MCMC Parameter Fit                  | All fields                       | Unified ε, λ, δ                         |
| H      | Spin Foam Embedding                 | `ΣΛ(j)`                          | Gauge modulations                       |
| I      | Symbolic Mass Field                 | `ψ(ν)`                           | Mass spectrum                           |
| J      | Decoherence Divergence              | `λ_div`, `ψ(ν_i)`                | Divergence metric                       |
| K      | Collapse–Rebirth Dynamics           | `ψ_m`, `ψ_anti`, `ψ_rebirth`     | Entropy spike, rebirth field            |
| L      | RFC vs Hidden Variable Models       | `S_RFC`, `J_RFC` vs classical    | Entropy divergence                      |
| M      | Recursive Mass–Energy Emergence     | `ψ`, `dψ/dt`, `E(t)`             | `m(ν)`, `p²`, energy trace              |
| N      | Derivation of Physical Constants    | `α_EM`, `α_G`, `Λ`               | Symbolic constants                      |
| O      | Baryogenesis via Collapse Curvature | `κ_rec`, `T_rec`                 | `η_B/S` (baryon asymmetry)              |
| P      | Dark Matter Entropy Bifurcation     | `ψ_B`, `ψ_D`                     | Missing mass and entropy spike          |
| Q      | Scalar-Induced Decoherence          | `ψ_scalar`, `λ_div`              | Observer divergence under scalar decay  |

---

## Reproducibility Protocol

To reproduce any simulation:

1. **Clone the repo**  
2. Open `notebooks/SimulationConfigs.json` and select a module (e.g. `"module": "N"`)  
3. Launch the notebook: `notebooks/RFC_Simulator.ipynb`  
4. Execute cells and inspect the generated plots or output `.json` files in `/output/`  

All kernel fields and PDE configurations are described in `Appendix/Appendix.tex` and simulation fields are automatically pulled from the JSON structure.

---

[![Launch RFC in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Charlie-glitch83/RFC/HEAD?filepath=notebooks%2FRFC_Simulator.ipynb)

> **Launch RFC Simulation Lab in Your Browser**  
> No installation required. Run symbolic PDEs (Modules A–Q) and explore modal fields, collapse bifurcations, and observer stability without any setup.

---

## Citing RFC

If you use or reference RFC, please cite the core presentations and extended collaborators:

- **RFC Presentation 24**:  
  Charlie-glitch83. (2025). *Recursive Fractal Cosmology (RFC): Core Kernel and Cosmological Modules*. Zenodo.  
  [https://doi.org/10.5281/zenodo.15205532](https://doi.org/10.5281/zenodo.15205532)

- **RFC Presentation 25**:  
  Charlie-glitch83. (2025). *Recursive Fractal Cosmology (RFC): Mass Fields, Identity, and Topos Logic*. Zenodo.  
  [https://doi.org/10.5281/zenodo.15234638](https://doi.org/10.5281/zenodo.15234638)

- **RFC Presentation 26**:  
  Charlie-glitch83. (2025). *Recursive Fractal Cosmology (RFC): Collapse-Rebirth and Symbolic Annihilation*. Zenodo.  
  [https://doi.org/10.5281/zenodo.15250393](https://doi.org/10.5281/zenodo.15250393)

- **Extended Modules** (M–Q) include integration of insights from:  
  - M. Pellis (Unified Physics & Symbolic Constants)  
  - A. M. Sultan (Gravitational Baryogenesis)  
  - BABAR Collaboration (Dark Sector B-meson Analysis)  
  - Y. J. Kim et al. (Scalar Field–Observer Decoherence)

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
