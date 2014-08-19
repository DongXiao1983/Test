1. >> help graphshortestpath
 GRAPHSHORTESTPATH solves the shortest path problem in graph.
 
  [DIST,PATH,PRED] = GRAPHSHORTESTPATH(G,S) determines the single source
  shortest paths from node S to all other nodes in the graph G. Weights of
  the edges are all nonzero entries in the n-by-n adjacency matrix
  represented by the sparse matrix G. DIST are the n distances from source
  to every node (using Inf for non-reachable nodes and zero for the source
  node). The PATH contains the winning paths to every node, and PRED
  contains the predecessor nodes of the winning paths. 


fearless_d
Fearless
