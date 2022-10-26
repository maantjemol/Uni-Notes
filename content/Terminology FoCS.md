## [[Set algebra]]

| Law               | Option A                             | Option B                             |
|-------------------|--------------------------------------|--------------------------------------|
| Idempotent laws   | (1a) A ∪ A = A                       | (1b) A ∩ A = A                       |
| Associative laws  | (2a) (A ∪ B) ∪ C = A ∪ (B ∪ C)       | (2b) (A ∩ B) ∩ C = A ∩ (B ∩ C)       |
| Commutative laws  | (3a) A ∪ B = B ∪ A                   | (3b) A ∩ B = B ∩ A                   |
| Distributive laws | (4a) A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C) | (4b) A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C) |
| Identity laws     | (5a) A ∪ ∅ = A                       | (5b) A ∩ U = A                       |
|                   | (6a) A ∪ U = U                       | (6b) A ∩ ∅ = ∅                       |
| Involution laws   | (7) $(A^c)^c$ = A                        |                                      |
| Complement laws   | (8a)$A \cup A^c$ =U                          | (8b)$A \cap A^c$ =∅                          |
|                   | (9a)UC =∅                            | (9b)$\varnothing ^c$ =U                            |
| DeMorgan’slaws    | (10a)(A∪B)C =AC ∩BC                  | (10b)$(A \cap B)^c$ =$A^c$ ∪ $B^c$                  |

>[!abstract] Math to Word:
>$A \cup B=$ $x\in A$ or $x\in B$
>$A \cap B=$ $x\in A$ and $x\in B$
>$A^{c}=$ $x\notin A$
>$A / B=$ $x\in A$ and $x\notin B$

## Sets
>[!abstract] Special Symbols
>
>Some sets will occur very often in the text, and so we use special symbols for them. Some such symbols are: 
>N = the set of natural numbers or positive integers: 1, 2, 3, . . 
>Z = the set of all integers: ...,−2,−1,0,1,2,...  
>Q = the set of rational numbers 
>R = the set of real numbers 
>C = the set of complex numbers 
>Observe that N ⊆ Z ⊆ Q ⊆ R ⊆ C.

>[!abstract] Disjoint Sets
>
Two sets A and B are said to be disjoint if they have no elements in common. 

>[!abstract] Dual
>
>The dual E∗ of E is the equation obtained by replacing each occurrence of ∪, ∩, U and ∅ in E by ∩, ∪, ∅, and U, respectively. For example, the dual of:
>(U∩A)∪(B∩A)=A is (∅∪A)∩(B∪A)=A

>[!abstract] Powerset
>
>Suppose S = {1,2,3}. Then  
>P(S) = [∅, {1}, {2}, {3}, {1, 2}, {1, 3}, {2, 3}, S]

## Counting:
>[!abstract] Counting for non disjoint sets  (2)
>
>Suppose A and B are finite sets. Then A ∪ B and A ∩ B are finite and 
>n(A∪B) = n(A)+n(B)−n(A∩B)

>[!abstract] Counting for non disjoint sets (3)
>
>Suppose A,B,C are finite sets.Then A∪B∪C is finite and 
>n(A∪B ∪C) = n(A)+n(B)+n(C)−n(A∩B)−n(A∩C)−n(B ∩C)+n(A∩B ∩C)

>[!abstract] Theorem
>
>Suppose A and B are finite disjoint sets.Then A∪B is finite and 
>n(A∪B) = n(A)+n(B)

>[!abstract] Powerset counting
>
>$2^{n(S)}$

>[!abstract] Counting \
>
>n(A\B) = n(A) − n(A ∩ B)
>For example, suppose an art class A has 25 students and 10 of them are taking a biology class B. Then the number of students in class A which are not in class B is:
>n(A\B) = n(A)−n(A∩B) = 25−10 = 15

## Relations:
>[!abstract] A × B
>
>Let A = {1,2} and B = {a, b, c}. Then  
>A×B ={(1,a), (1,b), (1,c), (2,a), (2,b), (2,c)}
>B×A={(a,1), (b,1), (c,1), (a,2), (b,2), (c,2)}
>n(A×B) = n(A)n(B) = 6
>$A^{2} = A \times A$

>[!abstract] binary relation
>
>A binary relation or, simply,relation from A to B is a subset of A×B
>:
>(i) (a,b)∈R;we then say “a is R-related to b”, written aRb.  

>[!abstract] Domain and Range
>
>The domain of a relation R is the set of all first elements of the ordered pairs which belong to R, and the
range is the set of second elements

>[!abstract] Inverse Relation
>
>For example, let A = {1, 2, 3} and B = {x, y, z}. Then the inverse of
>R = {(1,y),(1,z),(3,y)} is R−1 = {(y,1),(z,1),(y,3)}

>[!abstract] COMPOSITION OF RELATIONS
>
>Let A = {1,2,3,4}, B = {a,b,c,d}, C = {x,y,z} 
>and let R = {(1,a),(2,d),(3,a),(3,b),(3,d)} 
>and let S = {(b,x),(b,z),(c,y),(d,z)}
>
>R◦S ={(2,z),(3,x),(3,z)}

