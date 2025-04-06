# Graph Theory
# Introduction
A graph $(G)$ is a mathematical structure used to model pairwise relationships between objects. It consists of a pair of points $(V,E)$ where $V$ is a set of objects called vertices (representing entities such as locations, cities) and $E$ is a set of two elements called edges (representing reltionships such as roads, pipes). Consider the simple graph $G$ below:

![GraphExample](https://i.postimg.cc/RFpyhGfX/Graph-Example.png)

It consists of vertices $V(G)= \\{a,b,c,d,e\\}$ and edges $E(G)= \\{ab, bc, cd, de, ae\\}$.

Two vertices that are connected to each other via an edge are said to be **adjacent**. e.g.- $a$ and $b$, $a$ and $e$, $a$ and $d$, $b$ and $c$, etc.

Two edges that share a common vertice are said to be **incident**. e.g.- $ae$ and $ab$, $cd$ and $da$, etc

The **neighbours** of a vertex are the vertices it is adjacent to. e.g.- Neighbours to $a$ are $b$, $d$, and $e$.

The **degree** of a vertex is the number of edges it is an endpoint of. e.g.- $deg(d)= 4 \space \space \space \\{ad, cd, ed\\}$


