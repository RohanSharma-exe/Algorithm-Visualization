# Breadth-First Search Algorithm Visualization

![Gemini_Generated_Image_5qloo35qloo35qlo](https://github.com/RohanSharma-exe/Algorithm-Visualization/assets/68742910/44dcb9f3-2cfb-45fa-82dc-e6858704d0dd)


This interactive Python program demonstrates the Breadth-First Search (BFS) algorithm for finding the shortest path between two points in a grid-based world.

**Key Features:**

- **Interactive Grid:** Click and drag to create barriers (black squares), set the starting point (orange square), and the ending point (turquoise square).
- **Visual Exploration:** Observe the BFS algorithm's exploration in real-time as it systematically visits all neighboring nodes level-by-level, with visited nodes colored green and the final path highlighted in purple.
- **Clear Code:** Well-structured and commented code for easy understanding and customization.
- **Adjustable Grid Size:** Modify the `ROWS` variable in the `main` function to change the grid dimensions.

**How to Run:**

1. **Install Required Libraries:**
   ```bash
   pip install pygame
   ```
2. **Save the Code:** Create a Python file (e.g., `bfs.py`) and paste the code provided.
3. **Run the Script:** Execute the script using Python:
   ```bash
   python bfs.py
   ```

**Explanation:**

The code implements the BFS algorithm, a graph traversal technique that explores all nodes at a given level before moving on to the next level. Here's a breakdown of the core concepts:

- **Grid Representation:** Similar to A*, the world is modeled as a 2D grid of squares (nodes).
- **Neighbors:** Each node has a set of neighboring nodes it can connect to.
- **Queue:** BFS utilizes a queue (FIFO - First-In-First-Out) data structure. Nodes are added to the back of the queue and explored in the order they were added.
- **Exploration:** The algorithm starts at the starting point, adds its neighbors to the queue, marks it as visited, and then removes the first node from the queue. This process continues until the end point is found or the queue becomes empty.

**Customization:**

- Experiment with different grid sizes by modifying the `ROWS` variable.

**Learning Resources:**

- Breadth-First Search Algorithm: [https://en.wikipedia.org/wiki/Breadth-first_search](https://en.wikipedia.org/wiki/Breadth-first_search)
- Pygame Tutorial: [https://www.pygame.org/wiki/tutorials](https://www.pygame.org/wiki/tutorials)

I trust this revised README file accurately reflects the BFS algorithm and provides a clear understanding of its functionality. Feel free to reach out if you have any further questions!
