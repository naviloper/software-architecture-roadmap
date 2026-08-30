# [Topic Name]

> Copy this template when creating a new topic file. Delete this instruction block.

## Priority

Core | Supporting | Optional — _see the legend in [README.md](README.md)_

## What problem does it solve?

_Describe the architectural or design problem this concept addresses._

## Core concepts

- _Concept 1_
- _Concept 2_
- _Concept 3_

## When to use

_Situations where this is a good fit._

## When NOT to use

_Situations where alternatives are better — be honest about limitations._

## Alternatives

| Alternative | Trade-off |
| ----------- | --------- |
| _Option A_ | _Why you might choose or avoid it_ |
| _Option B_ | _Why you might choose or avoid it_ |

## Architectural trade-offs

_What you gain and what you give up._

## Mental model

```
Problem:
  _What goes wrong without this?_

        ↓

Concept:
  _The idea or pattern_

        ↓

Solution:
  _How it is implemented_

        ↓

Trade-offs:
  _Costs, risks, failure modes_
```

## Related concepts

- _Link to other topics in this repository_
- _Concepts from other levels (e.g. caching → scalability, consistency)_

## Resources

- [Resource title](url) — brief note on why it is useful

---

## Case study extension

Use the sections below when documenting a full system design in `09-case-studies/`.

### Requirements

_Functional and non-functional requirements._

### Constraints

_Budget, timeline, team size, existing systems, compliance._

### Capacity estimation

_Order-of-magnitude reasoning — users, requests/sec, storage, bandwidth._

### Domain model

_Key entities, bounded contexts, aggregates._

### Architecture diagrams

_Link to or embed C4 Context, Container, Component, and Deployment diagrams._

### API design

_Key endpoints, protocols, authentication._

### Data design

_Database choice, schema highlights, partitioning strategy._

### Caching

_What is cached, invalidation strategy, failure behavior._

### Messaging

_Queues, events, async flows, idempotency, DLQ._

### Scalability

_How the system handles growth._

### Reliability

_Failure modes, retries, circuit breakers, redundancy._

### Security

_Auth, encryption, secrets, network boundaries._

### Cloud architecture

_How this maps to cloud services (e.g. AWS)._

### ADRs

_Links to Architecture Decision Records for key choices._

### Trade-offs summary

_Final summary of major decisions and what was rejected._
