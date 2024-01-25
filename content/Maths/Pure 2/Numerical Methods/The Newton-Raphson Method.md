---
banner: "![[maths.jpg]]"
---
# The Newton-Raphson Method

> [!Tip] Newton-Raphson Method  
> $$x_{n+1}=x_{n}-\frac{f(x_{n})}{f^{'}(x_{n})}$$

> [!Example]- $x^3-2$
> $$f(x)=x^3-2\implies x_{n+1}=x_{n}-\frac{(x_{n})^3-2}{3(x_{n})^2}$$
> $$f(x)=\tan x\implies x_{n+1}=x_{n}-\frac{\tan x_{n}}{sec^2x_{n}}$$

> [!Example]- $\frac{1}{2}x_{n}^4-x_{n}^3+x_{n}-3$
> $$x_{n}-\frac{\frac{1}{2}x_{n}^4-x_{n}^3+x_{n}-3}{2x_{n}^3-3x_{n}^2+1}$$
> $$-1.5-\frac{\frac{1}{2}(-1.5)^4-(-1.5)^3+(-1.5)-3}{2(-1.5)^3-3(-1.5)^2+1}=-1.3875\dots$$

> [!Example]- $3x^2-\frac{11}{x^2}$
> $$1.4-\frac{3(1.4)^2-\frac{11}{1.4^2}}{(6\times1.4)+\frac{22}{1.4^3}}$$

