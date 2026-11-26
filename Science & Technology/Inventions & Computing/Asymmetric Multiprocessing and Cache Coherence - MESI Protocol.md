---
title: "Asymmetric Multiprocessing and Cache Coherence - MESI Protocol"
tags: [computing, computer-architecture, hardware]
related: [[[CPU Architecture - Pipelining, Branch Prediction, and Out-of-Order Execution]], [[Concurrency - Mutexes, Semaphores, and Deadlock Prevention]]]
created: 2026-11-26
updated: 2026-11-26
---

# Asymmetric Multiprocessing and Cache Coherence - MESI Protocol

## Overview
Multi-core microprocessors rely on hardware Cache Coherence protocols to guarantee that concurrent processor cores maintain a consistent, unified view of shared memory.

## Core Mechanics & Foundations
The Cache Coherence Problem: Each core possesses private L1 and L2 caches holding local copies of shared main memory lines. If Core A modifies a shared variable cached in Core B, Core B risks reading stale data unless an interconnect protocol enforces consistency.

## Modern Applications & Advanced Significance
The MESI Protocol: A 4-state invalidation-based snooping protocol: Modified (dirty line, present only in local cache), Exclusive (clean line, matches memory, present only here), Shared (clean line, potentially present in multiple caches), and Invalid (stale line, cannot be read). Bus snooping triggers automated cache invalidations or write-backs upon conflicting memory accesses.

## Real-World Impact & Systems
Multi-threaded server computing, symmetric multiprocessing (SMP) kernel schedulers, high-performance computing.

## Key Terminology
- **Cache Coherence**: Hardware guarantee that all processor cores observe memory writes in a uniform, logically consistent order.
- **MESI Protocol**: Four-state cache coherence protocol categorizing cache lines into Modified, Exclusive, Shared, or Invalid.
- **Bus Snooping**: Monitoring mechanism where CPU cache controllers listen to memory bus traffic to detect and invalidate shared stale lines.


## References & Further Exploration
[[CPU Architecture - Pipelining, Branch Prediction, and Out-of-Order Execution]], [[Concurrency - Mutexes, Semaphores, and Deadlock Prevention]]
