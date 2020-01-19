# Ex3

welcome to our README about the game: "The Maze Of Waze"!

This Object oriented programming task was written by:
* Shahar Niknazar - 316416668 
* Or Gamliel - 208202663

The main topic is developing logic for a game where a group of robots needs to perform movement on weighted and directed graph.
Our game represented by StdDraw.

Game rules:
The robots earn points while collecting a prize.
Each prize have different score.
The direction of the robot's movement is injective.


We have 8 classes in our project:

1. MyFruit - This class represents the "prizes" that the robot is supposed to collect during the game. Our chosen robot is the famous soccer player Cristiano Ronaldo. Accordingly, the prizes are the goblet of Gold and a football.

2. Robot - This class represents the "robots" that supposed to collect the prizes during the game. Our chosen robot is the famous soccer player Cristiano Ronaldo. 

3. StdDraw - for representing the game graphically.

4. DGraph  - implements the interface "graph" and represents a directional weighted graph.
 * The interface has a road-system or communication network in mind - and should support a large number of nodes (over 100,000).
 * The implementation based on an efficient compact representation.
 
5. Graph_Algo –  Implements the interface "graph_algorithms", represents bunch of algorithms based on the graph we've created in DGraph.
6. Vertex - Implements the interface node_data, represents a vertex in our graph
7. Edge - Implements the interface edge_data, represents a vertex in our graph
8. KML - In our task, We implements the interface KML_Logger. It allows us to import the graph, the robots and the fruits to KML file.





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


For more information you can see our Wiki pages!



