---
title: "Virtual Memory - Paging, Page Tables, and Translation Lookaside Buffers"
tags: [computing, operating-systems, computer-architecture]
related: [[[Operating System Kernels - Monolithic vs Microkernel Architectures]], [[CPU Architecture - Pipelining, Branch Prediction, and Out-of-Order Execution]]]
created: 2026-11-26
updated: 2026-11-26
---

# Virtual Memory - Paging, Page Tables, and Translation Lookaside Buffers

## Overview
Virtual Memory abstracts physical RAM into private, continuous linear address spaces per process, enforcing hardware memory isolation and transparent paging.

## Core Mechanics & Foundations
Multi-Level Paging & Page Tables: The CPU Memory Management Unit (MMU) translates virtual addresses into physical addresses via hierarchical page tables (typically 4 KB pages). Multi-level hierarchies (such as 4-level paging in x86-64: PML4, PDPT, PD, PT) prevent allocating memory tables for unused address space ranges.

## Modern Applications & Advanced Significance
Translation Lookaside Buffer (TLB) & Page Faults: Because traversing 4-level memory tables takes multiple clock cycles, the TLB caches recent virtual-to-physical address mappings on the CPU chip. A TLB miss triggers a page table walk; an unmapped address triggers a hardware page fault interrupt to fetch pages from secondary storage or terminate illegal memory access.

## Real-World Impact & Systems
Process process memory sandboxing, memory-mapped file access (mmap), copy-on-write memory sharing.

## Key Terminology
- **Virtual Memory**: Memory management capability creating the illusion of large, contiguous private memory spaces for processes.
- **Page Table**: Data structure used by virtual memory systems to store mapping between virtual and physical addresses.
- **TLB**: High-speed hardware associative cache on the CPU storing recent virtual-to-physical address translations.


## References & Further Exploration
[[Operating System Kernels - Monolithic vs Microkernel Architectures]], [[CPU Architecture - Pipelining, Branch Prediction, and Out-of-Order Execution]]
