---
tags:
  - computing
  - databases
  - software-engineering
category: Science & Technology/Inventions & Computing
related:
  - "[[Non-Relational Databases - NoSQL, Key-Value, and Graph Stores]]"
  - "[[Operating Systems - Kernel Architecture and Process Scheduling]]"
created: 2026-11-26
---

# Relational Databases - SQL and Edgar Codd's Relational Model

## Overview
Relational Databases organize data into structured tables (relations) consisting of rows and columns, queried using Structured Query Language (SQL) based on Edgar F. Codd's 1970 mathematical relational algebra.

---

## 1. Theoretical Foundations & Governing Principles
ACID Transaction Guarantees: 1. Atomicity (all-or-nothing execution); 2. Consistency (enforcing schema integrity constraints); 3. Isolation (transactions do not interfere); 4. Durability (committed data survives power loss).

---

## 2. Structural Mechanics & Scientific Analysis
Relational Algebra & Normalization: Mathematical operations (Select $\sigma$, Project $\pi$, Join $\bowtie$) operating on tables normalized to Third Normal Form (3NF) to eliminate data redundancy.

---

## 3. Real-World Applications & Technological Impact
Banking and financial ledger systems, enterprise ERP systems (PostgreSQL, MySQL, Oracle), and airline reservation platforms.

---

## Key Terms
- **ACID**: Set of four properties guaranteeing database transactions are processed reliably.
- **Primary Key**: A unique attribute identifier distinguishing each individual record within a database table.
- **Foreign Key**: Field in a relational table that references the primary key of another table to link records.
