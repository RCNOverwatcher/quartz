---
banner: "![[maths.jpg]]"
---
# Solving Differential Equations 

> [!Tip] Tips
> - $\frac{dy}{dx}=f(x)g(y)$
> - $\int \frac{1}{g(y)} \, dy=\int f(x) \, dx$
> - Need to add $+c$ to both sides of the equation after integration 
> - The family of solutions of a differential equation is the graphical representation of the curve with different values of $c$
> ---
> e.g. $\frac{dy}{dx}=12x^2-1$
> $\int 1 \, dy=\int (12x^2-1) \, dx$
> $y=4x^3-x+c$
> $=x(2x-1)(2x+1)+c \to$ This is a general solution as we do not know what $c$ is. 
> ---
> - If we know a point on the curve of the particular solution we want to find, you can find what $c$ is.
> - This point is called a boundary condition

> [!Example]- Find the general solution to $(1+x^2)\frac{dy}{dx}=x\tan y$
> - $\frac{1}{\tan y}dy=\frac{x}{1+x^2}dx$
> - $\int \frac{1}{\tan y} \, dy=\int \frac{x}{1+x^2} \, dx$
> - $\int \cot y \, dy=\int \frac{x}{1+x^2} \, dx$
> - $\ln |\sin y|=\frac{1}{2}\ln |1+x^2|+\ln k$
> - $\ln |\sin y|=\ln k\sqrt{ 1+x^2 }$
> - $\sin y=k\sqrt{ 1+x^2 }$
> - $y=\arcsin(k\sqrt{ 1+x^2 })$

> [!Example]- Find the particular solution to $\frac{dy}{dx}=-\frac{3(y-2)}{(2x+1)(x+2)}$ given that $x=1$ when $y=4$
> - $\frac{1}{y-2}dy=-\frac{3}{(2x+1)(x+2)}dx$
> - $-\frac{3}{(2x+1)(x+2)}=\frac{A}{2x+1}+\frac{B}{x+2}$
> - $-3=A(x+2)+B(2x+1)$
> - $x=-2$
> - $-3=-3B\to B=1$
> - $x=-\frac{1}{2}$
> - $-3=\frac{3}{2}A\to A=-2$
> ---
> - $\int \frac{1}{y-2} \, dy=\int \left( -\frac{2}{2x+1}+\frac{1}{x+2} \right) \, dx$
> - $\ln |y-2|=-\ln |2x+1|+\ln |x+2|+\ln k$
> - Since $x=1$, $y=4$
> - $\ln2=-\ln3+\ln3+\ln k$
> - $\ln2=\ln k$
> - $k=2$
> ---
> - $\ln |y-2|=\ln |\frac{k(x-2)}{2x+1}|$
> - $y-2=\frac{2(x+2)}{2x+1}$
> - $y=\frac{2x+4}{2x+1}+2$
> ---
> - Top heavy fraction so simplify:
> - $y=\frac{3}{2x+1}+3$

> [!Example]- Find the general solution to $\frac{dy}{dx}=(1+y)(1-2x)$
> - $\int \frac{1}{1+y} \, dy=\int 1-2x \, dx$
> - $\ln |1+y|=x-x^2+c$
> - $1+y=e^{x-x^2+c}$
> - $y=e^{x-x^2+c}-1$
> - $B=e^c$
> - $y=Be^{x-x^2}-1$

> [!Example]- Find the general solution to $\frac{dy}{dx}=y\tan x$
> - $\int \frac{1}{y} \, dy=\int \tan x \, dx$
> - $\dots$

