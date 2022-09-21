# RandomPolygons-GA-CSP
Generate Random Simple Polygons using Genetic Algorithm and CSP.

Generate random simple polygons, which is a polygon having no intersecting edges, from a
given set of points called S= {p1, p2 ,..., pn}, where and the points lie in a two dimensional plane. The
algorithm makes convex polygons.
The steps required to get to the solution are:
1. Design a chromosome for the problem [Must be binary Encoded]
2. Define Genetic operators for the problem. They can be different than standard Mutation and
crossover.
3. Define a Fitness function.
4. Roulette Wheel selection.
5. RUN GA using above chromosome, genetic operator, fitness function and selection function.

The solution works on n, where n is the number of points between 3-15.
