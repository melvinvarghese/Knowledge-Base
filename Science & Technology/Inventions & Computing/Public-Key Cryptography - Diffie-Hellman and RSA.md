---
title: "Public-Key Cryptography - Diffie-Hellman and RSA"
tags: [computing, cryptography, security, inventions]
related: [[[Number Theory - Modular Arithmetic, Euler's Totient, and RSA]], [[The Internet Protocol Suite - TCP-IP and Packet Switching]]]
created: 2026-11-26
updated: 2026-11-26
---

# Public-Key Cryptography - Diffie-Hellman and RSA

## Overview
Public-Key Cryptography revolutionized digital security by introducing asymmetric key pairs, enabling private communication across unencrypted channels without prior secret exchange.

## Core Mechanics & Foundations
Diffie-Hellman Key Exchange (1976): Whitfield Diffie and Martin Hellman solved key distribution using the discrete logarithm problem over finite cyclic groups: Alice and Bob compute shared secret $K = g^{ab} \pmod p$ from public values $g^a$ and $g^b$, which an eavesdropper cannot compute in polynomial time.

## Modern Applications & Advanced Significance
RSA & Digital Signatures: Rivest, Shamir, and Adleman (1977) introduced asymmetric trapdoor functions based on integer prime factorization. Beyond encryption, public keys allow digital signatures where a sender encrypts a hash with their private key, providing unforgeable authenticity and non-repudiation.

## Real-World Impact & Systems
Secure web browsing (HTTPS/TLS), SSH remote administration, blockchain cryptographic signatures, secure email (PGP).

## Key Terminology
- **Asymmetric Cryptography**: Cryptographic system using pairs of keys: public keys for encryption and private keys for decryption.
- **Diffie-Hellman**: Protocol allowing two parties to establish a shared secret over an insecure communication channel.
- **Discrete Logarithm**: The mathematically difficult problem of finding integer $k$ such that $g^k \equiv h \pmod p$.


## References & Further Exploration
[[Number Theory - Modular Arithmetic, Euler's Totient, and RSA]], [[The Internet Protocol Suite - TCP-IP and Packet Switching]]
