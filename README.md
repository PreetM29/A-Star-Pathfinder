# 🧭 A* Pathfinding Visualizer

A Python project built with **Pygame** that visually demonstrates how the **A\*** (A-star) pathfinding algorithm works in real-time on a grid.

## 🚀 Features

- Interactive grid-based environment
- Click to place:
  - **Start node** (orange)
  - **End node** (turquoise)
  - **Barriers/walls** (black)
- Visualizes the algorithm's open (green), closed (red), and final path (purple) nodes
- Reset and clear the grid easily

## 🎮 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/PreetM29/A-Star-Pathfinder.git
```
### 2. Navigate to the Folder
```bash
cd A-Star-Pathfinder
```
### 3. Install Dependencies
```bash
pip install pygame
```

### 4. Run the Program
```bash
python astar.py
```
### 🕹️ Controls

| Action           | Input              |
| ---------------- | ------------------ |
| Set Start Point  | Left Click         |
| Set End Point    | Left Click         |
| Add Barrier      | Left Click         |
| Remove Node      | Right Click        |
| Start Algorithm  | `Spacebar`         |
| Clear Grid       | `C`                |
| Quit Application | Close Window / `X` |


### 📘 How It Works
This tool uses the A* pathfinding algorithm. A* is a widely used algorithm in pathfinding and graph traversal.

## Heuristic Function
This implementation uses the Manhattan distance as the heuristic:

```
abs(x1 - x2) + abs(y1 - y2)

```
## A* Equation
```
f(n) = g(n) + h(n)
```

- g(n): Distance from the start node to the current node

- h(n): Estimated distance from the current node to the end node

The algorithm prioritizes nodes with the lowest f(n) value.

### Technologies Used
- Python 🐍

-  Pygame 🎮

### 📄 License
This project is licensed under the MIT License. Feel free to use and modify it for educational purposes!

