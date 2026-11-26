---
title: "Spectral Graph Theory and Graph Laplacians"
tags: [mathematics, graph-theory, linear-algebra]
related: [[[Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring]], [[Eigenvalues, Eigenvectors, and Spectral Decomposition]]]
created: 2026-11-26
updated: 2026-11-26
---

# Spectral Graph Theory and Graph Laplacians

## Overview
Spectral Graph Theory explores the structural and topological properties of graphs via the eigenvalues and eigenvectors of their associated matrices.

## Core Mechanics & Foundations
The Graph Laplacian Matrix: For an undirected graph $G = (V, E)$ with adjacency matrix $A$ and degree matrix $D$, the unnormalized Graph Laplacian is $L = D - A$. The Laplacian is symmetric and positive semi-definite; the multiplicity of eigenvalue $\lambda_0 = 0$ equals the number of connected components of the graph.

## Modern Applications & Advanced Significance
The Fiedler Vector & Cheeger's Inequality: The second smallest eigenvalue $\lambda_2$ (the algebraic connectivity or Fiedler value) and its corresponding Fiedler vector partition the graph into two optimal clusters. Cheeger's inequality bounds the graph conductance (bottleneck ratio) $\phi(G)$ between $\frac{\lambda_2}{2} \le \phi(G) \le \sqrt{2 \lambda_2}$.

## Real-World Impact & Systems
Spectral clustering in machine learning, image segmentation, distributed consensus in sensor networks, topological graph neural networks (GCNs).

## Key Terminology
- **Graph Laplacian**: Matrix representation $L = D - A$ encoding graph degree and adjacency connectivity.
- **Fiedler Vector**: Eigenvector corresponding to the second smallest eigenvalue of the graph Laplacian, used for optimal spectral graph bisection.
- **Cheeger's Inequality**: Theorem relating the spectral gap of the graph Laplacian to the geometric conductance bottleneck of the graph.


## References & Further Exploration
[[Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring]], [[Eigenvalues, Eigenvectors, and Spectral Decomposition]]
