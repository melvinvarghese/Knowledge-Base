---
title: "Distributed Consensus - Paxos and Raft Algorithms"
tags: [computing, distributed-systems, algorithms]
related: [[[Relational Database Management Systems (RDBMS) and SQL]], [[The Byzantine Generals Problem and Blockchain Consensus]]]
created: 2026-11-26
updated: 2026-11-26
---

# Distributed Consensus - Paxos and Raft Algorithms

## Overview
Distributed Consensus algorithms enable a cluster of independent, unreliable networked nodes to reach unanimous agreement on state machine updates despite network partitions and node crashes.

## Core Mechanics & Foundations
Paxos (Leslie Lamport, 1998): Guarantees safety under asynchronous network conditions via two-phase voting: Prepare/Promise (proposer acquires ballot leadership) and Accept/Accepted (nodes commit proposed values if a majority quorum agrees). Though mathematically elegant, basic Paxos is notoriously difficult to implement in practical multi-decree systems.

## Modern Applications & Advanced Significance
Raft (Ongaro & Ousterhout, 2014): Decomposes consensus into understandable, modular sub-problems: explicit Leader Election (heartbeats and randomized election timeouts), Log Replication (leader appends entries and commits upon majority replication), and Safety (leaders must contain all previously committed log entries).

## Real-World Impact & Systems
Cloud infrastructure state stores (ZooKeeper, etcd, Consul), distributed databases (CockroachDB, Google Spanner), Kubernetes control planes.

## Key Terminology
- **Distributed Consensus**: Process of reaching agreement among multiple nodes on a single data value or state transition.
- **Quorum**: Strict majority of nodes ($N/2 + 1$) required to make progress and prevent split-brain conditions.
- **Log Replication**: Mechanism in consensus protocols where state-machine command logs are synchronized across cluster replicas.


## References & Further Exploration
[[Relational Database Management Systems (RDBMS) and SQL]], [[The Byzantine Generals Problem and Blockchain Consensus]]
