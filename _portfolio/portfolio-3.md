---
title: "ordo - Distributed Container Orchestration System"
excerpt: "A scalable container orchestration system built from scratch in Go<br/>"
collection: portfolio
---

## Overview
ordo is a distributed container orchestration system designed to manage large-scale applications across clusters. Built with a focus on scalability and fault tolerance, it provides a robust platform for container management.

## Key Features
- **Modular Architecture**: Go interfaces enabling customizable scheduling algorithms
- **Enhanced PVM Scheduler**: Custom-built Parallel Virtual Machine scheduler for optimized resource allocation
- **RESTful APIs**: Comprehensive APIs for both worker and manager nodes
- **Persistent Storage**: BoltDB integration for data integrity and system recoverability

## Technologies Used
- **Language**: Go
- **Container Management**: Docker SDK
- **Database**: BoltDB
- **Architecture**: RESTful API design

## Technical Highlights
- Implemented efficient inter-node communication protocols
- Designed fault-tolerant system with automatic recovery mechanisms
- Created extensible scheduling framework supporting multiple algorithms
- Built comprehensive monitoring and logging capabilities

[View on GitHub](https://github.com/sajalkmr/ordo)