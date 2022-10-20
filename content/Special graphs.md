---
title: Special graphs
---
## Complete graph:
>[!abstract] Definition
>
>A Graph with all vertices connected to each other.

![[Pasted image 20221020103925.png]]

## $K_n$−regular:
>[!abstract] Definition
>
>All vertices have degree kK

![[Pasted image 20221020104025.png]]
## $K_{m,n}$ complete bipartite 
![[Pasted image 20221020104341.png]]

## Bipartite graph:
>[! abstract] Definition
>
>A graph G is called bipartite if the vertices can be split in two disjoint subsets $V_1$ and $V_2$ so that all edges run between $V_1$ and $V_2$.

A graph G is **2−colorable** if the graph’s vertices can be colored with two colors in such a way that adjacent vertices have a different color.
![[Pasted image 20221020104531.png]]
>[! abstract] Definition
>
>Given a graph G = (V, E). The following statements are equivalent: 
>(1) *G is bipartite* 
>(2) *G only has cycles of even length* 
>(3) G is 2−colorable

(2) =⇒ (1): Suppose G only has cycles of even length. We are going to color the nodes in the graph orange and blue to distinguish the two partitions. Choose any vertex x of the graph and color it blue; then color all vertices adjacent to x orange. If a node is colored, its neighbors get the opposite color. This does not lead to problems: there is no (uncolored) node y with both a blue and an orange neighbor. That would mean that y could be reached from x with both an odd and an even number of edges, and we find a circle of odd length.
![[Pasted image 20221020105027.png]]
