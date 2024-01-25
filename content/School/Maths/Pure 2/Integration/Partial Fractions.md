---
banner: "![[maths.jpg]]"
---
# Partial Fractions 
$\DeclareMathOperator{cosec}{cosec}$
> [!Info] Integrating Partial Fractions 
> - You can integrate algebraic fractions by converting them to partial fractions first.

> [!Example]- $\int \frac{x-5}{(x+1)(x-2)} \, dx$
> - $x-5=A(x-2)+B(x+1)$
> - Let $x=-1$:
> 	   $-6=-3A$ 
> 	   so $A=2$
> - Let $x=2$: 
> 	  $-3=B(3)$
> 	  So $B=-1$
> - So $\int \frac{x-5}{(x+1)(x-2)} \, dx=\int \left( \frac{2}{x+1}-\frac{1}{x-2} \right) \, dx$
> - $=2\ln |x+1|-\ln |x-2|+c$
> - $=\ln |\frac{(x+1)^2}{x-2}|+c$

