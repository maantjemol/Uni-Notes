>[!abstract] Definition
>
> A transformation (function / map) T from $R^n$ to $R^m$ is a rule that assigns each $x \in R^{n}$(domain) a vector $T(x)\in R^m$(codomain).
> T(x) is the image of x under T. Image of T is ${T(x): x\in R^n}$ written $T:R^{n}\to R^m$

>[!abstract] Linear
>
>$T:R^{n}\to R^{m}$ is linear if for all $x,y \in R^{n}$ : $T(x+y) = T(x)+T(y)$ and for all $x\in R^{n}$ and for all $C\in R^{n}$: $T(C\cdot x) = C\cdot T(x)$
>This means that $$T(\begin{bmatrix} 0 \\0\end{bmatrix}) = \begin{bmatrix} 0 \\0\end{bmatrix}$$ 
>![[Pasted image 20221115184256.png]]

>[!abstract] Definition
>
>Let A be an m x n matrix and $T_{A}: R^{n}\to R^{m}$, $\vec{x}\to A\vec{x}$, A = $[\vec{v_{1}}, \vec{v_{2}}...., \vec{v_{n}}]$ $T_A$ is linear 



## Examples:
1. $$ T: R^{2}\to R^1$$$$\begin{bmatrix}  
x \\  
y   
\end{bmatrix} \to [z]$$
2. Transformation on the x-axis$$ T: R^{2}\to R^2$$
$$\begin{bmatrix} x \\y\end{bmatrix} \to \begin{bmatrix} x + 1 \\y\end{bmatrix}=\begin{bmatrix} x \\y\end{bmatrix}+\begin{bmatrix} 1 \\0\end{bmatrix}$$
3. $$ T: R^{2}\to R^2$$
$$\begin{bmatrix} x \\y\end{bmatrix} \to \begin{bmatrix} \frac{1}{2}x + \frac{3}{4}y \\ -\frac{1}{2}x + \frac{1}{4}y\end{bmatrix}=x\begin{bmatrix} \frac{1}{2} \\ -\frac{1}{2}\end{bmatrix}+y\begin{bmatrix} \frac{3}{4} \\ \frac{1}{4}\end{bmatrix}$$
