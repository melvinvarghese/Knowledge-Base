---
title: "Probability Distributions - Gaussian, Poisson, and Exponential Distributions"
tags: [mathematics, probability-and-statistics, stochastic-processes]
related: [[[Central Limit Theorem and Law of Large Numbers]], [[Markov Chains and Random Walks]]]
created: 2026-11-26
updated: 2026-11-26
---

# Probability Distributions - Gaussian, Poisson, and Exponential Distributions

## Overview
Probability distributions assign probabilities to different measurable outcomes of random variables, modeling natural, industrial, and social phenomena.

## Core Mechanics & Foundations
The Gaussian (Normal) Distribution: Characterized by probability density function $f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{-\frac{(x - \mu)^2}{2\sigma^2}}$. By the Central Limit Theorem, sums of independent random variables converge to Gaussian distributions, forming the symmetric bell curve with 68-95-99.7% confidence intervals.

## Modern Applications & Advanced Significance
Poisson & Exponential Distributions: The Poisson distribution models the count of independent rare events occurring in fixed time intervals: $P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!}$. The continuous time elapsed between consecutive Poisson events follows the memoryless Exponential distribution: $f(t) = \lambda e^{-\lambda t}$ with $P(T > t + s \mid T > s) = P(T > t)$.

## Real-World Impact & Systems
Queuing theory in telecommunication networks, financial risk modeling, particle physics radioactive decay counting.

## Key Terminology
- **Gaussian Distribution**: Continuous probability distribution symmetric about its mean, displaying a characteristic bell curve.
- **Poisson Distribution**: Discrete probability distribution expressing the probability of a given number of events occurring in a fixed interval.
- **Memoryless Property**: Property of exponential distributions where future probability does not depend on past elapsed time.


## References & Further Exploration
[[Central Limit Theorem and Law of Large Numbers]], [[Markov Chains and Random Walks]]
