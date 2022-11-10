---
title: Matrices
---
## Notation:
$x_1+2x_2+x_{3}= 7$
$9x_1+8x_3=6$

$x_1+2x_2+x_{3}= 7$
$-18x_2-x_3=-57$
this is how we do that in matrices
**Coefficient matrix:** (2×3 matrix)
$$\begin{pmatrix}  
1 & 2 & 1\\  
9 & 0 & 8  
\end{pmatrix}$$
**Augmented Coefficient matrix:** (2×4 matrix)
$$\begin{pmatrix}  1 & 2 & 1 & |7\\  9 & 0 & 8 &|6 \end{pmatrix} \to R_{2}\to R_{2}-9\cdot R_{1} \to \begin{pmatrix}  1 & 2 & 1 & 7\\  0 & -18 & -1 &-57 \end{pmatrix}$$


These are the same matrices. This is called an elementary row operation.

## Matrix Equations:
>[!abstract] Definition
>
>Multiplication of a vector $\vec{V}$ and matrix M with $n$ columns is def:
>$$M \cdot \vec{V} = V_{1} \cdot M_{1} + V_{2} \cdot M_{2}$$

$$\begin{align*}
  A \vec{x} &= \left[
    \begin{array}{rrr}
      1 & -1 & 2\\
      0  & -3 & 1
    \end{array}
  \right]
  \left[
    \begin{array}{l}
      2\\1\\0
    \end{array}
  \right]\\
  &=
  \left[
    \begin{array}{r}
      2 \cdot 1 - 1\cdot 1 + 0 \cdot 2\\
      2 \cdot 0 - 1 \cdot 3 +0 \cdot 1
    \end{array}
  \right]
  \\
  &=
  \left[
    \begin{array}{r}
      1\\
      -3
    \end{array}
  \right].
\end{align*}$$


