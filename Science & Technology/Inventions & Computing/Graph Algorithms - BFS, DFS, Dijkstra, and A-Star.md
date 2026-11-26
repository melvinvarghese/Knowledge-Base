---
title: "Graph Algorithms - BFS, DFS, Dijkstra, and A-Star"
tags: [computing, algorithms, graph-theory]
related: [[[Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring]], [[Asymptotic Analysis and Big O Notation]]]
created: 2026-11-26
updated: 2026-11-26
---

# Graph Algorithms - BFS, DFS, Dijkstra, and A-Star

## Overview
Graph search and shortest-path algorithms traverse complex networks to find connectivity, topological orderings, and cost-optimal routes.

## Core Mechanics & Foundations
Unweighted Traversal: Breadth-First Search (BFS) explores vertices layer by layer using a FIFO queue, guaranteeing shortest paths on unweighted graphs in $O(V + E)$ time. Depth-First Search (DFS) explores along deep branches using a LIFO stack/recursion, identifying connected components and topological sort orderings.

## Modern Applications & Advanced Significance
Weighted Shortest Paths & Heuristics: Dijkstra's algorithm uses a priority queue (min-heap) to find the shortest path in non-negative weighted graphs in $O((V + E) \log V)$ time. The $A^*$ search algorithm extends Dijkstra by incorporating an admissible heuristic function $h(n)$ (estimated cost to target), focusing search exploration directly toward the goal node.

## Real-World Impact & Systems
GPS satellite navigation (Google Maps), internet packet routing (OSPF protocol), game AI pathfinding, social network friend recommendations.

## Key Terminology
- **Dijkstra's Algorithm**: Algorithm finding the shortest paths between nodes in a graph with non-negative edge weights.
- **A* Search**: Informed search algorithm using path cost plus an admissible heuristic estimate to find optimal paths efficiently.
- **Admissible Heuristic**: Heuristic function that never overestimates the true remaining cost to reach the target goal.


## References & Further Exploration
[[Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring]], [[Asymptotic Analysis and Big O Notation]]
