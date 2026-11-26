---
title: "Eigenvalues, Eigenvectors, and Spectral Decomposition"
tags: [mathematics, linear-algebra, spectral-theory]
related: [[[Singular Value Decomposition (SVD) and Dimensionality Reduction]], [[Quantum Mechanics - Superposition and Measurement]]]
created: 2026-11-26
updated: 2026-11-26
---

# Eigenvalues, Eigenvectors, and Spectral Decomposition

## Overview
Eigenvalues and eigenvectors characterize the invariant directional scaling behavior of linear operators on vector spaces, forming the core of the Spectral Theorem for normal matrices.

## Core Mechanics & Foundations
Mathematical Formulation: For a linear transformation represented by matrix $A \in \mathbb{C}^{n \times n}$, a non-zero vector $v$ is an eigenvector with eigenvalue $\lambda$ if $A v = \lambda v$, or equivalently $\det(A - \lambda I) = 0$. For Hermitian matrices ($A = A^*$), the Spectral Theorem guarantees an orthonormal basis of eigenvectors such that $A = Q \Lambda Q^*$.

## Modern Applications & Advanced Significance
Applications in Quantum & Data Science: In quantum mechanics, physical observables correspond to self-adjoint Hermitian operators whose eigenvalues represent observable measurement outcomes. In data science, principal component analysis (PCA) diagonalizes the sample covariance matrix to identify directions of maximal variance.

## Real-World Impact & Systems
Quantum state measurement, modal vibrational analysis, Google PageRank algorithm, dimensionality reduction.

## Key Terminology
- **Eigenvector**: A non-zero vector whose direction remains invariant under a linear transformation, only scaling by the eigenvalue.
- **Characteristic Polynomial**: The polynomial equation $\det(A - \lambda I) = 0$ whose roots yield the eigenvalues.
- **Spectral Theorem**: Theorem establishing that normal matrices can be diagonalized by a unitary basis of eigenvectors.


## References & Further Exploration
[[Singular Value Decomposition (SVD) and Dimensionality Reduction]], [[Quantum Mechanics - Superposition and Measurement]]
