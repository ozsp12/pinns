# Physics-Informed Neural Networks (PINNs) for Newtonian Systems

This repository demonstrates how to implement **Physics-Informed Neural Networks (PINNs)** to solve problems governed by **Newtonian mechanics**, without relying on large datasets.  
Instead, the neural network learns by minimizing both **physics residuals** (from the governing equations) and **initial/boundary condition losses**. The example problem here is the **nonlinear pendulum**:

$$
\ddot{\theta}(t) + \frac{g}{L} \sin(\theta(t) = 0,
$$
with initial conditions:
$$
\theta(0) = \theta_0, \quad \dot{\theta}(0) = \omega_0.
$$

---

## Features

- Minimal **functional** code structure (no heavy frameworks, just PyTorch).
- **Reusable functions** for:
  - Network construction
  - Automatic differentiation for time derivatives
  - Physics and initial condition loss calculation
  - Model training (Adam + optional LBFGS)
  - Sampling to Pandas DataFrames
  - Plotting results
- Fully documented example: **Nonlinear Pendulum**.
- Extensible to other **Newtonian ODEs/PDEs** by swapping the `residual_fn` and ICs.

---

# References

[1] M. Raissi, P. Perdikaris, G.E. Karniadakis,
Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations,
Journal of Computational Physics, Volume 378, 2019, Pages 686-707, ISSN 0021-9991, https://doi.org/10.1016/j.jcp.2018.10.045.  
[2] H. Goldstein, C. Poole, J. Safko, Classical Mechanics, 3rd ed., Addison-Wesley (2002).  
[3] J.B. Marion, S.T. Thornton, Classical Dynamics of Particles and Systems, 5th ed., Brooks/Cole (2003), Ch. 7.

# Social Media
🌐 Webpage: https://ozsp12.github.io/  
✅ GitHub: https://github.com/ozsp12  
🧪 ResearchGate: https://www.researchgate.net/profile/Osvaldo-Santos-Pereira  
🔬 Google Scholar: https://scholar.google.com/citations?user=HIZp0X8AAAAJ&hl=en  
🧾 ORCID: https://orcid.org/0000-0003-2231-517X  
💼 LinkedIn: https://www.linkedin.com/in/ozsp12  
🧡 Patreon: https://www.patreon.com/ozsp12  
✍️ Medium: https://medium.com/@ozsp12  
𝕏  X (Twitter): https://x.com/ozsp12  
📱 TikTok: https://www.tiktok.com/@ozsp12  
📸 Instagram: https://www.instagram.com/ozsp12/  
▶️ YouTube: https://www.youtube.com/@ozlsp12  
