---
title: "Representation Theory - Group Characters, Schur's Lemma, and Lie Algebras"
tags: [mathematics, abstract-algebra, representation-theory, linear-algebra]
related: [[[Group Theory - Symmetry, Subgroups, and Lie Groups]], [[Lie Groups and Lie Algebras in Mathematical Physics]]]
created: 2026-11-26
updated: 2026-11-26
---

# Representation Theory - Group Characters, Schur's Lemma, and Lie Algebras

## Overview
Representation Theory models abstract algebraic groups as linear transformations (matrices) acting on vector spaces, translating abstract symmetries into concrete linear algebra.

## Core Mechanics & Foundations
Linear Representations & Group Characters: A representation of group $G$ on vector space $V$ is a group homomorphism $\rho: G \to \text{GL}(V)$. The **character** $\chi_\rho(g) = \text{Tr}(\rho(g))$ is the trace of the representation matrix. Group characters are class functions that uniquely identify irreducible representations.

## Modern Applications & Advanced Significance
Schur's Lemma & Orthogonality: Schur's Lemma establishes that if $\rho, \sigma$ are irreducible representations, any linear map $T$ satisfying $T \rho(g) = \sigma(g) T$ is either zero or an isomorphism. Group characters obey grand orthogonality relations: $\frac{1}{|G|} \sum_{g \in G} \chi_\rho(g) \overline{\chi_\sigma(g)} = \delta_{\rho\sigma}$.

## Real-World Impact & Systems
Quantum mechanical angular momentum spin states (irreducible representations of $SU(2)$), particle classification in the Standard Model (Eightfold Way of $SU(3)$).

## Key Terminology
- **Representation**: Homomorphism mapping an abstract group into the general linear group of invertible matrices.
- **Character**: Function assigning to each group element the trace of its corresponding representation matrix.
- **Schur's Lemma**: Fundamental lemma in representation theory stating that intertwining maps between irreducible representations are scalars or zero.


## References & Further Exploration
[[Group Theory - Symmetry, Subgroups, and Lie Groups]], [[Lie Groups and Lie Algebras in Mathematical Physics]]
