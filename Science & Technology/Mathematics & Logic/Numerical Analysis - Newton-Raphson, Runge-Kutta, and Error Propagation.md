---
title: "Numerical Analysis - Newton-Raphson, Runge-Kutta, and Error Propagation"
tags: [mathematics, numerical-methods, algorithms]
related: [[[Differential Equations - Ordinary vs Partial and Boundary Value Problems]], [[Fast Fourier Transform (FFT) - Cooley-Tukey Algorithm]]]
created: 2026-11-26
updated: 2026-11-26
---

# Numerical Analysis - Newton-Raphson, Runge-Kutta, and Error Propagation

## Overview
Numerical Analysis designs and validates algorithms for solving continuous mathematical problems using discrete, finite-precision floating-point arithmetic.

## Core Mechanics & Foundations
Root-Finding & Newton-Raphson: Newton-Raphson iteratively approximates roots of $f(x) = 0$ via tangent lines: $x_{n+1} = x_n - \frac{f(x_n)}{f'(x_n)}$, exhibiting local quadratic convergence ($|e_{n+1}| \le M |e_n|^2$) near simple roots.

## Modern Applications & Advanced Significance
Numerical ODE Integration & Runge-Kutta: Simulating dynamic ODEs $\dot{y} = f(t, y)$ extends basic Euler steps to high-order approximations. The fourth-order Runge-Kutta method (RK4) evaluates four intermediate slope probes per step: $y_{n+1} = y_n + \frac{h}{6}(k_1 + 2k_2 + 2k_3 + k_4)$, achieving fourth-order global truncation error $O(h^4)$.

## Real-World Impact & Systems
Floating-point condition numbers, finite element simulation, computational fluid dynamics (CFD), rocket flight trajectory integration.

## Key Terminology
- **Newton-Raphson Method**: Iterative root-finding algorithm using linear tangent approximations achieving quadratic convergence.
- **Runge-Kutta Method (RK4)**: Widely used fourth-order numerical integration algorithm for solving ordinary differential equations.
- **Condition Number**: Metric measuring the sensitivity of an output function to small perturbations in input arguments.


## References & Further Exploration
[[Differential Equations - Ordinary vs Partial and Boundary Value Problems]], [[Fast Fourier Transform (FFT) - Cooley-Tukey Algorithm]]
