---
title: "Derivative"
---

# Derivative
## Uses:
See if a func is increasing/decreasing:
suppose $f:[a,b] \to   \mathbb{R}$
1. if $f(x_2) \gt f(x_1)$ where $x_{2} \gt x_1$ we say $f$ is increasing
2. if $f(x_2) < f(x_1)$ where $x_{2} \gt x_1$ we say $f$ is decreasing
3. if $f(x_2) \ge f(x_1)$ where $x_{2} \gt x_1$ we say $f$ is not decreasing
4. if $f(x_2) <= f(x_1)$ where $x_{2} \gt x_1$ we say $f$ is not increasing 

If derivative is positive in point $x_1$ in $f'(x_{1)}>0$ then the f is increasing in that point, Between interval: $f:[a,b] \to   \mathbb{R}$ 

### Example:
$f(x) = x^{3}- 12x+1$
$f'(x)=3x^2-12=3(x-2)(x+2)$
$f'(x)>0$ if $x<-2$  or $x>2$ 
$f'(x) < 0$ if $-2<x<2$
$f$ is increasing on $(-\infty, -2)$ and $(2, \infty)$
$f$ is decreasing on $(-2,2)$, -2 and 2 are places where $f'(x)=0$ . those points are called critical points.
## Definition
**Show differential:**
$$\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}=f'(x)$$
![[Derivative 2022-10-04 13.22.30.excalidraw.svg|250]]


### Example:
![[Pasted image 20221004133800.png]]

Compute:
- Use tricks below: 

We will focus on $C^{1}=[a,b]$  [[functions]], that means the function is [[derivative]] ones and it is continuous.

**Common rules:**
![[Pasted image 20220930094029.png]]
$(log_{a}(x))' = \frac{1}{x}\ln_a(e)$
$a^{x}=e^{x\ln(a)}(ln(a))$
$x^{x}=e^{x\ln(x)}(1+\ln x)$
## Theorem 1:
if $f(x)$ is differentiable at $x$, then $f$ is continuous at x
**Proof:**
![[Pasted image 20220930094609.png|200]]

## Theorem 3. Product Rule:
$$(f(x)\cdot g(x))',\text{ } f'(x)g(x)-f(x)g'(x)$$

## Theorem 5. Quotient rule:
$$(\frac{f(x)}{g(x)})'=\frac{nat-tan}{n^2}$$
## Theorem 6. Chain Rule
![[Pasted image 20220930095930.png]]

## Examples:
![[Derivative 2022-09-30 09.23.51.excalidraw.svg|200]]![[Derivative 2022-09-30 09.32.12.excalidraw.svg|200]]
## Backlinks

## Refrences:

---
Tags: #Concept #Derivative #Uni 