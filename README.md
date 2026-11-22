DSC212 - MODULARITY ON KARATE CLUB GRAPH

We apply modularity to Zachary's Karate Club graph to detect communities.
A random baseline graph (same node degrees, random edges) is used to find
divisions with more intra-community and fewer inter-community edges than
chance. The modularity score Q is maximised using recursive spectral
partitioning, and node metrics (degree, betweenness, closeness, clustering)
are tracked after each split.

