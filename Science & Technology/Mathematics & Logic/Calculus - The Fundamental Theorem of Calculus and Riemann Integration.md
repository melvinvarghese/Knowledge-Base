---
title: "Calculus - The Fundamental Theorem of Calculus and Riemann Integration"
tags: [mathematics, calculus, real-analysis]
related: [[[Measure Theory and the Lebesgue Integral]], [[Differential Equations - Ordinary vs Partial and Boundary Value Problems]]]
created: 2026-11-26
updated: 2026-11-26
---

# Calculus - The Fundamental Theorem of Calculus and Riemann Integration

## Overview
The Fundamental Theorem of Calculus bridges differential and integral calculus, proving that differentiation and integration are inverse operations.

## Core Mechanics & Foundations
Part 1 & Part 2 Formulations: 1. If $f$ is continuous on $[a, b]$ and $F(x) = \int_a^x f(t) \, dt$, then $F'(x) = f(x)$; 2. If $F$ is an antiderivative of $f$ ($F' = f$), then definite integration computes net accumulation: $\int_a^b f(x) \, dx = F(b) - F(a)$.

## Modern Applications & Advanced Significance
Riemann Sums & Integrability: The Riemann integral partitions $[a,b]$ into $n$ subintervals $\Delta x_i$: $\int_a^b f(x) \, dx = \lim_{\|\Delta\| \to 0} \sum_{i=1}^n f(x_i^*) \Delta x_i$. A bounded function is Riemann integrable if and only if its set of discontinuities has Lebesgue measure zero.

## Real-World Impact & Systems
Calculation of physical work, trajectory arc lengths, probability cumulative distribution functions, electromagnetic flux.

## Key Terminology
- **Fundamental Theorem of Calculus**: Theorem linking differentiation and integration as inverse mathematical operations.
- **Riemann Integral**: Rigorous definition of the integral based on approximating areas under curves with summing rectangular partitions.
- **Antiderivative**: Differentiable function whose derivative is equal to the original function.


## References & Further Exploration
[[Measure Theory and the Lebesgue Integral]], [[Differential Equations - Ordinary vs Partial and Boundary Value Problems]]
