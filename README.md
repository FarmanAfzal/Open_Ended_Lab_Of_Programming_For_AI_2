# 🧠 Campus Path Finder using Search Algorithms

This project implements two search algorithms to find a path from Building A to Building G in a university campus.

---

## 📌 Objective

To find the shortest path from **Building A to G** using:
1. **Depth First Search (DFS)**
2. **A* Search Algorithm**

---

## 📊 Graph Description

The campus map is modeled as a graph with buildings as nodes and distances (in meters) as edge weights.

### Graph:
```python
graph = {
    'A': [('B', 6), ('C', 2)],
    'B': [('D', 5), ('E', 3)],
    'C': [('F', 4)],
    'D': [('G', 2)],
    'E': [('G', 6)],
    'F': [('G', 1)],
    'G': []
}
