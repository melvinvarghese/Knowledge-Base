---
title: "TCP Congestion Control - Tahoe, Reno, and BBR"
tags: [computing, networking, internet]
related: [[[The Internet Protocol Suite - TCP-IP and Packet Switching]], [[Information Theory - Shannon Entropy and Channel Capacity]]]
created: 2026-11-26
updated: 2026-11-26
---

# TCP Congestion Control - Tahoe, Reno, and BBR

## Overview
TCP Congestion Control algorithms prevent packet collapse across the global internet by dynamically matching data transmission rates to available network capacity.

## Core Mechanics & Foundations
Loss-Based Congestion Control (Tahoe and Reno): Jacobson (1988) introduced Additive Increase / Multiplicative Decrease (AIMD). Slow Start exponentially doubles the congestion window ($cwnd$) until a threshold ($ssthresh$), followed by linear probing. Reno uses Fast Retransmit and Fast Recovery upon 3 duplicate ACKs, cutting $cwnd$ in half rather than resetting to 1.

## Modern Applications & Advanced Significance
Model-Based Control (Google BBR): Loss-based algorithms suffer from 'bufferbloat' (delay spikes caused by filled switch buffers before packet drops). Bottleneck Bandwidth and Round-trip propagation time (BBR) explicitly models the physical pipe by measuring maximum delivery rate and minimum RTT, maximizing throughput while minimizing queuing delay.

## Real-World Impact & Systems
High-speed content delivery networks (CDNs), video streaming (YouTube, Netflix), cloud data center inter-rack communication.

## Key Terminology
- **AIMD**: Additive Increase / Multiplicative Decrease; feedback control algorithm adjusting bandwidth windows in computer networks.
- **Bufferbloat**: High latency and packet jitter caused by excessive buffering of packets inside network routers.
- **BBR**: Congestion control algorithm that measures bottleneck bandwidth and minimum RTT instead of relying on packet loss.


## References & Further Exploration
[[The Internet Protocol Suite - TCP-IP and Packet Switching]], [[Information Theory - Shannon Entropy and Channel Capacity]]
