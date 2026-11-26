---
title: "Graph Theory - Minimum Spanning Trees (Kruskal and Prim) and Flow Networks"
tags: [mathematics, graph-theory, algorithms, discrete-mathematics]
related: [[[Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring]], [[Graph Algorithms - BFS, DFS, Dijkstra, and A-Star]]]
created: 2026-11-26
updated: 2026-11-26
---

# Graph Theory - Minimum Spanning Trees (Kruskal and Prim) and Flow Networks

## Overview
Network optimization in Graph Theory finds minimum-cost connected subgraphs and maximum flow capacity through constrained directed networks.

## Core Mechanics & Foundations
Minimum Spanning Trees (MST): For a connected undirected weighted graph $G = (V, E)$, an MST is a tree connecting all vertices with minimal total edge weight: 1. Kruskal's Algorithm: A greedy algorithm that sorts edges and adds them if they do not create a cycle using Disjoint-Set (Union-Find) data structures in $O(E \log E)$ time; 2. Prim's Algorithm: Grows a single tree outward from an arbitrary root using a priority queue in $O(E \log V)$ time.

## Modern Applications & Advanced Significance
Flow Networks & The Max-Flow Min-Cut Theorem: In a directed network with source $s$, sink $t$, and edge capacities $c(u, v)$, the maximum amount of flow passing from $s$ to $t$ is strictly equal to the minimum capacity of an $s-t$ cut that partitions the graph (Ford-Fulkerson algorithm).

## Real-World Impact & Systems
Electrical power grid layout optimization, telecommunications fiber optic network routing, logistics transportation flow.

## Key Terminology
- **Minimum Spanning Tree**: Subset of edges in a connected edge-weighted graph that connects all vertices together without cycles and with minimum total weight.
- **Max-Flow Min-Cut**: Fundamental theorem equating the maximal network flow from source to sink with the minimal bottleneck capacity cut.
- **Union-Find**: Data structure tracking a set of elements partitioned into disjoint subsets supporting near-constant time union and find operations.


## References & Further Exploration
[[Graph Theory - Eulerian Paths, Hamiltonian Cycles, and Coloring]], [[Graph Algorithms - BFS, DFS, Dijkstra, and A-Star]]
