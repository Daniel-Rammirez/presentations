# Post-Quantum Cryptography: Lattice-Based Algorithms

## Overview

This repository contains a PDF presentation I delivered in **February 2025** at **Labrys**, where I worked at the time. The talk introduces the fundamentals of post-quantum cryptography (PQC), with a focus on **lattice-based algorithms** — the leading family of quantum-resistant cryptographic primitives.

The goal is to explain why current cryptographic systems are vulnerable to quantum computers, how lattice problems fill the security gap, and how practical algorithms like **CRYSTALS-Kyber** (encryption) and **CRYSTALS-Dilithium** (signatures) work under the hood.

---

## Contents of the Presentation

1. **Historical context**
   - From Diffie–Hellman (1976) to ECDSA (1992) and early lattice cryptography (2004).

2. **Hard math problems in classical crypto**
   - Discrete Logarithm Problem (DLP), Integer Factorization, Elliptic Curve DLP.

3. **Shor’s algorithm**
   - How quantum computers break factorization and DLP (with the N=15 example).

4. **The shift to post-quantum crypto**
   - Ajtai’s 1996 breakthrough: worst-case to average-case reduction for lattice problems.

5. **Lattice basics**
   - Definition, basis (good vs. bad), Shortest Independent Vector Problem (SIVP).

6. **Practical lattice problems**
   - Short Integer Solutions (SIS) for hash functions and signatures (Dilithium).
   - Learning with Errors (LWE) for public-key encryption (Kyber).

7. **NIST standardization**
   - 82 submissions → 11 finalists → 3 standards (2023).
   - Lattice-based winners: **Kyber**, **Dilithium**, and **Falcon**.

8. **How Kyber works (step‑by‑step)**
   - Without errors → with errors (LWE) → modular arithmetic.
   - Encryption & decryption walkthrough.

9. **Final thoughts**
   - Timeline: current crypto deprecated by 2030, disallowed after 2035.
   - Impact on Bitcoin, Ethereum, and blockchains (key generation/storage).

---

## Why This Matters

- Quantum computers (when mature) will break RSA, ECC, and ECDSA using Shor’s algorithm.
- Lattice-based problems remain hard for both classical and quantum computers.
- NIST has already finalized the first PQC standards – migration is starting now.

---

## File

- `Lattice based cryptography.pdf` – the original slide deck.

---

## How to Use This

1. Clone the repo or download the PDF.
2. Open the PDF to view the full presentation (25 pages).
3. Use this `README.md` as a study guide or as context before watching/reading the slides.

---

## Author

**Daniel Ramirez**  
Presentation given at **Labrys**, February 2025.

---

## References

- NIST Post-Quantum Cryptography Standardization – [https://csrc.nist.gov/projects/post-quantum-cryptography](https://csrc.nist.gov/projects/post-quantum-cryptography)
- Shor’s algorithm (1994)
- Ajtai (1996) – Worst-case to average-case reductions for lattices
- CRYSTALS – Kyber & Dilithium specifications

---
