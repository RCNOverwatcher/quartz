---
banner: "![[maths.jpg]]"
---
# Implicit Differentiation 

> [!Info] Implicit Differentiation 
> $$\frac{dy}{dx}x^2+y^2=100$$
>
>##### Fake way to do it
> - Rearrange for $y$
> - $y=(100-x^2)^{\frac{1}{2}}$
> - $\frac{dy}{dx} \frac{1}{2}(100-x^2)^{-\frac{1}{2}} \times -2x$
> - $\frac{dy}{dx}=-\frac{x}{\sqrt{ (100-x^2) }}$
>   
>  ##### The real way to do it
>  - Differentiate from left to right
>  - $x^2+y^2=100$
>  - $2x+2y \frac{dy}{dx}=0$
>  - $2y \frac{dy}{dx}=2x$
>  - $\frac{dy}{dx}=\frac{2x}{-2y}$
>  - $\frac{dy}{dx}=-\frac{x}{y}$

> [!Example]- $y^2+3x+xy=0$ with respect to $x$
> - $3y^2 \frac{dy}{dx}+3+\frac{dy}{dx}=0$
> - $3y^2 \frac{dy}{dx}+\frac{dy}{dx}=-3$
> - $3y^2 \frac{dy}{dx}=-3-\frac{dy}{dx}$

> [!Example]- $x^3+x+y^3+3y=6$
> - $3x^2+1+3y^2\frac{dy}{dx}+3\frac{dy}{dx}=0$
> - $3y^2\frac{dy}{dx}+3\frac{dy}{dx}=-3x^2-1$
> - $\frac{dy}{dx}(3x^2+3)=-3x^2-1$
> - $\frac{dy}{dx}=-\frac{3x^2-1}{3x^2+3}$

> [!Example]- $x^2+y^2+10x+2y-4xy=10$
> - $\frac{dy}{dx}\to2x+2y \frac{dy}{dx}+10+\frac{dy}{dx}-4x\frac{dy}{dx}-4y=0$
> - $2x+10-4y=-2y\frac{dy}{dx}-\frac{dy}{dx}+4x\frac{dy}{dx}$
> - $\frac{dy}{dx}(-2y-1+4x)=2x+10-4y$
> - $\frac{dy}{dx}=\frac{2x+10-4y}{-2y-1+4x}$

