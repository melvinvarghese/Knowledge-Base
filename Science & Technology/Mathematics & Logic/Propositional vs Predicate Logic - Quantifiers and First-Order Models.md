---
tags:
  - mathematical-logic
  - philosophy-of-logic
  - computer-science
category: Science & Technology/Mathematics & Logic
related:
  - "[[Boolean Algebra - Logic Gates and Digital Circuit Minimization]]"
  - "[[Fuzzy Logic - Membership Functions and Approximate Reasoning]]"
created: 2026-11-26
---

# Propositional vs Predicate Logic - Quantifiers and First-Order Models

## Overview
Formal Logic formalizes valid deductive inference, advancing from Propositional Logic (truth tables of atomic statements) to First-Order Predicate Logic incorporating **quantifiers** and internal predicates.

---

## 1. Theoretical Foundations & Governing Principles
Predicate Logic Grammar & Quantifiers: Introduces predicates $P(x)$ operating on domain objects, coupled with the Universal Quantifier ($\forall x$: 'for all x') and Existential Quantifier ($\exists x$: 'there exists an x'), enabling statements like: $\forall x (\text{Human}(x) \rightarrow \text{Mortal}(x))$.

---

## 2. Structural Analysis & Mathematical Modeling
Completeness & Soundness (Gödel's Completeness Theorem): First-Order Predicate Logic is sound (proven statements are true) and semantically complete (all logically valid formulas have formal deductive proofs), unlike second-order systems.

---

## 3. Real-World Applications & Scientific Impact
Automated theorem provers (Z3 SMT solver), relational database SQL calculus queries, formal software verification.

---

## Key Terms
- **Predicate Logic**: Formal logic system utilizing predicates, variables, and quantifiers to represent propositions.
- **Universal Quantifier ($\forall$)**: Logical symbol expressing that a property applies to all members of a domain of discourse.
- **Soundness**: Property of a logical system that any statement formally provable within it is semantically true.
