---
title: "Software-Defined Networking (SDN) and OpenFlow"
tags: [computing, networking, telecommunications]
related: [[[The Internet Protocol Suite - TCP-IP and Packet Switching]], [[Operating System Kernels - Monolithic vs Microkernel Architectures]]]
created: 2026-11-26
updated: 2026-11-26
---

# Software-Defined Networking (SDN) and OpenFlow

## Overview
Software-Defined Networking decouples the network control plane (routing intelligence) from the underlying data plane (packet forwarding hardware).

## Core Mechanics & Foundations
Control Plane vs Data Plane Separation: Traditional switches tightly couple proprietary firmware routing with ASIC forwarding hardware. SDN strips switches down to high-speed programmable forwarding engines (Data Plane) orchestrated by a centralized, software-based SDN Controller (Control Plane).

## Modern Applications & Advanced Significance
The OpenFlow Protocol & Flow Tables: OpenFlow standardizes communication between controller and switches. The controller dynamically installs match-action flow entries (matching IP, port, VLAN headers and executing actions: forward, drop, modify), turning physical networks into software-programmable fabrics.

## Real-World Impact & Systems
Hyperscale cloud data center fabrics (Google Andromeda, AWS VPC), network virtualization, carrier telecom networks.

## Key Terminology
- **SDN**: Software-Defined Networking; architectural approach separating network control mechanisms from forwarding hardware.
- **OpenFlow**: Communications protocol giving SDN controllers direct programmatic access to switch forwarding planes.
- **Control Plane**: Part of a network architecture that determines how packet traffic is routed through the topology.


## References & Further Exploration
[[The Internet Protocol Suite - TCP-IP and Packet Switching]], [[Operating System Kernels - Monolithic vs Microkernel Architectures]]
