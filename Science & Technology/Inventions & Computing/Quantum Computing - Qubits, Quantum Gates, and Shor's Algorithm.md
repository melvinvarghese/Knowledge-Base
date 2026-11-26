---
title: "Quantum Computing - Qubits, Quantum Gates, and Shor's Algorithm"
tags: [computing, quantum-computing, physics]
related: [[[Quantum Mechanics - Superposition and Measurement]], [[Public-Key Cryptography - Diffie-Hellman and RSA]]]
created: 2026-11-26
updated: 2026-11-26
---

# Quantum Computing - Qubits, Quantum Gates, and Shor's Algorithm

## Overview
Quantum Computing leverages the quantum mechanical principles of superposition and entanglement to execute specific computational classes exponentially faster than classical computers.

## Core Mechanics & Foundations
Qubits & Unitary Gates: A classical bit holds state 0 or 1. A quantum bit (qubit) exists in a complex superposition state $|\psi\rangle = \alpha |0\rangle + \beta |1\rangle$ with $|\alpha|^2 + |\beta|^2 = 1$. Quantum gates are unitary matrix transformations ($U^\dagger U = I$) operating on the $2^n$-dimensional Hilbert state space, preserving probability norm.

## Modern Applications & Advanced Significance
Shor's & Grover's Algorithms: Peter Shor (1994) demonstrated that quantum computers can factor large integers in polynomial time ($O((\log N)^3)$) using the Quantum Fourier Transform (QFT), threatening current public-key cryptography (RSA/ECC). Grover's algorithm provides quadratic speedup ($O(\sqrt{N})$) for unstructured database search.

## Real-World Impact & Systems
Post-quantum cryptographic migration, quantum chemical simulation for drug discovery, material science catalyst design.

## Key Terminology
- **Qubit**: Basic unit of quantum information capable of existing in superpositions of basis states $|0angle$ and $|1angle$.
- **Quantum Entanglement**: Phenomenon where the quantum states of two or more particles cannot be described independently.
- **Shor's Algorithm**: Quantum algorithm for prime factorization running in polynomial time on quantum circuits.


## References & Further Exploration
[[Quantum Mechanics - Superposition and Measurement]], [[Public-Key Cryptography - Diffie-Hellman and RSA]]
