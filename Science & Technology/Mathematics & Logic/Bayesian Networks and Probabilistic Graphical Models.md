---
title: "Bayesian Networks and Probabilistic Graphical Models"
tags: [mathematics, artificial-intelligence, probability-and-statistics]
related: [[[Bayesian Probability and Inference]], [[Markov Decision Processes (MDPs) and Bellman Equations]]]
created: 2026-11-26
updated: 2026-11-26
---

# Bayesian Networks and Probabilistic Graphical Models

## Overview
Bayesian Networks are directed acyclic graphical models (DAGs) whose nodes represent random variables and directed edges encode conditional probabilistic dependencies via $d$-separation.

## Core Mechanics & Foundations
Joint Probability Factorization: By the chain rule of probability combined with conditional independence properties, the joint probability over variables $X = \{X_1, \dots, X_n\}$ factors compactly as $P(X_1, \dots, X_n) = \prod_{i=1}^n P(X_i \mid \text{Parents}(X_i))$, drastically reducing parameter complexity from $2^n$ to polynomial scale.

## Modern Applications & Advanced Significance
Inference & Belief Propagation: Exact inference algorithms (e.g., Pearl's belief propagation, junction tree algorithm) compute posterior distributions $P(Q \mid E)$ given observed evidence $E$, while approximate inference leverages Markov Chain Monte Carlo (MCMC) and Gibbs sampling for NP-hard general topologies.

## Real-World Impact & Systems
Medical diagnostic systems, bioinformatic gene regulatory networks, risk assessment in autonomous driving.

## Key Terminology
- **Bayesian Network**: Directed acyclic graph representing variables and their conditional probabilistic dependencies.
- **d-separation**: Graph-theoretic criterion determining conditional independence between sets of variables.
- **Belief Propagation**: Message-passing algorithm for exact probabilistic inference on tree-structured graphs.


## References & Further Exploration
[[Bayesian Probability and Inference]], [[Markov Decision Processes (MDPs) and Bellman Equations]]
