---
banner: "![[maths.jpg]]"
---
# Differentiating Trigonometric Functions 

> [!Example]- Differentiating $\tan(x)$
> - $u=\sin x$
> - $v=\cos x$
> - $\frac{d}{dx}\frac{u}{v}=\frac{(\cos x\times \cos x)-(\sin x\times-\sin x)}{\cos^2x}$
> - $=\frac{\cos^2x+\sin^2x}{\cos^2x}$
> - $=\frac{1}{\cos^2x}=\sec^2x$

> [!Example]- Differentiating $\sec (x)$
> - $u=1$
> - $v=\cos x$
> - $\frac{d}{dx}\frac{u}{v}=\frac{(0\times \cos x)-(1\times-\sin x)}{\cos^2x}$
> - $=\frac{\sin x}{\cos^2x}$
> - $=\frac{\sin x}{\cos x}\times\frac{1}{\cos x}$
> - $=\sec x\tan x$

> [!Example]- Show that $\frac{d}{dx}(\sec^{2}3x)$ can be written in the form $\mu(\tan_{3}x+\tan^{3}3x)$ where $\mu$ is a constant.
> - $\frac{d}{dx}(\sec^{2}3x)=\frac{dy}{dx}(\sec3x)^2$
> - $=2\sec3x\times3\sec3x\tan 3x=6\sec^23x\tan3x$
> - $\sec^2x=1+\tan^2x$
> - So $6\sec^23x\tan3x=6(1+\tan^{2}3x)(\tan3x)=6\tan3x+6\tan^{3}3x=6(\tan3x+\tan^{3}3x)$
> - So $\mu=6$

> [!Example]- Show that if $y=\arcsin x$, then $\frac{dy}{dx}=\frac{1}{\sqrt{ 1-x^2 }}$
> - $y=\arcsin x$
> - $x=\sin y$
> - $\frac{dx}{dy}=\cos y$
> - $\frac{dy}{dx}=\frac{1}{\cos y}=\frac{1}{\sqrt{ 1-\sin^2y }}=\frac{1}{\sqrt{ 1-x^2 }}$

> [!Example]- Given that $y=\arcsin x^2$ find $\frac{dy}{dx}$
> - $y=\arcsin x^2$
> - $x^2=\sin y$
> - $x=\sqrt{ \sin y }=(\sin y)^{\frac{1}{2}}$
> - $\frac{dx}{dy}=\frac{1}{2}(\sin y)^{-\frac{1}{2}}\times \cos y$
> - $=\frac{\cos y}{2\sqrt{ \sin y }}$
> - $=\frac{2\sqrt{ \sin y }}{\cos y}$
> - $=\frac{2x}{\cos y}$
> - $\frac{dy}{dx}=\frac{2x}{\sqrt{ 1-x^4 }}$

> [!Example]- $x=\sec2y$ Find $\frac{dx}{dy}$
> - $\frac{dx}{dy}=2\sec2y\tan2y$
> - $\frac{dy}{dx}=\frac{1}{2\sec2y\tan2y}$
> - $=\frac{1}{\sqrt{ 2x }}\times\frac{1}{\sqrt{ x^2-1 }}$
