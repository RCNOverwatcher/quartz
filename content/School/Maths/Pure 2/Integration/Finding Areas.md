---
banner: "![[maths.jpg]]"
---
# Finding Areas 
$\DeclareMathOperator{cosec}{cosec}$
> [!Tip] Equation 
> $$R=\int ^b_{a}f(x) \, dx-\int ^b_{a}g(x) \, dx  =\int ^b_{a}(f(x)-g(x)) \, dx $$

> [!Example]- $f(x)=\sin2x$, $g(x)=\sin x\cos^2x$
> - Integrate between $0$ and $\frac{\pi}{2}$
> - $$\int _{0}^{\frac{\pi}{2}}(\sin2x-\sin x\cos^2x) \, dx=\left[ \frac{1}{2}\cos2x+\frac{1}{3}\cos^3x \right]^{\frac{\pi}{2}}_{0}$$

> [!Info] Differentiating Parametric Equations 
>  $$A=\int y \, dx=\int y\frac{dx}{dt} \, dt $$

> [!Example]- Parametric example, $x=t(1+t)$, $y=\frac{1}{1+t}$
> 
> - Find the indefinite integral: 
>   $$x=t(1+t)=t+t^2$$
>  
> 
> - $$\frac{dx}{dt}=1+2t$$
> 
> - $$\text{Area}=\int \frac{1}{1+t}\times(1+2t) \, dt $$
> 
> 
> - Find limits:
> $$x=2t(t+1)=2$$
> 
>
> - $$t^2+t-2=0$$
> 
> - $$\cancel{ t=-2 } \text{ or } t=1$$
>
> - Substitute limits in: $$\int _{0}^1 \frac{1+2t}{1+t} \, dt$$
>
> - $$\int _{0}^1\left( 2-\frac{1}{1+t} \right) \, dt $$
> 
> - $$\left[2t-\ln |1+t|te\right]^1_{0}$$

> [!Example]- The diagram with curve $C$ with parametric equations: $x=3t^2$, $y=\sin2t$, $t\geq 0$
> - Find the roots of this curve 
> - $\sin2t=0$
> - $t=0$, $t=\frac{\pi}{2}$
> ---
> - $\frac{dx}{dt}=6t$
> - $\therefore\int \sin2t \, dx=\int \sin2t\times6t \, dt$
> ---
> - Use integration by parts 
> - $u=6t$
> - $\frac{du}{dx}=6$
> - $\frac{dv}{dx}=\sin2t$
> - $v=-\frac{1}{2}\cos2t$
> - $-3t\cos2t-\int (-3\cos2t) \, dx$
> - $=-3t\cos2t-\frac{3}{2}\sin2t$
> - $-\frac{3\pi}{2}\cos \pi\cancel{ -\frac{3}{2}\sin \pi }$
> - $=\frac{3}{2}\pi$ 

