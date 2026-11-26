---
tags:
  - computing
  - databases
  - distributed-systems
category: Science & Technology/Inventions & Computing
related:
  - "[[Relational Databases - SQL and Edgar Codd's Relational Model]]"
  - "[[Cloud Computing - Virtualization, Containers, and Microservices]]"
created: 2026-11-26
---

# Non-Relational Databases - NoSQL, Key-Value, and Graph Stores

## Overview
NoSQL Databases are non-relational distributed databases designed for horizontal scalability, high-velocity writes, and flexible schema-less data storage across large clusters.

---

## 1. Theoretical Foundations & Governing Principles
The CAP Theorem: A distributed data store can simultaneously provide at most two of three guarantees: Consistency ($C$), Availability ($A$), and Partition Tolerance ($P$).

---

## 2. Structural Mechanics & Scientific Analysis
The Four NoSQL Archetypes: 1. Key-Value Stores (Redis); 2. Document Stores (MongoDB JSON documents); 3. Wide-Column Stores (Cassandra); 4. Graph Databases (Neo4j for connected social graphs).

---

## 3. Real-World Applications & Technological Impact
Social network graph traversals, real-time web caching tiers, big data analytics pipelines, and IoT sensor telemetry ingestion.

---

## Key Terms
- **CAP Theorem**: Theorem stating distributed systems must trade off between consistency and availability under partition.
- **Eventual Consistency**: Consistency model guaranteeing all replicas converge to identical values given sufficient time.
- **Sharding**: Database partitioning strategy dividing large datasets across multiple independent server nodes.
