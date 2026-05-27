# Graph Report - E_Commerce_Web_application  (2026-05-26)

## Corpus Check
- 29 files · ~33,468 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 184 nodes · 198 edges · 27 communities (13 shown, 14 thin omitted)
- Extraction: 87% EXTRACTED · 13% INFERRED · 0% AMBIGUOUS · INFERRED: 26 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `04a6b500`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Community 0|Community 0]]
- [[_COMMUNITY_Community 1|Community 1]]
- [[_COMMUNITY_Community 2|Community 2]]
- [[_COMMUNITY_Community 3|Community 3]]
- [[_COMMUNITY_Community 4|Community 4]]
- [[_COMMUNITY_Community 5|Community 5]]
- [[_COMMUNITY_Community 6|Community 6]]
- [[_COMMUNITY_Community 7|Community 7]]
- [[_COMMUNITY_Community 8|Community 8]]
- [[_COMMUNITY_Community 10|Community 10]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]
- [[_COMMUNITY_Community 14|Community 14]]
- [[_COMMUNITY_Community 15|Community 15]]
- [[_COMMUNITY_Community 16|Community 16]]
- [[_COMMUNITY_Community 17|Community 17]]
- [[_COMMUNITY_Community 18|Community 18]]
- [[_COMMUNITY_Community 19|Community 19]]
- [[_COMMUNITY_Community 20|Community 20]]
- [[_COMMUNITY_Community 21|Community 21]]
- [[_COMMUNITY_Community 22|Community 22]]
- [[_COMMUNITY_Community 23|Community 23]]
- [[_COMMUNITY_Community 24|Community 24]]
- [[_COMMUNITY_Community 25|Community 25]]

## God Nodes (most connected - your core abstractions)
1. `E_Commerce_Web_application Project Context` - 16 edges
2. `Primary App` - 15 edges
3. `E_Commerce_Web_application Architecture` - 14 edges
4. `CartDetails` - 10 edges
5. `ProductDetails` - 10 edges
6. `E_Commerce_Web_application Workflows` - 10 edges
7. `E_Commerce_Web_application Coding Rules` - 9 edges
8. `next()` - 7 edges
9. `Details` - 7 edges
10. `SessionBean` - 6 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (27 total, 14 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.13
Nodes (5): next(), Authentication, Details, DomParsing, register

### Community 3 - "Community 3"
Cohesion: 0.38
Nodes (8): clearMenus(), complete(), getParent(), getTargetFromTrigger(), Plugin(), removeElement(), ScrollSpy(), transitionEnd()

### Community 4 - "Community 4"
Cohesion: 0.12
Nodes (16): Business Purpose, Critical Dependencies, Current Architecture Themes, Deployment Model, E_Commerce_Web_application Project Context, Environments, Important APIs, Important Databases (+8 more)

### Community 5 - "Community 5"
Cohesion: 0.67
Nodes (4): b(), c(), d(), f()

### Community 10 - "Community 10"
Cohesion: 0.12
Nodes (15): Critical Workflows, Dangerous Code Paths, Databases Used, Dependencies, Failure Modes, Important Source Files, Inbound APIs, Known Technical Debt (+7 more)

### Community 11 - "Community 11"
Cohesion: 0.13
Nodes (14): Auth Flow, Caching Layers, Deployment Topology, E_Commerce_Web_application Architecture, End-to-End Request Flows, Event-Driven Architecture, Failover Behavior, Frontend / Backend Interaction (+6 more)

### Community 12 - "Community 12"
Cohesion: 0.18
Nodes (10): Debugging, Deployment, E_Commerce_Web_application Workflows, Feature Rollout, Incident Response, Local Development, Migrations, Observability Investigation (+2 more)

### Community 13 - "Community 13"
Cohesion: 0.2
Nodes (9): API Conventions, Architecture Patterns, Database / Migration Patterns, E_Commerce_Web_application Coding Rules, Error Handling / Logging, Naming / Structure, State Management, Testing Conventions (+1 more)

### Community 14 - "Community 14"
Cohesion: 0.29
Nodes (6): Critical Entrypoints, E_Commerce_Web_application Onboarding, First Read, How To Start Reasoning, Local Run Baseline, Module Map

### Community 15 - "Community 15"
Cohesion: 0.5
Nodes (3): E_Commerce_Web_application Decision Log, Graphify-first repo discovery, Preserve repo separation

### Community 16 - "Community 16"
Cohesion: 0.5
Nodes (3): Critical Entrypoints, Read First, Top-Level Modules

## Knowledge Gaps
- **78 isolated node(s):** `Business Purpose`, `System Overview`, `Major Applications`, `Environments`, `Tech Stack` (+73 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **14 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `next()` connect `Community 0` to `Community 3`?**
  _High betweenness centrality (0.027) - this node is a cross-community bridge._
- **Why does `Controller` connect `Community 6` to `Community 0`?**
  _High betweenness centrality (0.014) - this node is a cross-community bridge._
- **Why does `SessionBean` connect `Community 7` to `Community 0`?**
  _High betweenness centrality (0.012) - this node is a cross-community bridge._
- **What connects `Business Purpose`, `System Overview`, `Major Applications` to the rest of the system?**
  _78 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Community 0` be split into smaller, more focused modules?**
  _Cohesion score 0.13 - nodes in this community are weakly interconnected._
- **Should `Community 4` be split into smaller, more focused modules?**
  _Cohesion score 0.12 - nodes in this community are weakly interconnected._
- **Should `Community 10` be split into smaller, more focused modules?**
  _Cohesion score 0.12 - nodes in this community are weakly interconnected._