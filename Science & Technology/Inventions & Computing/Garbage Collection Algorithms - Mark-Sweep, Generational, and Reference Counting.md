---
title: "Garbage Collection Algorithms - Mark-Sweep, Generational, and Reference Counting"
tags: [computing, programming-languages, memory-management]
related: [[[Virtual Memory - Paging, Page Tables, and Translation Lookaside Buffers]], [[Compilers and Interpreters - Lexing, Parsing, and LLVM Intermediate Representation]]]
created: 2026-11-26
updated: 2026-11-26
---

# Garbage Collection Algorithms - Mark-Sweep, Generational, and Reference Counting

## Overview
Automated Garbage Collection (GC) reclaims dynamic heap memory allocated to objects that are no longer accessible by an executing application program.

## Core Mechanics & Foundations
Reference Counting & Cyclic Memory: Increments an object's reference counter when assigned and decrements when unreferenced, freeing memory immediately when count reaches zero (e.g., Python, Swift). However, reference counting cannot reclaim isolated cyclic references ($A \to B \to A$) without supplementary cycle detectors.

## Modern Applications & Advanced Significance
Tracing Collectors & Generational Hypothesis: Tracing collectors (Mark-Sweep and Copying) traverse object graphs from root pointers, marking reachable objects and sweeping unreferenced objects. The Weak Generational Hypothesis observes that most allocated objects die very young. High-performance runtimes (Java JVM, V8) segregate the heap into Young and Old generations, running frequent fast minor GCs on young objects.

## Real-World Impact & Systems
High-level managed language runtimes (Java, Go, JavaScript, Python, C#), high-throughput web backends.

## Key Terminology
- **Garbage Collection**: Automated memory management reclaiming heap memory occupied by unreachable objects.
- **Mark-Sweep**: Two-phase garbage collection algorithm that marks reachable objects and sweeps unmarked memory into free lists.
- **Generational Hypothesis**: Empirical observation in computing that most newly allocated objects have very short lifetimes.


## References & Further Exploration
[[Virtual Memory - Paging, Page Tables, and Translation Lookaside Buffers]], [[Compilers and Interpreters - Lexing, Parsing, and LLVM Intermediate Representation]]
