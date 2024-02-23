# Graphs

## Lesson

1. In a graph a node is also called a _______.

1. An _______ is the connection between two nodes.

1. A graph with each node connected to every other nodes is a _______ graph.

1. The values on the edges of a weighted graph are the _______.

Answers Below[^1]

## Notes

- Non-linear data structure represented as vertices (nodes) and lines (edges)
- Terms
  - Vertex: node object with 0 or more adjacent vertices
  - Edge: connection between two nodes (vertices)
  - Neighbor: adjacent nodes connected with an edge
  - Degree: the number of edges connected to a node (vertex)
- Undirected Graph: all edges are undirected or bi-directional, graph does not "move" an any direction
- Directed Graph (Digraph): all edges are directed, each node is directed at another node
- Complete Graph: all nodes are connected to all other nodes
- Connected: all nodes have at least one edge
- Disconnected: some nodes do not have edges
- Cycle: a path starting at a node traversing through the graph that can end at the starting node
  - Cyclic Graph: a graph with at least one cycle
  - Acyclic Graph: a graph with no cycles
- Graph Representation:
  - Adjacency Matrix: A two-dimensional array, the rows and columns represent the vertices of the graph. If there is a edge a "1" is in the element at the position (row, col), if not then "0".
  - Adjacency List: Collection of linked lists or arrays representing all the vertices. Each list or array is a collection of all the other vertices it is connected to.
- Weighted Graph: a graph with numbers assigned to edges called weights

## References

[Code Fellows: Graphs](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-35/resources/graphs.html)

[^1]:> Answers: vertex, edge, complete, weights
