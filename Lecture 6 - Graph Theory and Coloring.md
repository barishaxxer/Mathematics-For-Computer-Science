
A **graph** G is a pair of sets (V, E) where\
V is a nonempty set of items called **vertices** or **nodes**\
E is a set of 2-item subsets of V called **edges**. 

![[Pasted image 20250126132159.png]]

$x \textemdash y$ is another notation for a edge.

Two nodes x and y are **adjacent** if they are connected by edge.

An edge e = {x, y} is **incident** to x and y.

The number of edges incident to a node is the **degree** of the node.Denoted by deg(x).

A graph is **simple** if it has no loops or multiple edges:
- ==Loop== is a edge only connect up one node.
- **Multiple edge** is we have got two edges connects the same endpoints.


# Graph Coloring Problem  

> [!info] Definition
> Given a graph G and K colors,  assign a color to each node so adjacent nodes get different colors.

> [!tip] Chromatic Number
> The minimum value of K for which such a coloring exists is the **Chromatic Number** of G denoted by $\chi(G)$

## Basic Graph Coloring Alg

for G = (V, E)

1. order the nodes
2. order the colors
3. For  i=1,2... n assign lowest legal color.


A *bipartite graph* can be colored with two colors such that no two adjacent vertices share the same color. This means we can divide the graph’s vertices into two distinct sets where:
- All edges connect vertices from one set to vertices in the other set.
- No edges exist between vertices within the same set.

![[BipartiteGraph.svg]]

