---
title: "Variational Inference and Expectation-Maximization (EM)"
tags: [mathematics, probability-and-statistics, machine-learning]
related: [[[Bayesian Probability and Inference]], [[Bayesian Networks and Probabilistic Graphical Models]]]
created: 2026-11-26
updated: 2026-11-26
---

# Variational Inference and Expectation-Maximization (EM)

## Overview
Variational Inference (VI) and Expectation-Maximization (EM) approximate intractable posterior probability distributions over latent variables in probabilistic graphical models.

## Core Mechanics & Foundations
Expectation-Maximization Formulation: For observed data $X$ and latent variables $Z$, EM maximizes the marginal log-likelihood $\log P(X \mid \theta)$ via alternating iterative steps: 1. E-step: Compute expected value of complete log-likelihood under current posterior: $Q(\theta \mid \theta^{(t)}) = \mathbb{E}_{Z \mid X, \theta^{(t)}}[\log P(X, Z \mid \theta)]$; 2. M-step: Update parameters $\theta^{(t+1)} = \arg\max_\theta Q(\theta \mid \theta^{(t)})$.

## Modern Applications & Advanced Significance
Variational Inference & Evidence Lower Bound (ELBO): In complex Bayesian models where exact posteriors are intractable, VI posits a tractable family $q(Z)$ and minimizes Kullback-Leibler divergence $\text{KL}(q(Z) \parallel P(Z \mid X))$ by maximizing the ELBO: $\mathcal{L}(q) = \mathbb{E}_q[\log P(X, Z)] - \mathbb{E}_q[\log q(Z)]$.

## Real-World Impact & Systems
Gaussian Mixture Models (GMM) clustering, hidden Markov parameter learning, Variational Autoencoders (VAEs) in generative AI.

## Key Terminology
- **EM Algorithm**: Iterative numerical algorithm alternating between calculating expected latent states and maximizing model parameters.
- **ELBO**: Evidence Lower Bound; functional maximized in variational inference as a surrogate for marginal data likelihood.
- **KL Divergence**: Asymmetric statistical distance measure quantifying information lost when approximating one probability distribution with another.


## References & Further Exploration
[[Bayesian Probability and Inference]], [[Bayesian Networks and Probabilistic Graphical Models]]
