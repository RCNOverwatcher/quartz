---
banner: "![[furthermaths.jpg]]"
---
# Sums of Natural Numbers

## What are Series

> [!Info] Series
> - A series is a sum of a finite or infinite number of terms
> - $\sum$ is the notation used to define a series
> - E.G. $$\sum_{r=1}^{5} (2r+1)$$
> - The answer to this would be $3+5+7+9+11 = 35$

## Essential Formulae

> [!Info] The formulae
> - n: $$\sum_{r=1}^{n}1=n$$
> - Sum of the first n integers: $$\sum_{r=1}^{n}r=1+2+3+\dots+n = \frac{n\times (n+1)}{2}$$
> - Sum of the first n squares: $$\sum_{r=1}^{n}r^{2}=\frac{1}{6}n(n+1)(2n+1)$$
> - Sum of the first n cubes: $$\sum_{r=1}^{n}r^{3}=\frac{1}{4}n^{2}(n+1)^2$$
> - Subtracting series: $$\sum_{r=a}^nf(r)=\sum_{r=1}^nf(r)-\sum_{r=1}^{a-1}f(r)$$
> - Variables: $$\sum_{r=1}^nkf(r)=k\sum_{r=1}^nf(r)$$


## Subtracting Series
 
> [!Info] Subtracting series
> - To add up all the integers from 3 to 9: $$\sum_{n=1}^9r-\sum_{r=1}^2r$$
> - This gives us $$\sum_{n=3}^9r$$
 
> [!Info] With algebra
> - Example with algebra: $$\sum_{r=n}^{3n}r=\sum_{r=1}^{3n}r-\sum_{r=1}^{n-1}r$$
> - $$=\frac{1}{2}(3n)(3n+1)-\frac{1}{2}(n-1)(n)$$
> - $$=\frac{1}{2}n(3(3n+1)-(n-1))$$
> - $$=\frac{1}{2}n(9n+3-n+1)$$
> - $$\frac{1}{2}n(8n+4)$$
> - $$2n(2n+1)$$


## Breaking Up Summations

> [!Info] Breaking up summations
> - $$\sum_{i=1}^n(a_{i}+b{i})=a_{1}+b_{1}+a_{2}+b_{2}+\dots+a_{n}+b_{n}$$
> - $$=a_{1}+a_{2}+a_{3}+a_{4}+\dots+a_{n}+b_{1}+b_{2}+b_{3}+b_{4}+\dots+b_{n}$$
> - $$=\sum_{i=1}^na_{i}+\sum_{i=1}^nb_{i}$$

> [!Example]- Show that $\sum_{r=1}^n(3r+2)=\frac{n}{2}(3n+7)$
> - $$\sum_{r=1}^n3r+\sum_{r=1}^n2$$
> - $$\frac{3}{2}n(n+1)+2n$$
> - $$\frac{n}{2}[3(n+1)+4]$$
> - $$\frac{n}{2}(3n+3+4)$$
> - $$\frac{n}{2}(3n+7)$$
