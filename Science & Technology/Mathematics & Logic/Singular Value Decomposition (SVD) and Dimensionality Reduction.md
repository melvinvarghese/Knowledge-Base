---
tags:
  - mathematics
  - linear-algebra
  - data-science
category: Science & Technology/Mathematics & Logic
related:
  - "[[Linear Algebra - Eigenvalues, Eigenvectors, and Matrix Diagonalization]]"
  - "[[Markov Chains - Transition Matrices and Stationary Distributions]]"
created: 2026-11-26
---

# Singular Value Decomposition (SVD) and Dimensionality Reduction

## Overview
Singular Value Decomposition (SVD) is a matrix factorization theorem generalizing eigendecomposition to arbitrary rectangular $m \times n$ matrices, fundamental to data dimensionality reduction.

---

## 1. Theoretical Foundations & Governing Principles
The SVD Theorem: Any real matrix $A \in \mathbb{R}^{m \times n}$ decomposes as $A = U \Sigma V^T$, where $U$ and $V$ are orthogonal matrices and $\Sigma$ contains non-negative singular values $\sigma_1 \ge \sigma_2 \ge \dots \ge 0$.

---

## 2. Structural Analysis & Mathematical Modeling
Principal Component Analysis (PCA) & Eckart-Young Theorem: Truncating SVD to rank $k$ yields the optimal low-rank matrix approximation under Frobenius norm, projecting high-dimensional data onto orthogonal axes of maximum variance.

---

## 3. Real-World Applications & Scientific Impact
Machine learning latent semantic analysis, image lossy compression, recommender systems (Netflix collaborative filtering).

---

## Key Terms
- **Singular Value Decomposition (SVD)**: Factorization of a rectangular matrix into two orthogonal matrices and a diagonal singular matrix.
- **Principal Component Analysis (PCA)**: Statistical method converting correlated variables into linearly uncorrelated principal components.
- **Low-Rank Approximation**: Simplified matrix representation capturing the maximum structural variance with fewer parameters.
