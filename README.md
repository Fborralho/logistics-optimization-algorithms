# Truck Pallet Packing Optimization

This project addresses the **0/1 Knapsack problem** applied to logistics: how to load pallets into delivery trucks to maximize profit without exceeding capacity. Different algorithmic approaches were implemented and compared.

## Features
- Import datasets of trucks and pallets from `.csv` files.
- Multiple solvers implemented:
  - **Exhaustive Search** (brute force) – finds the optimal solution by exploring all subsets.
  - **Greedy Algorithm** – fast heuristic based on profit-to-weight ratio.
  - **Dynamic Programming** – efficient solution with optimal substructure.
  - **Integer Linear Programming (ILP)** with Branch-and-Bound – optimal search with pruning.
  - (Optional) **Genetic Algorithm** – experimental solver for evolutionary optimization.

## Tech Stack
- Language: **C++**
- Algorithms: Brute Force, Greedy, Dynamic Programming, ILP, Genetic Algorithms

## Complexity
- Exhaustive: `O(2^n)`  
- Greedy: `O(n log n)`  
- Dynamic Programming: `O(n * W)`  
- ILP with pruning: much faster than exhaustive in practice

##  User Interface
- Load dataset by typing its index (e.g. `05` → `Pallets_05.csv`, `TruckAndPallets_05.csv`).
- Select solver to run and display results.
- View loaded pallets and truck capacity.

## Highlights
- Greedy algorithm designed for **high performance** with large datasets.  
- ILP solver uses greedy as initialization, pruning search space effectively.  
- Genetic Algorithm implemented to experiment with evolutionary techniques.

## Authors
- Francisco Rafael dos Santos Borralho  
- Gonçalo Tavares de Pinho Mendes Calvo
