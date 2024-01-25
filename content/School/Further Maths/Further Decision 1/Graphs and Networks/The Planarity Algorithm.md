---
banner: "![[furthermaths.jpg]]"
---
<div class="title">​</div>
<div class="title">​</div>

# The Planarity Algorithm

> [!Info] Method
> 1. Identify a Hamiltonian Cycle
> 2. Arrange it in a polygon (E.G. 8 nodes in a hamiltonian cycle would be drawn as an octogon)
> 3. Draw arcs inside the polygon created to match the original graph before the hamiltonian cycle
> 4. Make a list of all the arcs **inside** the polygon (E.G. AC, DF, CG)
> 5. Choose any unlabeled arc in the list and label it (I). If all arcs are now labeled, then the graph is planar
> 6. Look at the **unlabeled** arcs that cross over the arc that was just labelled
>     - If there are none, go to step 5
>     - If any of these arcs cross over each other, then the graph is **non-planar**
>     - If none of these arcs cross each other, give the (O) tag to the arc that was previously labelled (I)
>     - If all edges are now labelled, the graph is **planar**, otherwise go back to the beginning of step 6.

