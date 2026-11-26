---
title: "Calculus of Variations - Euler-Lagrange Equations and Action Principle"
tags: [mathematics, calculus, classical-mechanics]
related: [[[Classical Mechanics - Newtonian, Lagrangian, and Hamiltonian Dynamics]], [[Differential Geometry - Curvature and Tensors]]]
created: 2026-11-26
updated: 2026-11-26
---

# Calculus of Variations - Euler-Lagrange Equations and Action Principle

## Overview
The Calculus of Variations seeks extrema (minima and maxima) of functionals—mappings from spaces of functions to real numbers—generalizing ordinary differential calculus.

## Core Mechanics & Foundations
Euler-Lagrange Equation Derivation: For a functional $J[y] = \int_{x_1}^{x_2} L(x, y(x), y'(x)) \, dx$ with fixed boundary conditions, perturbing $y(x) \to y(x) + \epsilon \eta(x)$ and requiring the functional derivative $\delta J = 0$ yields the fundamental Euler-Lagrange differential equation: $\frac{\partial L}{\partial y} - \frac{d}{dx}\left(\frac{\partial L}{\partial y'}\right) = 0$.

## Modern Applications & Advanced Significance
Hamilton's Principle of Stationary Action: In fundamental physics, physical trajectories minimize (or make stationary) the action functional $S = \int_{t_1}^{t_2} \mathcal{L}(q, \dot{q}, t) \, dt$, where $\mathcal{L} = T - V$ is the Lagrangian, deriving all classical mechanics and field equations.

## Real-World Impact & Systems
The Brachistochrone curve problem, catenary curve minimization, optimal trajectory control in aerospace engineering.

## Key Terminology
- **Functional**: Mathematical mapping that takes a function as its input and returns a scalar value.
- **Euler-Lagrange Equation**: Second-order partial differential equation whose solutions are functions for which a given functional is stationary.
- **Principle of Least Action**: Variational principle stating that physical systems follow paths that make the action functional stationary.


## References & Further Exploration
[[Classical Mechanics - Newtonian, Lagrangian, and Hamiltonian Dynamics]], [[Differential Geometry - Curvature and Tensors]]
