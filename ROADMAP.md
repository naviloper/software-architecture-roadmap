# Roadmap

Full learning path for Software Architecture and System Design. All topics start as **🔴 Not started** — update status as you progress.

See [README.md](README.md) for the status legend.

## Overview

```
0. Programming Foundations     (gap-check only)
          ↓
1. Data Structures & Algorithms
          ↓
2. Software Design
          ↓
3. Software Architecture
          ↓
4. Architecture Modeling & Communication
          ↓
5. Architecture Patterns
          ↓
6. Cloud & AWS Architecture
          ↓
7. Distributed Systems
          ↓
8. System Design
          ↓
9. Architecture Practice & Case Studies
```

You do not need equal depth at every level. For experienced developers, prioritize **Software Architecture**, **Distributed Systems**, and **System Design**.

---

## 0. Programming Foundations

**Goal:** Gap-check only if you already have professional experience.

| Topic | Status |
| ----- | ------ |
| OOP, abstraction, encapsulation, interfaces | 🔴 |
| Generics, exceptions, concurrency basics | 🔴 |
| HTTP, TCP/IP basics, REST, JSON | 🔴 |
| Authentication | 🔴 |
| Databases, SQL | 🔴 |
| Git, testing | 🔴 |

---

## 1. Data Structures & Algorithms

**Goal:** Develop algorithmic thinking and complexity awareness — not competitive-programming mastery.

| Topic | Status |
| ----- | ------ |
| Arrays, strings | 🔴 |
| Linked lists | 🔴 |
| Stacks, queues | 🔴 |
| Hash maps, hash sets | 🔴 |
| Trees, binary search trees | 🔴 |
| Heaps / priority queues | 🔴 |
| Graphs | 🔴 |
| Linear search, binary search | 🔴 |
| Sorting | 🔴 |
| BFS, DFS | 🔴 |
| Dijkstra, topological sorting | 🔴 |
| Recursion, divide & conquer | 🔴 |
| Greedy algorithms, dynamic programming | 🔴 |
| Two pointers, sliding window | 🔴 |
| Big-O, time/space/amortized complexity | 🔴 |
| B-trees, inverted indexes | 🔴 |
| Consistent hashing, bloom filters | 🔴 |

**Target:** Look at an implementation and say: _"This is O(n²); we can probably solve it in O(n log n)."_

Folder: [`01-dsa/`](01-dsa/)

---

## 2. Software Design

**Goal:** Move from _"I can write code"_ to _"I can design code that remains maintainable as requirements change."_

| Topic | Status |
| ----- | ------ |
| Composition vs inheritance, coupling, cohesion | 🔴 |
| Dependency inversion, immutability, encapsulation | 🔴 |
| SOLID principles | 🔴 |
| Design patterns (Strategy, Factory, Adapter, Decorator, Facade, Observer, Command, State, Builder, Proxy) | 🔴 |
| Layered architecture | 🔴 |
| Hexagonal architecture | 🔴 |
| Clean Architecture | 🔴 |
| Onion Architecture, ports & adapters | 🔴 |
| Entities, value objects, aggregates | 🔴 |
| Repositories, domain services, application services | 🔴 |
| Domain events | 🔴 |
| Domain-Driven Design | 🔴 |

Folder: [`02-software-design/`](02-software-design/)

---

## 3. Software Architecture

**Goal:** Learn to make system-level decisions under constraints.

| Topic | Status |
| ----- | ------ |
| Architecture characteristics (scalability, availability, reliability, performance) | 🔴 |
| Security, maintainability, testability, deployability | 🔴 |
| Observability, resilience, fault tolerance | 🔴 |
| Architecture styles (monolith, modular monolith, layered, service-based) | 🔴 |
| Microservices, event-driven, serverless | 🔴 |
| Coupling, cohesion, component boundaries | 🔴 |
| Service boundaries, data ownership | 🔴 |
| Dependency management, granularity | 🔴 |
| ADRs, architecture principles, constraints | 🔴 |
| Trade-off analysis, technical debt | 🔴 |
| Evolutionary architecture, fitness functions | 🔴 |

Folder: [`03-software-architecture/`](03-software-architecture/)

---

## 4. Architecture Modeling & Communication

**Goal:** Communicate architecture — not just design it.

| Topic | Status |
| ----- | ------ |
| C4 — System Context (C1) | 🔴 |
| C4 — Containers (C2) | 🔴 |
| C4 — Components (C3) | 🔴 |
| C4 — Code (C4) | 🔴 |
| Deployment diagrams, dynamic diagrams | 🔴 |
| UML (class, sequence, component, deployment, activity, state) | 🔴 |
| Architecture documentation | 🔴 |
| ADRs | 🔴 |
| Structurizr, PlantUML, Mermaid | 🔴 |

