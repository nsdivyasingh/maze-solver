# Maze Solver AI - A* Pathfinding  

## Overview
Maze Solver AI is a pathfinding visualization tool that implements the A* algorithm to find the shortest path in a maze. The program provides a visual interface where you can interact with the grid by placing barriers, setting the start and end points, and watching the algorithm work in real-time.

The project helps visualize how the A* algorithm works in solving mazes, providing an easy-to-understand graphical representation.

## Features
- **Pathfinding Visualization:** Visualize the A* algorithm in action as it solves mazes.
- **Interactive Grid:** Click and drag to place barriers, and set start and end points on the grid.
- **Real-time Algorithm:** Watch the algorithm work step by step in real-time.
- **Reset Functionality:** Reset the grid to create a new maze without restarting the application.
- **Exit Option:** Close the application when done.

## Pre-requisites
To run the Maze Solver AI, you need the following:
- Python 3.x
- Pygame library (for GUI and graphics)

1. To install Pygame:
  ```bash
  pip install pygame
  ```

## Installation
1. Clone this repository:
```bash
git clone https://github.com/your-username/maze-solver.git
```

## Usage
1. Run the program:
```bash
python maze_solver.py
```

2. Set Start Point: Click on any cell in the grid to set the **starting point**, which will be represented by **orange**.

3. Set End Point: Click on another cell to set the **ending point**, which will be represented by **purple**.

4. Place Barriers: Click and drag to place **barriers**, which will be represented by **black**. The barriers block the path.

5. Run the Algorithm: Press the **Spacebar** to start the A* algorithm and watch it find the shortest path.

6. Reset the Grid: Press the **Reset** button to **clear the grid** and start over.

Quit the Application: Press the **Quit** button to **exit the program**.

## Color Legend
- Orange: Start point
- Purple: End point
- Black: Barriers (impassable)
- Yellow: Final path (shortest path)
- Light Blue: Open nodes (nodes currently being considered)
- Red: Closed nodes (nodes already evaluated)

## Instructions
1. Place the start and end points by clicking on the grid.
2. Use the mouse to drag and place barriers that will block the path.
3. Once you're ready, hit the **Spacebar** to run the algorithm and find the shortest path.
4. The grid can be **reset** at any time using the Reset button.
5. To exit the program, click the **Quit** button.





