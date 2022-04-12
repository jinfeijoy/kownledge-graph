# Graph Neural Network




## Embedding:
* How does the GNN create the graph embedding? When the graph data is passed to the GNN, the features of each node are combined with those of its neighboring nodes. This is called “message passing.” If the GNN is composed of more than one layer, then subsequent layers repeat the message-passing operation, gathering data from neighbors of neighbors and aggregating them with the values obtained from the previous layer. For example, in a social network, the first layer of the GNN would combine the data of the user with those of their friends, and the next layer would add data from the friends of friends and so on. Finally, the output layer of the GNN produces the embedding, which is a vector representation of the node’s data and its knowledge of other nodes in the graph.

## Reference:
* [Top Trends of Graph Machine Learning in 2020](https://towardsdatascience.com/top-trends-of-graph-machine-learning-in-2020-1194175351a3)
* [Graph ML in 2022: Where Are We Now?](https://towardsdatascience.com/graph-ml-in-2022-where-are-we-now-f7f8242599e0) 
* [Graph Embedding](https://dmccreary.medium.com/understanding-graph-embeddings-79342921a97f) 