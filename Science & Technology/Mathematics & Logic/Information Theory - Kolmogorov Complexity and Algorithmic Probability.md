---
title: "Information Theory - Kolmogorov Complexity and Algorithmic Probability"
tags: [mathematics, computer-science, information-theory]
related: [[[Information Theory - Shannon Entropy and Channel Capacity]], [[Turing Machines and the Halting Problem]]]
created: 2026-11-26
updated: 2026-11-26
---

# Information Theory - Kolmogorov Complexity and Algorithmic Probability

## Overview
Kolmogorov Complexity (algorithmic information theory) defines the absolute information content of an object as the length of the shortest computer program that outputs it.

## Core Mechanics & Foundations
Formal Definition: For a binary string $s$, Kolmogorov complexity $K(s) = \min_{p} \{ |p| : U(p) = s \}$, where $U$ is a fixed universal Turing machine. An incompressibility theorem proves that $K(s)$ is strictly uncomputable for general strings due to reduction from the Halting Problem.

## Modern Applications & Advanced Significance
Algorithmic Probability & Solomonoff Induction: Solomonoff induction defines the universal prior probability of string $s$ as $M(s) = \sum_{p: U(p) = s*} 2^{-|p|}$, formalizing Occam's Razor by assigning exponentially higher probability to hypotheses with short algorithmic program representations.

## Real-World Impact & Systems
Occam's razor formalization, lossless data compression limit evaluation, minimum description length (MDL) principle in machine learning.

## Key Terminology
- **Kolmogorov Complexity**: Length of the shortest computer program that outputs a given string and halts.
- **Solomonoff Induction**: Mathematical formalization of universal induction and prediction based on algorithmic probability.
- **Incompressibility**: Property of a string whose Kolmogorov complexity is approximately equal to its literal length.


## References & Further Exploration
[[Information Theory - Shannon Entropy and Channel Capacity]], [[Turing Machines and the Halting Problem]]
