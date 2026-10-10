# Intelligent Systems – Task 1: Warehouse Delivery Robot

**Team:** Nosiba Mohammed (2403246862), Malak Ahmed (2403248974)

Path planning for a robot on a 2D grid using three search algorithms:

- **BFS** (uninformed): fewest steps, ignores cost
- **UCS** (uninformed): cheapest path
- **A\*** (informed, Manhattan distance heuristic): cheapest path with fewer expanded nodes

## Files
- `task1_intelligent.ipynb`: the full code and outputs

## How to run
1. Open `task1_intelligent.ipynb` in Google Colab or Jupyter.
2. Run all cells from top to bottom (Runtime → Run all).

## How to change the map
In the "Maps" cell, change these two variables:
- `GRID = MAP_B` (choose `MAP_A`, `MAP_B`, `MAP_C`, or paste your own list of strings)
- `RUN_ALL = False` (if `True`, `GRID` is ignored and all 3 maps are run)

Your own map must contain exactly one `S` and one `G`, using `.` (cost 1), `~` (cost 3), and `#` (wall).

## Output
For each algorithm: path, path length, total cost, nodes expanded, max frontier size, run time, and the path drawn on the map with `*`.
