---
title: "Stochastic Calculus - Itô's Lemma and Geometric Brownian Motion"
tags: [mathematics, calculus, stochastic-processes]
related: [[[Markov Chains and Random Walks]], [[Differential Equations - Ordinary vs Partial and Boundary Value Problems]]]
created: 2026-11-26
updated: 2026-11-26
---

# Stochastic Calculus - Itô's Lemma and Geometric Brownian Motion

## Overview
Stochastic Calculus extends classical calculus to systems driven by non-differentiable random noise, such as Brownian motion.

## Core Mechanics & Foundations
Itô's Lemma vs Classical Chain Rule: Standard Brownian motion $W_t$ has quadratic variation $[W, W]_t = t$, meaning $(dW_t)^2 = dt$. For a smooth function $f(t, X_t)$ where $X_t$ obeys Itô drift-diffusion $dX_t = \mu_t dt + \sigma_t dW_t$, Itô's Lemma includes a vital second-order Taylor correction term: $df = \left(\frac{\partial f}{\partial t} + \mu_t \frac{\partial f}{\partial x} + \frac{1}{2}\sigma_t^2 \frac{\partial^2 f}{\partial x^2}\right) dt + \sigma_t \frac{\partial f}{\partial x} dW_t$.

## Modern Applications & Advanced Significance
Geometric Brownian Motion & Black-Scholes PDE: Modeling asset prices $S_t$ via Geometric Brownian Motion $dS_t = \mu S_t dt + \sigma S_t dW_t$ enables the derivation of the Black-Scholes-Merton partial differential equation for risk-neutral options pricing.

## Real-World Impact & Systems
Quantitative finance derivatives pricing, physical diffusion with Langevin equations, filtering theory in noisy robotics tracking.

## Key Terminology
- **Itô's Lemma**: Stochastic counterpart of the chain rule incorporating second-order derivative corrections for Brownian variance.
- **Brownian Motion**: Continuous-time stochastic process with independent Gaussian increments and continuous paths.
- **Quadratic Variation**: Measure of cumulative variance growth of a stochastic path over time, equaling $t$ for standard Brownian motion.


## References & Further Exploration
[[Markov Chains and Random Walks]], [[Differential Equations - Ordinary vs Partial and Boundary Value Problems]]
