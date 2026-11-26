---
title: "Database Sharding and Distributed Transactions - Two-Phase Commit (2PC)"
tags: [computing, databases, distributed-systems]
related: [[[Relational Database Management Systems (RDBMS) and SQL]], [[Distributed Consensus - Paxos and Raft Algorithms]]]
created: 2026-11-26
updated: 2026-11-26
---

# Database Sharding and Distributed Transactions - Two-Phase Commit (2PC)

## Overview
Database Sharding horizontally partitions massive relational tables across independent database nodes, requiring specialized protocols for cross-shard distributed transactions.

## Core Mechanics & Foundations
Horizontal Sharding & Consistent Hashing: Datasets exceeding single-node capacity are partitioned horizontally across shards using range-based or hash-based keys. Consistent Hashing distributes shard partitions along a virtual hash ring, minimizing data rebalancing churn when scaling nodes up or down.

## Modern Applications & Advanced Significance
Two-Phase Commit Protocol (2PC): Guarantees atomicity across multiple distributed shards via a coordinator: 1. Prepare Phase (coordinator asks all participating shards to write updates to WAL and vote YES or NO); 2. Commit Phase (if all vote YES, coordinator broadcasts COMMIT; if any vote NO, coordinator broadcasts ROLLBACK). While ensuring safety, 2PC is a blocking protocol vulnerable to coordinator failure.

## Real-World Impact & Systems
Large-scale distributed relational databases (Google Spanner, CockroachDB, Vitess), global e-commerce order processing.

## Key Terminology
- **Sharding**: Horizontal database partitioning splitting large tables into smaller, faster individual node segments.
- **Two-Phase Commit (2PC)**: Atomic distributed commitment protocol ensuring all participating nodes commit or abort a transaction together.
- **Consistent Hashing**: Distributed hashing scheme where adding or removing a bucket does not significantly reassign keys.


## References & Further Exploration
[[Relational Database Management Systems (RDBMS) and SQL]], [[Distributed Consensus - Paxos and Raft Algorithms]]
