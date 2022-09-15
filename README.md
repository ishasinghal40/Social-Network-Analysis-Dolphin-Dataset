# Social-Network-Analysis-Dolphin-Dataset

**The Dataset:**

The bottlenose dolphin is a very intelligent social creature. Just like humans, dolphins group have their own social connection with each member. They communicate with their group by ultrasonic, which can help them exchange information and divide their work and make decisions.

The dataset contains a list of all of links, where a link represents frequent associations between dolphins.

**Betweenness Centrality:**

It measures how often a node appears on shortest paths between nodes in the network.

Betweenness centrality is a way of detecting the amount of influence a node has over the flow of information in a graph. It is often used to find nodes that serve as a bridge from one part of a graph to another. The algorithm calculates unweighted shortest paths between all pairs of nodes in a graph.

**Closeness Centrality:**

The average distance from a given starting node to all other nodes in the network.
Closeness centrality is a measure of the average shortest distance from each vertex to each other vertex. Specifically, it is the inverse of the average shortest distance between the vertex and all other vertices in the network. The formula is 1/(average distance to all other vertices).

**Degree:**

The degree of a vertex is the number of edges that are attached to it. The degree sum formula says that if you add up the degree of all the vertices in a (finite) graph, the result is twice the number of the edges in the graph.

**Average Degree (5.129):**

The average degree of an undirected graph is used to measure the number of edges compared to the number of nodes. To do this we simply divide the summation of all nodes' degree by the total number of nodes.

**Diameter of a Network (8):**

It is the shortest distance between the two most distant nodes in the network. In other words, once the shortest path length from every node to all other nodes is calculated, the diameter is the longest of all the calculated path lengths.

**Graph Density (0.084):**

Graph density represents the ratio between the edges present in a graph and the maximum number of edges that the graph can contain. Conceptually, it provides an idea of how dense a graph is in terms of edge connectivity.

**Clustering Coefficient (0.303):**

A clustering coefficient is a measure of the degree to which nodes in a graph tend to cluster together.

It tells how well connected the neighborhood of the node is. If the neighborhood is fully connected, the clustering coefficient is 1 and a value close to 0 means that there are hardly any connections in the neighborhood.

**Eigenvector Centrality:**

Eigenvector Centrality is an algorithm that measures the transitive influence of nodes. Relationships originating from high-scoring nodes contribute more to the score of a node than connections from low-scoring nodes. A high eigenvector score means that a node is connected to many nodes who themselves have high scores.

**Average Path Length (3.357):**

Average path length, or average shortest path length is a concept in network topology that is defined as the average number of steps along the shortest paths for all possible pairs of network nodes.

**Connections of a Node:**

Begin at any arbitrary node of the graph, G. Proceed from that node using either depth-first or breadth-first search, counting all nodes reached. Once the graph has been entirely traversed, if the number of nodes counted is equal to the number of nodes of G, the graph is connected; otherwise it is disconnected.
