---
banner: "![[furthermaths.jpg]]"
---
# The Method of Differences 

> [!Info] The Method of Differences 
> - If we have a series in the form of $f(r)-f(r+1)$, then:
> 	- $\sum_{r=1}^{n}u_{r}=\sum_{r=1}^{n}(f(r)-f(r+1))$
> 	- $u_{1} = f(1)-f(2)$
> 	- $u_{2}=f(2)-f(3)$
> 	- $\dots$
> 	- $u_{n}=f(n)-f(n+1)$
> - This means that $\sum_{r=1}^{n}=f(1)-f(n+1)$


> [!Example]- Example 1
> 1. Show that $4r^3\equiv r^2(r+1)^2-(r-1)^2r^2$
> 	- $=r^2(r^2+2r+1)-(r^2-2r+1)r^2$
> 	- $=r^4+2r^3+r^2-r^4+2r^3-r^2$
> 	- $=4r^3$
> 
> 2. Prove that $\sum_{r=1}^{n}r^3=\frac{1}{4}n^2(n+1)^2$
> 	- Consider$\sum_{r=1}^{n}(r^2(r+1)^2-(r-1)^2r^2)$
> 	- Let $r=1$:  $\cancel{ 1^2(2^2) }-0^2(1^2)$
> 	- Let $r=2$: $\cancel{ 2^2(3^2) }\cancel{ -1^2(2^2) }$
> 	- Let $r=3$: $3^2(4^2)\cancel{ -2^2(3^2) }$
> 	- $\dots$
> 	- Let $r=n$: $n^2(n+1)^2\cancel{ -(n-1)^2n^2 }$
> 	- Leaves us with $n^2(n+1)^2$
> 	- So: $4\sum_{r=1}^{n}r^3=n^2(n+1)^2$
> 	- $\therefore \sum_{r=1}^nr^3=\frac{1}{4}n^2(n+1)^2$

> [!Example]- 1a) Show that $r\equiv \frac{1}{2}(r(r+1))-r(r-1)$
> - $r\equiv \frac{r^2+r}{2}-r^2+r$
> - $2r\equiv r^2+r-r^2+r$
> - $2r=2r$
> - $r=r$

> [!Example] 1b) Hence show that $\sum_{r=1}^{n}r=\frac{n}{2}(n+1)$ using the method of differences.
> 	- $\sum_{r=1}^{n}=\frac{1}{2}\sum_{r=1}^{n}r(r+1)-\frac{1}{2}\sum_{r=1}^{n}r(r-1)$
> 	- $r=1$: $\cancel{ \frac{1}{2}\times 1 \times 2 }-\frac{1}{2}\times 1 \times 0$
> 	- $r=2$: $\frac{1}{2}\times2\times3-\cancel{ \frac{1}{2}\times2\times 1 }$
> 	- $\dots$
> 	- $r=n$: $\left( \frac{1}{2}\times n\times (n+1) \right)\cancel{ -(\frac{1}{2}\times n \times ((n-1)) })$
> 	- Leaves us with$\frac{1}{2}n( n+1)$