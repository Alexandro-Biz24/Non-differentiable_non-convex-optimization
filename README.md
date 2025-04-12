# Stochastic Gradient Descent in Non-Convex Landscapes

**What happens when optimization meets complexity?**  
This project dives into the behavior of **Stochastic Gradient Descent (SGD)** when facing **non-convex functions**, those with multiple local minima, plateaus, or deceptive gradients.

We explore — visually and experimentally — how SGD navigates chaotic loss surfaces, and what this means for real-world financial models.

---

## Why this matters (Finance Case Study)

In modern **quantitative finance**, many models rely on numerical optimization:

- **Portfolio optimization** often involves non-convex cost functions due to transaction costs, nonlinear constraints, or risk measures.
- **Neural networks** for fraud detection or pricing require tuning over non-convex loss surfaces.
- **Risk modeling** using complex objectives (e.g., Value-at-Risk approximations) also leads to non-convex optimization.

Understanding how SGD behaves in such environments helps practitioners:

- Avoid premature convergence
- Adapt learning rates and momentum
- Better interpret irregular model behaviors

---

## What this notebook does

- Generates **non-convex loss functions** (e.g. Rastrigin, Ackley-like surfaces)
- Implements custom **SGD loops** with tunable learning rates
- **Visualizes trajectories** of the optimizer in 2D/3D
- Explores phenomena like:
  - Local minima traps
  - Oscillations near saddle points
  - The effect of noise and batch randomness

---

Click on "SG_non_convexe.ipynb"

## Project Structure

- `SG_non_convexe.ipynb` — Main interactive notebook with all code, plots, and insights.

---

Alexandro Bizeul
