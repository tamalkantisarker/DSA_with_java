# ☕ Data Structures & Algorithms with Java

Comprehensive collection of competitive programming and interview-grade Data Structures and Algorithms implemented in Java, with a special focus on Advanced Graph Theory and Dynamic Programming paradigms.

---

## 📂 Repository Structure

```text
├── 1. Graph/
│   ├── Normal_Graph/                      # Adjacency List, Matrix, BFS traversal
│   ├── Topological Sort/                  # Kahn's Algorithm (BFS) & DFS-based Topo Sort, Course Schedule
│   ├── Dijkstra’s Algorithm/              # Shortest path with PriorityQueue, Path with Max Probability
│   ├── Bellman-Ford Algorithm/            # Negative cycle detection, Network Delay Time
│   ├── Minimum Spanning Tree/
│   │   ├── Kruskal’s MST Algorithm/      # Disjoint Set Union (DSU) & Edge Check
│   │   └── Prim’s MST Algorithm/         # PriorityQueue-based Cut Property
│   ├── Strongly Connected Component/      # Kosaraju's 2-Pass DFS Algorithm (CSES Planets & Kingdoms)
│   ├── Articulation Point/                # Tarjan's discovery & low-link time algorithms
│   ├── Bridge/                            # Cut-edge detection (Rhezo and HackerEarth)
│   └── Eulerian path and circuit/         # Hierholzer's Algorithm & Valid Arrangement of Pairs
│
├── DP/                                    # Dynamic Programming Master Suite
│   ├── 0 - 1 Knapsack Problem.java
│   ├── Fractional Knapsack.java
│   ├── Knapsack with Duplicate Items.java
│   ├── Knapsack Problems/CoinChange.java
│   ├── Unbounded Knapsack Problem (Closest Sum Not Exceeding Target).java
│   ├── Longest Increasing Subsequence.java
│   ├── Partition Equal Subset Sum.java
│   ├── Perfect Sum Problem.java
│   ├── Target Sum.java
│   └── z_dynamic_programming_analysis.md
│
└── README.md
```

---

## 🚀 Getting Started & Compilation

### Prerequisites
- **Java SE Development Kit (JDK) 17+** (JDK 21/22/23 recommended)

### Quick Run
Clone the repository:
```bash
git clone https://github.com/tamalkantisarker/DSA_with_java.git
cd DSA_with_java
```

Compile and run any algorithm (e.g. Kosaraju's SCC or 0-1 Knapsack):
```bash
# Compile
javac "1. Graph/Strongly Connected Component/Kosaraju's algorithm/Flight_Routes_Check.java"

# Or run single-file source code directly (Java 11+)
java "1. Graph/Normal_Graph/BFS.java"
```

---

## 🏆 Key Topics Covered
- **Graph Representations**: Sparse vs. dense graphs, adjacency list memory efficiency.
- **Shortest Paths**: Single-source positive ($O(E \log V)$ Dijkstra) vs. negative weights ($O(V \cdot E)$ Bellman-Ford).
- **Spanning Trees**: Greedy cut property, Kruskal with path compression and rank optimization.
- **Connectivity & Articulation Points**: Low-link values, back-edges, bridge classification.
- **Dynamic Programming Archetypes**:
  - 0/1 Knapsack & Unbounded variants
  - Subset sum / Partition equivalence
  - Longest Increasing Subsequence ($O(n \log n)$ binary search & $O(n^2)$ DP)
  - Coin Change (minimum coins & total permutations)

---

## 📜 License
This repository is open-sourced under the MIT License. Contributions and optimizations are welcome!
