# Metaheuristic-Optimization-for-Routing-Networks
Engineered Simulated Annealing algorithms with geometric cooling to solve NP-Hard Traveling Salesman Problem (TSP) routing networks across 48 city nodes.

# Metaheuristic Optimization for Routing Networks

**Course:** IE684 - Operations Research Lab  
**Institution:** IIT Bombay  

## Project Overview
This repository explores the computational intractability of the Traveling Salesman Problem (TSP) by transitioning from exact Integer Linear Programming (ILP) formulations to probabilistic metaheuristic approximations. The project engineers a custom Simulated Annealing (SA) engine to optimize complex routing networks.

## Key Implementations
* **Topological Validation:** Developed algorithms to evaluate the extreme points of the TSP polytope, proving strict compliance with Dantzig-Fulkerson-Johnson (DFJ) degree and Sub-tour Elimination Constraints (SECs).
* **Simulated Annealing Engine:** Programmed stochastic state-transition logic utilizing the Boltzmann acceptance probability distribution ($P = e^{-\Delta c / T_k}$) to escape local minima traps.
* **Cooling Schedule Tuning:** Benchmarked geometric cooling schedules ($T_{k+1} = \alpha T_k$) against linear and logarithmic alternatives to optimize the exploration-exploitation tradeoff.
* **Dimensionality Scaling:** Evaluated the algorithm across an 11-node and 48-node spatial network, successfully minimizing total travel distances while analyzing the impact of the "Curse of Dimensionality" on heuristic variance.

## Technologies Used
* **Languages:** Python
* **Libraries:** NumPy, Pandas, Matplotlib, Math
