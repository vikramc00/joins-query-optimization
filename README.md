# Joins and Query Optimization
Implemented some common join algorithms and a limited version of the Selinger optimizer.

## Design
1) Join Algorithms: Simple Nested Loop Join (SNLJ), Page Nested Loop Join (PNLJ), Block Nested Loop Join (BNLJ), Simple Hash Join (SHJ), Grace Hash Join (GHJ), Sort Merge Join
2) Query Optimization Process: Single Table Access Selection (Pass 1), Join Selection (Pass i > 1), QueryPlan#execute (Optimal Plan Selection)
