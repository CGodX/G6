---
title: Grid
order: 5
---

Grid Layout will order the nodes according to the parameters, and then place the nodes on the grids.

## Usage

As the demo below, you can deploy it in `layout` while instantiating Graph. it can also be used for [Subgraph Layout](/zh/docs/manual/middle/layout/#%E5%AD%90%E5%9B%BE%E5%B8%83%E5%B1%80). By tuning the parameters, you can adjust the iteration number, compact degree, layout buy cluster, and so on. By tuning the parameters, you can adjust the ordering method, rows, cols, prevent node overlappings, and so on.

- Example 1 : Basic Grid Layout, the nodes are ordered according to the data.
- Example 2 : Order the nodes according to the property `cluster`.
