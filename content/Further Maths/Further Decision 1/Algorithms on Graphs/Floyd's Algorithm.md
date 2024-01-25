---
banner: "![[furthermaths.jpg]]"
---
<div class="title">​</div>
<div class="title">​</div>

# Floyd's Algorithm

> [!Info] Method
> 1. Complete an initial distance table with only nodes that connect, if there is no direct route, then replace with an infinity symbol
> 2. Complete an initial route table
> 3. In the first iteration, copy the first row and first column into a new table and shade these values lightly
> 4. Consider each unshaded box in turn and match it up with the values on the shaded row and column
> 5. If the box and column values that correspond to the unshaded value are less, then update the value in the new table with brackets around it
> 6. Repeat for the second row and column

> [!Example] [[Floyd's Algorithm]] 
> 
> | -         | 7         | 10 | $\infty$ | 14        |
|-----------|-----------|----|-----------|-----------|
| 7         | -         | 19 | 11        | $\infty$ |
| $\infty$ | 19        | -  | 24        | $\infty$ |
| $\infty$ | 11        | 24 | -         | 1         |
| 10        | $\infty$ | 17 | 1         | -         |
