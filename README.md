# GA
GA-Find Shortest Path
Write a program by using genetic algorithm (GA) to find the shortest path to visit all the cities. Your program
has to include all GA operations (selection, cross over, mutation). Choose mutation and crossover rate that
are appropriate for the problem.
Input file: a280
AME : a280
COMMENT : drilling problem (Ludwig)
TYPE : TSP
DIMENSION: 280
EDGE_WEIGHT_TYPE : EUC_2D
NODE_COORD_SECTION
1 288 149
2 288 129
3 270 133
Distance: d(p1, ps) = √(x2 − x1) 2 + (y2 − y1) 2
Output file: sol_a280_SID
Output format
NAME : ./TSPLIB/a280.tsp.opt.tour
TYPE : TOUR
DIMENSION : 280
TOUR_SECTION
1
2
242
243
...
279
3
280
-1
