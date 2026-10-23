# ⚡ Interactive Graph Algorithm & Pathfinding Suite

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![NetworkX](https://img.shields.io/badge/NetworkX-3.0-green)

An interactive Jupyter Notebook developed for the **Design and Analysis of Algorithms (DAA)** coursework. This suite provides real-time state inspection, step-by-step memory tracking, top-down tree visualization, and algorithm comparisons.

---

## ✨ Features

* **Interactive Controls:** Switch dynamically between algorithms using dropdowns and step sliders.
* **Core Algorithms Included:**
  * **Breadth-First Search (BFS):** Level-by-level exploration tracking Queue state.
  * **Depth-First Search (DFS):** Depth-first branch navigation tracking Stack state.
  * **Dijkstra's Algorithm:** Weighted shortest path selection tracking Priority Queue (Min-Heap) and edge relaxations.
* **Top-Down Waterfall Layout:** Displays graph nodes in a clean, hierarchical tree layout using explicit coordinates.
* **Live Telemetry & Logs:** Displays step-by-step memory changes, active/visited node color-coding, and execution logs.

---

## 📊 Algorithmic Complexity

| Algorithm | Time Complexity | Space Complexity | Primary Data Structure |
| :--- | :--- | :--- | :--- |
| **Breadth-First Search (BFS)** | $O(\|V\| + \|E\|)$ | $O(\|V\|)$ | Queue (FIFO) |
| **Depth-First Search (DFS)** | $O(\|V\| + \|E\|)$ | $O(\|V\|)$ | Stack (LIFO) |
| **Dijkstra's Shortest Path** | $O((\|V\| + \|E\|) \log \|V\|)$ | $O(\|V\|)$ | Priority Queue / Min-Heap |

---

## 🚀 How to Run

1. Open `app.ipynb` in VS Code or Google Colab.
2. Ensure required packages are installed:
   ```bash
   pip install networkx matplotlib ipywidgets
   