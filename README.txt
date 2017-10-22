Project Description
Background
o A Traveling Salesperson Problem (TSP) is an NP-complete problem. A salesman is
given a list of cities and a cost to travel between each pair of cities (or a list of city
locations). The salesman must select a starting city and visit each city exactly one
time and return to the starting city. His problem is to find the route (also known as a
Hamiltonian Cycle) that will have the lowest cost. (See http://www.tsp.gatech.edu for
more info)

• Problem
o You will be expected to implement a GA for a TSP dataset with up to 100 cities
o Data for each problem will be supplied

Solved by using a modified version of the splitting function created in project 3 to
generate a set of already fit parents, or by using randomly generated parents. The 
parents are fed into a Partially-mapped crossover (PMX) genertic algorithm to
create the next generation. Once the most fit child is returned x amount of times
in a row from the GA, the algorithm will stop being called and display the results.
AI Reports Link: https://drive.google.com/drive/folders/0By--ZxTFsr-mZDR5dUt6bElHajg?usp=sharing 