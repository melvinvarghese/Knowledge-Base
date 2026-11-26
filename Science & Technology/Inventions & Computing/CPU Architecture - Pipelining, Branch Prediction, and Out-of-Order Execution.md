---
title: "CPU Architecture - Pipelining, Branch Prediction, and Out-of-Order Execution"
tags: [computing, computer-architecture, hardware]
related: [[[Semiconductor Physics and the Silicon Transistor]], [[Virtual Memory - Paging, Page Tables, and Translation Lookaside Buffers]]]
created: 2026-11-26
updated: 2026-11-26
---

# CPU Architecture - Pipelining, Branch Prediction, and Out-of-Order Execution

## Overview
Modern Central Processing Units (CPUs) maximize Instruction-Level Parallelism (ILP) through multi-stage execution pipelines, speculative branch predictors, and dynamic out-of-order execution engines.

## Core Mechanics & Foundations
Instruction Pipelining & Hazards: Divides instruction execution into sequential stages (Fetch, Decode, Execute, Memory Access, Write-back). Hardware hazards (data dependencies, structural resource conflicts, and control branch delays) are resolved via register forwarding and hardware stalls (bubbles).

## Modern Applications & Advanced Significance
Branch Prediction & Out-of-Order (OoO) Engines: Tomasulo's algorithm and reservation stations allow instructions to execute dynamically as soon as their operand data dependencies are ready, rather than in program order. Modern TAGE branch predictors achieve >97% accuracy; mispredicted branches trigger pipeline flushes and rollback of speculative states via the Reorder Buffer (ROB).

## Real-World Impact & Systems
High-performance supercomputing, modern consumer microprocessors (x86-64, ARM Cortex, Apple Silicon).

## Key Terminology
- **Instruction Pipeline**: Technique decomposing instruction execution into multiple sequential stages to process instructions concurrently.
- **Branch Predictor**: Hardware digital circuit attempting to guess the outcome of conditional branch instructions before execution.
- **Out-of-Order Execution**: Paradigm where instructions execute dynamically based on operand availability rather than compiler sequence.


## References & Further Exploration
[[Semiconductor Physics and the Silicon Transistor]], [[Virtual Memory - Paging, Page Tables, and Translation Lookaside Buffers]]
