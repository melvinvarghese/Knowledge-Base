---
title: "Event-Driven Architecture and Distributed Message Brokers"
tags: [computing, software-engineering, distributed-systems]
related: [[[Microservices Architecture and API Gateways]], [[Distributed Consensus - Paxos and Raft Algorithms]]]
created: 2026-11-26
updated: 2026-11-26
---

# Event-Driven Architecture and Distributed Message Brokers

## Overview
Event-Driven Architectures (EDA) decouple distributed software components through the asynchronous publication, persistence, and consumption of discrete domain events.

## Core Mechanics & Foundations
Publish-Subscribe vs Message Queues: Traditional message queues (RabbitMQ) route messages to consumer pools, deleting messages upon acknowledgement. Log-based message brokers (Apache Kafka, Apache Pulsar) model events as immutable, append-only partitioned commit logs on disk, allowing multiple consumer groups to read independently at their own offsets.

## Modern Applications & Advanced Significance
Event Sourcing & CQRS: Event Sourcing records every state change as an immutable event sequence rather than mutating in-place database records, providing complete historical auditability. Command Query Responsibility Segregation (CQRS) separates write models from read-optimized query models.

## Real-World Impact & Systems
Financial ledger audit logging, real-time telemetry analytics, large-scale asynchronous microservice integration.

## Key Terminology
- **Event-Driven Architecture**: Software architecture pattern where decoupled components interact through event emissions and listeners.
- **Publish-Subscribe**: Messaging pattern where senders categorize messages into topics without knowing who the subscribers are.
- **Event Sourcing**: Architectural pattern storing state changes as an immutable chronological append-only sequence of events.


## References & Further Exploration
[[Microservices Architecture and API Gateways]], [[Distributed Consensus - Paxos and Raft Algorithms]]
