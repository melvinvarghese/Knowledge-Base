---
title: "Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring"
tags: [mathematics, graph-theory, discrete-mathematics]
related: [[[The P versus NP Problem - Complexity Classes and Verification]], [[Graph Algorithms - BFS, DFS, Dijkstra, and A-Star]]]
created: 2026-11-26
updated: 2026-11-26
---

# Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring

## Overview
Graph Theory studies relational structures composed of vertices (nodes) and edges, modeling pairwise relationships across networks, geography, and computation.

## Core Mechanics & Foundations
Eulerian Paths vs Hamiltonian Cycles: An Eulerian path traverses every edge exactly once and exists if and only if a connected graph has at most two vertices of odd degree (Euler's Seven Bridges of Königsberg, 1736, polynomial time). In contrast, finding a Hamiltonian cycle—traversing every vertex exactly once—is NP-complete.

## Modern Applications & Advanced Significance
Graph Coloring & The Four Color Theorem: A vertex coloring assigns colors such that no adjacent vertices share a color. The chromatic number $\chi(G)$ is the minimal colors required. The Four Color Theorem (proven with computer assistance by Appel & Haken, 1976) proves that any planar graph requires at most 4 colors.

## Real-World Impact & Systems
Network routing protocols, compiler register allocation, map cartography, scheduling and timetable optimization.

## Key Terminology
- **Eulerian Path**: Trail in a finite graph that visits every edge exactly once.
- **Hamiltonian Cycle**: Closed loop in a graph that visits each vertex exactly once.
- **Chromatic Number**: Minimum number of colors needed to color the vertices of a graph such that no two adjacent vertices share a color.


## References & Further Exploration
[[The P versus NP Problem - Complexity Classes and Verification]], [[Graph Algorithms - BFS, DFS, Dijkstra, and A-Star]]
