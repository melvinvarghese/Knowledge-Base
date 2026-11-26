---
tags:
  - computing
  - software-engineering
  - operating-systems
category: Science & Technology/Inventions & Computing
related:
  - "[[The Microprocessor - Intel 4004 to Modern Multi-Core Architectures]]"
  - "[[Compilers and Interpreters - From Source Code to Machine Code]]"
created: 2026-11-26
---

# Operating Systems - Kernel Architecture and Process Scheduling

## Overview
An Operating System (OS) is system software that manages computer hardware and software resources, providing a secure, abstracted interface between user applications and bare physical hardware.

---

## 1. Theoretical Foundations & Governing Principles
Monolithic vs Microkernel Design: Monolithic kernels (Linux) execute core drivers, memory management, and file systems in privileged supervisor mode; microkernels (seL4) minimize kernel code, running drivers in user space.

---

## 2. Structural Mechanics & Scientific Analysis
Preemptive Process Scheduling & Virtual Memory: CPU context switching between threads via round-robin or multi-level feedback queues, paired with Memory Management Unit (MMU) page table translations for isolated virtual address spaces.

---

## 3. Real-World Applications & Technological Impact
Enterprise servers (Linux), personal operating systems (Windows, macOS), smartphone systems (Android, iOS), and real-time avionics operating systems (RTOS).

---

## Key Terms
- **Kernel**: Core foundational program of an operating system possessing complete control over system hardware.
- **Virtual Memory**: Memory management technique giving processes the illusion of contiguous private address spaces.
- **Context Switch**: Process of storing the CPU state of a running process so another process can be executed.
