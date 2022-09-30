---
title: "Limits"
---

# Limits
**course:**
## Definition 
$$\lim_{x\to c}f(x)=L \text{ if for every N > 0 there exists B > 0 such that for all points } x \cdot |x-c|<B, \text{ one has } |f(x)-L|<N$$ 
### Example:
prove $\lim_{x\to 2}x=2$, $f(x)=x$
suppose $N > 0$ Let $B = N$
if $x$ is such that $|x-2|<B=N$
Then $|f(x)-f(2)|=|x-2|<N$

![[Limits 2022-09-27 14.09.53.excalidraw]]

![[Limits 2022-09-27 14.13.35.excalidraw]]
## Use of limits
1. $$\lim_{x \to \infty} \frac{1}{x^\infty } = 0$$
2. $$\lim_{x \to \infty} a^{-x}= 0$$
3. $$\lim_{x \to \infty} a^{x}= 0 \text{ when a < 1}$$
- [[asymptote]]
## Normal limits
$$\lim_{x\to a} f(x)=l$$
$f(x)$ is close to $l$ as $x$ approaches $a$. You can approach from the right and from the left.
Right:
$$\lim_{x\to a+} f(x)=l$$
Left:
$$\lim_{x\to a-} f(x)=l$$
**Rule 1:**
if P is a polynomial 
$$\lim_{x\to a} P(x)=P(a)$$
**Rule 2:**
P, Q as polynomials, $Q(a)!=0$
$$\lim_{x\to a} \frac{P(x)}{Q(x)}=\frac{P(a)}{Q(a)}$$

**Rule 3**
f(x), g(x), h(x) defined around an interval.
suppose $f(x)\leq h(x) \leq g(x)$
$$\lim_{x\to a} f(x)=l=\lim_{x\to a} g(x)$$
then $$\lim_{x\to a} h(x)=l$$
**Example:**
![[Pasted image 20220920133625.png]]

## Limits to infinity 
**Example:**[[asymptote]]
![[Pasted image 20220920134751.png]]
![[Pasted image 20220920134744.png]]

## Backlinks

## Refrences:

---
Tags: #Concept #Limits #Uni 