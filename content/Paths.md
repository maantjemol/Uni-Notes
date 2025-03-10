---
title: Paths
---
Walking along a path in a graph. The length of the path is the number of vertices visited.
![[Pasted image 20221020091813.png]]
**Trail:** a path where you only visit edges once.
**Simple path:** a path where you only visit distinct vertices.

## Types of paths:
*Closed path*: $V_{0}=V_{n}$ it's just a loop 
*Circuit*: Closed path where you only visit edges once(closed trail) 
*Cycle*: Closed path with distinct vertices
![[Pasted image 20221020092200.png]]
> [!INFO] Definition 
> 
> Suppose u, v ∈ V(G) and there is a path from u to v in which vertex x occurs twice: xi = xj = x. Then we can omit the intermediate vertices (and corresponding edges).
> ![[Pasted image 20221020094205.png]]

## Distance:
> [!INFO] Definition 
> 
> The **distance** between two nodes **u** and **v** is the length (nr. of edges) of a shortest path between **u** and **v**.

Notation: *d(u,v)*
d(u,v) = 0 iff u = v
d(u,v) = d(v,u)

## Bridge and cutpoint:
![[Pasted image 20221020094302.png]]
