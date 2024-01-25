---
banner: "![[furthermaths.jpg]]"
---
# Order of an Algorithm

> [!Info] Quadratic Order
> Bubble sort is an example of an algorithm with quadratic order
> - Bubble sort is to do with making comparisons. Therefore for a list of size $n$, the first pass will take $(n-1)$ comparisons
> - Assuming some swaps are made, the next pas will take $(n-2)$ comparisons. This trend continues, and when we expand this final expression out, we get a quadratic. Therefore it has quadratic order
> - This means that if a list has size of 10 and it takes 2 seconds to solve, then a list of size 100 will take 200 seconds to solve.

 >[!Info] Other orders
 >If $k$ is the factor of how much larger the size of the list is, then:
 >- Linear order will be $k$
 >- Quadratic order will be $k^2$
 >- Cubic order will be $k^3$
 
 > [!Info] Time taken for a list of $n$ numbers
 > Bob's Algorithm: $\frac{n^3}{100}-3n$ (cubic order)
 > Terry's Algorithm: $7000000n^2+40000n$ (quadratic order)
 > 
 > When combining algorithms together, *the order is only as big as the largest exponent in any of the orders in the seperate algorithms*.
 
 
 
 