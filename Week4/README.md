# Graph Theory
## Introduction
A graph $(G)$ is a mathematical structure used to model pairwise relationships between objects. It consists of a pair of points $(V,E)$ where $V$ is a set of objects called vertices (representing entities such as locations, cities) and $E$ is a set of two elements called edges (representing reltionships such as roads, pipes). Consider the simple graph $G$ below:

![GraphExample](https://i.postimg.cc/RFpyhGfX/Graph-Example.png)

It consists of vertices $V(G)= \\{a,b,c,d,e\\}$ and edges $E(G)= \\{ab, bc, cd, de, ae\\}$.

Two vertices that are connected to each other via an edge are said to be **adjacent**. e.g.- $a$ and $b$, $a$ and $e$, $a$ and $d$, $b$ and $c$, etc.

Two edges that share a common vertice are said to be **incident**. e.g.- $ae$ and $ab$, $cd$ and $da$, etc

The **neighbours** of a vertex are the vertices it is adjacent to. e.g.- Neighbours to $a$ are $b$, $d$, and $e$.

The **degree** of a vertex is the number of edges it is an endpoint of.
- $deg(d)= 4 \space\\{ad, cd, ed\\}$
- $deg(b)= 2 \space \\{ab, cb\\}$

## Types of Graphs
1. Undirected Graph – Edges have no direction.
2. Directed Graph (Digraph) – Edges have a direction (from one vertex to another).
3. Mixed Graph – Contains both directed and undirected edges.
4. Weighted Graph – Edges have weights (e.g., distances, costs).
5. Unweighted Graph – All edges are considered equal (no weights).
6. Cyclic Graph – Contains at least one cycle.
7. Acyclic Graph – No cycles (A connected graph that contains no cycles is refered to as a (minimum) spanning tree)
8. Bipartite Graph – Vertices can be divided into two disjoint sets with edges only between sets.

## Applications
1. **Transportation & logistics:** Graphs model optimal (eg- shortest, least costly) routes to minimize delays and high costs, minimize costs in manufacturing/distribution networks, traffic and road/highway networks.
2. **Biology and medicine:** Disease spread modelling with people as nodes and interactions as edges.
3. **Electrical Design:** Model power stations and transmission lines

