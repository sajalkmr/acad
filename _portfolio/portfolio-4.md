---
title: "raftly - Raft Consensus Algorithm Implementation"
excerpt: "Java implementation of the fault-tolerant Raft Consensus Algorithm for distributed systems<br/>"
collection: portfolio
---

## Overview
raftly is a comprehensive implementation of the Raft Consensus Algorithm in Java, designed to ensure reliable log replication and leader election across distributed nodes. This project demonstrates deep understanding of distributed systems principles and consensus mechanisms.

## Key Features
- **Leader Election**: Robust implementation ensuring single leader selection
- **Log Replication**: Reliable log entry replication across all nodes
- **State Machine**: Consistent command application from replicated logs
- **Fault Tolerance**: Handles network partitions and node failures gracefully

## Technologies Used
- **Language**: Java
- **Build Tool**: Maven
- **Testing**: Comprehensive test suite for various failure scenarios

## Technical Implementation
- Developed efficient RPC (Remote Procedure Call) mechanisms for inter-node communication
- Implemented timeout-based leader election with randomized election timeouts
- Created persistent state management for crash recovery
- Built comprehensive logging and debugging capabilities

## Testing & Validation
Conducted thorough testing to validate:
- Performance under network partitions
- Recovery from node failures
- Consistency guarantees under various failure modes
- Leader election convergence time

[View on GitHub](https://github.com/sajalkmr/raftly)