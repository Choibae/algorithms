# Shortest Path Algorithms

Relax $\left(u, v, w \right)$
if $$ d\left[ v \right] > d\left[ u \right] + \omega\left(u, v\right) $$
$$ d\left[ v \right] = d\left[ u \right] + \omega\left(u, v\right) $$

```
Relax(u,v,w)
if d[v] > d[u]+w(u,v)
  d[v]=d[u]+w(u,v)
```
