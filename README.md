
# Maze Solver

A graphical Java application that demonstrates maze solving using both **Depth-First Search (DFS)** and **Breadth-First Search (BFS)** algorithms. The application allows users to visualize the pathfinding process, generate random mazes, and compare the performance of DFS and BFS in solving the maze.

## Features

- **DFS & BFS Solvers:** Solve the maze using either DFS (stack-based) or BFS (queue-based) algorithms.
- **Random Maze Generation:** Generate random mazes with obstacles and free paths.
- **Visual Representation:** The maze and solution are displayed graphically using color-coded squares:
  - **Yellow**: Start position
  - **Red**: Goal position
  - **Dark Gray**: Wall/Block
  - **Green**: Explored path
  - **White**: Free path
- **Performance Measurement:** Time taken to solve the maze using DFS or BFS is displayed in milliseconds.

## Prerequisites

- Java JDK (version 8 or later)
- Maven (if using Maven for dependency management)

## Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/maze-solver.git
cd maze-solver
```

### 2. Compile and Run

You can run the project directly from your IDE (e.g., Eclipse, IntelliJ IDEA) or via the command line.

#### Via IDE:
- Import the project into your preferred IDE.
- Run the `Maze` class as a Java application.

#### Via Command Line:

1. Compile the project:
   ```bash
   javac proj/Maze.java
   ```

2. Run the compiled program:
   ```bash
   java proj.Maze
   ```

## How to Use the Application

1. Launch the application.
2. **Generate Random Maze:** Click on "Generate Random Maze" to generate a random maze.
3. **Solve Using DFS:** Click "Solve DFS" to solve the maze using Depth-First Search. The solution path will be marked in green, and the time taken to solve will be displayed.
4. **Solve Using BFS:** Click "Solve BFS" to solve the maze using Breadth-First Search. The solution path will be marked in green, and the time taken will be displayed.
5. **Clear the Maze:** Click "Clear" to reset the maze to its initial state.
6. **Exit:** Click "Exit" to close the application.

## Code Overview

- `Maze`: The main class that sets up the JFrame and handles user interaction, maze generation, and solving logic.
- `solveStack()`: Solves the maze using DFS (Depth-First Search) with a stack.
- `solveQueue()`: Solves the maze using BFS (Breadth-First Search) with a queue.
- `GenerateArray()`: Generates a random maze of size 10x10 with random obstacles.
- **GUI Elements:**
  - Buttons to control maze generation, solving, clearing, and exiting.
  - Text fields to display elapsed time for each algorithm.
  
## Screenshots

### Maze GUI:
- Initial state
- Solved maze using DFS
- Solved maze using BFS


![Maze Solver](path-to-screenshot.png)

## Dependencies

This project does not use any external libraries and relies on core Java (`javax.swing`, `java.awt`) for GUI rendering.

SCREENSHOT


![Screenshot 2023-11-08 092201](https://github.com/user-attachments/assets/2bbf2a41-19e4-4584-a009-67158ecd9781)



