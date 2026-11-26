---
title: "Artificial Neural Networks - Backpropagation and Gradient Descent"
tags: [computing, artificial-intelligence, deep-learning]
related: [[[Convex Optimization and Karush-Kuhn-Tucker (KKT) Conditions]], [[Transformer Architecture and Self-Attention Mechanisms]]]
created: 2026-11-26
updated: 2026-11-26
---

# Artificial Neural Networks - Backpropagation and Gradient Descent

## Overview
Artificial Neural Networks (ANNs) are parameterized function approximators trained on empirical datasets by optimizing weight matrices through backpropagation of gradient errors.

## Core Mechanics & Foundations
Mathematical Forward & Backward Passes: Given layer activations $a^{(l)} = \sigma(W^{(l)} a^{(l-1)} + b^{(l)})$ with non-linear activation $\sigma$ (ReLU, GELU), error with respect to scalar loss $\mathcal{L}$ propagates backward via the multivariable chain rule: $\frac{\partial \mathcal{L}}{\partial W^{(l)}} = \delta^{(l)} (a^{(l-1)})^T$, where error vector $\delta^{(l)} = ((W^{(l+1)})^T \delta^{(l+1)}) \odot \sigma'(z^{(l)})$.

## Modern Applications & Advanced Significance
Gradient Descent Variants: Standard Gradient Descent updates parameters along negative gradients: $\theta \leftarrow \theta - \eta \nabla_\theta \mathcal{L}$. Stochastic Gradient Descent (SGD) with momentum and adaptive learning rate optimizers (Adam, AdamW) scale updates using running exponential averages of first and second gradient moments.

## Real-World Impact & Systems
Computer vision image classification, natural language processing, speech synthesis, autonomous robotic navigation.

## Key Terminology
- **Backpropagation**: Efficient algorithm for computing the gradients of a loss function with respect to weights using the chain rule.
- **Activation Function**: Non-linear mathematical function applied element-wise to introduce non-linearity into neural networks.
- **Adam Optimizer**: Adaptive learning rate optimization algorithm utilizing exponentially decaying averages of past gradients and squared gradients.


## References & Further Exploration
[[Convex Optimization and Karush-Kuhn-Tucker (KKT) Conditions]], [[Transformer Architecture and Self-Attention Mechanisms]]
