---
title: "Central Limit Theorem and Law of Large Numbers"
tags: [mathematics, probability-and-statistics]
related: [[[Bayesian Probability and Inference]], [[Markov Chains and Random Walks]]]
created: 2026-11-26
updated: 2026-11-26
---

# Central Limit Theorem and Law of Large Numbers

## Overview
The Central Limit Theorem (CLT) establishes that the normalized sum of a large number of independent and identically distributed (i.i.d.) random variables converges in distribution to a Gaussian normal distribution.

## Core Mechanics & Foundations
Lindeberg-Lévy CLT Formulation: Let $X_1, X_2, \dots, X_n$ be i.i.d. random variables with finite mean $\mu$ and variance $\sigma^2 > 0$. The standardized sample mean converges in distribution: $\sqrt{n}\left(\frac{\bar{X}_n - \mu}{\sigma}\right) \xrightarrow{d} \mathcal{N}(0, 1)$ as $n \to \infty$. This holds regardless of the underlying distribution's shape.

## Modern Applications & Advanced Significance
Weak & Strong Laws of Large Numbers: The Weak Law (WLLN) guarantees convergence in probability ($\bar{X}_n \xrightarrow{P} \mu$), while the Strong Law (SLLN) ensures almost sure convergence ($\mathbb{P}(\lim_{n \to \infty} \bar{X}_n = \mu) = 1$).

## Real-World Impact & Systems
Statistical hypothesis testing, poll sampling error bounds, quality control in industrial manufacturing, insurance risk pooling.

## Key Terminology
- **Central Limit Theorem**: Fundamental statistical theorem stating sample sums converge to a normal distribution.
- **Law of Large Numbers**: Theorem stating the empirical average of i.i.d. trials converges to the expected value.
- **Almost Sure Convergence**: Strong convergence where the event that the sequence fails to converge has probability zero.


## References & Further Exploration
[[Bayesian Probability and Inference]], [[Markov Chains and Random Walks]]
