# 🚙 UGV Grid Pathfinding with Static Obstacles

## Project Overview
This project demonstrates path planning for an Unmanned Ground Vehicle (UGV) operating in a battlefield-like grid environment.

The UGV must travel from a start position to a goal while avoiding obstacles that are known in advance.

## Objectives
- Model a battlefield using a grid.
- Generate static obstacles.
- Define UGV start and goal positions.
- Find a feasible/shortest path.
- Compare different obstacle densities.
- Visualize the final UGV route.
- Evaluate pathfinding performance.

## Environment
Each grid cell represents either:
- Free space
- Obstacle

The experiment considers low, medium, and high obstacle densities.

## Technologies
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Priority Queue / Graph Search

## Methodology
1. Create the grid.
2. Generate obstacles.
3. Set the start and goal.
4. Check valid neighboring cells.
5. Search for a route.
6. Reconstruct the path.
7. Calculate performance measures.
8. Visualize the environment and route.

## Measures of Effectiveness
- Path length
- Number of steps
- Search effort
- Execution time
- Goal success/failure

## Expected Observation
As obstacle density increases, available routes generally decrease and pathfinding becomes more difficult. Very dense environments may make the goal unreachable.

## Limitations
The basic experiment assumes that obstacles are static and known before navigation. It does not model unexpected changes during movement.

## Future Scope
The system can be extended with dynamic obstacle detection, D* Lite, repeated A*, sensor simulation, and real-time robotics.

## Conclusion
The project demonstrates how a UGV can navigate a grid environment while avoiding known obstacles and how obstacle density affects navigation performance.

## How to Run
1. Open the notebook in Google Colab.
2. Run the setup/import cells.
3. Generate the grid.
4. Select obstacle density.
5. Define start and goal.
6. Run the pathfinding algorithm.
7. View the route and performance results.
