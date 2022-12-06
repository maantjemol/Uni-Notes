---
title: Directed Graphs
---
## Definition:
>[!abstract] Definition
>
>A directed graph G consists of two (finite) sets
>• V = V(G) vertices (nodes or points)
>• E = E(G) $\subset$ E x E directed edges (arcs or edges)
>![[Pasted image 20221013104417.png]]

- *trail*: distinct edges 
- *simple path*: distinct vertices closed path $v_0 = v_n$
- *circuit*: distinct edges 
- *cycle*: distinct vertices 
- *spanning path*: contains all vertices (at least one time)

## Degree:
>[!abstract] Definition
>
>outdegree of v = number of outgoing edges
>indegree of v = number of incoming edges
>outdeg(v), indeg(v)
>
>source indeg(v) = 0 (Start of the graph)
>sink outdeg(v) = 0 (End of the graph)


## Connectivity 
>[!abstract] Definition
>
>**strongly connected**: all vertices conncected by directed walks
>**weakly connected**: all vertices connected by undirected walks
 
 ![[Pasted image 20221110100622.png]]


## Topological sort:
![[Pasted image 20221110101611.png]]
