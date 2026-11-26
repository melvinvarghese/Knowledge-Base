---
title: "Relational Database Management Systems (RDBMS) and SQL"
tags: [computing, databases, software-engineering]
related: [[[The Relational Database and SQL - Edgar Codd's Foundation]], [[Distributed Consensus - Paxos and Raft Algorithms]]]
created: 2026-11-26
updated: 2026-11-26
---

# Relational Database Management Systems (RDBMS) and SQL

## Overview
Relational Database Management Systems organize data into structured tables (relations) governed by relational algebra, foundational data integrity rules, and declarative SQL queries.

## Core Mechanics & Foundations
Codd's Relational Model (1970): Edgar F. Codd pioneered tabular relational abstraction where data consists of tuples and attributes independent of physical hardware storage paths, enabling mathematical query optimization via relational algebra operators (select, project, join).

## Modern Applications & Advanced Significance
ACID Transactions & Concurrency: Robust RDBMS architectures enforce ACID properties: Atomicity (all-or-nothing execution), Consistency (schema constraints preserved), Isolation (concurrent transactions execute without interference via locking or Multi-Version Concurrency Control / MVCC), and Durability (committed changes persist via Write-Ahead Logging / WAL).

## Real-World Impact & Systems
Enterprise financial ledgers, transactional e-commerce engines, healthcare record management, ERP systems.

## Key Terminology
- **ACID Properties**: Set of guarantees (Atomicity, Consistency, Isolation, Durability) ensuring reliable database transaction processing.
- **MVCC**: Multi-Version Concurrency Control; technique allowing concurrent reads and writes without table locking by maintaining multiple data versions.
- **Write-Ahead Logging (WAL)**: Protocol where state modifications are written to durable storage logs before being applied to database pages.


## References & Further Exploration
[[The Relational Database and SQL - Edgar Codd's Foundation]], [[Distributed Consensus - Paxos and Raft Algorithms]]
