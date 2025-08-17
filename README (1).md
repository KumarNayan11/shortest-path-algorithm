# Shortest Path Algorithm (Python)

This project contains a simple Python implementation of a **Shortest Path Algorithm** using a Dijkstra-style approach.  
It calculates the shortest distance and the path from a given start node to all other nodes in a weighted graph.

---

## 📌 Graph Example
The graph is represented as an adjacency list with weights:

```python
my_graph = {
    'A': [('B', 5), ('C', 3), ('E', 11)],
    'B': [('A', 5), ('C', 1), ('F', 2)],
    'C': [('A', 3), ('B', 1), ('D', 1), ('E', 5)],
    'D': [('C', 1), ('E', 9), ('F', 3)],
    'E': [('A', 11), ('C', 5), ('D', 9)],
    'F': [('B', 2), ('D', 3)]
}
```

---

## ▶️ Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/KumarNayan11/shortest-path-algorithm.git
   cd shortest-path-algorithm
   ```

2. Run the program:
   ```bash
   python shortest_path.py
   ```

---

## 📊 Example Output

```
A-B distance: 4
Path: A -> C -> B

A-C distance: 3
Path: A -> C

A-D distance: 4
Path: A -> C -> D

A-E distance: 8
Path: A -> C -> E

A-F distance: 6
Path: A -> C -> D -> F
```

---

## 📂 File Structure
```
shortest-path-algorithm/
│
├── shortest_path.py   # Python script implementing the algorithm
└── README.md          # Project documentation
```

---

## 📜 License
This project is open-source and available under the **MIT License**.
