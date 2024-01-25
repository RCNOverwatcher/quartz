---
banner: "![[maths.jpg]]"
---
# Integration by parts 
$\DeclareMathOperator{cosec}{cosec}$
> [!Tip] Equation 
> 
> $$\int u\frac{dv}{dx} \, dx =uv-\int v\frac{du}{dx} \, dx$$
> 
> - The $x$ part (the part which can disappear) is the one which we use for $u$
> - If part of the integral loops round (like a trig identity), then we use that part for the integration bit ($v$) , not the differentiation bit

> [!Example]- $\int x\cos x \, dx$
> - $u=x$
> - $\frac{du}{dx}=1$
> - $\frac{dv}{dx}=\cos x$
> - $v=\sin x$
> ---
> - $\int x\cos x \, dx=x\sin x--\cos x+c$
> - $=x\sin x+\cos x+c$

> [!Example]- $\int x^2\ln x \, dx$
> - $u=\ln x$
> - $\frac{du}{dx}=\frac{1}{x}$
> - $\frac{dv}{dx}=x^2$
> - $v=\frac{x^3}{3}$
> ---
> - $\int x^2\ln x \, dx=\frac{x^3}{3}\ln x-\int x^{\cancel{ 3 }2}\times\frac{1}{\cancel{ x }} \, dx$
> - $=x^3\ln x-\int \frac{x^2}{3} \, dx$
> - $=\frac{x^3}{3}\ln x-\frac{x^3}{9}+c$

> [!Example]- $\int x^2e^x \, dx$
>  - $u=x^2$
>  - $\frac{du}{dx}=2x$
>  - $\frac{dv}{dx}=e^x$
>  - $v=e^x$
>  ---
>  - $=x^2e^x-\int e^x2x \, dx$

