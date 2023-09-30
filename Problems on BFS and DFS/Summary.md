## Important points to remember : 

1. Conver matrix to Adjacency List :

```java
private  List<List<Integer>> buildGraph(int n, int[][] connections) {
      List<List<Integer>> adjList = new ArrayList<>();
      for (int i = 0; i < n; i++) {
          adjList.add(new ArrayList<>());
      }
      for (int[] connection: connections) {
          adjList.get(connection[0]).add(connection[1]);
          adjList.get(connection[1]).add(connection[0]);
      }
      return adjList;
  }

```

   
2. 

