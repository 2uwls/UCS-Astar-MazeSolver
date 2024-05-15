# README.md  
## Quick Start Guide  
### Running the Maze Solver  
To run the maze solver, use the following command:

``
python -m examples.quick_start
``

This command initiates the maze solving process using two distinct search algorithms: Uniform Cost Search and A* Search.

### Maze Generation
The program begins by generating a 20x20 maze using the `MazeManager`.  
To ensure a fair comparison, the same maze is duplicated and used for both the Uniform Cost Search and A* Search algorithms.

### Solving the Maze
The maze is solved using two different methods specified in `maze_manager.py`:  
- Uniform Cost Search (ucs_manager)
- A* Search (astar_manager)

### Visualization
After solving the maze, results can be visualized using the `show_solution` method for both search algorithms.  
This visual representation helps in understanding the path found by each algorithm and the differences in their approaches.
### Execution Flow
- `MazeManager`: Generates and manages mazes for solving.
- `Solving the Maze`: Passes the maze to the solvers with the specified method.
  - Uniform Cost Search: Invoked via `uniform_cost_search` method in the `UniformCostSearch` class.
  - A Search*: Invoked via `a_star_search` method in the `AStarSearch` class.
- Visualization: Displays the solution paths for each algorithm.

### Performance and Execution Time Comparison of Two Algorithms
<img width="537" alt="image" src="https://github.com/2uwls/UCS-Astar-MazeSolver/assets/101469780/74f9dd05-80fe-46b3-ad03-16ffc8047c26">
