---
banner: "![[furthermaths.jpg]]"
---
# Kruskal's Algorithm

### Kruskal's algorithm is used to find a minimum spanning tree

> [!Info] Kruskal's Algorithm
> 1. Sort arcs into ascending weight
> 2. Select arc of least weight to start
> 3. Look at the next arc in the list:
>     - if the next arc forms a cycle, reject it
> 	- otherwise, add it to the new graph
> 4. Repeat step 3 until there are no more arcs left
>    
>    
> ![[Pasted image 20221107164334.png|500]]

