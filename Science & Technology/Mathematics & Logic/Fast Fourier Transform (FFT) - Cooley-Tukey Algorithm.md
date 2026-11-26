---
title: "Fast Fourier Transform (FFT) - Cooley-Tukey Algorithm"
tags: [mathematics, computer-science, algorithms]
related: [[[Fourier Transform and Frequency Domain Analysis]], [[The P versus NP Problem - Complexity Classes and Verification]]]
created: 2026-11-26
updated: 2026-11-26
---

# Fast Fourier Transform (FFT) - Cooley-Tukey Algorithm

## Overview
The Fast Fourier Transform (FFT) is an algorithmic divide-and-conquer breakthrough that computes the Discrete Fourier Transform (DFT) of length $N$ in $O(N \log N)$ time instead of naive $O(N^2)$.

## Core Mechanics & Foundations
Cooley-Tukey Radix-2 Decomposition: For $N = 2^m$, the DFT sum $X_k = \sum_{n=0}^{N-1} x_n e^{-2\pi i n k / N}$ splits into even-indexed and odd-indexed sub-transforms: $X_k = E_k + e^{-2\pi i k / N} O_k$ and $X_{k + N/2} = E_k - e^{-2\pi i k / N} O_k$, reusing intermediate butterfly computations.

## Modern Applications & Advanced Significance
Computational Impact: By reducing operational complexity from $10^{12}$ steps down to $\sim 10^7$ steps for million-point datasets, the FFT made real-time digital telecommunications, audio compression (MP3), radar, and computerized tomography computationally feasible.

## Real-World Impact & Systems
Audio codec engineering, radar pulse compression, telecommunications (OFDM/LTE/5G), seismic data processing.

## Key Terminology
- **FFT**: High-efficiency algorithm computing the Discrete Fourier Transform in $O(N \log N)$ time.
- **Butterfly Operation**: Fundamental 2-point computation unit in Cooley-Tukey FFT combining sub-transform outputs with twiddle factors.
- **Discrete Fourier Transform (DFT)**: Transformation mapping discrete, finite sampled sequences into discrete frequency bins.


## References & Further Exploration
[[Fourier Transform and Frequency Domain Analysis]], [[The P versus NP Problem - Complexity Classes and Verification]]
