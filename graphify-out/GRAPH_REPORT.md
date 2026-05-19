# Graph Report - E_Commerce_Web_application  (2026-05-19)

## Corpus Check
- 12 files · ~31,584 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 70 nodes · 90 edges · 10 communities (3 shown, 7 thin omitted)
- Extraction: 71% EXTRACTED · 29% INFERRED · 0% AMBIGUOUS · INFERRED: 26 edges (avg confidence: 0.8)
- Token cost: 0 input · 0 output

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

## God Nodes (most connected - your core abstractions)
1. `CartDetails` - 9 edges
2. `ProductDetails` - 9 edges
3. `next()` - 6 edges
4. `Details` - 6 edges
5. `SessionBean` - 5 edges
6. `Controller` - 5 edges
7. `b()` - 3 edges
8. `register` - 3 edges
9. `Authentication` - 3 edges
10. `DomParsing` - 3 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (10 total, 7 thin omitted)

### Community 0 - "Community 0"
Cohesion: 0.3
Nodes (3): next(), Authentication, Details

### Community 5 - "Community 5"
Cohesion: 0.6
Nodes (3): b(), c(), d()

## Knowledge Gaps
- **7 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `next()` connect `Community 0` to `Community 3`, `Community 4`?**
  _High betweenness centrality (0.141) - this node is a cross-community bridge._
- **Why does `Controller` connect `Community 6` to `Community 4`?**
  _High betweenness centrality (0.068) - this node is a cross-community bridge._
- **Why does `SessionBean` connect `Community 7` to `Community 0`?**
  _High betweenness centrality (0.055) - this node is a cross-community bridge._
- **Are the 5 inferred relationships involving `next()` (e.g. with `.get_product_info()` and `.insert_data()`) actually correct?**
  _`next()` has 5 INFERRED edges - model-reasoned connections that need verification._