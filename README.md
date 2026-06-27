# BFS & DFS Pathfinding Game

An interactive visualization project that demonstrates Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms for finding paths in a graph.

The project provides a visual representation of how search algorithms explore nodes, use their data structures, and find a path from a start node to a goal node.

---

## Project Overview
<img width="1366" height="617" alt="image" src="https://github.com/user-attachments/assets/952389be-9f8c-471c-86b8-4b409d7b2def" />

This project implements graph traversal algorithms in JavaScript and visualizes their behavior using an interactive graph.

Users can select an algorithm, choose start and goal nodes, and observe how the algorithm explores the graph step by step until a path is found.

---

## Features

- Interactive graph visualization
- BFS and DFS algorithm selection
- Step-by-step search execution
- Automatic search execution
- Adjustable execution speed
- Random graph generation
- Visualization of:
  - Start node
  - Goal node
  - Visited nodes
  - Queue or Stack contents
  - Final solution path

The application also displays search statistics:

- Number of visited nodes
- Number of steps performed
- Path length
- Maximum queue/stack size

---

## Algorithms

### Breadth-First Search (BFS)

Breadth-First Search explores the graph level by level using a queue data structure.

Characteristics:

- Uses a First-In-First-Out (FIFO) queue
- Explores all neighboring nodes before moving deeper
- Finds the shortest path in an unweighted graph
- Requires more memory compared to DFS

---

### Depth-First Search (DFS)

Depth-First Search explores the graph by going as deep as possible before backtracking.

Characteristics:

- Uses a Last-In-First-Out (LIFO) stack
- Explores one branch before checking other branches
- Similar to Prolog backtracking search
- Does not always find the shortest path

---

## BFS vs DFS Comparison

| Feature | BFS | DFS |
|---|---|---|
| Data Structure | Queue | Stack |
| Strategy | Level-by-level exploration | Deep exploration |
| Shortest Path | Guaranteed | Not guaranteed |
| Memory Usage | Higher | Lower |
| Searching Style | Explores neighbors first | Explores one branch first |

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Open the project folder.

3. Open the HTML file in a web browser.

No installation or additional dependencies are required.

---

## How to Use

1. Select the desired algorithm:
   - BFS
   - DFS

2. Click on a node to set it as the start node.

3. Click on another node to set it as the goal node.

4. Choose an execution method:
   - Run: Executes the algorithm automatically.
   - Step: Executes the algorithm one step at a time.

5. Observe the exploration process and the final path.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Canvas API

---

## Concepts Demonstrated

This project demonstrates:

- Graph traversal algorithms
- Graph representation using adjacency lists
- Queue and stack data structures
- Path reconstruction
- Search visualization
- Algorithm comparison

---

## Educational Purpose

This project was developed to provide a visual understanding of graph search algorithms and their applications in Artificial Intelligence and problem-solving techniques.

---

## Author

Your Name

---

## License

This project is open-source and available for educational purposes.
