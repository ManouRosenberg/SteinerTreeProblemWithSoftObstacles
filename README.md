# SteinerTreeProblemWithSoftObstacles
These files contain problem instances for the Euclidean Steiner tree problem with polygonal soft and solid obstacles and results achieved by a genetic algorithm approach.
The problem instances were submitted to GECCO '21 as supplementary material. A description and analysis of the algorithm can be found in the work accepted for GECCO '21:   

Rosenberg et al. (2021) "A Genetic Algorithm Approach for the Euclidean Steiner TreeProblem with Soft Obstacles", ACM,*Genetic and Evolutionary Computation Conference,  2021*, 
https://doi.org/10.1145/3449639.3459397  
Please use the link above for citation when using the problem instances.


The two folders contain test cases for the Euclidean Steiner tree problem with soft and solid obstacles or a mix thereof.  Two files named 
obstaclei.csv   and  terminalsi.csv,
where i is the problem instance number,  belong together to build one test instance.
The files are organised as follows:

- In the obstacle file  each obstacle is separated by an empty line. For each obstacle the first number contains the obstacle's crossing weight followed by the x- and y-coordinated of the polygon's corner points in the order the edges are connected. The last corner point is supposed to be connect back to the first one. In case of a solid obstacle the crossing weight says "max".  

  Examples are:
  
 - for two solid obstacles:
 
  max\
  3.4225,	3.76125\
  5.5625,	4.40125\
  6.2825,	6.16125\
  7.4225,	4.82125\
  7.7225,	3.02125\
  5.5,	2.8
  	
    
  max	\
  1.25,	6.2\
  2.2,	4.8\
  0.5,	5


- and for two soft obstacles:

1.1  \	
0.098,	0.9\
0.21,	0.902\
0.204,	0.488\
0.094,	0.488

1.1	\
0.602,	0.81\
0.578,	0.6\
0.766,	0.466\
0.912,	0.704\
0.72,	0.622\
0.718,	0.834



- The  terminal file contains the x- and y-coordinates of the terminals. The first line can be ignored. An example is given below

  Xcoord,	Ycoord\
  0.644,	0.242\
  0.24,	0.386\
  0.048,	0.39\
  0.152,	0.15\
  0.654,	0.698\
  0.526,	0.87\
  0.156,	0.85\
  0.43,	0.59\
  0.91,	0.72\
  0.88,	0.634\
  0.728,	0.406\



Note: 
Some of the problem instances in the "Soft" folder contain the points for the Sierpinski triangle instance. This problem instance was adapted from: 

Garrote et al. (2019) "Weighted Euclidean Steiner Trees for Disaster-Aware Network Design", IEEE,*15th International Conference on the Design of Reliable Communication Networks, DRCN 2019* 



Paper License:
Permission to make digital or hard copies of all or part of this work for personal or classroom use is granted without fee provided that copies are not made or distributed for profit or commercial advantage and that copies bear this notice and the full citation on the first page. Copyrights for components of this work owned by others than the author(s) must be honored. Abstracting with credit is permitted. To copy otherwise, or republish, to post on servers or to redistribute to lists, requires prior specific permission and/or a fee. Request permissions from Permissions@acm.org.

GECCO '21, July 10–14, 2021, Lille, France 
© 2021 Copyright is held by the owner/author(s). Publication rights licensed to ACM.
ACM ISBN 978-1-4503-8350-9/21/07…$15.00 
https://doi.org/10.1145/3449639.3459397

