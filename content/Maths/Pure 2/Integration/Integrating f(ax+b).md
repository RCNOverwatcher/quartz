---
banner: "![[maths.jpg]]"
---
# Integrating f(ax+b) 
$\DeclareMathOperator{cosec}{cosec}$
> [!Example]- $\int sec^{2} 3x \, dx$
> - Consider $y=\tan 3x$
> - $\frac{dy}{dx}=3sec^{2}3x$
> - $\therefore =\frac{1}{3}\tan 3x$

> [!Info] Info on how to integrate $f(ax+b)$
> - Guess as to what you could differentiate to get the equation you are given
> - E.G. If the equation was $\frac{1}{3x+2}$, you would guess $y=\ln |3x+2|$
> - If you get a result as the thing you want but multiplied by a constant, just divide by that constant.
> - $\frac{dy}{dx}=\frac{1}{3x+2}\times 3$
> - and don't forget to plus $c$
> - So our answer would be $\frac{1}{3}\ln |3x+2|+c$

> [!Example]- $\int \cos(2x+1) \, dx$
> - Let $y=\sin(2x+1)$
> - $\frac{dy}{dx}=\sin(2x+1)\times 2$
> - So $\int \cos(2x+1) \, dx=\frac{1}{2}\sin(2x+1)+c$

> [!Example]- $\int \sin(2x+3) \, dx$
> - Let $y=-\cos(2x+3)$
> - $\frac{dy}{dx}=\sin(2x+3)\times 2$
> - So $\int \sin(2x+3) \, dx=-\frac{1}{2}\cos(2x+3)+c$

> [!Example]- $\int 3e^{2x} \, dx$
> - Let $y=e^{2x}$
> - $\frac{dy}{dx}=2e^{2x}$
> - So $\int 3e^{2x} \, dx=\frac{3}{2}e^{2x}+c$

> [!Example]- $\int 4e^{x+5} \, dx$
> - Let $y=e^{x+5}$
> - $\frac{dy}{dx}=e^{x+5}$
> - So $\int 4e^{x+5} \, dx=4e^{x+5}+c$

> [!Example]- $\int \cos(1-2x) \, dx$
> - Let $y=\sin(1-2x)$
> - $\frac{dy}{dx}=-2\cos(1-2x)$
> - So $\int \cos(1-2x) \, dx=-\frac{1}{2}\sin(1-2x)+c$

> [!Example]- $\int \sec4x \tan4x \, dx$
> $\frac{dy}{dx}\sec 4x=16\sec4x \tan4x$
> So $\int \sec4x \tan4x \, dx=\frac{1}{4}\sec4x+c$

> [!Example]- $\int \cosec 2x \cot 2x \, dx$
> - $\frac{dy}{dx}(-\cosec 2x)=4\cosec 2x \cot 2x$