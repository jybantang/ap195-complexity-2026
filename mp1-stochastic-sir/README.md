# MP1: Tipping Points and Stochastic Dynamics
[Main](../README.md) | [Next](./)

This machine problem covers an introduction to basic ODE dynamics and their stochastic versions.
Also includes the use of ODE solver packages as stable implementations of known numerical methods.

## 🎯 Objective
Demonstrate how demographic noise alters macroscopic tipping thresholds and triggers 
premature extinction in finite-population epidemic dynamics.

## 📊 Key Results (Your Grading Rubric)

### 😎 Basic KRs (≤ 80%)
- [ ] **KR1 (Execution):** Successfully instantiate the Julia environment (`Project.toml`).
Report how the dynmical system behaves based on its deterministic ODE model for sub-critical ($R_0 < 1$) and super-critical ($R_0 > 1$) regimes.
- [ ] **KR2 (Modification):** Modify the provided codebase to introduce a stochastic noise term ($\sigma \ge 0.15$) and run 50 stochastic trajectories.
- [ ] **KR3 (Basic report):** Submitted two files: (1) PDF export as report of the jupyter file/s containing cells with outputs, and (2) file of the zipped folder containing the notebook and the codes (except the PDF).

### 🫡 Advanced KRs (up to +20%)
- [ ] **KR4 (Quantitative Sweep):** Compute and plot the extinction probability $P_{\text{extinct}}$ as a function of noise magnitude $\sigma \in [0.0, 0.5]$ across at least 200 Monte Carlo runs.
- [ ] **KR5 (Physical Analysis):** Identify and document the critical noise floor $\sigma_c$ where deterministic persistence collapses into complete fade-out.
- [ ] **KR6 (Advanced report)** Submitted additional two files: (1) PDF export as report of the jupyter file/s containing cells with outputs, and (2) file of the zipped folder containing the notebook and the codes (except the PDF).