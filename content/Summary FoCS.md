---
title: Summary
---

## **Sets:** [[set]]
>[!abstract] Definition
>
>Set is a collection of things. A set is a concept intended to turn serveral seperate objects into one whole, new object. They are the basis of modern mathematics. A aset consists of elements.  

### Notation:
$A = \{ 2, 3, 4, 5 \}$
$2 ∈ A$
2 is in A

$A = \{ 1, 2, 3, 4\}$
$B = \{ 2, 3\}$
$A \subseteq B$

$\{X | X \text{ is even and } X \geq 0\}$
Means^: $\{0, 2, 4, ...\}$

### Operations: [[set operations]]
#### Union: ∪ 
Combine sets:
![[Pasted image 20220908103744.png]]
#### Intersection: ∩
Intersect sets 
![[Pasted image 20220908103809.png]]
#### Compliment:
Everything outside A
![[Pasted image 20220908104400.png]]
#### Difference:
A / B
![[Pasted image 20220908104457.png]]


### Powersets: [[powerset set]]
>[!abstract] Definition
>
>powerset of S: **it contains all subsets of a set S.** P ({a,b}) = { 0/, {a}, {b}, {a,b} } 
>![[Screenshot 2022-09-22 at 09.07.08.png]]

### Partition set: [[partition set]] 
>[!abstract] Definition
>
>partition of S: **some disjoint nonempty subsets that together** **are S.** 
{ {1,4}, {2}, {3,5,6} } is a partition of { 1,2,3,4,5,6 }
*There is no overlap between them*

### Set algebra: [[Set algebra]] 
>[!abstract] Definition
>
>![[Pasted image 20220915094639.png]]


### Counting sets: [[Counting sets]] 
>[!abstract] Definition
>
>If we want to count the elements in the union of sets, we should *not 
count the common elements twice*

Counting with finite sets:
![[Pasted image 20220915104201.png]]
![[Pasted image 20220915104302.png]]


---
## **Relations:** [[relation]]
>[!abstract] Definition
>
>A relation is a subset of a Cartesian product. 
![[Pasted image 20220922101358.png|200]]

### Binary relation:
>[!abstract] Definition
>
>A binary relation describes a relationship between the elements of 2 sets. If A and B are sets, then a binary relation R from A to B is a subset of the Cartesian product of A and B (A x B).

### Helpfull other relations
- [[Identity relation]]
- [[Representations]]
- [[Inverse relation]]
- [[Domain and range]]

### Types of relations:
- **Reflexive**: A = A
- **Symmetric**: A = B and B = A 
- **Transative**: A = B and B = C so A = C 
**Partial order**: transative and reflexive 
**Equivalence relation**: symmetric, transative and reflexive 
**Example:** [[Types of relations#Example:]]

### P-closure:
Add as little as possible to a [[relation]] so it becomes transitive or any other type of relation.¥

### Counting:
>[!warning] Definition
>
>there are $2^{n(A)\cdot n(B)}$ different relations from A to B possible 

- A set of $n$ elements has $2^n$ [[subsets]] 
- For finite sets $A$ and $B$, $A\times B$ has $n(A)\cdot n(B)$ elements, meaning *objects in A times objects in B*
- So, there are $2^{n(A)\cdot n(B)}$ different relations from A to B possible

---
## **Functions:** [[functions (discr)]]
>[!abstract] Definition
>
>A function from $A \to B$ assigns to *each* element $x$ of $A$. one element $y$ of $B$
>- Every A only has one [[relation]] to a B
>- It can't have multiple [[relation]]s from A 

![[Screenshot 2022-10-06 at 10.16.53.png]]

### Identity:
$f(x) = x$

### Examples:
![[Screenshot 2022-10-06 at 10.21.23.png]]


---
## **Pairs:** [[pairs]]
2 pairs are equal:
- $(a,b) = (c,d)$ if $a = c$ and $b = d$
- (A, B) is not equal to (B, A)  $\to$  *ELEMENTS*
- {A, B} is equal to {B, A}  $\to$  *SETS*
![[Screenshot 2022-09-22 at 09.41.37.png]]


---
## **Graphs:** [[Graph Theory]]
### Terminology:
**[[Directed Graphs]]**: Graph met pijltjes
**[[Undirected  Graphs]]**: Graph zonder pijltjes 
**Degree**: The edges out/in a vertex
**[[Handshaking lemma]]**: The sum of the degrees in a graph is 2 times the edges
**[[Removing vert and edges]]**: 
- if vertex $v \in V$, then $G - v$ is the graph resulting when we remove $v$ and al it's [[edges]] that are connected to $v$ in $G$
- if $e \in E$ then $G - e$ is the graph resulting when removing an edge.

### Subgraphs: [[Subgraphs]]
**[[Subgraphs]]**: subsets but with graphs. All edges and vertecies in the subgraph are also in the original graph. *see orange in figure below*
**Induced subgraph**: A subgraph that includes all edges of the original graph. *see green in figure below*
![[Pasted image 20221020091058.png]]

### Paths: [[Paths]]
read [[paths]]

### Types of graphs: 
#### [[Isomorphic graphs]]:
>[!info] Definition
>
>A graph that has de same edges an vertices. They can differ in names of vertices. The vertices need to have the same number of edges connected to them
>![[Pasted image 20221020103150.png]]

#### **[[Eulerian circuit]]**:
> [!info] Definition 
> 
> An Eulerian circuit is a closed path (walk) that visits each edge exactly once.

#### Eulerian trail:
>[!info] Definition 
>
>An Eulerian trail is a path that contains each edge exactly once.
![[Pasted image 20221020101313.png]]

#### [[Hamiltonian cycle]]
> [!info] Definition 
>
>A Hamiltonian cycle (circuit) is a closed path (walk) that contains each vertex except the end points exactly once.

> [!info] Definition 
>
>A Hamiltonian path is a path that contains each vertex exactly once.

![[Pasted image 20221020102139.png]]

**Hamiltonian graph** contains a Hamiltonian cycle.

### Special Graphs: [[Special graphs]]
Read [[Special graphs]]