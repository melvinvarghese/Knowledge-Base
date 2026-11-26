---
tags:
  - mathematics
  - number-theory
  - algorithms
category: Science & Technology/Mathematics & Logic
related:
  - "[[Prime Number Distribution - The Riemann Hypothesis and Prime Number Theorem]]"
  - "[[Public-Key Cryptography - Diffie-Hellman and RSA Algorithm]]"
created: 2026-11-26
---

# Euclidean Algorithm and the Fundamental Theorem of Arithmetic

## Overview
The Euclidean Algorithm is one of the oldest numerical algorithms, computing the Greatest Common Divisor (GCD) of two integers using repeated division with remainder.

---

## 1. Theoretical Foundations & Governing Principles
Euclidean Division Step: $\gcd(a, b) = \gcd(b, a \bmod b)$. Termination is guaranteed in logarithmic steps $O(\log(\min(a,b)))$ (Lamé's theorem).

---

## 2. Structural Analysis & Mathematical Modeling
The Fundamental Theorem of Arithmetic (Unique Factorization): Every integer $n > 1$ can be represented uniquely as a product of prime powers: $n = p_1^{a_1} p_2^{a_2} \cdots p_k^{a_k}$, unique up to the order of factors.

---

## 3. Real-World Applications & Scientific Impact
Bézout's identity linear combinations ($ax + by = \gcd(a,b)$), modular inverse computation in RSA cryptography.

---

## Key Terms
- **Greatest Common Divisor (GCD)**: The largest positive integer dividing two integers without a remainder.
- **Unique Factorization**: Theorem stating every integer factors uniquely into a product of prime numbers.
- **Bézout's Identity**: Theorem stating $\gcd(a, b)$ can be expressed as a linear combination $ax + by$.
