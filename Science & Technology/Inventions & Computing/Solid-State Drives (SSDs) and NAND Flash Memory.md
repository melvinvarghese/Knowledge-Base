---
title: "Solid-State Drives (SSDs) and NAND Flash Memory"
tags: [computing, hardware, computer-architecture]
related: [[[Semiconductor Physics and the Silicon Transistor]], [[Operating System Kernels - Monolithic vs Microkernel Architectures]]]
created: 2026-11-26
updated: 2026-11-26
---

# Solid-State Drives (SSDs) and NAND Flash Memory

## Overview
Solid-State Drives (SSDs) store non-volatile data electronically using floating-gate or charge-trap NAND flash memory, eliminating mechanical latency inherent to hard disk drives.

## Core Mechanics & Foundations
NAND Flash Physics & Block Erasure: NAND cells store charges in isolated floating gates to modulate threshold voltage. Flash memory possesses an asymmetrical physical constraint: reads and writes occur in small pages (typically 4–16 KB), but updates cannot overwrite existing data—memory must be erased in large blocks (typically 2–8 MB) via high-voltage clearing.

## Modern Applications & Advanced Significance
The Flash Translation Layer (FTL) & Wear Leveling: The onboard FTL controller abstracts flash blocks, mapping logical block addresses (LBA) to physical flash pages. Dynamic Wear Leveling distributes write-erase cycles evenly across physical cells to prevent premature cell breakdown; background Garbage Collection and TRIM commands clean stale blocks.

## Real-World Impact & Systems
Consumer laptops and smartphones, enterprise data center cloud storage, high-frequency transactional caching.

## Key Terminology
- **NAND Flash**: Non-volatile semiconductor storage technology retaining electronic charge without power.
- **Wear Leveling**: Technique used by SSD controllers to prolong drive lifespan by distributing writes across all memory blocks.
- **TRIM Command**: OS command informing SSD controllers which data pages are no longer needed, enabling efficient background block collection.


## References & Further Exploration
[[Semiconductor Physics and the Silicon Transistor]], [[Operating System Kernels - Monolithic vs Microkernel Architectures]]
