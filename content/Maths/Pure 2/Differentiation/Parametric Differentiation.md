---
banner: "![[maths.jpg]]"
---
# Parametric Differentiation 

> [!Tip] If $x$ and $y$ are given as functions of a parameter $t$, then:
> $$\frac{dy}{dx}=\frac{\frac{dy}{dt}}{\frac{dx}{dt}}$$

> [!Example]- Find the equation of the normal at the point $p$ where $\theta=\frac{\pi}{6}$ to the curve with parametric equations $x=3\sin\theta$ and $y=5\cos\theta$
> - When $\theta=\frac{\pi}{6}$, $x=3\sin\left( \frac{\pi}{6} \right)=\frac{3}{2}$ and $y=5\cos\left( \frac{\pi}{6} \right)=\frac{5\sqrt{ 3 }}{2}$
> - $\frac{dx}{d\theta}=3\cos\theta$
> - $\frac{dy}{d\theta}=-5\sin\theta$
> - $\frac{dy}{dx}=-\frac{5\sin\theta}{3\cos\theta}=-\frac{3}{5}\tan\theta$
> - When $\theta=\frac{\pi}{6}$, $\frac{dy}{dx}=-\frac{5}{3}\tan\left( \frac{\pi}{6} \right)=-\frac{5\sqrt{ 3 }}{9}$
> ---
> - $\left( y-\frac{5\sqrt{ 3 }}{2} \right)=-\frac{9}{5\sqrt{ 3 }}\left( x-\frac{3}{2} \right)$
> - $\left( y-\frac{5\sqrt{ 3 }}{2} \right)=-\frac{3\sqrt{ 3 }}{5}\left( x-\frac{3}{2} \right)$

> [!Example]- $x=\sqrt{ 3 }\sin2t$, $y=4\cos^2t$, $0\leq t\leq \pi$
> Show that $\frac{dy}{dx}=k\sqrt{ 3 }\tan2t$
> - $\frac{dy}{dt}4(\cos t)^2=8\cos t\times-\sin t=-8\cos t\sin t$
> - $\frac{dx}{dt}=2\sqrt{ 3 }\cos2t$
> - $\frac{dy}{dx}=-\frac{8\cos t\sin t}{2\sqrt{ 3 }\cos2t}$

