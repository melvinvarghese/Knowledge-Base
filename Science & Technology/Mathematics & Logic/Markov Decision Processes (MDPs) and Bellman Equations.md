---
title: "Markov Decision Processes (MDPs) and Bellman Equations"
tags: [mathematics, reinforcement-learning, optimization]
related: [[[Game Theory - Nash Equilibrium and Dominant Strategies]], [[Markov Chains and Random Walks]]]
created: 2026-11-26
updated: 2026-11-26
---

# Markov Decision Processes (MDPs) and Bellman Equations

## Overview
Markov Decision Processes provide a formal mathematical framework for modeling sequential decision-making under uncertainty, forming the foundation of Reinforcement Learning.

## Core Mechanics & Foundations
Mathematical Tuple & Bellman Optimality: An MDP is defined as $(S, A, P, R, \gamma)$, where agent choices yield state transitions $P(s' \mid s, a)$ and reward $R(s, a)$. The optimal value function $V^*(s)$ satisfies the recursive Bellman Optimality Equation: $V^*(s) = \max_{a \in A} \left[ R(s, a) + \gamma \sum_{s' \in S} P(s' \mid s, a) V^*(s') \right]$.

## Modern Applications & Advanced Significance
Dynamic Programming & Policy Iteration: The Bellman equation defines a contraction mapping in the Banach space of value functions under the infinity norm (Banach Fixed-Point Theorem), guaranteeing that iterative dynamic programming algorithms (Value Iteration, Policy Iteration) converge geometrically to the unique optimal policy $\pi^*$.

## Real-World Impact & Systems
Autonomous robotics control, game-playing AI engines (AlphaGo, Chess engines), automated financial trading execution.

## Key Terminology
- **MDP**: Mathematical framework for sequential decision making characterized by states, actions, transitions, and rewards.
- **Bellman Equation**: Recursive equation decomposing optimal value functions into immediate rewards plus discounted downstream values.
- **Contraction Mapping**: Transformation that brings points closer together, ensuring a unique fixed point by the Banach Fixed-Point Theorem.


## References & Further Exploration
[[Game Theory - Nash Equilibrium and Dominant Strategies]], [[Markov Chains and Random Walks]]
