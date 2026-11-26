---
tags:
  - information-theory
  - machine-learning
  - statistics
category: Science & Technology/Mathematics & Logic
related:
  - "[[Information Theory - Shannon Entropy and Channel Capacity]]"
  - "[[Bayes' Theorem - Prior Probability, Likelihood, and Posterior Inference]]"
created: 2026-11-26
---

# Kullback-Leibler Divergence and Relative Entropy

## Overview
Kullback-Leibler (KL) Divergence (Relative Entropy) is a non-symmetric statistical measure of the difference between two probability distributions $P$ and $Q$.

---

## 1. Theoretical Foundations & Governing Principles
Mathematical Definition: Discrete KL divergence from true distribution $P$ to approximation $Q$:

$$D_{\text{KL}}(P \parallel Q) = \sum_{x} P(x) \log_2\left(\frac{P(x)}{Q(x)}\right)$$

Gibbs' inequality guarantees $D_{\text{KL}}(P \parallel Q) \ge 0$, with equality if and only if $P = Q$.

---

## 2. Structural Analysis & Mathematical Modeling
Asymmetry & Cross-Entropy: $D_{\text{KL}}(P \parallel Q) \ne D_{\text{KL}}(Q \parallel P)$, meaning it is not a true mathematical distance metric. Minimizing KL divergence is mathematically identical to minimizing cross-entropy loss in machine learning.

---

## 3. Real-World Applications & Scientific Impact
Training loss functions in artificial neural networks, Variational Autoencoders (VAEs), statistical model selection criteria (AIC).

---

## Key Terms
- **KL Divergence**: Statistical measure quantifying the information lost when approximating distribution P with distribution Q.
- **Relative Entropy**: Another name for Kullback-Leibler divergence measuring informational divergence.
- **Cross-Entropy Loss**: Standard machine learning classification loss function derived from KL divergence.
