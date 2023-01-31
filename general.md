- [](#)

# stack a number of GNN layers equal to the network diameter

> In the Neural Message Passing framework, each node in a GNN layer makes use of the info coming from its direct neighbors.
When you stack 2 GNN layers, it means that the 2nd layer takes as input the info resulting from the 1st GNN layer, thus using the info coming from the neighbors of neighbors (so called 2-hop neighborhood, the set of nodes having shortest path from the source node equal to 2).  
source from: https://stats.stackexchange.com/questions/501244/how-many-layers-are-needed-in-a-graph-network-before-each-node-indirectly-uses