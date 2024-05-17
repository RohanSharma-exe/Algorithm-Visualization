# A* Path Finding Algorithm Visualization

![Gemini_Generated_Image_sx6322sx6322sx63](https://github.com/RohanSharma-exe/Algorithm-Visualization/assets/68742910/b7d7ae4e-abbc-4bb1-875c-8a7571314239)


This repository contains Python code for visualizing the A* Path Finding Algorithm on a grid.  You can interact with the grid to set the starting and ending points, as well as create barriers.

**Features:**

* Interactive grid where you can:
    * Set the starting point (Orange Square)
    * Set the ending point (Turquoise Square)
    * Create barriers (Black Squares)
    * Reset the grid (Clear Button - 'C' key)
* Find the shortest path between the starting and ending points (Spacebar)

**How to Run:**

1. Make sure you have Python 3 and Pygame installed. You can install Pygame using `pip install pygame`.
2. Clone this repository or download the code.
3. Open a terminal or command prompt and navigate to the directory containing the code.
4. Run the script using `python main.py`.

**Controls:**

| Action | Shortcut |
|---|---|
| Set Starting Point | Left Mouse Click |
| Set Ending Point | Left Mouse Click |
| Create Barriers | Left Mouse Click (except on Start/End) |
| Reset Cell | Right Mouse Click |
| Find Shortest Path | Spacebar |
| Reset Grid | 'C' Key |

**Code Structure:**

The code is divided into several functions, each responsible for a specific task:

* `Spot`: Represents a single cell on the grid.
* `make_grid`: Creates a grid of `Spot` objects.
* `draw_grid`: Draws the grid lines on the screen.
* `draw`: Draws all the elements on the screen (grid, spots, path).
* `get_clicked_pos`: Gets the row and column of a clicked position on the grid.
* `reconstruct_path`: Traces the shortest path found by the algorithm.
* `algorithm`: Implements the A* Path Finding Algorithm.
* `main`: Initializes Pygame, creates the grid, and handles user interactions.

**Further Exploration:**

* Try changing the grid size (currently set to 50x50) in the `main` function.
* Modify the heuristic function (`h`) to explore different pathfinding strategies. 
* Add functionalities like diagonal movement or different types of barriers.

I hope this enhanced README with visuals makes the code more inviting and informative!
