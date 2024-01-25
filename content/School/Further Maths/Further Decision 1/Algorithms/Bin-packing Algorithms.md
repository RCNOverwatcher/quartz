---
banner: "![[furthermaths.jpg]]"
---
# Bin-packing Algorithms

### First Fit Algorithm

> [!Info] First Fit Algorithm
> **There are 12 vehicles waiting to get on a 3 lane ferry of 30m length**
> 3, 15, 14, 2, 5, 5, 8, 11, 4, 17, 7, 3 m in length respectively
> L<sub>1</sub> 3, 15<sub>18</sub> , 2<sub>20</sub> , 5<sub>25</sub> , 5<sub>30</sub>
> L<sub>2</sub> 14, 8<sub>22</sub> , 4<sub>26</sub> , 3<sub>29</sub>
> L<sub>3</sub> 11, 17<sub>28</sub>
> 
> **7 cannot get on, as the amount of space left is less than 7**

### First Fit Decreasing

> [!Info] First Fit Decreasing
> **Sort the list into size order decreasing.**
> 3, 15, 14, 2, 5, 5, 8, 11, 4, 17, 7, 3
> 
> *17, 15, 14, 11, 8, 7, 5, 5, 4, 3, 3, 2*
> 
> L<sub>1</sub> 17, 11<sub>28</sub> , 2<sub>30</sub>
> L<sub>2</sub> 15, 14<sub>29</sub>
> L<sub>3</sub> 8, 7<sub>15</sub> , 5<sub>20</sub> , 5<sub>25</sub> , 4<sub>29</sub>
>
>**Better by 1, two 3m vehicles dont get in**

### Full Bin Algorithm

> [!info] Inspection (Full bin algorithm)
> Can you do any better by yourself?
> 
> 14+11+5 = 30
> 15+7+3+5 = 30
> 17+8+3+2 = 30
> 
> 4m vehicle left over
> 
> $\therefore$ we can do better!

