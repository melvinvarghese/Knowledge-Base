---
title: "Database Indexing - B-Trees, LSM-Trees, and Hash Indexes"
tags: [computing, databases, algorithms]
related: [[[Relational Database Management Systems (RDBMS) and SQL]], [[Asymptotic Analysis and Big O Notation]]]
created: 2026-11-26
updated: 2026-11-26
---

# Database Indexing - B-Trees, LSM-Trees, and Hash Indexes

## Overview
Database Indexes are specialized data structures that accelerate data retrieval operations at the cost of additional storage and slower write operations.

## Core Mechanics & Foundations
B+ Trees for Read-Heavy Workloads: Self-balancing $M$-way search trees optimized for block storage. All data records are stored in leaf nodes linked sequentially, facilitating fast range queries ($O(\log N)$ point lookups and $O(K)$ sequential scans). Standard in traditional RDBMS engines (PostgreSQL, MySQL InnoDB).

## Modern Applications & Advanced Significance
Log-Structured Merge-Trees (LSM-Trees) for Write-Heavy Workloads: Buffer incoming writes sequentially in memory (MemTable) backed by a write-ahead log. Flushed immutable SSTables on disk are periodically consolidated via background compaction. Maximizes sequential write performance at the expense of read amplification (Cassandra, RocksDB).

## Real-World Impact & Systems
Search engine inverted indexes, high-throughput financial time-series logging, spatial GIS indexing (R-Trees).

## Key Terminology
- **B+ Tree**: Self-balancing tree data structure storing data keys in leaves with high branching factor for disk block efficiency.
- **LSM-Tree**: Log-Structured Merge-Tree; write-optimized storage structure converting random disk writes into sequential append logs.
- **Compaction**: Background process in LSM-trees merging multiple sorted SSTables to remove deleted keys and duplicates.


## References & Further Exploration
[[Relational Database Management Systems (RDBMS) and SQL]], [[Asymptotic Analysis and Big O Notation]]
