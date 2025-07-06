# Dynamic-VRP
DYNAMIC VEHICLE ROUTING PROBLEM:

INTRODUCTION:
The Vehicle Routing Problem (VRP) traditionally involves determining the most efficient paths for vehicles based on static data like maps, road networks, and schedules. In contrast, the Dynamic Capacitated VRP (DCVRP) introduces active customer requests that appear dynamically, adding complexity to planning routes and allocating resources.

PROBLEM STATEMENT:
The goal is to optimize vehicle allocation and route planning while minimizing travel time, distance traveled, and the number of vehicles used. Unlike static VRP, DCVRP deals with unpredictability in customer demand and service timing, requiring a solution that adapts to dynamic conditions without relying on traffic data.

DVRP:
The DVRP involves planning efficient vehicle routes where customer requests or delivery conditions change in real time. Unlike traditional VRP which works with fixed data, DVRP adapts on the fly—vehicles must reroute based on new pickups, cancellations, or updated constraints like time windows and capacity.

Core Features:
Dynamic Requests: Customers can make orders at any time during operation.

Real-Time Updates: Routes are recalculated based on changing conditions.

Goal: Minimize total travel distance/time while satisfying all delivery constraints.

GENETIC ALGORITHM:
A Genetic Algorithm (GA) is employed to solve the DCVRP. It evolves a population of candidate solutions to find optimal routes under dynamic constraints.

POPULATION: A diverse set of route assignments for vehicles, improving solution variety.

CHROMOSOME: Each represents a sequence of customer visits, respecting constraints like vehicle capacity and delivery deadlines.

FITNESS FUNCTION: Evaluates solutions based on metrics such as total distance and route efficiency.

SELECTION: Chooses the best-performing solutions to generate the next generation.

CROSSOVER: Mixes traits from two parent solutions to form offspring with improved routing potential.

MUTATION: Introduces slight changes to explore new routing possibilities and avoid premature convergence.
