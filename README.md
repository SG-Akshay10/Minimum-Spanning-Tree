# Minimum Spanning Tree
Implementaion of Prim's and Kruskal's algorithm using Minimum Spanning Tree

Minimum Spanning Tree (MST) is a popular problem in graph theory where the goal is to find a subgraph of a given graph that connects all of the vertices together and has the minimum possible total edge weight. There are two well-known algorithms to solve this problem: Prim's and Kruskal's algorithm.

# Prim's algorithm

Prim's algorithm starts with an arbitrary vertex and iteratively adds the closest vertex that is not yet in the MST. The closest vertex is determined by the edge with the minimum weight that connects a vertex in the MST to a vertex not in the MST. The algorithm terminates when all the vertices are in the MST.

# Kruskal's algorithm 

Kruskal's algorithm starts with an empty MST and iteratively adds edges with the minimum weight, as long as they do not create a cycle. The algorithm terminates when all the vertices are connected. Kruskal's algorithm uses a union-find data structure to check if adding an edge will create a cycle.

Both of these algorithms have a time complexity of O(E log V) for sparse graph and can be implemented using a priority queue. The difference between these two algorithms is that Prim's algorithm is used for dense graphs and Kruskal's algorithm is used for sparse graphs.

When to use Prim's algorithm and when to use Kruskal's algorithm?

Prim's algorithm is useful when the graph is dense and the number of edges is close to the number of vertices squared.
Kruskal's algorithm is useful when the graph is sparse and the number of edges is much less than the number of vertices squared.
In order to use these algorithms, it's important to have a good understanding of the graph data structure and the time and space complexity of the algorithms. Additionally, it's important to have a good understanding of the union-find data structure, which is used to check if adding an edge will create a cycle in the Kruskal's algorithm.

In summary, Minimum Spanning Tree is an important problem in graph theory, and Prim's and Kruskal's algorithms are two well-known algorithms that can be used to solve this problem. Both of these algorithms have a time complexity of O(E log V) and can be implemented using a priority queue. However, Prim's algorithm is useful when the graph is dense and the number of edges is close to the number of vertices squared, whereas Kruskal's algorithm is useful when the graph is sparse and the number of edges is much less than the number of vertices squared.