**Target:** Given an unfamiliar system, produce Context → Container → Component → Deployment diagrams and explain the architecture to developers and non-developers.

Folder: [`04-modeling/`](04-modeling/)

---

## 5. Architecture Patterns

**Goal:** Learn common solutions to recurring architectural problems.

| Topic | Status |
| ----- | ------ |
| Modular monolith | 🔴 |
| Microservices | 🔴 |
| API Gateway, BFF | 🔴 |
| Strangler Fig, anti-corruption layer | 🔴 |
| Event-driven architecture | 🔴 |
| CQRS, event sourcing | 🔴 |
| Saga | 🔴 |
| Transactional outbox | 🔴 |
| Retry, circuit breaker, bulkhead | 🔴 |
| Rate limiting, cache aside | 🔴 |
| Caching | 🔴 |
| Resilience patterns | 🔴 |

**Key skill:** Problem → Pattern → Advantages → Disadvantages → When to use → When NOT to use

Folder: [`05-architecture-patterns/`](05-architecture-patterns/)

---

## 6. Cloud & AWS Architecture

**Goal:** Translate architecture principles into real infrastructure.

| Topic | Status |
| ----- | ------ |
| Networking (VPC, subnets, routing, DNS, load balancing) | 🔴 |
| Compute (EC2, ECS, Lambda) | 🔴 |
| Storage (S3, EBS) | 🔴 |
| Databases (RDS, DynamoDB, ElastiCache) | 🔴 |
| Messaging (SQS, SNS, EventBridge, Kinesis) | 🔴 |
| Security (IAM, encryption, WAF) | 🔴 |
| Reliability (multi-AZ, auto-scaling, health checks) | 🔴 |
| Observability (CloudWatch, X-Ray, logging) | 🔴 |
| Infrastructure as Code (Terraform, CloudFormation) | 🔴 |
| AWS Well-Architected Framework | 🔴 |

Folder: [`06-cloud/aws/`](06-cloud/aws/)

---

## 7. Distributed Systems

**Goal:** Understand what happens when components interact over a network.

| Topic | Status |
| ----- | ------ |
| Scalability (vertical vs horizontal) | 🔴 |
| Replication (leader-follower, multi-leader, leaderless) | 🔴 |
| Partitioning / sharding | 🔴 |
| Consistency models | 🔴 |
| CAP theorem, PACELC | 🔴 |
| Consensus (Raft) | 🔴 |
| Distributed transactions | 🔴 |
| Idempotency, exactly-once semantics | 🔴 |
| Eventual consistency | 🔴 |
| Message queues vs event streams | 🔴 |

Folder: [`07-distributed-systems/`](07-distributed-systems/)

---

## 8. System Design

**Goal:** Design complete systems from requirements to deployment.

| Topic | Status |
| ----- | ------ |
| Requirements gathering | 🔴 |
| Capacity estimation | 🔴 |
| API design | 🔴 |
| Database design | 🔴 |
| Caching strategy | 🔴 |
| Messaging and async processing | 🔴 |
| Scalability patterns | 🔴 |
| Reliability and failure handling | 🔴 |
| Security | 🔴 |
| Cost optimization | 🔴 |

**Target:** Given a problem like _"Design a platform that sells digital products globally, supports millions of customers, integrates with external providers, and must remain available when providers fail"_ — work through requirements → capacity → domain boundaries → C4 → API → database → caching → messaging → consistency → failure handling → infrastructure → security → observability → cost → ADRs.

Folder: [`08-system-design/`](08-system-design/)

---

## 9. Architecture Practice & Case Studies

**Goal:** Apply everything — design complete systems and document your reasoning.

| Case study | Status |
| ---------- | ------ |
| E-commerce | 🔴 |
| Payment system | 🔴 |
| Notification system | 🔴 |
| Digital goods platform | 🔴 |

Each case study should cover:

```
Requirements → Constraints → Capacity estimation → Domain model
      ↓
C4 Context → C4 Containers → Components
      ↓
Database → API → Caching → Messaging
      ↓
Scalability → Reliability → Security
      ↓
Cloud architecture → Trade-offs → ADRs
```

Folder: [`09-case-studies/`](09-case-studies/)

---

Layers reinforce each other — you do not need to finish every topic in one level before moving forward.
