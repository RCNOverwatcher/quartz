---
banner: "![[maths.jpg]]"
---
# Reverse Chain Rule
$\DeclareMathOperator{cosec}{cosec}$
> [!Info] What is Reverse Chain Rule: Example
> - A function in the form: $\frac{f^{'}(x)}{f(x)}$
> - $\int \frac{2x}{x^2+1} \, dx$
> - Consider $y=\ln |x^2+1|$
> - $\frac{dy}{dx}=\frac{1}{x^2+1}\times 2x$ (using chain rule)
> - = $\frac{2x}{x^2+1}$
> - $\int \frac{2x}{x^2+1} \, dx=\ln |x^2+1|+c$

##### Using fractions

> [!Example]- Example 1
> - E.G. $\int x(x^2+1)^6\, dx$
> - Try $(x^2+1)^7$
> - $\frac{d}{dx}=7(x^2+1)^6$
> - $= 14x(x^2+1)^6$
> - $= \frac{1}{14}(x^2+1)^7$

> [!Example]- Example 2
> - E.G. $\int \sin^4x\cos x\, dx$
> - Try $\sin^5x$
> - $\frac{d}{dx}=5\sin^4x\cos x$
> - $\int  =\frac{1}{5}\sin^5x$

##### Using $\ln$

> [!Example]- Example 4
> - E.G. $\int \frac{\cos x}{3+2\sin x}\, dx$
> - Try $\ln|3+2\sin x|$
> - $\frac{1}{3+2\sin x}\times 2\cos x$
> - $= \frac{2\cos x}{3+2\sin x}$
> - This result is double of the equation we want so we put a $\frac{1}{2}$ in front of our $\ln$ equation we tried earlier.
> - $\frac{1}{2}\ln|3+2\sin x|+c$

> [!Example]- Ex4 Q1a
> - E.G. $\frac{e^{2x}}{e^{2x}+1}$
> - Try: $\ln|e^{2x}+1|$
> - $= \frac{1}{e^{2x}+1}\times2e^{2x}$
> - $= \frac{2x}{x^2+4}$
> - So our final answer is:$\frac{1}{2}\ln|x^2+4|+c$

> [!Example]- Ex4 Q1b
> - E.G. $\frac{e^{2x}}{e^{2x}+1}$
> - Try: $\ln|e^{2x}+1|$
> - $= \frac{1}{e^{2x}}\times2e^{2x}$
> - $= \frac{2e^{2x}}{2e^{2x}+1}$
> - So our final answer is:$\frac{1}{2}\ln|e^{2x}+1|+c$

##### Using $\int kf^{'}(x)(f(x))^n \, dx$

> [!Example]- Given that $\int ^\theta_{0}5\tan x \sec^4x \, dx=\frac{15}{4}$ find the exact value of $\theta$
> - Let $I=\int ^\theta_{0}5\tan x \sec^4x \, dx$
> - Let $y=\sec^4x$
> - $\frac{dy}{dx}=4\sec^3x\times\sec x\tan x=4\sec^4x\times \tan x$
> - So $I=\left[ \frac{5}{4}\sec^4x \right]^\theta_{0}=\frac{15}{4}$
> - $\left( \frac{5}{4}\sec^4\theta \right)-\left( \frac{5}{4}\sec^40 \right)=\frac{15}{4}$
> - $\frac{5}{4}\sec^4\theta-\frac{5}{4}=\frac{15}{4}$
> - $\frac{5}{4}\sec^4\theta=\frac{20}{4}$
> - $\sec^4\theta=4$
> - $\sec\theta=^+_{-}\sqrt{ 2 }$
> - $\theta=\frac{\pi}{4}$

##### Practice Questions

> [!Example]- $\frac{x}{x^2+4}$
> - Try $\ln |x^2+4|$
> - $\frac{1}{x^2+4}\times 2x$
> - $\frac{2x}{x^2+4}$
> - Add constant to adjust:
>   $\frac{1}{2}\ln |x^2+4|$

> [!Example]- $\frac{e^{2x}}{e^{2x}+1}$
> - Try $\ln |e^{2x}+1|$
> - $\frac{dy}{dx}=\frac{1}{e^{2x}+1}\times e^{2x}$
> - $=\frac{2e^{2x}}{e^{2x}+1}$
> - Adjust with constant 
> - $\frac{1}{2}\ln |e^{2x}+1|$

> [!Example]- $\frac{x}{(x^2+4)^3}$
> - Try $(x^2+4)^{-2}$
> - $\frac{dy}{dx}=(x^2+4)^{-3}\times 2x$
> - $2x(x^2+4)^{-3}$
> - $\frac{2x}{(x^2+4)^3}$
> - Adjust with constant 
> - $\frac{1}{2}(x^2+4)^{-2}$

> [!Example]- $\frac{e^{2x}}{(e^{2x}+1)^3}$
> - Let $y=(e^{2x}+1)^{-2}$
> - $\frac{dy}{dx}=-2(e^{2x}+1)^{-3}\times2e^{2x}$
> - $=-4e^{2x}(e^{2x+1})^{-3}$
> - $=\frac{-4e^{2x}}{(e^{2x}+1)^{-3}}$
> - Add constant to adjust 
> - $-4(e^{2x}+1)^{-2}$

