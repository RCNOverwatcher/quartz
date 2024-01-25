---
banner: "![[maths.jpg]]"
---
# Expanding $(1-x)^n$ 

> [!Tip] The Binomial Infinite Series 
> - $$1+nx+\frac{n(n-1)}{2!}x^2+\frac{n(n-1)(n-2)}{3!}x^3\dots$$
> - This works for positive, negative or fractional powers, unlike the $nCr$ method.

> [!Example]- Expand: $\frac{1}{x-1}$
> - $\frac{1}{1-x}=(1-x)^{-1}$
> - $1+(1)(-x)+\frac{-1)(-2}{2!}(-x)^2\dots$
> - $1-x+x^2-x^3+\dots$

> [!Example]- Find the binomial expansion for these terms up to $x^3$
> 1. $(1+x)^{-4}=1+(-4)(x)+\frac{(-4)(-5)}{2!}x^2+\frac{(-4)(-5)(-6)}{3!}x^3$
>    $1-4x+10x^2-20x^3$
>   $|x|<1$
>2. $(1+x)^{-6}=1+(-6)(x)+\frac{(-6)(-7)}{2!}x^2+\frac{(-6)(-7)(-8)}{3!}x^3$
>    $1-6x+21x^2-56x^3$
>     $|x|<1$
>3. $(1+x)^{\frac{1}{2}}=1+\left( \frac{1}{2} \right)(x)+\frac{\left( \frac{1}{2} \right)\left( -\frac{1}{2} \right)}{2!}x^2+\frac{\left( \frac{1}{2} \right)\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right)}{3!}x^3$
>    $1+\frac{1}{2}x-\frac{1}{8}x^2+\frac{1}{16}x^3$
>     $|x|<1$

> [!Example]- Find the binomial expansion for these terms up to $x^3$
> 1. 
> 	   $(1+3x)^{-3}=1+(-3)(3x)+\frac{(-3)(-4)}{2}(3x)^2+\frac{(-3)(-4)(-5)}{6}(3x)^3$
> 	   $=1-9x+54x^2-270x^3$
> 	    $|x|<\frac{1}{3}$

> [!Abstract] Checking for Validity 
> - Expansions of $(1+bx)^n$ are valid for $|bx|<1$ or $|x|< \frac{1}{|b|}$

> [!Example]- $\frac{1+x}{1-2x}$
> a)
> 	- $(1+x)(1-2x)^{-1}$
> 	- $(1-2x)^{-1}=1+(-1)(-2x)+\frac{(-1)(-2)}{2}(-2x)^2+\frac{(-1)(-2)(-3)}{6}(-2x)^{3}$
> 	- $1+2x+4x^2+8x^3$
> 	- $(1+x)(1+2x+4x^2+8x^3)$
> 	- $(1+2x+4x^2+8x^3)+(x+2x^2+4x^3+8x^4)$
> 	- $(1+3x+6x^2+12x^3+8x^4)$
> b)
> 	- Validity is: $|-2x|<1$
> 	- Validity is: $|x|<-\frac{1}{2}$

> [!Example]- In the expansion of $(1+ax)^{-\frac{1}{2}}$, the coefficient of $x^2$ is 24. Find the possible values of $a$, then find the coefficients of $x^3$.
> a)
> 	- $1+(ax)\left( -\frac{1}{2} \right)+\frac{\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right)}{2}(ax)^2+\frac{\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right)\left( -\frac{5}{2} \right)}{6}(ax)^3$
> 	- $1-\frac{ax}{2}+\frac{3}{8}a^2x^2-\frac{5}{16}a^3x^3$
> 	- $\frac{3}{8}a^2x^2=24x^2$
> 	- $\frac{3}{8}a^2=24$
> 	- $a^2=64$
> 	- $a=8$
>b) 
> 	- $a=8$
> 	- $-\frac{5}{16}a^3x^3=-160x^3$