>[!abstract] CLOSURE
>
>Let R be a relation on a set A. Then:  
(i) R ∪ ^A is the reflexive closure of R.
>(ii) $R \cup R^{-1}$ is the symmetric closure of R.
>
>In other words, reflexive(R) is obtained by simply adding to R those elements (a, a) in the diagonal which do not already belong to R, and symmetric(R) is obtained by adding to R all pairs (b, a) whenever (a, b) belongs to R.

>[!abstract] Equivalence relation
>
>Consider a nonempty set S. A relation R on S is an equivalence relation if R is reflexive, symmetric, and transitive. That is, R is an equivalence relation on S if it has the following three properties:
>
>(1) For every a ∈ S, aRa. 
>(2) If aRb, then bRa. 
>(3) If aRb and bRc, then aRc.

>[!abstract] Partial order relation
>
> relation R on a set S is called a partial ordering or a partial order of S if R is reflexive, antisymmetric, and transitive. A set S together with a partial ordering R is called a partially ordered set or poset

## Functions:
>[!abstract] Definition
>
>Suppose that to each element of a set A we assign a unique element of a set B; the collection of such assignments is called a function from A into B. The set A is called the domain of the function, and the set B is called the target set or codomain
>
>**Remark:** Whenever a function is given by a formula in terms of a variable x, we assume, unless it is otherwise stated, that the domain of the function is R (or the largest subset of R for which the formula has meaning) and the codomain is R

>[!abstract] Relation
>
>There is another point of view from which functions may be considered. First of all, every function f : A → B gives rise to a relation from A to B called the graph of f and defined by

>[!abstract] Composit function
>
>Consider functions f: A → B and g: B → C; that is, where the codomain of f is the domain of g. Then we may define a new function from A to C, called the composition of f and g and written g◦f , as follows:
(g◦f )(a) ≡ g(f (a))

>[!abstract] One to One
>
>If every value in set A maps with a function to a unique value in set B

>[!abstract] Onto
>
>If every B has an A mapped to it.

>[!abstract] INVERTIBLE FUNCTIONS (bijective)
>
>If a function is both One to One and Onto it kan be inverted: $A \to B$ becomes $B \to A$

## Graphs 
>[!abstract] Multigraphs
>
>Graph with multiple edges from the same 2 vertices

>[!abstract] Deg
>
>The sum of the degrees of the vertices of a graph G is equal to twice the number of edges in G. 
>
>A vertex is said to be even or odd according as its degree is an even or an odd number. Thus, A and D are even vertices whereas B and C are odd vertices.

>[!abstract] Distance and Diameter
>
>Consider a connected graph G. The distance between vertices u and v in G, written d(u, v), is the length of the shortest path between u and v. The diameter of G, written diam(G), is the maximum distance between any two points in G

>[!abstract] Cutpoint
>
>A cutpoint is a vertex on a graph that when removed from the graph splits the graph in 2 separate graphs 

>[!abstract] Bridge
>
>A bridge is an edge e that when removed from the graph splits the graph in 2 separate graphs 

>[!abstract] Definition: Walk
>
>**Walk**: An $x\to y$ walk is a sequence
>**Closed walk**: In a closed walk $x = y$
>![[Pasted image 20221022191923.png]]

>[!abstract] Definition: Trail
>
>**Trail**: A walk with no repeated edges
>**Circuit**: A closed trail 
>![[Pasted image 20221022192136.png]]

>[!abstract] Traversable trail
>
>A path that which includes all vertices and uses each edge exactly once.

>[!abstract] Eularian trail
>
>A closed traversable trail

>[!abstract] Eularian Graph
>
>A graph where there exists a eularian trail.

>[!abstract] Theorem 8.4
>
>A finite connected graph is eularian if and only if each vertex has even degree

>[!abstract] Corollary 8.4
>
>Every finite graph with two odd vertices is traversable. A traversable trail may begin at either odd vertex and end at the other odd vertex.

>[!abstract] Hamiltonian Graph/circuit
>
>A Hamiltonian circuit is a closed path the visits every vertex exactly ones. If G does admit a hamiltonian circuit, then g is called a hamiltonian graph.

>[!abstract] Definition: Simple path
>
>**Path**: A walk with no repeated vertices
>**Closed path**: A closed path:
>**Cycle:** Closed path with length 3 or more
>![[Pasted image 20221022192227.png]]

>[!abstract] Definition: Connected Graph
>
>![[Pasted image 20221022192430.png]]

>[!abstract] Weights
>
>A graph is called a weighted graph if each edge of G is assigned a non-negative number w(e). The weight of a graph is all weights added up.

>[!abstract] Complete graph:
>
>A graph G is said to be complete if every vertex in G is connected to every other vertex in G. Thus, a complete graph G must be connected. The complete graph with n vertices is denoted by $K_{n}$
>![[Pasted image 20221026111337.png]]

>[!abstract] Regular graphs
>
>A graph G is regular of degree k or k-regular if every vertex has degree k. In other words, a graph is regular if every vertex has the same degree.
>![[Pasted image 20221026111643.png]]

>[!abstract] Bipartite graph
>
>A graph G is said to be bipartite if its vertices V can be partitioned into two subsets M and N such that each edge of G connects a vertex of M to a vertex of N. By a complete bipartite graph, we mean that each vertex of M is connected to each vertex of N; this graph is denoted by $K_{m,n}$ where m is the number of vertices in M and n is the number of vertices in N, and, for standardization, we will assume m ≤ n
>![[Pasted image 20221026111849.png]]


