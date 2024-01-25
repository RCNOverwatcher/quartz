---
banner: "![[maths.jpg]]"
---
# Integration by Substitution

> [!Example]- Example 12a
> - Find $\int x\sqrt{ 2x+5 }\, dx$
> - We let $u=2x+5$ be our substitution.
> - $\frac{du}{dx}=2$
> - Rearrange to give $dx=\frac{du}{2}$
> - Now the sqaure root goes to $\sqrt{ 2x+5 }=u^{\frac{1}{2}}$
> - $x=\frac{u-5}{2}$
> - We can now rewrite our integral in terms of $u$: $I = \int \frac{u-5}{2}u^{\frac{1}{2}} \times \frac{1}{2}\, du$
> - $= \int \frac{1}{4}(u-5)u^{\frac{1}{2}} \, du$
> - $= \int \frac{1}{4}\left( u^{\frac{3}{2}}-5u^{\frac{1}{2}} \right) \, du$
> - We now integrate: $\frac{1}{4}\times \frac{u^{\frac{5}{2}}}{\frac{5}{2}}-\frac{5u^{\frac{3}{2}}}{4\times \frac{3}{2}}+c$
> - Simplifies to: $\frac{u^{\frac{5}{2}}}{10}-\frac{5u^{\frac{3}{2}}}{6}+c$
> - Our final answer is: $\int = \frac{(2x+5)^{5/2}}{10}-\frac{5(2x+5)^{\frac{3}{2}}}{6}+c$

> [!Example]- Example 12b
> - Our integral is $\int x\sqrt{ 2x+5 }\, dx$
> - Substitution is: $u^2=2x+5$
> - [[Implicit Differentiation]] means that this differentiates to $2u \frac{du}{dx}=2$
> - Rearrange: $2u \frac{du}{2}=dx$
> - $dx=udu$
> ---
> - $\sqrt{ 2x+5 }=u$
> - $x=\frac{u^2-5}{2}$
> - $I=\int (\frac{u^2-5}{2})u^2\times du$ (simplified $u\times u \to u^2$)
> - $= \int \left( \frac{u^4}{2} -\frac{5u^2}{2}\right) du$
> $= \frac{u^5}{10}-\frac{5u^3}{6}+c$

> [!Example]- $\int \cos x\sin x (1-\sin x)^3\, dx$
> - Using $u=\sin x+1$
> - $\frac{du}{dx}=\cos x$
> - $dx=\frac{du}{\cos x}$
> - $\int (u-1)(u^3) \, du$
> - $\int u^4-u^3 \, du$
> - $=\frac{u^5}{5}-\frac{u^4}{4}+c$
> - $\frac{(\sin x+1)^5}{5}-\frac{(\sin x+1)^4}{4}+c$

> [!Example]- $\int x\sqrt{ 1+x } \, dx, u=1+x$
> - $\frac{du}{dx}=1$
> - $du=dx$
> - $\int (u-1)(u)^{\frac{1}{2}} \, du$
> - $= \int u^{\frac{3}{2}}-u^{\frac{1}{2}} \, du$
> - $=\frac{u^{\frac{5}{2}}}{\frac{5}{2}}-\frac{u^{\frac{3}{2}}}{\frac{3}{2}}$
> - $=\frac{2u^{\frac{5}{2}}}{5}+\frac{2u^{\frac{3}{2}}}{3}+c$

> [!Example]- $\int \frac{1+\sin x}{\cos x} \, dx,u=\sin x$
> - $\frac{du}{dx}=\cos x$
> - $dx=\frac{du}{\cos x}$
> - $\int \frac{1+u}{\cos^2x} \, du$
> - $\int \frac{1+u}{\cos^2x} \, du$
> - $\int \frac{1+u}{(1+u)(1-u)} \, du$
> - $\int \frac{1}{1-u} \, du$
> - $=\ln |1-u|+c$
> - $=\ln |1-\sin x|+c$

> [!Example]- $\int \sin^3x \, dx,u=\cos x$
> - $\frac{du}{dx}=-\sin x$
> - $-du=\sin xdx$
> - $dx=-\frac{du}{\sin x}$
> - $\int (\sin x)(1-\cos^2x) \, dx$
> - $\int (\cos^2x-1) \, du$
> - $\int (u^2-1) \, du$
> - $= \frac{u^3}{3}-x$
> - $=\frac{\cos^3 x}{3}-\cos x+c$

