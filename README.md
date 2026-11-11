# Truck Pallet Packing — Optimization Algorithms

Academic C++ project exploring the **0/1 Knapsack Problem** in a logistics setting: selecting pallets for a delivery truck to maximize total profit without exceeding its weight capacity.

## Problem

Each pallet has a weight and a profit, and each truck has a maximum load capacity. The optimization goal is to select a subset of pallets that maximizes profit while satisfying the capacity constraint.

This problem can be approached with different trade-offs between optimality, runtime and memory consumption.

## Documented algorithmic approaches

The original project description covers the following strategies:

| Approach | Main idea | Trade-off |
| --- | --- | --- |
| Exhaustive search | Explore subsets of pallets | Exact but exponential in the number of pallets |
| Greedy heuristic | Prioritize pallets by profit-to-weight ratio | Fast, but not guaranteed to be optimal |
| Dynamic programming | Reuse subproblem solutions | Exact for integer capacities, with capacity-dependent complexity |
| Branch-and-bound / integer optimization | Use bounds to prune candidate solutions | Can reduce search effort, but runtime depends on the instance |
| Genetic algorithm | Explore candidate solutions with evolutionary operators | Experimental heuristic; no optimality guarantee |

## Input and output described by the project

- CSV input datasets with truck capacities and pallet weights/profits.
- Solver selection for algorithm comparison.
- Result reporting for the selected pallets and profit/capacity trade-off.

## Repository status

**This public GitHub repository currently contains only this README.** No C++ source code, datasets, build configuration, benchmarks or executable demonstrations are included here. The algorithms above describe the academic project scope; their implementation and performance **cannot be independently verified from this repository**.

For that reason, this repository should not be treated as a reproducible software demonstration until the source and input examples are added.

## Authors

- Francisco Rafael dos Santos Borralho
- Gonçalo Tavares de Pinho Mendes Calvo

**Topic:** C++ · Algorithms · Operations Research · Dynamic Programming · Combinatorial Optimization
