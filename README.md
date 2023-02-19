# Comaprsison-Between-BFS-and-DFS

## Task Explanation:

Depth-First Search (DFS) & Breadth First Search (BFS) Algorithms: Depth-First Search (DFS) and Breadth-First Search (BFS) are two of the most common search algorithms used in graph traversal. Both algorithms can be used to find a path from a source node to a goal node, but they work in different ways.
DFS starts at the source node and explores as far as possible along each branch before backtracking. This means that it searches deeply before exploring breadth-wise. It uses a stack to keep track of the nodes to be visited, and it visits the first unvisited node on the stack. DFS is useful when the solution is deep in the graph, and it is not necessary to explore all the nodes in the graph.
BFS, on the other hand, explores all the neighboring nodes of the source node before moving on to the next level of nodes. This means that it searches breadth-wise before exploring deeply. It uses a queue to keep track of the nodes to be visited, and it visits the first unvisited node in the queue. BFS is useful when the solution is close to the source node, and it is necessary to explore all the nodes in the graph.

## Code Explanation:

This code implements the Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms to find the shortest path between two nodes in a graph. The graph is represented as an adjacency list, where each node has a list of its neighboring nodes and the weight of the edge between them.
The DFS and BFS classes are defined as subclasses of the data_set class, which contains the graph data. Each of these subclasses has a constructor that takes the source and destination nodes as input. The finding_shortest_path() method of the DFS and BFS classes uses the respective algorithm to traverse the graph and find the shortest path between the source and destination nodes. The output_shortest_path() method prints the shortest path found using the respective algorithm.
The outperform_other() function takes the shortest path found by the BFS and DFS algorithms and checks which algorithm outperformed the other. If the distance found by the BFS is smaller than the distance found by the DFS, then the BFS algorithm outperformed the DFS algorithm, and vice versa. If both algorithms return the same distance, then they are considered to have the same performance.
In the main section, an object of the BFS class and an object of the DFS class are created with the source and destination nodes. Then the shortest path between the source and destination nodes is found using the finding_shortest_path() method and printed using the output_shortest_path() method. Finally, the performance of the two algorithms is compared using the outperform_other() function.


