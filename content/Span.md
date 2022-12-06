---
title: Span
---
>[!abstract] Theorem
>
>Let A be an m × n matrix. The columns of A span $R^m$ iff every row of an echelon form for A contains a pivot

## Linear independence:
1. There is nontrivial solution to vector equation $x_{1} \vec{V_{1}} + ... + x_{n} \vec{V_{n}} = \vec{0}$
2. There is a nonzero solution to the matrix equation $A \vec{x} = \vec{0}$
3. One of $\vec{V_{1}},...,\vec{V_{n}}$ is a linear combination of the others 
If 1, 2 and/or 3 holds, then $\vec{V_{1}},...,\vec{V_{n}}$ are linear dependent.
![[Pasted image 20221115174852.png]]
![[Pasted image 20221115175543.png]]

>[!abstract] Definition
>
>Suppose N > M, then $\vec{V_{1}},...,\vec{V_{n}} \in N^{m}$ are linearly dependent. 

>[!abstract] Definition
>
>$\vec{V_{1}},...,\vec{V_{n}}$ are linearly dependent iff there is an i with span($\vec{V_{1}},...,\vec{V_{n}}$) = span($...,\vec{V_{n}}$) 
## Example:
![[Pasted image 20221115173253.png]]
