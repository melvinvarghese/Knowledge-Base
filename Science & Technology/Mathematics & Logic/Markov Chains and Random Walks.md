---
title: "Markov Chains and Random Walks"
tags: [mathematics, probability-and-statistics, stochastic-processes]
related: [[[Markov Decision Processes (MDPs) and Bellman Equations]], [[Central Limit Theorem and Law of Large Numbers]]]
created: 2026-11-26
updated: 2026-11-26
---

# Markov Chains and Random Walks

## Overview
A Markov Chain is a stochastic model describing a sequence of possible events where the probability of transitioning to each next state depends solely on the current state (the Markov property).

## Core Mechanics & Foundations
Transition Probability Matrix & Stationary Distribution: For discrete states, transitions are governed by transition matrix $P_{ij} = \mathbb{P}(X_{t+1} = j \mid X_t = i)$. A stationary distribution $\pi$ satisfies $\pi P = \pi$. For irreducible, aperiodic, and positive recurrent chains, the Perron-Frobenius theorem guarantees convergence to a unique stationary distribution regardless of initial state.

## Modern Applications & Advanced Significance
Random Walks on Lattices: A simple random walk on a 1D or 2D integer lattice is recurrent (Pólya's Theorem, 1921: a random walker will return to the origin with probability 1), whereas random walks in 3D or higher dimensions are transient (probability of return drops to $\approx 0.34$ in 3D).

## Real-World Impact & Systems
MCMC sampling, web search engine PageRank scoring, diffusion simulation in statistical mechanics, speech recognition (Hidden Markov Models).

## Key Terminology
- **Markov Property**: Memoryless property where the future state depends only upon the present state and not past history.
- **Stationary Distribution**: Probability distribution over states that remains invariant under repeated application of the transition matrix.
- **Recurrent State**: State in a Markov chain that is guaranteed to be visited infinitely many times.


## References & Further Exploration
[[Markov Decision Processes (MDPs) and Bellman Equations]], [[Central Limit Theorem and Law of Large Numbers]]
