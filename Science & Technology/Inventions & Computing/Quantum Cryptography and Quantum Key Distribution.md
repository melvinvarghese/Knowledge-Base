---
tags:
  - cryptography
  - quantum-computing
  - cybersecurity
  - physics
category: Science & Technology/Inventions & Computing
related:
  - "[[Quantum Mechanics and Quantum States]]"
  - "[[Cybersecurity - Encryption, Firewalls, and Exploits]]"
  - "[[The Structure of the Internet]]"
created: 2026-11-25
---

# Quantum Cryptography and Quantum Key Distribution

## Overview
**Quantum Cryptography** is an approach to cybersecurity that leverages the fundamental laws of **quantum mechanics** rather than mathematical complexity to achieve provably secure communications. While conventional public-key cryptography (e.g., RSA and Elliptic Curve Cryptography) relies on unproven mathematical assumptions—such as the computational difficulty of prime factorization, which quantum algorithms like **Shor's Algorithm** can break—quantum cryptography relies on physical principles like the **No-Cloning Theorem** and the **Heisenberg Uncertainty Principle**. Its primary practical realization is **Quantum Key Distribution (QKD)**.

```
       [ Alice (Transmitter) ]                  [ Bob (Receiver) ]
      Generates Random Bits &                  Chooses Random Bases
      Random Polarization Bases               (Rectilinear / Diagonal)
                 │                                       │
                 ▼                                       ▼
      [ Single Photon Stream ] ──Quantum Channel──> [ Single Photon Detectors ]
                                      │
                         [ Eve (Eavesdropper Intercept) ]
                         - Measurement Alters Quantum State
                         - Incurred Error Rate Warns Alice & Bob!
                                      │
                 ◄──Public Classical Channel (Sifting)──►
                 - Compares Chosen Bases
                 - Calculates Quantum Bit Error Rate (QBER)
                                      │
                                      ▼
                       [ Unconditional Secret Key ]
                                      │
                                      ▼
                   [ One-Time Pad (OTP) Data Encryption ]
```

---

## 1. Theoretical Foundations
Quantum cryptography derives its unbreakable security from core physical principles:
1. **The No-Cloning Theorem**: In quantum mechanics, it is mathematically impossible to create an identical copy of an arbitrary unknown quantum state ($|\psi\rangle$) without altering the original. An eavesdropper ("Eve") cannot silently duplicate photons carrying cryptographic data.
2. **Measurement Collapse (Wavefunction Collapse)**: Observing or measuring a quantum superposition alters the system. Any attempt by an eavesdropper to measure intercepted photons introduces measurable disturbances and transmission errors.

---

## 2. The BB84 Protocol
Proposed by Charles Bennett and Gilles Brassard in 1984, **BB84** is the foundational protocol for Quantum Key Distribution:
1. **State Preparation**: Alice prepares individual photons polarized in one of four states across two non-orthogonal bases:
   - **Rectilinear Basis ($+$)**: Horizontal ($0^\circ$, representing Bit `0`) or Vertical ($90^\circ$, representing Bit `1`).
   - **Diagonal Basis ($\times$)**: Diagonal Left ($45^\circ$, representing Bit `0`) or Diagonal Right ($135^\circ$, representing Bit `1`).
2. **Transmission**: Alice transmits the sequence of single photons through a quantum channel (such as optical fiber or free space).
3. **Measurement**: For each arriving photon, Bob randomly selects either the Rectilinear ($+$) or Diagonal ($\times$) measurement basis.
4. **Sifting Phase**: Over a public classical channel, Alice and Bob publicly announce *which basis* they used for each photon, without disclosing the actual bit values:
   - When Bob randomly chose the **same basis** as Alice, their bits match deterministically.
   - When their bases differed, the measurement outcome is completely random, and those bits are discarded.
5. **Error Estimation**: Alice and Bob compare a small random subset of their remaining bits to determine the **Quantum Bit Error Rate (QBER)**:
   - If an eavesdropper intercepted and measured photons, quantum collapse introduces an expected 25% error rate on intercepted bits.
   - If the observed QBER is below a strict threshold (typically ~11%), the channel is mathematically proven to be secure. The shared bits form a secret key.
   - If the QBER exceeds the threshold, eavesdropping is detected; the entire key is aborted, and communication halts.

---

## 3. Real-World Implementations
- **Fiber-Optic QKD Networks**: Deployed across metropolitan fiber rings in Europe, China, and the US, providing secure cryptographic key exchange between data centers and financial institutions over distances up to 100–200 km before optical attenuation limits single-photon detection.
- **Satellite Quantum Communications**: In 2016, China launched the **Micius (Mozi)** satellite, demonstrating space-to-ground free-space QKD over distances exceeding **1,200 kilometers**, overcoming the terrestrial fiber distance barrier.
- **Measurement-Device-Independent QKD (MDI-QKD)**: Advanced architectures designed to close real-world hardware side-channel attacks, such as detector blinding and timing vulnerabilities.

---

## 4. The One-Time Pad (OTP) Synergism
When a cryptographic key generated via QKD is paired with a **One-Time Pad (OTP)** cipher:
- The key must be completely random, as long as the message, used only once, and kept secret.
- Claude Shannon mathematically proved in 1949 that OTP encryption provides **information-theoretic security (unconditional security)**—it is mathematically impossible to decrypt, even with infinite computational power.

---

## Key Terms
- **Quantum Key Distribution (QKD)**: Secure communication method utilizing quantum properties to exchange symmetric encryption keys between remote parties.
- **No-Cloning Theorem**: Quantum mechanical theorem stating that an identical duplicate of an unknown quantum state cannot be created.
- **Quantum Bit Error Rate (QBER)**: The ratio of erroneous bits to total received bits in a QKD transmission, used to detect eavesdropping attempts.
