# Dijkstra's Algorithm Visualization ‍♂️ (Python)

This is a fun and interactive visualization of Dijkstra's algorithm, a popular algorithm for finding the shortest path between two points on a grid. 

**What you can do:**

* Click and drag to create barriers (black squares) on the grid.
* Click to set the starting point (orange square) and the ending point (turquoise square).
* Press spacebar to start the visualization and see the algorithm find the shortest path in real-time!

**How it works:**

The visualization uses Pygame to create a grid and color-code the squares to represent different stages of the algorithm:

* **White:** Unvisited square
* **Green:** Square currently being considered (open set)
* **Red:** Square already evaluated (closed set)
* **Black:** Barrier (cannot be passed through)
* **Orange:** Starting point
* **Turquoise:** Ending point
* **Purple:** Part of the shortest path

**Try it out!**

1. Clone or download this repository.
2. Make sure you have Python and Pygame installed. You can install Pygame using `pip install pygame`.
3. Run the script `Dijkstra.py`.
4. Have fun creating mazes and watching the algorithm find its way through!

**Want to learn more?**

* Check out the code in the `main.py` file for a detailed implementation of Dijkstra's algorithm and the visualization.
* There are many online resources that explain Dijkstra's algorithm in more depth. Here are a couple of good ones:
    * [https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
    * [https://m.youtube.com/watch?v=_lHSawdgXpI](https://m.youtube.com/watch?v=_lHSawdgXpI)

**Bonus!**

This code can be easily extended to include additional features, such as:

* Different maze generation algorithms
* Diagonal movement
* A-star algorithm (another popular pathfinding algorithm)

Feel free to experiment and make this visualization your own!

