# LabReport02-IDDFS.
 IDDFS Maze Solver:
This project implements the Iterative Deepening Depth-First Search (IDDFS) algorithm to find a path from a start position to a target position in a maze. The algorithm combines the depth-first search approach with iterative deepening, ensuring an optimal path is found within a given depth limit.

 Features:
✔️ Implements IDDFS for maze navigation.
✔️ Searches iteratively up to a defined depth.
✔️ Prints the traversal path if a solution is found.
✔️ Uses backtracking to explore paths efficiently.

 Objectives:
Understand and implement IDDFS for pathfinding.

Analyze efficiency in finding paths in a constrained environment.

Compare IDDFS with other search algorithms in terms of traversal order and memory usage.

Analysis & Discussion:
IDDFS efficiently finds paths by incrementally increasing depth, avoiding large memory consumption.

Unlike BFS, which stores all nodes at each level, IDDFS only keeps track of the current depth, making it more memory-efficient.

However, redundant computations occur since nodes are re-explored at each depth increment.

The algorithm is best suited for problems where the depth of the solution is unknown but expected to be shallow.
