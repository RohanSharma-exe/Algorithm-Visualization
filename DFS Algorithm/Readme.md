## DFS Path Finding Algorithm
![Gemini_Generated_Image_1r5gl31r5gl31r5g](https://github.com/RohanSharma-exe/Algorithm-Visualization/assets/68742910/02bcb4de-38f4-4c49-8078-fcbbc962b46d)


This repository contains the code for a Depth-First Search (DFS) path finding algorithm visualized using Pygame. The DFS algorithm is a traversal technique for searching tree or graph data structures. The algorithm starts at the root node (the starting point in our case) and explores as far as possible along each branch before backtracking and exploring other branches.

**Features**

* Visualizes the DFS algorithm in real-time.
* Allows users to set the starting and ending points for the pathfinding.
* Enables users to create barriers on the grid.
* Option to clear the grid and reset the simulation.

**How to Use**

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/dfs-path-finding-algorithm.git
   ```

2. Install the required libraries:

   ```bash
   pip install pygame
   ```

3. Run the script:

   ```bash
   python main.py
   ```

**Explanation of the Code**

The code is well-structured and uses clear variable names, making it easy to understand. Here's a brief breakdown of the code:

* **Classes:**
   * `Spot`: This class represents a single cell on the grid. It has attributes like `row`, `col`, `color`, and methods to draw itself, update its neighbors, and change its color state.
* **Functions:**
   * `h`: This function calculates the heuristic cost, which is the estimated distance between a current node and the end node.
   * `make_grid`: This function creates a 2D grid of `Spot` objects.
   * `draw_grid`: This function draws the grid lines on the Pygame window.
   * `draw`: This function draws all the `Spot` objects on the Pygame window and updates the display.
   * `get_clicked_pos`: This function gets the row and column index of a cell clicked by the user.
   * `reconstruct_path`: This function backtracks from the end node to the starting node to find the DFS path.
   * `algorithm`: This function implements the DFS algorithm. It iterates through the neighbors of the current node, recursively exploring each branch until it finds the end node.
   * `main`: This function is the entry point of the program. It initializes the Pygame window, grid, and event handling loop.

**Customization**

You can easily customize the code by:

* Changing the size of the grid by modifying the `ROWS` variable in the `main` function.
* Implementing different pathfinding algorithms like Breadth-First Search (BFS) or A*.

**Feel free to play around with the code and explore the world of pathfinding algorithms!**
