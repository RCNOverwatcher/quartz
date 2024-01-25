---
banner: "![[furthermaths.jpg]]"
---
# Proof by Mathematical Induction

> [!Tip] The process
> 1. Show the statement works for $n=1$
> 2. Assume the statement is true for $n=k$
> 3. Show if true for $n=k$ then must be true for $n=k+1$.
> 4. Conclusion: If it is true for $n=1$ and true for $n=k$ then it is true for $n=k+1$ making it true for all natural$n$

> [!Example]- Prove by induction for all positive  $n$, that $\sum_{r=1}^{n}r^3=\frac{1}{4}n^2(n+1)^2$
> 1. Sub in $n=1$
>    $1^2=\frac{1}{4}(1)(4)=1$
>    2. We assume equal for $n=k$
>    3. $\sum_{r=1}^{k+1}r^3=\sum_{r=1}^{k}r^3+(k+1)^3$
>       $\sum_{r=1}^{k+1}r^3=\frac{1}{4}k^2(k+1)^2+(k+1)^3$
>       $=(\frac{1}{4}k^3+\frac{1}{4}k^2)^2+(k+1)^3$
>       $=(\frac{1}{4}k^6+\frac{1}{4}k^4)+(k+1)^3$
>        $=\frac{1}{4}(k^6+k^4)+(k+1)^3$
>       
>       
>       $=\frac{1}{4}(k+1)^2(k+1+1)^2$