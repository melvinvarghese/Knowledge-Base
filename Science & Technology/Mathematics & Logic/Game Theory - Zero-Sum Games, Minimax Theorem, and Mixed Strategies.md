---
title: "Game Theory - Zero-Sum Games, Minimax Theorem, and Mixed Strategies"
tags: [mathematics, game-theory, optimization, economics]
related: [[[Game Theory - Nash Equilibrium and Dominant Strategies]], [[Linear Programming and the Simplex Algorithm]]]
created: 2026-11-26
updated: 2026-11-26
---

# Game Theory - Zero-Sum Games, Minimax Theorem, and Mixed Strategies

## Overview
Classical Game Theory models zero-sum adversarial competition where one player's gain is exactly equal to the opposing player's loss ($u_1 + u_2 = 0$).

## Core Mechanics & Foundations
von Neumann's Minimax Theorem (1928): John von Neumann proved that in every finite, two-player zero-sum game with payoff matrix $A$, there exists a unique game value $V$ and optimal mixed strategies $p^* \in \Delta_m, q^* \in \Delta_n$ satisfying the saddle point condition: $\max_{p} \min_{q} p^T A q = \min_{q} \max_{p} p^T A q = V$. Minimizing maximum possible loss produces optimal defense.

## Modern Applications & Advanced Significance
Equivalence to Linear Programming: Solving a zero-sum matrix game is mathematically equivalent to solving a dual pair of linear programs via the Simplex algorithm. Mixed strategies randomize choices to make the player unpredictable (e.g., bluffing in poker, penalty kick aiming in football).

## Real-World Impact & Systems
Algorithmic adversarial training in Generative Adversarial Networks (GANs), military defensive deployment strategies, chess engine evaluation.

## Key Terminology
- **Minimax Theorem**: Theorem stating that every two-player zero-sum game with finite strategies has a unique optimal mixed strategy value.
- **Zero-Sum Game**: Mathematical representation of a situation in which each participant's gain or loss of utility is exactly balanced by that of the other.
- **Mixed Strategy**: Assignment of a probability to each pure strategy, allowing a player to randomly select an action.


## References & Further Exploration
[[Game Theory - Nash Equilibrium and Dominant Strategies]], [[Linear Programming and the Simplex Algorithm]]
