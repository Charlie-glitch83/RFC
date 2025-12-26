# 02 - Key Equations of Recursive Fractal Cosmology (RFC)

This file contains the core mathematical equations of RFC in both LaTeX (for rendering) and plain text (for easy copy-paste into prompts or code).

## Recursive Kernel (Core Operator)
**LaTeX**  
\[ R_{\delta,\alpha}[f_j(t)] = \sum_{j=1}^{\infty} \frac{f_j(t)}{\delta^j \, e^{-\alpha j t}} \]

**Plain Text**  
R_delta,alpha[f_j(t)] = sum_{j=1 to inf} f_j(t) / (delta^j * exp(-alpha * j * t))  
delta ≈ 4.669 (Feigenbaum constant)  
alpha = damping parameter

## Master PDE (Unifying Equation)
**LaTeX**  
\[ \frac{\partial^2 u}{\partial t^2} - \nabla^2 u + \lambda u^3 = R[f_j(t)] + \sum_i \phi_i(x,t) \]

**Plain Text**  
∂²u/∂t² - ∇²u + λ u³ = R[f_j(t)] + sum ϕ_i(x,t)

## Fractal Measure
**LaTeX**  
\[ \omega(x) = |x|^{D_f - 4} \exp(i \epsilon \Theta(x)) \]  
D_f ≈ 2.5, ε << 1 (CP-violating phase amplitude)

**Plain Text**  
omega(x) = |x|^(D_f - 4) * exp(i ε Θ(x))  
D_f ≈ 2.5

## Observer Identity Attractor PDE
**LaTeX**  
\[ \frac{d^2 \psi_{\text{self}}}{dt^2} = -4 \psi_{\text{self}}^3 + \beta \psi_{\text{self}} - \Psi_\chi(t) - \Omega_\nu(t) \]

**Plain Text**  
d²ψ_self/dt² = -4 ψ_self³ + β ψ_self - Ψ_χ(t) - Ω_ν(t)

## Recursive Entropy
**LaTeX**  
\[ S_{\text{rec}} = -\sum_j p_j \log p_j \qquad p_j = \left(\frac{1}{\delta}\right)^j \]

**Plain Text**  
S_rec = - sum p_j log p_j, where p_j = 1/delta^j

## CP-Phase Soliton (Sine-Gordon)
**LaTeX**  
\[ \square \Theta - \lambda \sin(\Theta) = 0 \]

**Plain Text**  
□ Θ - λ sin(Θ) = 0


These equations form the mathematical backbone of RFC. All modules (A–Q) instantiate the kernel with domain-specific f_j(t) modes.
