# Ex3

This Object oriented programming task was written by:
* Shahar Niknazar - 316416668 
* Or Gamliel - 208202663

The main topic is developing logic for a game where a group of robots needs to perform movement on weighted and directed graph.
Our game represented by StdDraw.

We have 5 classes in our project:

Fruit -

Robot - 

StdDraw - 

DGraph  - implements the interface "graph" and represents a directional weighted graph.
 * The interface has a road-system or communication network in mind - and should support a large number of nodes (over 100,000).
 * The implementation based on an efficient compact representation.
 
Graph_Algo –  Implements the interface "graph_algorithms", represents bunch of algorithms based on the graph we've created in DGraph.
Vertex - Implements the interface node_data, represents a vertex in our graph
Edge - Implements the interface edge_data, represents a vertex in our graph
GUI  - This class represents a graphical interface here we can display a graph, Run algorithms on it and View their results.




Our graph have few methods:

1) **getV** - returns a collection that contains all the vertecis.
2) **getE** - returns a collection of edges of a given vertex key.
3) **removeNode** - remove the node and all the linked edges.
4) **removeEdge** - remove the edge with a  source and destination as input.
5) **addNode** - add a node to the graph.
6) **getNode** - returns the node with a given node key.
7) **connect** - initialize an edge from source node to destination with weight as input.
8) **getEdge** - initialize the edge of source and destination as input.




Graph_Algo class have few methods:

1) **shortestPathDist** - returns the shortest distance from source to destination using dijkstra algorithem.
2) **shortestPath** - returns the shortest path from the source to destination using dijkstra algorithem.
3) **TSP** -from list of keys as input , the function will calculate and return the shortest path between all the vertices.
4) **init** - initialize a graph from an input file.
5) **save** - save a graph to a file.
6) **isConnected** - checks whether the graph is strongly connected.


GUI:

This class represents a graphical interface. Here we can display a graph, Run algorithms on it and View their results.




