---
title: Elementary row operations
---
## Definition:
>[!abstract] Definition
>
>Two matrices are row equivalent if a sequence of ERO (Equivalent Row Operations) turns one into the other.

>[!abstract] Definition: (row)echelon form
>
> 1. Every zero row is below non-zero rows, so the zero row is on the bottom
> 2. The leading coeff of a nonzero row is to the right of the leading coeff of the row above
> 3. All terms in a column under some leading coeff are zero
> $$\begin{pmatrix}  1 & 0 & -5 & |&1\\  0 & 1 & 1 &|&4\\ 0 & 0 & 0 &|&0 \end{pmatrix}$$

>[!abstract] Definition: reduced (row)echelon form
>
>4. Every leading coeff is one (1)
>5. Every leading coeff has only zero's above it
> $$\begin{pmatrix}  1 & 0 & 0 & |&1\\  0 & 1 & 0 &|&0\\ 0 & 0 & 1 &|&-1 \end{pmatrix}$$

>[!abstract] Theorem: 
> A linear system is consistent iff there is a pivot in the rightmost column of the bottom row is not a pivot column
>

## Rules:

1. Add a multiple of a row to another row
2. Switch two rows
3. Multiply a row by a non-zero constant

## Add a multiple of a row to another row:
$x_1+2x_2+x_{3}= 7$
$9x_1+8x_3=6$

$x_1+2x_2+x_{3}= 7$
$-18x_2-x_3=-57$
this is how we do that in matrices
$$\begin{pmatrix}  1 & 2 & 1 & |&7\\  9 & 0 & 8 &|&6 \end{pmatrix} \to R_{2}\to R_{2}-9\cdot R_{1} \to \begin{pmatrix}  1 & 2 & 1 &|& 7\\  0 & -18 & -1&| &-57 \end{pmatrix}$$These are the same matrices. This is called an elementary row operation.
## Switch two rows 
$x_{1}+ x_2 = 1$
$x_{1} - x_{2}= 0$

$2x_{1}+ 2x_2 = 2$
$2x_{1} - 2x_{2}= 0$

$$\begin{pmatrix}  1 & 1 & |&1\\  1 & -1 &|&0 \end{pmatrix} \to_{R_{1}\to 2R_{1}}\to \begin{pmatrix}  2 & 2 & |&2\\  2 & -2 &|&0 \end{pmatrix}$$
These equations are the same


## Multiply a row by a non-zero constant



## Examples:
![[Pasted image 20221101180321.png]]
![[Pasted image 20221101184629.png]]
![[Pasted image 20221101185750.png]]