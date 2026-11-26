---
title: "Euclidean Algorithm and Continued Fractions"
tags: [mathematics, number-theory, algorithms]
related: [[[Number Theory - Modular Arithmetic, Euler's Totient, and RSA]], [[Prime Number Distribution - The Riemann Hypothesis and Prime Number Theorem]]]
created: 2026-11-26
updated: 2026-11-26
---

# Euclidean Algorithm and Continued Fractions

## Overview
The Euclidean Algorithm (c. 300 BCE) computes the greatest common divisor (GCD) of two integers through successive division without requiring prime factorization.

## Core Mechanics & Foundations
Division Algorithm & Bézout's Identity: Given $a, b \in \mathbb{Z}$ with $b > 0$, divide $a = q b + r$; then $\gcd(a, b) = \gcd(b, r)$. The Extended Euclidean Algorithm finds integers $x, y$ satisfying Bézout's Identity: $a x + b y = \gcd(a, b)$, computing modular inverses in $O(\log(\min(a, b)))$ time.

## Modern Applications & Advanced Significance
Continued Fractions: Successive quotients from the Euclidean algorithm express real numbers as continued fractions: $x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \dots}}$. Rational approximations (convergents $p_k / q_k$) provide the mathematically best rational approximations to irrational numbers like $\pi$ and $e$.

## Real-World Impact & Systems
RSA public-key cryptography key generation, calendar leap-year calculations, lattice basis reduction (LLL algorithm).

## Key Terminology
- **Euclidean Algorithm**: Efficient method for computing the greatest common divisor of two integers via iterative remainder division.
- **Bézout's Identity**: Theorem stating that the greatest common divisor of $a$ and $b$ can be expressed as a linear combination $ax + by$.
- **Continued Fraction**: Representation of a real number through an iterative nested fraction of integers.


## References & Further Exploration
[[Number Theory - Modular Arithmetic, Euler's Totient, and RSA]], [[Prime Number Distribution - The Riemann Hypothesis and Prime Number Theorem]]
