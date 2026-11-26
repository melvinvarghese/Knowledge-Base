---
title: "Fourier Series and Orthogonal Function Expansions"
tags: [mathematics, calculus, harmonic-analysis, signal-processing]
related: [[[Fourier Transform and Frequency Domain Analysis]], [[Functional Analysis - Hilbert and Banach Spaces]]]
created: 2026-11-26
updated: 2026-11-26
---

# Fourier Series and Orthogonal Function Expansions

## Overview
Fourier Series represent periodic mathematical functions as infinite linear combinations of harmonically related sines and cosines.

## Core Mechanics & Foundations
Mathematical Expansion & Coefficients: For a $2\pi$-periodic function $f \in L^2([-\pi, \pi])$, its Fourier series is: $f(x) = \frac{a_0}{2} + \sum_{n=1}^\infty \left[ a_n \cos(nx) + b_n \sin(nx) \right] = \sum_{n=-\infty}^\infty c_n e^{i n x}$. By orthogonality of trigonometric basis functions ($\int_{-\pi}^\pi e^{i m x} e^{-i n x} dx = 2\pi \delta_{mn}$), Fourier coefficients are computed via inner products: $c_n = \frac{1}{2\pi} \int_{-\pi}^\pi f(x) e^{-i n x} dx$.

## Modern Applications & Advanced Significance
Convergence & Gibbs Phenomenon: Dirichlet conditions guarantee pointwise convergence at points of continuity. At jump discontinuities, truncated Fourier series overshoot the function value by approximately 9% (the Gibbs Phenomenon), failing to converge uniformly.

## Real-World Impact & Systems
Solving the Heat Equation on bounded domains, vibration harmonics in musical acoustics, audio synthesizers.

## Key Terminology
- **Fourier Series**: Way to represent a periodic function as a sum of simple sinusoidal waves.
- **Orthogonal Functions**: Set of functions whose pairwise inner product integrals equal zero, serving as coordinate basis vectors in Hilbert space.
- **Gibbs Phenomenon**: Peculiar ringing overshoot near jump discontinuities in truncated Fourier series approximations.


## References & Further Exploration
[[Fourier Transform and Frequency Domain Analysis]], [[Functional Analysis - Hilbert and Banach Spaces]]
