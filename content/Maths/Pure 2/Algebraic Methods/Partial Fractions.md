---
banner: "![[maths.jpg]]"
---
# Partial Fractions

> [!Info] Partial Fractions 

> [!Example]- $\frac{6x-2}{(x-3)(x+1)}=\frac{A}{x-3}+\frac{B}{x+1}$
> - $A(x+1)+B(x-3)=6x-2$
> - $Ax+A+Bx-3B=6x-2$
> - $Ax+Bx+A-3B=6x-2$
> - $A+B=6$
> - $A-3B=-2$
> - $4B=8$
> - $B=2$
> - $A=4$
> ---
> - Set $x=3$ to cancel out one fraction.
> - $4A=16$
> - $A=4$
>   
> - Set $x=-1$
> - $-4B=-8$
> - $B=2$

> [!Example]- $\frac{6x^2+5x-2}{x(x-1)(2x+1)}=\frac{A}{x}+\frac{B}{x+1}+\frac{C}{2x+1}$
> - $6x^2+5x-2=A(x-1)(2x+1)+Bx(2x+1)+Cx(x-1)$
> - Set $x=1$
> - $9=3B$
> - $B=3$
> - Set $x=0$
> - $-2=-A$
> - $A=2$
> - Set $x=-1$
> - $6-5-2=4+3+2C$
> - $-1=7+2C$
> - $2C=-8$
> - $C=-4$

> [!Example]- $\frac{5x+3}{(2x-3)(x+2)}=\frac{A}{2x-3}+\frac{B}{x+2}$
> - $5x+3=A(x+2)+B(2x-3)$
> - Set $x=-2$
> - $-7=-7B$
> - $B=1$
> - Set $x=0$
> - $3=2A-3(1)$
> - $2A=6$
> - $A=3$

> [!Example]- Express $\frac{9x^2+20x-10}{(x+2)(3x-1)}$ in partial fractions.
> - $9x^2+20x-10=A(3x-1)+B(x+2)$
> - Set $x=-2$
> - Come back to this later 

> [!Example]- Express $\frac{4-2x}{(2x+1)(x+1)(x+3)}$
> - $4-2x=A(x+1)(x+3)+B(2x+1)(x+3)+C(2x+1)(x+1)$
> ---
> - Sub in $x=-\frac{1}{2}$
> - $4-2\left( -\frac{1}{2} \right)=A\left( -\frac{1}{2} \right)\left( \frac{5}{2} \right)$
> - $5=\frac{5}{4}A$
> - $A=4$
> ---
> Sub in $x=-1$
> - $6=-2B$
> - $B=-3$
> ---
> - Sub in $x=-3$
> - $10=10C$
> - $C=1$
> ---
> - Answer: $\frac{4}{2x+1}-\frac{3}{x+1}+\frac{1}{x+3}$


#### Repeated Linear Factors

> [!Example]- Split $\frac{9x^2}{(x-1)^2(2x+1)}$ into partial fractions 
> - $9x^2=A(x-1)(2x+1)+B(2x+1)+C(x-1)^2$
> ---
> - To find C, we sub in $x=-\frac{1}{2}$
> - $\frac{9}{4}=\frac{9}{4}C$
> - $C=1$
> ---
> - To find B, we sub in $x=1$
> - $9=B(3)$
> - $B=3$
> ---
> - To find A, we equate coefficients for $x^2$
> - $2A+C=9$
> - $2A+1=9$
> - $2A=8$
> - $A=4$

> [!Example]- $\frac{27x^2+32x+16}{(3x+2)^2(1-x)}$
> - $27x^2+32x+16=\frac{A}{(3x+2)}+\frac{B}{(3x+2)^2}+\frac{C}{(1-x)}$

> [!Example]- $\frac{3x+4}{(1+x)(2+x)^2}$
> $3x+4=\frac{A}{(1+x)}+\frac{B}{(2+x)}+\frac{C}{(2+x)^2}$
> $3x+4=A(2+x)^2+B(1+x)(2+x)+C(1+x)$
> ---
> - To find C we sub in $x=-2$
> - $-2=-C$
> - $C=2$
> ---
> - To find A we sub in $x=-1$
> - $1=A$
> - $A=1$
> ---
> - To find B we equate coefficients 
> - Set $x=0$
> - $4=4A+2B+C$
> - $2B=-2$
> - $B=-1$
> ---
> $3x+4=\frac{1}{(1+x)}-\frac{1}{(2+x)}+\frac{2}{(2+x)^2}$

