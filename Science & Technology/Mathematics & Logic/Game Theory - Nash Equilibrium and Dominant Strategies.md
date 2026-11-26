---
title: "Game Theory - Nash Equilibrium and Dominant Strategies"
tags: [mathematics, game-theory, economics]
related: [[[Markov Decision Processes (MDPs) and Bellman Equations]], [[Decision Theory - Expected Utility and Prospect Theory]]]
created: 2026-11-26
updated: 2026-11-26
---

# Game Theory - Nash Equilibrium and Dominant Strategies

## Overview
Game Theory mathematically models strategic interaction among rational decision-makers where each participant's payoff depends on the collective choices of all players.

## Core Mechanics & Foundations
Nash Equilibrium Definition: In an $n$-player game with strategy sets $S_i$ and payoff functions $u_i(s_1, \dots, s_n)$, a strategy profile $s^* = (s_1^*, \dots, s_n^*)$ is a Nash Equilibrium if no player can unilaterally deviate to increase their payoff: $u_i(s_i^*, s_{-i}^*) \ge u_i(s_i, s_{-i}^*)$ for all $s_i \in S_i$. John Nash (1950) proved that every finite game has at least one mixed-strategy equilibrium.

## Modern Applications & Advanced Significance
The Prisoner's Dilemma & Dominant Strategy: In the canonical Prisoner's Dilemma, confessing strictly dominates remaining silent for both players, leading to a unique Nash equilibrium that is Pareto-suboptimal compared to mutual cooperation.

## Real-World Impact & Systems
Auction mechanism design (FCC spectrum auctions), evolutionary biology (evolutionarily stable strategies), antitrust economics, military deterrence.

## Key Terminology
- **Nash Equilibrium**: State in a game where no player has an incentive to unilaterally deviate from their chosen strategy.
- **Dominant Strategy**: Strategy that earns a player a higher payoff than any other strategy, regardless of what opponents do.
- **Pareto Optimality**: Allocation of resources where no individual can be made better off without making another worse off.


## References & Further Exploration
[[Markov Decision Processes (MDPs) and Bellman Equations]], [[Decision Theory - Expected Utility and Prospect Theory]]
