---
banner: "![[maths.jpg]]"
---
# Iteration

> [!Example]- Find the roots of $x^3+2x^2-3$
> - $x^3=3-2x^2$
> - $x=\sqrt[3]{ 3-2x^2 }$
> ---
> - $2x^2=2-x^3$
> - $x=\sqrt{ \frac{3-x^3}{2} }$
> ---
> - The same $x$ value must satisfy all of these equations!
> ---
> - We can use an iterative formula to get an accurate guess at the root.
> - $x=\sqrt{ \frac{3-x^3}{2} }\to x_{n}=\sqrt{ \frac{3-x_{n}^3}{2} }$

> [!Example]- Using the iterative formula $x_{n+1}=\sqrt{ 1+\frac{2}{3}x_{n}\sin\left( \frac{1}{2}(x_{n})^2 \right) }$, $x_{0}=1.3$
> - Find the values of $x_{1}$ and $x_{2}$
> - $x_{1}:\sqrt{ 1+\frac{2}{3}\times1.3\times\sin\left( \frac{1}{2}(1.3)^2 \right) }=1.2838\dots$
> - $x_{2}:\sqrt{ 1+\frac{2}{3}\times1.2838\times\sin\left( \frac{1}{2}(1.2838)^2 \right) }=1.2760\dots$

> [!Example]- Iterative formulae that converge and diverge
> $$\sqrt{\frac{ x_{n}^3-2x_{n}+5 }{3}}$$
> - $x=1.5 \implies 1.2016\dots$
> - $x=4\implies\infty$

