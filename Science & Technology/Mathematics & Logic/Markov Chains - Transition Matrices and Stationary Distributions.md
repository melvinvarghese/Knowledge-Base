---
tags:
  - mathematics
  - stochastic-processes
  - probability
category: Science & Technology/Mathematics & Logic
related:
  - "[[Bayes' Theorem - Prior Probability, Likelihood, and Posterior Inference]]"
  - "[[Information Theory - Shannon Entropy and Channel Capacity]]"
created: 2026-11-26
---

# Markov Chains - Transition Matrices and Stationary Distributions

## Overview
A Markov Chain is a stochastic model describing a sequence of random events where the probability of transitioning to the next state depends solely on the current state (**Markov property**).

---

## 1. Theoretical Foundations & Governing Principles
The Memoryless Property & Transition Matrix: $P(X_{n+1} = j \mid X_n = i, \dots, X_0) = P(X_{n+1} = j \mid X_n = i) = P_{ij}$. State vector propagates via $\pi_{n+1} = \pi_n P$.

---

## 2. Structural Analysis & Mathematical Modeling
Stationary Distribution ($\pi^*$): For ergodic (irreducible and aperiodic) chains, distribution converges to a unique stationary state satisfying $\pi^* P = \pi^*$, independent of initial conditions.

---

## 3. Real-World Applications & Scientific Impact
Markov Chain Monte Carlo (MCMC) statistical sampling, natural language next-token prediction, queuing theory.

---

## Key Terms
- **Markov Property**: Memoryless property where future state depends exclusively upon the present state.
- **Transition Matrix**: Square matrix whose non-negative entries represent probabilities of transitioning between states.
- **Stationary Distribution**: Probability vector that remains invariant under repeated application of the transition matrix.
