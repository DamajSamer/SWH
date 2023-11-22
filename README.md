# SWH
Small-World Heuristic - a Full mesh network

## INTRODUCTION
The Small world Heuristic or SWH G(d,k) is a smart algorithm process to generate differents connected graphs.

* What is a graph? Graph or Network diagram show interconnections between a set of entities.
* What is an entity? entity is represented by a Node or vertice, e.g sensor.
* Connections between nodes are represented through links or edges or degree denoted (d).
* The -maximum distance- between two nodes is a Diameter denoted (k).
* What is a distance between two nodes? it is the length of longest shortest path.

## SWH CRITERIAS

According to an algorithm criterias, like a custom diameter calculation and nodes process generator, SWH(d,k) is a full mesh topology.
* small mesh graphs
* medium mesh graphs
* large mesh graphs
  
According to a smart input criteria, SWH(d,k) can change its characteristics and can reach:
* Torus and Hypercube networks
* de Bruijn graph

SWH can reach the Moore bound with specific criterias.

## RESULTS 
With SWH graph, you can customise your graph in term of number of nodes, number of links and diameter.

SWH can reach the same/better characteristics of some largest known graphs and much faster:

https://en.wikipedia.org/wiki/Table_of_the_largest_known_graphs_of_a_given_diameter_and_maximal_degree.

### Some SWH large graphs
* SWH(6,5) can reach 6000 nodes
* SWH(10,5) can reach 13200 nodes
* SWH(11,5) can reach 19520 nodes
* SWH(16,3) can reach 3800 nodes
* SWH (10,10) can reach over 2000 000 nodes
* SWH(15,10) can reach over 10 000 000 nodes

Some excellent results have been made by using an HPC computer.

### Some SWH mesh graphs
* SWH(63,1) reaches 64 nodes 
* SWH(255,2) reaches 256 nodes
* SWH(1023,2) reaches 1024 nodes

## APPLICATIONS

###  SWH for 802.15.4 radio
Figure 1 shows a full SWH (63,1) mesh netwok with 64 nodes for a decentralize mesh 802.15.4 application used a Si44XX Radio chip.

![swh][1st_img]
**Figure 1 -** Full SWH mesh network with 64 nodes and 63 links by node.

###  SWH for a military application
Figure 2 shows a SWH netwok with 10 000 nodes and 4 links by node for a private application.

![swh][2nd_img]
**Figure 2 -** SWH network with 10 000 nodes

### SWH for mesh Wi-Fi (application 1)
Figure 3 shows a small SWH network with 16 nodes for a decentralize mesh 802.11 Wi-Fi application and a custom HWMP stack used a Murata chip.

![swh][3rd_img]
**Figure 3 -** SWH network with 16 nodes

### SWH for mesh Wi-Fi (application 2)
Figure 4 shows a small SWH network with 16 nodes for a decentralize mesh 802.11 Wi-Fi application and a custom HWMP stack used a TI chip.

![swh][4th_img]
**Figure 4 -** SWH network with 16 nodes

###  SWH for 802.15.4 radio

Figure 5 shows a SWH network with 512 nodes for a decentralize mesh 802.15.4 application used a Si44XX Radio chip.

![swh][5th_img]
**Figure 5 -** SWH network with 512 nodes


## References

* https://ieeexplore.ieee.org/document/5291366
* https://ieeexplore.ieee.org/document/5365413

## Contact

For more informations about the stack:

* Samer DAMAJ
* e-mail: sdamaj@gmail.com


Copyright ©, 2022-2023

[1st_img]: img/swh_64_63_mesh.png?raw=true
[2nd_img]: img/swh_10000_4.png?raw=true
[3rd_img]: img/swh_16_2_application1.png?raw=true
[4th_img]: img/swh_16_2_application2.png?raw=true
[5th_img]: img/swh_512.png?raw=true


