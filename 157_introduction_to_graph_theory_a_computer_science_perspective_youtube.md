
# Table of Contents

1.  [Definition of A Graph](#org44fe77b)
2.  [Terminology](#org81f4ce4)
    1.  [Neighbors](#org1236b10)
    2.  [Degree](#org3b7ad4a)
    3.  [Path](#org3d99d5b)
        1.  [path length](#orgdac0be1)
        2.  [cycle](#org5453355)
    4.  [Connectivity](#orga383c60)
        1.  [Connected component](#org20b1862)
3.  [Types of Graphs](#orgfa2e357)
    1.  [Undirected graph](#org9b1b827)
    2.  [Directed graph](#org7eae090)
    3.  [Cyclic vs Acyclic graph](#org1b4fab9)
    4.  [Weighted graph](#org5df9979)
    5.  [Trees](#org6986931)
4.  [Graph Representations](#org7ccccdd)
    1.  [Adjacency matrix](#orgdca3f13)
    2.  [Edge Set](#org219b44d)
    3.  [Adjacency List](#org846e97c)
5.  [Personal Summary](#org10cbb08)



<a id="org44fe77b"></a>

# Definition of A Graph

A graph $G = (V, E)$ is a set of vertices $V$ and edges $E$ where each $(u, v)$ is a connection between vertices. $u, v \in V$
 Vertices and nodes are used interchangebly.


<a id="org81f4ce4"></a>

# Terminology


<a id="org1236b10"></a>

## Neighbors

    Two vertices are neighbors if an edge connects them.
vertices $u$ and $v$ are neighbors if an edge $(u, v)$ connects them.


<a id="org3b7ad4a"></a>

## Degree

Degree - degree$(v)$ is equal to the number of edges connected to $v$


<a id="org3d99d5b"></a>

## Path

Sequence of vertices connected by edges


<a id="orgdac0be1"></a>

### path length

number of edges in a path


<a id="org5453355"></a>

### cycle

path that starts and ends at the same vertex


<a id="orga383c60"></a>

## Connectivity

two vertices are connected if a path exists between them.

A graph is connected when all vertices are connected.


<a id="org20b1862"></a>

### Connected component

A subset of vertices  $V_{i} \subseteq V$ that is connected


<a id="orgfa2e357"></a>

# Types of Graphs


<a id="org9b1b827"></a>

## Undirected graph

Edges don&rsquo;t have a direction


<a id="org7eae090"></a>

## Directed graph

Edges are unidirectional


<a id="org1b4fab9"></a>

## Cyclic vs Acyclic graph

A graph with cycles is called cyclic

A graph without cycles is called acyclic


<a id="org5df9979"></a>

## Weighted graph

A graph where edges are weighted


<a id="org6986931"></a>

## Trees

1.  Trees are connected and acyclical graphs
2.  Removing an edge disconnects the graph
3.  Adding an edge creates a cycle


<a id="org7ccccdd"></a>

# Graph Representations


<a id="orgdca3f13"></a>

## Adjacency matrix

\begin{equation}
A_{ij} = \begin{cases}
1, & \text{for edge $(i,j)$}\\
0, & \text{otherwise}
\end{cases}
\end{equation}

Each edge creates 2 entries because the graph is undirected.


<a id="org219b44d"></a>

## Edge Set


<a id="org846e97c"></a>

## Adjacency List

Each node gets a list of other nodes it is connected to.
This is common because it is memory efficient


<a id="org10cbb08"></a>

# Personal Summary

Graph Theory is a useful tool for modeling many computer science problems. Graphs are edges and vertices (nodes). Its useful for modeling many problems, Some that come to mind are the Directed Acyclical nature of personal identity and git.

