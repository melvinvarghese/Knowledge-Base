---
title: "Stochastic Differential Equations - Fokker-Planck and Langevin Dynamics"
tags: [mathematics, calculus, stochastic-processes, physics]
related: [[[Stochastic Calculus - Itô's Lemma and Geometric Brownian Motion]], [[Statistical Mechanics - Microcanonical, Canonical, and Grand Canonical Ensembles]]]
created: 2026-11-26
updated: 2026-11-26
---

# Stochastic Differential Equations - Fokker-Planck and Langevin Dynamics

## Overview
Stochastic Differential Equations (SDEs) model dynamical systems subject to continuous thermal fluctuations and random environmental noise.

## Core Mechanics & Foundations
The Langevin Equation: Formulates Newton's second law for a Brownian colloidal particle subject to systematic friction $\gamma$ and random Gaussian thermal white noise $\xi(t)$: $m \frac{dv}{dt} = -\gamma v + \xi(t)$, where $\langle \xi(t) \rangle = 0$ and $\langle \xi(t) \xi(t') \rangle = 2 \gamma k_B T \delta(t - t')$, establishing the Fluctuation-Dissipation Theorem.

## Modern Applications & Advanced Significance
The Fokker-Planck Equation: While Langevin equations describe individual stochastic particle trajectories, the deterministic Fokker-Planck PDE governs the time evolution of the probability density function $P(x, t)$: $\frac{\partial P}{\partial t} = -\frac{\partial}{\partial x} [\mu(x, t) P] + \frac{\partial^2}{\partial x^2} [D(x, t) P]$, balancing drift advection against diffusion spread.

## Real-World Impact & Systems
Generative diffusion models in AI (Score-based generative models), quantitative financial option pricing, biological ion channel kinetics.

## Key Terminology
- **Langevin Equation**: Stochastic differential equation describing the time evolution of a system subject to both deterministic forces and random fluctuating noise.
- **Fokker-Planck Equation**: Partial differential equation describing the time evolution of the probability density function of velocity or position.
- **Fluctuation-Dissipation Theorem**: Fundamental statistical theorem relating microscopic thermal fluctuations to macroscopic frictional resistance.


## References & Further Exploration
[[Stochastic Calculus - Itô's Lemma and Geometric Brownian Motion]], [[Statistical Mechanics - Microcanonical, Canonical, and Grand Canonical Ensembles]]
