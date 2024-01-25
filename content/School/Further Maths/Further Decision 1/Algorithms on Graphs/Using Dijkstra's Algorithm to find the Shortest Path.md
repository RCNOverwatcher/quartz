---
banner: "![[furthermaths.jpg]]"
---
# Using Dijkstra's Algorithm to find the Shortest Path

### Dijkstra's Algorithm can be used to find the shortest path between two nodes on a weighted network (pronounce "Dike-Stra")

> [!Info] Dijkstra's Algorithm
> 1. Label the start vertex, S, with the final label, 0.
> 2. Record a working value at every vertex, Y, that is directly connected to the vertex, that has just received its final label, X.
> 	- Working value at Y. final label at X+ weight of arc XY
> 	- If there is already a working value at Y, it is only replaced if the new value is smaller.
> 	- Once a vertex has a final label, it is not revisited and its working values are no longer considered.
> 3. Look at the working values at all vertices without final labels. Select the smallest working value. This now becomes the final label at that vertex. (If two vertices have the same smallest working value, either may be given its final label first.)
> 4. Repeat steps 2 and 3 until the destination vertex, T, receives its final label.
> 5. To find the shortest path, trace back from T to S. Given that B already lies on the route, include arc AB whenever: final label of B — final label of A = weight of arc AB

