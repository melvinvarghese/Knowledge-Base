---
tags:
  - artificial-intelligence
  - machine-learning
  - computing
category: Science & Technology/Inventions & Computing
related:
  - "[[Convolutional Neural Networks (CNNs) and Computer Vision]]"
  - "[[Transformer Architecture and Self-Attention Mechanisms]]"
created: 2026-11-26
---

# Artificial Neural Networks - Perceptrons and Multi-Layer Backpropagation

## Overview
Artificial Neural Networks (ANNs) are computational models inspired by biological brain neural architectures, learning complex non-linear patterns from data through interconnected layers of artificial neurons.

---

## 1. Theoretical Foundations & Governing Principles
The Artificial Neuron Model: Weighted sum of inputs passed through a non-linear activation function:

$$y = f\left(\sum_{i=1}^n w_i x_i + b\right)$$

Activation functions (ReLU, Sigmoid) introduce non-linearity, enabling networks to approximate arbitrary functions (Universal Approximation Theorem).

---

## 2. Structural Mechanics & Scientific Analysis
Backpropagation and Gradient Descent: Calculating the gradient of the loss function $\nabla \mathcal{L}$ with respect to all network weights using the calculus chain rule, iteratively updating weights: $w \leftarrow w - \eta \nabla_w \mathcal{L}$.

---

## 3. Real-World Applications & Technological Impact
Speech recognition systems, medical diagnostic classification, financial fraud detection, and predictive analytics.

---

## Key Terms
- **Backpropagation**: Algorithm calculating gradient of loss function relative to network weights via chain rule.
- **Activation Function**: Mathematical function determining whether and how strongly a neuron fires.
- **Gradient Descent**: First-order iterative optimization algorithm used to minimize a network loss function.
