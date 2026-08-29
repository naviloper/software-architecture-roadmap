# Resources

Consolidated books, courses, and tools for the learning path. **Link to originals — do not copy substantial content into this repository.**

See [ROADMAP.md](ROADMAP.md) for how these map to each learning level.

---

## Suggested reading order

For architecture-focused learning:

1. **Fundamentals of Software Architecture** — structured intro to architecture thinking
2. **Clean Architecture** — mental model for long-living systems
3. **Designing Data-Intensive Applications (2nd ed.)** — distributed systems and data
4. **Software Architecture: The Hard Parts** — real-world trade-offs
5. **Domain-Driven Design Distilled** — selective DDD for complex domains

---

## Books

### Core architecture & design

| Book | Author(s) | Best for |
| ---- | --------- | -------- |
| [Fundamentals of Software Architecture](https://www.oreilly.com/library/view/fundamentals-of-software/9781492043447/) | Mark Richards, Neal Ford | Architecture styles, quality attributes, fitness functions — **start here** |
| [Software Architecture: The Hard Parts](https://www.oreilly.com/library/view/software-architecture-the/9781492097549/) | Neal Ford, Mark Richards, et al. | Trade-offs, microservices vs monoliths, data ownership |
| [Clean Architecture](https://www.oreilly.com/library/view/clean-architecture-a/9780134494272/) | Robert C. Martin | Separation of concerns, dependency rule, framework-agnostic design |
| [Designing Data-Intensive Applications (2nd ed.)](https://dataintensive.net/) | Martin Kleppmann | Databases, replication, consistency, event streams — **the distributed systems bible** |

### Software design & patterns

| Book | Author(s) | Best for |
| ---- | --------- | -------- |
| [Patterns of Enterprise Application Architecture](https://martinfowler.com/books/eaa.html) | Martin Fowler | Repository, service layer, unit of work — classic patterns still in use |
| [Domain-Driven Design Distilled](https://www.oreilly.com/library/view/domain-driven-design-distilled/9780134434421/) | Vaughn Vernon | Bounded contexts, aggregates — practical DDD without the full Evans book |
| [Domain-Driven Design](https://www.domainlanguage.com/ddd/blue-book/) | Eric Evans | Strategic and tactical DDD — read selectively for complex domains |
| [Refactoring](https://martinfowler.com/books/refactoring.html) | Martin Fowler | Recognizing and fixing design problems in existing code |

### Architecture patterns & microservices

| Book | Author(s) | Best for |
| ---- | --------- | -------- |
| [Building Microservices (2nd ed.)](https://samnewman.io/books/building_microservices_2nd_edition/) | Sam Newman | Service boundaries, deployment, evolutionary architecture |
| [Release It!](https://pragprog.com/titles/mnee2/release-it-second-edition/) | Michael T. Nygard | Circuit breakers, bulkheads, stability patterns — production survival |

### Data structures & algorithms

| Book | Author(s) | Best for |
| ---- | --------- | -------- |
| [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms) | Aditya Bhargava | Practical introduction to algorithms and complexity |

---

## Courses

| Course | Provider | Best for |
| ------ | -------- | -------- |
| [Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview) | Educative | Load balancers, caching, sharding — builds system design intuition |
| [Software Architecture Fundamentals](https://www.oreilly.com/live-events/software-architecture-fundamentals/0636920061760/) | O'Reilly / Mark Richards | Architecture styles, trade-off analysis, ADRs |
| [MIT 6.824 / 6.5840 Distributed Systems](https://pdos.csail.mit.edu/6.824/) | MIT (free, YouTube) | Raft, consensus, replication, fault tolerance |
| [AWS Certified Solutions Architect – Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/) | AWS | Structured AWS architecture curriculum — use as learning path, not just exam prep |

---

## References & tools

| Resource | URL | Best for |
| -------- | --- | -------- |
| [The Twelve-Factor App](https://12factor.net/) | 12factor.net | Stateless services, config, logs, scaling |
| [C4 Model](https://c4model.com/) | c4model.com | Architecture diagram hierarchy |
| [Structurizr](https://structurizr.com/) | structurizr.com | C4-focused architecture-as-code |
| [PlantUML](https://plantuml.com/) | plantuml.com | Architecture diagrams as code |
| [Mermaid](https://mermaid.js.org/) | mermaid.js.org | Lightweight diagrams in Markdown |
| [draw.io / diagrams.net](https://www.diagrams.net/) | diagrams.net | Quick visual modeling |

---

## Primary resource by area

Quick reference — one primary resource per topic area:

| Area | Primary resource |
| ---- | ---------------- |
| DSA | _Grokking Algorithms_ |
| Software Design | _Clean Architecture_ |
| Enterprise Design | _Patterns of Enterprise Application Architecture_ |
| DDD | _Domain-Driven Design Distilled_ |
| Architecture | _Fundamentals of Software Architecture_ |
| Architecture Trade-offs | _Software Architecture: The Hard Parts_ |
| Microservices | _Building Microservices_ |
| Resilience | _Release It!_ |
| Distributed Systems | _Designing Data-Intensive Applications (2nd ed.)_ |
| AWS | AWS SAA learning path |
| C4 & Modeling | Structurizr + C4 model docs |
| Distributed Systems (deep) | MIT 6.5840 |
| System Design | Practice + real-world designs |

---

## Practice platforms

| Platform | URL | Notes |
| -------- | --- | ----- |
| LeetCode | [leetcode.com](https://leetcode.com/) | DSA practice — supplement, not primary learning method |
| Educative System Design | See courses above | Structured system design scenarios |

---

## How to use these resources

1. **Read** the primary resource for the topic area.
2. **Understand** the concepts — ask: what problem does this solve?
3. **Explain** in your own words in a topic file (see [TEMPLATE.md](TEMPLATE.md)).
4. **Link** back to the original — never reproduce chapters or paid course content.
5. **Apply** — design something, write an ADR, add a case study.
