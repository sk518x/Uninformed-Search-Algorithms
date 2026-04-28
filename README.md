# Uninformed Search Algorithms (BFS, DFS, IDDFS)

## Project Description

This project implements three uninformed search algorithms to traverse a graph:

* Breadth-First Search (BFS)
* Depth-First Search (DFS)
* Iterative Deepening Depth-First Search (IDDFS)

The algorithms explore the graph starting from the root node without using any heuristic information.

---

## How the Algorithms Work

* **BFS** explores nodes level by level, visiting all neighbors before moving deeper.
* **DFS** explores as far as possible along one branch before backtracking.
* **IDDFS** combines both approaches by performing DFS with increasing depth limits until the goal is reached.

---

## Files Included

1. `uninformed_test.py`
   Defines the graph as an adjacency list and runs all search algorithms

2. `bfs.py`
   Implements the Breadth-First Search algorithm

3. `dfs.py`
   Implements the Depth-First Search algorithm

4. `id_dfs.py`
   Implements the Iterative Deepening DFS algorithm

5. `output.txt`
   Contains the output of BFS, DFS, and IDDFS traversals

6. `cmd_output.png`
   Screenshot showing the program execution

---

## How to Run

```bash
python uninformed_test.py
```

---

## Conclusion

The uninformed search algorithms demonstrate different strategies for exploring a graph. BFS guarantees level-wise exploration, DFS explores depth-first, and IDDFS balances both approaches efficiently.
