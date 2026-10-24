# optimization-algorithms

> **Status:** early learning exercises in Java, kept for reference. Not production code.

Small, self-contained implementations of classic algorithms, run from `App`:

| Algorithm | File |
|---|---|
| Fibonacci (recursive) | `Fibonacci.java` |
| Knapsack (simple selection in item order, not an optimal solver) | `Knapsack.java` |
| Dijkstra shortest path | `Dijkstra.java` |
| Bellman-Ford shortest path | `BellmanFord.java` |
| A* search | `AStar.java` |
| Travelling salesman (nearest-neighbour heuristic) | `TravellingSalesmanProblem.java` |

Build and run: `mvn compile exec:java -Dexec.mainClass=com.piglin.optimization.App` (the demo asks for input on stdin).

Placeholder files for genetic algorithms, hill climbing, particle swarm, simulated annealing and ant colony were empty and have been removed.
