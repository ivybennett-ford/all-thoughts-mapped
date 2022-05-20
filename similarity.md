---
source: https://github.com/SkepticMystic/graph-analysis#jaccard-similarity
tags:
  - computer-science
  - statistics
  - code
  - probability
---
### [Similarity](https://github.com/SkepticMystic/graph-analysis#jaccard-similarity)

Similarity is a measure of how similar two [[note|notes]] are based on their connectedness in the graph (ie. note content is not considered). Currently, only the Jaccard Similarity measure is implemented. This topic similar to a [[relational-database]].

#### Jaccard Similarity

**Formula**:

[![image](https://user-images.githubusercontent.com/70717676/139872572-93504295-6d29-4722-bdb1-3fbeb7bc22ec.png)](https://user-images.githubusercontent.com/70717676/139872572-93504295-6d29-4722-bdb1-3fbeb7bc22ec.png)

Where

-   `|x|` is the number of neighbours the node `x` has (links going in or out).
-   `|x & y|` is the number of neighbours that both `x` and `y` have in common