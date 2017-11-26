# Shortest Path Problem
In graph theory, the shortest path problem is the problem of finding a path between two vertices (or nodes) in a graph such that the sum of the weights of its edges is minimized.

```
Relax(u,v,w)
if d[v] > d[u]+w(u,v)
  d[v]=d[u]+w(u,v)
```
