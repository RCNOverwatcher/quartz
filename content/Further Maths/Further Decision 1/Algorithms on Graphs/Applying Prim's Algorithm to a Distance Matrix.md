---
banner: "![[furthermaths.jpg]]"
---
# Applying Prim's Algorithm to a Distance Matrix

#### Large Networks are sometimes described using a distance matrix

> [!Info] Prim's in a distance matrix
> 1. Choose any vertex to start the tree.
> 2. Delete the **row** in the matrix for the chosen vertex.
> 3. Number the **column** in the matrix for the chosen vertex.
> 4. Put a ring around the lowest undeleted entry in the numbered columns.
> 5. The ringed entry becomes the next arc to add to the graph.
> 6. Repeat steps 2-5 until all rows are deleted.

