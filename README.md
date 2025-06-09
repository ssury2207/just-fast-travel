# 🧭 bro-just-fast-travel

A Java project that compares **Dijkstra's Algorithm** and **A\*** for shortest pathfinding — running **both in parallel threads** with synchronization to simulate a fast-travel system between nodes. 🚀

---

## 🔍 What It Does

- Accepts a **directed graph** and a **source/target node**
- Runs **Dijkstra's** and **A\*** algorithms in **separate threads**
- Uses synchronization to manage shared results safely
- Compares:
  - Shortest path cost
  - Time taken by each algorithm
  - Number of nodes explored

---

## 🛠️ Technologies & Concepts

- Java Threads & Synchronization
- Priority Queue (Min-Heap)
- Dijkstra’s Algorithm
- A* Algorithm with heuristic
- Performance Benchmarking

---

## 🧪 How to Use

1. Clone the repo
2. Run `Main.java`
3. Input:
   - Number of nodes
   - Edges in the format: `from, to, cost`
   - Source and target nodes
4. Watch both algorithms race to the goal 🏁

---

