# SWH
Small-World Heuristic - a Full mesh network

The Small world Heuristic or SWH G(d,k) is a smart algorithm process to generate differents connected graphs.

* What is a graph? Graph or Network diagram show interconnections between a set of entities.
* What is an entity? entity is represented by a Node or vertice, e.g sensor.
* Connections between nodes are represented through links or edges or degree denoted (d).
* The -maximum distance- between two nodes is a Diameter denoted (k).
* What is a distance between two nodes? it is the length of longest shortest path.

According to some algorithm criteria:
* SWH generates new large vertex graphs with an out-degree and diameter.
* SWH can reach the Moore bound with some criteria.
* SWH generates mesh, torus and hypercube networks.
* SWH generates networks near to de Bruijn graph.


With SWH graph, you can customise your graph in term of number total of nodes, number of links and diameter.
SWH can reach the same/better characteristics of some largest known graphs,but the algo generates these graphs much faster:
https://en.wikipedia.org/wiki/Table_of_the_largest_known_graphs_of_a_given_diameter_and_maximal_degree.

* SWH(11,5) can reach 19520 nodes.
* SWH(16,3) can reach 3800 nodes

Figure 1 shows a full SWH (63,1) mesh netwok with 64 nodes.
Figure 2 shows a SWH netwok with 10K nodes and 4 links by node.

![swh][1st_img]

**Figure 1 -** Full SWH mesh network with 64 nodes and 63 links by node.

![swh][2nd_img]

**Figure 2 -** SWH network with 10 000 nodes.






For more informations about the stack, please contact: Samer DAMAJ, sdamaj@gmail.com, http://www.damaj.fr

Reference: https://ieeexplore.ieee.org/document/5291366

Copyright ©, 2022-2023

[1st_img]: img/swh_64_63_mesh.png?raw=true
[2nd_img]: img/swh_10000_4.png?raw=true
