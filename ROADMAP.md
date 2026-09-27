# Roadmap

Full learning path for Software Architecture and System Design. Topics are marked **Core**, **Supporting**, or **Optional** — see [README.md](README.md) for the legend.

Start with Core. Pick up Supporting and Optional as they become relevant to the systems you are designing.

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

**Goal:** Gap-check only if you already have professional experience. Core here means you should already be comfortable — not that you should start the roadmap with a first-year syllabus.

| Topic | Priority |
| ----- | -------- |
| OOP, abstraction, encapsulation, interfaces | Core |
| HTTP, TCP/IP basics, REST, JSON | Core |
| Authentication | Core |
| Databases, SQL | Core |
| Generics, exceptions, concurrency basics | Supporting |
| Git, testing | Supporting |

Folder: [`00-programming-foundations/`](00-programming-foundations/)

---

## 1. Data Structures & Algorithms

**Goal:** Develop algorithmic thinking and complexity awareness — not competitive-programming mastery.

| Topic | Priority |
| ----- | -------- |
| Hash maps, hash sets | Core |
| Stacks, queues | Core |
| Graphs | Core |
| Big-O, time/space/amortized complexity | Core |
| B-trees, inverted indexes | Core |
| Consistent hashing, bloom filters | Core |
| Arrays, strings | Supporting |
| Trees, binary search trees | Supporting |
| Heaps / priority queues | Supporting |
| Linear search, binary search | Supporting |
| BFS, DFS | Supporting |
| Dijkstra, topological sorting | Supporting |
| Linked lists | Optional |
| Sorting | Optional |
| Recursion, divide & conquer | Optional |
| Greedy algorithms, dynamic programming | Optional |
| Two pointers, sliding window | Optional |

**Target:** Look at an implementation and say: _"This is O(n²); we can probably solve it in O(n log n)."_

Folder: [`01-dsa/`](01-dsa/)

---

## 2. Software Design

**Goal:** Move from _"I can write code"_ to _"I can design code that remains maintainable as requirements change."_

| Topic | Priority |
| ----- | -------- |
| Composition vs inheritance, coupling, cohesion | Core |
| Dependency inversion, immutability, encapsulation | Core |
| SOLID principles | Core |
| Layered architecture | Core |
| Hexagonal architecture | Core |
| Entities, value objects, aggregates | Core |
| Domain-Driven Design | Core |
| Design patterns (Strategy, Factory, Adapter, Decorator, Facade, Observer, Command, State, Builder, Proxy) | Supporting |
| Clean Architecture | Supporting |
| Repositories, domain services, application services | Supporting |
| Domain events | Supporting |
| Onion Architecture, ports & adapters | Optional |

Folder: [`02-software-design/`](02-software-design/)

---

## 3. Software Architecture

**Goal:** Learn to make system-level decisions under constraints.

| Topic | Priority |
| ----- | -------- |
| Architecture characteristics (scalability, availability, reliability, performance) | Core |
| Security, maintainability, testability, deployability | Core |
| Observability, resilience, fault tolerance | Core |
| Architecture styles (monolith, modular monolith, layered, service-based) | Core |
| Microservices, event-driven, serverless | Core |
| Coupling, cohesion, component boundaries | Core |
| Service boundaries, data ownership | Core |
| ADRs, architecture principles, constraints | Core |
| Trade-off analysis, technical debt | Core |
| Dependency management, granularity | Supporting |
| Evolutionary architecture, fitness functions | Supporting |

Folder: [`03-software-architecture/`](03-software-architecture/)

---

## 4. Architecture Modeling & Communication

**Goal:** Communicate architecture — not just design it.

| Topic | Priority |
| ----- | -------- |
| C4 — System Context (C1) | Core |
| C4 — Containers (C2) | Core |
| C4 — Components (C3) | Core |
| Architecture documentation | Core |
| ADRs | Core |
| Deployment diagrams, dynamic diagrams | Supporting |
| UML (class, sequence, component, deployment, activity, state) | Supporting |
| Structurizr, PlantUML, Mermaid | Supporting |
| C4 — Code (C4) | Optional |

**Target:** Given an unfamiliar system, produce Context → Container → Component → Deployment diagrams and explain the architecture to developers and non-developers.

Folder: [`04-modeling/`](04-modeling/)

---

## 5. Architecture Patterns

**Goal:** Learn common solutions to recurring architectural problems.

| Topic | Priority |
| ----- | -------- |
| Modular monolith | Core |
| Microservices | Core |
| API Gateway, BFF | Core |
| Event-driven architecture | Core |
| Retry, circuit breaker, bulkhead | Core |
| Rate limiting, cache aside | Core |
| Caching | Core |
| Strangler Fig, anti-corruption layer | Supporting |
| Saga | Supporting |
| Transactional outbox | Supporting |
| Resilience patterns | Supporting |
| CQRS, event sourcing | Optional |

**Key skill:** Problem → Pattern → Advantages → Disadvantages → When to use → When NOT to use

Folder: [`05-architecture-patterns/`](05-architecture-patterns/)

---

## 6. Cloud & AWS Architecture

**Goal:** Translate architecture principles into real infrastructure.

| Topic | Priority |
| ----- | -------- |
| Networking (VPC, subnets, routing, DNS, load balancing) | Core |
| Compute (EC2, ECS, Lambda) | Core |
| Storage (S3, EBS) | Core |
| Databases (RDS, DynamoDB, ElastiCache) | Core |
| Messaging (SQS, SNS, EventBridge, Kinesis) | Core |
| Security (IAM, encryption, WAF) | Core |
| Reliability (multi-AZ, auto-scaling, health checks) | Core |
| Observability (CloudWatch, X-Ray, logging) | Core |
| Infrastructure as Code (Terraform, CloudFormation) | Supporting |
| AWS Well-Architected Framework | Supporting |

Folder: [`06-cloud/aws/`](06-cloud/aws/)

---

## 7. Distributed Systems

**Goal:** Understand what happens when components interact over a network.

| Topic | Priority |
| ----- | -------- |
| Scalability (vertical vs horizontal) | Core |
| Replication (leader-follower, multi-leader, leaderless) | Core |
| Partitioning / sharding | Core |
| Consistency models | Core |
| CAP theorem, PACELC | Core |
| Distributed transactions | Core |
| Idempotency, exactly-once semantics | Core |
| Eventual consistency | Core |
| Message queues vs event streams | Core |
| Consensus (Raft) | Supporting |

Folder: [`07-distributed-systems/`](07-distributed-systems/)

---

## 8. System Design

**Goal:** Design complete systems from requirements to deployment.

| Topic | Priority |
| ----- | -------- |
| Requirements gathering | Core |
| Capacity estimation | Core |
| API design | Core |
| Database design | Core |
| Caching strategy | Core |
| Messaging and async processing | Core |
| Scalability patterns | Core |
| Reliability and failure handling | Core |
| Security | Core |
| Cost optimization | Supporting |

**Target:** Given a problem like _"Design a platform that sells digital products globally, supports millions of customers, integrates with external providers, and must remain available when providers fail"_ — work through requirements → capacity → domain boundaries → C4 → API → database → caching → messaging → consistency → failure handling → infrastructure → security → observability → cost → ADRs.

Folder: [`08-system-design/`](08-system-design/)

---

## 9. Architecture Practice & Case Studies

**Goal:** Apply everything — design complete systems and document your reasoning. Two well-documented case studies beat four shallow ones.

| Case study | Priority |
| ---------- | -------- |
| E-commerce | Core |
| Payment system | Core |
| Notification system | Supporting |
| Digital goods platform | Supporting |

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
