# Aircraft Flight Dynamics Simulation — Cessna 172 Class

**4-DOF longitudinal model · state-space representation · MIL-SPEC CAP verified**

📄 [Full Technical One-Pager (PDF)](./flight_dynamics_onepager.pdf)  
🎥 [Demo video](https://youtu.be/YOUR-VIDEO-ID) *(add after Phase 3)*

---

## Summary

Developed a 4-DOF longitudinal flight dynamics simulation using state-space representation (ẋ = Ax + Bu) and small-perturbation theory; built around a V-Model development approach for traceable model verification.

## Key Results

- **Short-period mode**: ωₙ = 5.60 rad/s, ζ = 0.580 — verified against MIL-SPEC CAP requirements
- **Lyapunov stability**: all modes confirmed stable
- **Six-criteria V&V**: validated against NACA/NASA aerodynamic derivatives + classical references (Etkin & Reid, Stengel, Cook)
- **Four elevator input profiles** simulated (step, impulse, doublet, sinusoidal)

## Tools

MATLAB · Simulink · Control System Toolbox

## Methodology
---

📄 [Back to CV](https://github.com/YOUR-USERNAME/YOUR-USERNAME/blob/main/dinesh_cv_general_v3.pdf)  
🔗 [LinkedIn](https://linkedin.com/in/dinesh-natarajan-baaa95206)

1. Linearised state-space model around trim condition
2. Eigenvalue stability analysis (short-period + phugoid modes)
3. Time-domain response benchmarking against classical aerodynamic references
4. Structured V&V report aligned with aerospace validation standards

## Repository structure
