## Connected components : 

A connected component or simply component of an undirected graph is a subgraph in which each pair of nodes is connected with each other via a path.

![image](https://github.com/alkabharti/Graph/assets/23376002/7042bf71-d89f-4dd4-8dc3-733c4c7948c7)

### Because of different components in a graph we use the concept of visited array to traverse all nodes. 

```java
Vertex = 5
for node to Vertex(n)
  if (!visited[index])
    do traversal
```

## Traversal Techniques : 

### BFS Traversal 

- The **Breadth First Search (BFS) algorithm** is used to search a graph data structure for a node that meets a set of criteria. It starts at the root of the graph and **visits all nodes at the current depth level** before moving on to the nodes at the next depth level.
- Breadth-First Traversal (or Search) for a graph is similar to the Breadth-First Traversal of a tree.

- The only catch here is, that, **unlike trees, graphs may contain cycles**, so we may come to the same node again. To avoid processing a node more than once, we divide the vertices into two categories:
  - Visited and
  - Not visited.

 - https://www.geeksforgeeks.org/breadth-first-search-or-bfs-for-a-graph/


### DFS Traversal 

- Depth-first search is an algorithm for traversing or searching tree or graph data structures.
- The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.

- https://www.geeksforgeeks.org/depth-first-search-or-dfs-for-a-graph/




  

