---
title: "Differential Topology - Transversality, Morse Theory, and Critical Points"
tags: [mathematics, differential-topology, calculus, manifolds]
related: [[[Differential Geometry - Curvature and Tensors]], [[Topology - Homeomorphism, Manifolds, and Euler Characteristic]]]
created: 2026-11-26
updated: 2026-11-26
---

# Differential Topology - Transversality, Morse Theory, and Critical Points

## Overview
Differential Topology investigates smooth manifolds and differentiable mappings, exploring global topological structures through non-degenerate critical points.

## Core Mechanics & Foundations
Transversality & Sard's Theorem: Two smooth submanifolds $A, B \subset M$ intersect transversally if at every intersection point $p$, their tangent spaces span the entire ambient tangent space: $T_p A + T_p B = T_p M$. Sard's Theorem proves that the set of critical values of a smooth map has Lebesgue measure zero, ensuring generic transversality.

## Modern Applications & Advanced Significance
Morse Theory (Marston Morse): Studies the topology of a manifold $M$ by analyzing the critical points ($\nabla f = 0$) of a smooth function $f: M \to \mathbb{R}$. A critical point is non-degenerate if its Hessian matrix of second partial derivatives is invertible. The **Morse Index** $\lambda$ (the number of negative eigenvalues of the Hessian) corresponds to the dimension of a topological handle glued onto the manifold as level sets $f^{-1}((-\infty, c])$ pass through critical values.

## Real-World Impact & Systems
Topological landscape analysis in computational biochemistry (protein folding energy surfaces), proof of the generalized Poincaré conjecture.

## Key Terminology
- **Morse Function**: Smooth function on a manifold whose critical points are all non-degenerate (having invertible Hessian matrices).
- **Morse Index**: Number of negative eigenvalues of the Hessian matrix at a critical point, indicating the direction of downward slopes.
- **Transversality**: General position geometric condition where two intersecting submanifolds do not meet tangentially.


## References & Further Exploration
[[Differential Geometry - Curvature and Tensors]], [[Topology - Homeomorphism, Manifolds, and Euler Characteristic]]
