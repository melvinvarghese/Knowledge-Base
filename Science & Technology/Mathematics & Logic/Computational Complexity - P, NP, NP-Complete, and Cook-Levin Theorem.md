---
title: "Computational Complexity - P, NP, NP-Complete, and Cook-Levin Theorem"
tags: [mathematics, computer-science, theoretical-computer-science, complexity-theory]
related: [[[The P versus NP Problem - Complexity Classes and Verification]], [[Turing Machines and the Halting Problem]]]
created: 2026-11-26
updated: 2026-11-26
---

# Computational Complexity - P, NP, NP-Complete, and Cook-Levin Theorem

## Overview
Computational Complexity Theory categorizes decision problems according to the asymptotic resources (time and memory space) required for an algorithm to solve them.

## Core Mechanics & Foundations
The P versus NP Classes: Class **P** comprises decision problems solvable by a deterministic Turing machine in polynomial time ($O(n^k)$). Class **NP** (Nondeterministic Polynomial time) comprises problems whose positive solutions can be *verified* in polynomial time, even if finding the solution appears to require exponential search.

## Modern Applications & Advanced Significance
The Cook-Levin Theorem & Karp's 21 NP-Complete Problems: Stephen Cook (1971) and Leonid Levin proved that the Boolean Satisfiability Problem (SAT) is **NP-Complete**—meaning every problem in NP can be reduced to SAT in polynomial time. Richard Karp (1972) proved that 21 fundamental problems (Traveling Salesperson, Clique, Knapsack, Vertex Cover) are NP-complete, proving that if a polynomial-time algorithm exists for any one of them, $P = NP$.

## Real-World Impact & Systems
Foundation of cryptographic security assumptions, algorithmic hardness limits, combinatorial optimization benchmarking.

## Key Terminology
- **NP-Complete**: Class of computational problems in NP to which every other problem in NP can be reduced in polynomial time.
- **Boolean Satisfiability (SAT)**: Problem of determining whether there exists an interpretation that satisfies a given Boolean formula.
- **Polynomial-Time Reduction**: Method of transforming one problem into another such that the transformation takes polynomial time.


## References & Further Exploration
[[The P versus NP Problem - Complexity Classes and Verification]], [[Turing Machines and the Halting Problem]]
