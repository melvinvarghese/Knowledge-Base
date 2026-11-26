---
title: "Number Theory - Modular Arithmetic, Euler's Totient, and RSA"
tags: [mathematics, number-theory, cryptography]
related: [[[Prime Number Distribution - The Riemann Hypothesis and Prime Number Theorem]], [[Public-Key Cryptography - Diffie-Hellman and RSA]]]
created: 2026-11-26
updated: 2026-11-26
---

# Number Theory - Modular Arithmetic, Euler's Totient, and RSA

## Overview
Modular Arithmetic explores algebraic congruence relations on integers, forming the theoretical bedrock of modern public-key cryptography.

## Core Mechanics & Foundations
Euler's Totient & Fermat's Little Theorem: Euler's totient function $\phi(n)$ counts integers $1 \le k \le n$ coprime to $n$. For prime $p$, $\phi(p) = p - 1$; for product of distinct primes $n = pq$, $\phi(n) = (p-1)(q-1)$. Euler's Theorem states that if $\gcd(a, n) = 1$, then $a^{\phi(n)} \equiv 1 \pmod{n}$, generalising Fermat's Little Theorem ($a^{p-1} \equiv 1 \pmod{p}$).

## Modern Applications & Advanced Significance
The RSA Cryptosystem: RSA leverages the asymmetry between rapid prime multiplication and intractable prime factorization. Public modulus $n = pq$ and encryption exponent $e$ satisfy $\gcd(e, \phi(n)) = 1$. The private decryption key $d$ is the modular inverse $d \equiv e^{-1} \pmod{\phi(n)}$, recovering plaintext via $m \equiv c^d \equiv (m^e)^d \equiv m^{k\phi(n)+1} \equiv m \pmod{n}$.

## Real-World Impact & Systems
Internet TLS/SSL cryptographic encryption, digital signatures, hash tables, pseudorandom number generators.

## Key Terminology
- **Modular Arithmetic**: System of arithmetic for integers where numbers wrap around upon reaching a modulus value.
- **Euler's Totient Function**: Function $\phi(n)$ calculating the number of positive integers up to $n$ that are relatively prime to $n$.
- **Modular Inverse**: Integer $x$ such that $a x \equiv 1 \pmod m$, computable via the Extended Euclidean Algorithm.


## References & Further Exploration
[[Prime Number Distribution - The Riemann Hypothesis and Prime Number Theorem]], [[Public-Key Cryptography - Diffie-Hellman and RSA]]
