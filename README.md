#Introduction
        The A* algorithm is a search algorithm that efficiently finds the shortest path between a starting node and a goal node in a graph. It combines the strengths of Dijkstra's algorithm and Greedy best-first search. This algorithm uses a heuristic function to estimate the cost from the current node to the goal, helping it prioritize exploration of promising paths. By evaluating a node's actual cost from the start (g-score) and the estimated cost to the goal (h-score), A* calculates a total cost (f-score) and explores nodes with the lowest f-score first. This approach effectively balances exploration and exploitation, making it suitable for various pathfinding problems.
# Components
      There are 3 components in this program namely Node, AStar and AStarDemo.
      
