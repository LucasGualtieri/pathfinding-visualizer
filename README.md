# Pathfinding Visualizer

A C++ application for visualizing pathfinding algorithms, built with **SFML** for grid rendering and **ImGui** for an interactive control panel. This tool allows users to explore how popular pathfinding algorithms like A*, Dijkstra, and BFS/DFS operate on a grid.

## Features

- Interactive grid to place start/end points and obstacles.
- Visualization of pathfinding algorithms step-by-step.
- Adjustable settings for grid size, animation speed, and more.
- Algorithms implemented:
  - A* (A-star)
  - Dijkstra
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)

## Screenshots
*...*

## Getting Started

### Prerequisites
- A C++20 compatible compiler.
- CMake 3.16 or higher.
- [SFML](https://www.sfml-dev.org/) (Simple and Fast Multimedia Library).
- [ImGui](https://github.com/ocornut/imgui) (Dear ImGui for graphical user interfaces).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/LucasGualtieri/pathfinding-visualizer.git
   cd pathfinding-visualizer
   ```

2. Build the project:
   ```bash
   mkdir build && cd build
   cmake ..
   cmake --build .
   ```

3. Run the application:
   ```bash
   ./pathfinding-visualizer
   ```

### Usage
1. Launch the application.
2. Use the grid to place the **start** and **end** points.
3. Draw obstacles on the grid.
4. Choose an algorithm from the control panel (powered by ImGui).
5. Click "Start" to visualize the algorithm in action.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## ✅ Todo List
- [ ] Adjustable settings for grid size, animation speed, and more.
- [ ] Interactive grid to place start/end points and obstacles.
- [ ] Visualization of pathfinding algorithms step-by-step.
- [ ] Algorithms implemented:
  - [ ] A* (A-star)
  - [ ] Dijkstra
  - [ ] Breadth-First Search (BFS)
  - [ ] Depth-First Search (DFS)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [SFML](https://www.sfml-dev.org/)
- [ImGui](https://github.com/ocornut/imgui)
- [CMake](https://cmake.org/)
