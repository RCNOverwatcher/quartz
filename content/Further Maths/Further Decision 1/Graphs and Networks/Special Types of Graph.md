---
banner: "![[furthermaths.jpg]]"
---
# Special types of Graph

>[!Info] Types of Graph
> - A tree is a connected graph with no cycles and one less arc than nodes.
> - A spanning tree of Graph G (where G is a full graph, not a tree) is a subgraph which includes all the vertices of G and is also a tree.
> - A complete network is a network where each node is directly connected to every other node in the network.
> - On a connected graph, you can get from one node to any other node, but not necessarily directly.
> - Isomorphic graphs are graphs that show the same information, but are drawn in a different way.


##### A complete network is a network where each node is directly connected to every other node in the network.

> [!Info] Info
> Notation K<sub>n</sub> is the complete network of **n** number of nodes.
The sequence for the number of arcs in a complete network is basically factorial with addition. (aka $\sum_{r=1}^{n}r=1+2+3+\dots+n = \frac{n\times (n+1)}{2}$)
One way of thinking about this is that an arc has two endings, therefore you can do Number of nodes in network x Number of nodes in network -1, all divided by 2.
This gives the same answer.
