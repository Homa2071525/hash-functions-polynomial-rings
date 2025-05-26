# 🔐 Algebraic Hash Functions Using Polynomial Rings

This project explores the construction of **toy cryptographic hash functions** based on **polynomial rings over finite fields**. It is designed as a learning tool to understand key concepts in algebra, cryptography, and post-quantum security.

## 🎯 Motivation

Cryptographic systems that resist quantum attacks often rely on **structured algebraic foundations**. Polynomial rings such as \( \mathbb{F}_q[x]/(f(x)) \) play a central role in lattice-based and hash-based cryptographic schemes. This project aims to:

- Strengthen understanding of algebraic structures in cryptography
- Implement simple, deterministic hash functions over polynomial rings
- Explore their behavior in terms of collision resistance and the avalanche effect

## 🧪 What This Project Does

- Encodes strings as polynomials in \( \mathbb{F}_p[x] \)
- Reduces them modulo an irreducible polynomial \( f(x) \)
- Outputs fixed-size "hash values" in the ring \( \mathbb{F}_p[x]/(f(x)) \)
- Tests toy hash functions for basic properties like:
  - Collision resistance (hard to find the same outputs)
  - Avalanche effect (small input changes → big output changes)

## 🛠️ Tools and Language

- Python with optional use of SageMath for symbolic computation
- Jupyter Notebook for demonstrations
- No prior experience with SageMath is required; we provide all steps

## ✍️ Educational Value

This repository is part of a self-driven effort to learn about:
- Digital signatures and hash functions
- The role of algebra in post-quantum cryptography
- Constructing hash functions from mathematical first principles

## 📁 Folder Overview

- `src/` — Python/Sage code for hash functions
- `tests/` — Tests for input-output consistency and collisions
- `examples/` — Demo notebook for visualization and walkthrough

## 🧠 Author's Note

This is an educational and exploratory project, not for production use. It is designed to deepen understanding of the algebraic principles behind modern cryptographic techniques.

---

