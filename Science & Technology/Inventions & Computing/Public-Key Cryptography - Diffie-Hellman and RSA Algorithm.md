---
tags:
  - cryptography
  - cybersecurity
  - computing
category: Science & Technology/Inventions & Computing
related:
  - "[[Hash Functions and Cryptographic SHA-256]]"
  - "[[Quantum Cryptography and Quantum Key Distribution]]"
created: 2026-11-26
---

# Public-Key Cryptography - Diffie-Hellman and RSA Algorithm

## Overview
Public-Key Cryptography (Asymmetric Cryptography) uses mathematically paired keys—a public key for encryption and a private key for decryption—solving the key distribution problem over insecure networks.

---

## 1. Theoretical Foundations & Governing Principles
Diffie-Hellman Key Exchange: Two parties compute a shared secret over an insecure channel using modular exponentiation: $K = (g^a)^b \equiv (g^b)^a \pmod p$. Security relies on the discrete logarithm problem.

---

## 2. Structural Mechanics & Scientific Analysis
The RSA Encryption Algorithm: Select large primes $p, q$, compute modulus $n = pq$ and totient $\phi(n) = (p-1)(q-1)$. Public exponent $e$ and private exponent $d$ satisfy $ed \equiv 1 \pmod{\phi(n)}$. Factoring $n$ is computationally intractable for classical computers.

---

## 3. Real-World Applications & Technological Impact
HTTPS TLS/SSL secure web browsing, SSH encrypted remote server terminal access, digital signatures, and cryptocurrency transactions.

---

## Key Terms
- **Asymmetric Encryption**: Cryptographic system utilizing paired public and private keys for encryption and decryption.
- **Modular Arithmetic**: System of arithmetic for integers where numbers wrap around upon reaching a fixed modulus value.
- **Trapdoor Function**: Mathematical function easy to compute in one direction but virtually impossible to invert without private trapdoor information.
