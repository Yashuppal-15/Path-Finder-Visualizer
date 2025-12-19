# Pathfinding Visualizer

Welcome to the Pathfinding Visualizer!  
This project was built to visually demonstrate how different pathfinding algorithms work in real time. The application provides an interactive grid where users can explore how algorithms traverse nodes and determine paths between a start and an end point.

The project focuses on learning, experimentation, and visualization of algorithms rather than backend or server-side development.

---

## Purpose of the Project

The main objectives of this project are:

- To visualize pathfinding algorithms step by step
- To understand how different algorithms explore nodes
- To compare algorithm performance and behavior
- To strengthen JavaScript logic and frontend development skills

---

## Technologies Used

- **HTML5** – application structure
- **CSS3** – layout, grid styling, and animations
- **JavaScript** – algorithm logic and visualization

---

## Meet the Algorithms

This application supports the following pathfinding algorithms:

- **Dijkstra's Algorithm (weighted)**  
  The foundation of pathfinding algorithms; guarantees the shortest path.

- **A* Search (weighted)**  
  Uses heuristics to find the shortest path faster than Dijkstra’s Algorithm.

- **Greedy Best-First Search (weighted)**  
  A heuristic-heavy algorithm that does not guarantee the shortest path.

- **Swarm Algorithm (weighted)**  
  A hybrid of Dijkstra’s Algorithm and A* Search; does not guarantee the shortest path.

- **Convergent Swarm Algorithm (weighted)**  
  A faster, more heuristic-driven version of Swarm.

- **Bidirectional Swarm Algorithm (weighted)**  
  Runs Swarm from both the start and end nodes.

- **Breadth-First Search (unweighted)**  
  Guarantees the shortest path.

- **Depth-First Search (unweighted)**  
  Does not guarantee the shortest path and is inefficient for pathfinding.

In addition to pathfinding algorithms, the project also includes a  
**Recursive Division Maze Generation algorithm**.

---

## More About the Swarm Algorithm

The Swarm Algorithm is a hybrid algorithm developed to combine characteristics of Dijkstra’s Algorithm and A* Search. While it converges toward the target node like A*, it also explores surrounding nodes near the start like Dijkstra’s Algorithm.

The algorithm continuously balances:
- Distance from the start node
- Estimated distance to the target node (heuristics)

This balance results in the distinctive triangular exploration pattern produced by the Swarm Algorithm. One potential application of this algorithm could be in gaming environments, where an entity must prioritize a target while remaining aware of surrounding threats.

---

## Project Structure

Path-finder-visualizer-main/
│
├── index.html # Main entry point
├── css/ # Stylesheets
├── js/ # Algorithms and visualization logic
├── server.js # Optional helper file (not required)
└── README.md

---

## How to Run the Project

This is a **frontend-only application**.  
It does **not** require Node.js, npm, or Express.

### Option 1: Open Directly (Recommended)

1. Download or clone the repository
2. Navigate to the project folder
3. Open `index.html` in any modern web browser

---

### Option 2: Run on Localhost (Optional)

If you prefer running it on localhost:

python -m http.server
Then open your browser and visit: http://localhost:8000

## Important Notes

- npm and Node.js are not required
- `server.js` is optional and not needed to run the project
- The entire application runs in the browser

---

## Future Improvements

Possible enhancements include:

- Adding more pathfinding algorithms
- Improving visualization speed controls
- Enhancing UI responsiveness
- Improving performance on larger grids
- Adding accessibility improvements

---

## Contact

**Name:** Yash Uppal  
**Email:** 2k22.cse.2212320@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/yashuppal15  

Feel free to reach out for collaboration, feedback, or opportunities.

---

## License

This project is open-source and available under the MIT License.

---

