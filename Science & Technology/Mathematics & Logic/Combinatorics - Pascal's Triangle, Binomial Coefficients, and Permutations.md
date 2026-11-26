---
tags:
  - mathematics
  - discrete-mathematics
  - combinatorics
category: Science & Technology/Mathematics & Logic
related:
  - "[[Game Theory - Nash Equilibrium and Prisoner's Dilemma]]"
  - "[[Abstract Algebra - Group Theory and Symmetry Operations]]"
created: 2026-11-26
---

# Combinatorics - Pascal's Triangle, Binomial Coefficients, and Permutations

## Overview
Combinatorics is the branch of discrete mathematics concerned with counting, arrangement, and structural combination of finite collections.

---

## 1. Theoretical Foundations & Governing Principles
Binomial Theorem & Pascal's Triangle: Expands algebraic binomial powers $(x + y)^n = \sum_{k=0}^n \binom{n}{k} x^{n-k} y^k$. Binomial coefficients $\binom{n}{k} = \frac{n!}{k!(n-k)!}$ correspond to values in Pascal's triangle via identity $\binom{n}{k} = \binom{n-1}{k-1} + \binom{n-1}{k}$.

---

## 2. Structural Analysis & Mathematical Modeling
Permutations vs Combinations: Permutations count ordered arrangements ($P(n,k) = \frac{n!}{(n-k)!}$); combinations count unordered subset selections ($C(n,k) = \binom{n}{k}$).

---

## 3. Real-World Applications & Scientific Impact
Cryptographic key-space size calculations, probability distributions, statistical physics microstate counting.

---

## Key Terms
- **Binomial Coefficient ($\binom{n}{k}$)**: Number of ways to choose $k$ unordered outcomes from $n$ possibilities ('n choose k').
- **Permutation**: Ordered arrangement of a set of items where selection sequence matters.
- **Pigeonhole Principle**: Combinatorial theorem stating if $n$ items occupy $m$ containers with $n > m$, at least one container holds $>1$ item.
