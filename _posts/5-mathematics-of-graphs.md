---
title: '5 Mathematics Of Graphs'
excerpt:
  »	apply concepts/procedures in graph theory to real life problems (S)<br/>
  »	advocate the use of graphs in real life situations (V)  <br/>
order: 5
coverImage: '/assets/blog/5/Connected-Graph.png'
ogImage:
  url: '/assets/blog/5/Connected-Graph.png'
---

## Graph
A graph is a set of
points called *vertices*
and line segments or
curves called *edges*
that connects
vertices.

The number of vertices of a graph is called **order**.

The number of edges that meet at a vertex is called the
**degree** of a vertex.

A **path** in a graph can be thought of as a movement from
one vertex to another by traversing edges.

If a path ends at the same vertex at which it started, it is
considered a **closed path**, or **circuit**.

A circuit that uses every edge, but never uses the same edge
twice, is called an **Euler circuit**.  

## Eulerian Graph Theorem
A connected graph is
**Eulerian**
if and only if
each vertex of the graph is
of even degree.

- A *Euler path* is a path that uses every edge of a graph
exactly once.
- A *Euler circuit* is a circuit that uses every edge of a
graph exactly once.
- A *Euler path* starts and ends at different vertices.
- A *Euler circuit* starts and ends at the same vertex.

## Weighted Graphs

A *weighted graph* is
a graph in which
each edge is
associated with a
value, called a
*weight*.



## Euler's Formula


![Tetrahedron](/assets/blog/5/Tetrahedron.png)

In a connected planar
graph drawn with no
intersecting edges, let v be
the number of vertices, e
the number of edges, and
f the number of faces,
then **v + f = e + 2**.

## Map Coloring

In graph coloring, each vertex of a graph will be assigned
one color in such away that no two adjacent vertices have
the same color. The interesting idea here is to determine
the minimum number of (distinct) colors to be used so that
we can color each vertex of a graph with no two adjacent
vertices have the same color.

The minimum number of
colors needed to color a
graph so that no edge
connects vertices of the
same color is called the
**chromatic number**.