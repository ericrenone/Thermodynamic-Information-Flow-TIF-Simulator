# InfoFlowSim — Entropy-Attractor Dynamics Simulator

**InfoFlowSim** is a high-fidelity, real-time simulation framework that models how discrete probability distributions evolve under **competing forces of entropy reduction and attractor alignment**, with stochastic noise. It visualizes convergence dynamics using first-principles information theory, making complex probabilistic systems intuitively understandable.

---

## Features

- **State Simplex Visualization**: Displays the evolving probability distribution across discrete states, with the target attractor overlaid.
- **Information Flow Topology**: Phase plot of **Entropy (H)** vs **KL Divergence**, showing convergence trajectories.
- **Metrics Timeline**: Continuous plotting of entropy and KL divergence over simulation steps.
- **Dynamic Parameter Scheduling**: Smoothly interpolates **entropy decay (α)** and **attractor pull (β)** during the simulation.
- **Stochastic Exploration**: Temperature-based noise ensures probabilistic exploration while maintaining reproducibility.
- **Fully Reproducible**: Random seed management allows consistent, repeatable simulations.

---

## Core 

The system evolves via a **gradient-like update** with multiplicative noise, visualized across three real-time perspectives:

1. **State Simplex** – probability distribution vs target.
2. **Information Flow Topology** – entropy vs KL divergence trajectory.
3. **Metrics Timeline** – time-series tracking of H and KL.


