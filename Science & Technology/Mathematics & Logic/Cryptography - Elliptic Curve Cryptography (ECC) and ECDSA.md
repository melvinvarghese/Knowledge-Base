---
title: "Cryptography - Elliptic Curve Cryptography (ECC) and ECDSA"
tags: [mathematics, cryptography, number-theory, security]
related: [[[Public-Key Cryptography - Diffie-Hellman and RSA]], [[Number Theory - Modular Arithmetic, Euler's Totient, and RSA]]]
created: 2026-11-26
updated: 2026-11-26
---

# Cryptography - Elliptic Curve Cryptography (ECC) and ECDSA

## Overview
Elliptic Curve Cryptography (ECC) achieves public-key security equivalent to RSA using exponentially smaller cryptographic key sizes by leveraging the algebraic geometry of elliptic curves over finite fields.

## Core Mechanics & Foundations
Weierstrass Form & Point Addition Group Law: An elliptic curve over finite field $\mathbb{F}_p$ satisfies: $y^2 \equiv x^3 + a x + b \pmod p$. Points on the curve together with an ideal point at infinity ($\mathcal{O}$) form an abelian group under the geometric chord-and-tangent addition rule: drawing a line through points $P$ and $Q$ intersects the curve at a third point $R$, which is reflected across the x-axis to yield $P + Q$.

## Modern Applications & Advanced Significance
The Elliptic Curve Discrete Logarithm Problem (ECDLP): Given base point $G$ and public key point $Q = d \cdot G$ (multiplying $G$ by private integer $d$ via double-and-add point addition), computing private key $d$ is mathematically intractable. A 256-bit ECC key provides equivalent cryptographic security to a massive 3072-bit RSA key.

## Real-World Impact & Systems
Bitcoin and Ethereum transaction signatures (ECDSA on secp256k1), TLS/SSL encrypted web handshakes (ECDH), Apple Secure Enclave.

## Key Terminology
- **Elliptic Curve**: Smooth algebraic curve defined by the equation $y^2 = x^3 + ax + b$ possessing an abelian group structure.
- **ECDLP**: Elliptic Curve Discrete Logarithm Problem; the computationally intractable task of finding integer $d$ given points $G$ and $dG$.
- **ECDSA**: Elliptic Curve Digital Signature Algorithm; cryptographic standard used to create unforgeable digital signatures.


## References & Further Exploration
[[Public-Key Cryptography - Diffie-Hellman and RSA]], [[Number Theory - Modular Arithmetic, Euler's Totient, and RSA]]
