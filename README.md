This repository contains useful templates for competitive programming that can be used in ACM and UVa problem solving.

Using C++ 5.3.0 with -std=c++11

Some templates are written by myself and some are inspired by other talented authors and then modified to either general or specific usage.

Contents Table:
    
    Template:

        General template for c++ competitive problem solving

    Special Data Structures:

        Union-Find or Disjointed set implementation
        Fenwick Tree(Binary Indexed Tree) implementation
        Segment Tree implementation
        //Suffix Tree

    Techniques:

        Longest Increasing Subseqence(LIS)
        Maximum Sum Subarray(Kadane's Algorithm)
        Dynamic Programming + Memoization

    Graph Algorithms:
        
        UNWEIGHTED SHORTEST PATH:
        Breath First Search(BFS) O(V+E)
        Depth First Search(DFS) O(V+E)

        WEIGHTED SHORTEST PATH:
        Dijkstra's algorithm --- single-source shortest path problem. O(ElogV) E times logV using extract min from heap
        Bellman–Ford algorithm --- single-source problem if edge weights may be negative. O(VE) O(V^2) on sparse O(V^3) on dense.
        Floyd–Warshall algorithm --- all pairs shortest paths. O(V^3) dp three for loop ijk
        //Johnson's algorithm --- all pairs shortest paths, and may be faster than Floyd–Warshall on sparse graphs.
        SPFA(Shortest Path Faster Algorithm) --- Improve performance of Bellman-Ford
        
        UNWEIGHTED ORDERING:
        Topological Sort(dfs + stack)

        MINIMUM SPANNING TREE:
        Kruskal's algorithm
        Prim's algorithm

        MAXFLOW MIN-CUT:
        Ford-Fullkerson algorithm

        ARTICULATION & BRIDGES:
        Tarjan's Algorithm

    String Algorithms:
        
        Violent string matching O(TP)
        Knuth-Morris-Pratt(KMP) O(T+P)

    Geometry:
        
        Graham scanning(Convex Hull) O(n^2 log n)

Created by DENG ZISHI on 2/17/17.
Copyright © 2017 DENG ZISHI. All rights reserved.


