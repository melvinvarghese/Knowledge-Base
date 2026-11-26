---
tags:
  - information-theory
  - mathematics
  - telecommunications
category: Science & Technology/Mathematics & Logic
related:
  - "[[Markov Chains - Transition Matrices and Stationary Distributions]]"
  - "[[Graph Theory - The Konigsberg Bridges and Eulerian Paths]]"
created: 2026-11-26
---

# Information Theory - Shannon Entropy and Channel Capacity

## Overview
Claude Shannon's *A Mathematical Theory of Communication* (1948) founded **Information Theory**, quantifying information content, compression limits, and communication channel capacities.

---

## 1. Theoretical Foundations & Governing Principles
Shannon Entropy Equation: Expected uncertainty of a discrete random variable:

$$H(X) = -\sum_{i=1}^n P(x_i) \log_2 P(x_i)$$

Measured in **bits**, defining the absolute theoretical limit on lossless data compression.

---

## 2. Structural Analysis & Mathematical Modeling
The Shannon-Hartley Channel Capacity Theorem: Maximum error-free data rate over a noisy channel with bandwidth $B$ and signal-to-noise ratio $\text{SNR}$:

$$C = B \log_2(1 + \text{SNR})$$

---

## 3. Real-World Applications & Scientific Impact
Lossless data compression algorithms (Huffman, LZMA), mobile cellular error-correcting codes, cryptography.

---

## Key Terms
- **Shannon Entropy**: Measure of the average information content, surprise, or uncertainty in a random variable.
- **Channel Capacity ($C$)**: The tight upper bound on the rate at which information can be reliably transmitted over a communications channel.
- **Bit**: Fundamental binary unit of information representing a choice between two equally likely alternatives.
