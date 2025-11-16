---

# 🚚 Delivery Route Optimization — ADA Lab Assignment 5

This project implements a **multi-strategy delivery route optimization system** as part of the *Design and Analysis of Algorithms (BCA AI & DS, Semester V)* coursework.
The system models a set of delivery locations and computes the most efficient route using classical algorithmic techniques, visualizations, and performance analysis.

---

## 📌 Project Overview

The goal of this assignment is to explore multiple algorithmic strategies used in real-world route planning, such as:

* **Divide and Conquer (Closest Pair)**
* **Greedy Algorithms**
* **Graph Algorithms (Dijkstra, MST)**
* **Dynamic Programming**
* **Travelling Salesman Problem (TSP) — Brute Force + Held-Karp DP**
* **Backtracking**
* **Visualization (Route Maps + Gantt Charts)**

Each algorithm demonstrates a different approach to solving routing problems, allowing comparison of time complexity, performance, and practicality.

---

## 🧠 Key Features

### ✔ Multiple optimization algorithms implemented:

* **TSP Brute Force** (Exact but exponential)
* **TSP Dynamic Programming (Held-Karp)** (Optimized exact solution)
* **Greedy Nearest Neighbor** (Fast heuristic)
* **Minimum Spanning Tree (MST)** (Kruskal Algorithm)
* **Dijkstra’s Shortest Path Algorithm**
* **Divide & Conquer Closest Pair**

### ✔ Realistic Route Visualizations:

* Matplotlib-based route plot
* Gantt chart showing delivery schedule
* Distance matrix heatmap

### ✔ Performance & Time Complexity Analysis:

* Execution time tracking
* Asymptotic complexity included
* Comparison table between all algorithms

---

## 📂 Project Structure

```
delivery_route_optimization/
│
├── delivery_route_optimization.ipynb     # Main Notebook
├── requirements.txt                      # Python dependencies
├── README.md                             # Project documentation
```

---

## ⚙️ Installation & Setup

### **1️⃣ Clone the repository**

```bash
git clone https://github.com/yourusername/delivery-route-optimization.git
cd delivery-route-optimization
```

### **2️⃣ Create a virtual environment**

```bash
python -m venv venv
```

### **3️⃣ Activate the environment**

Windows:

```bash
venv\Scripts\activate
```

### **4️⃣ Install dependencies**

```bash
pip install -r requirements.txt
```

### **5️⃣ Run the Notebook**

Open in VS Code or Jupyter:

```bash
jupyter notebook
```

---

## 📊 Algorithms Implemented

| Algorithm                     | Category          | Time Complexity | Notes                                |
| ----------------------------- | ----------------- | --------------- | ------------------------------------ |
| TSP Brute Force               | Exhaustive Search | O(n!)           | Exact but slow                       |
| TSP Held-Karp                 | DP                | O(n²·2ⁿ)        | Exact, faster than brute force       |
| Nearest Neighbor              | Greedy            | O(n²)           | Very fast heuristic                  |
| Dijkstra                      | Graph/Greedy      | O(E log V)      | Shortest path from source            |
| MST (Kruskal)                 | Greedy            | O(E log E)      | Connects all nodes with minimum cost |
| Divide & Conquer Closest Pair | D&C               | O(n log n)      | Used for spatial clustering          |
| Backtracking                  | Constraint Search | Exponential     | Used for feasible scheduling         |

---

## 🗺 Visualizations Included

* ✔ Route visualization
* ✔ Node-to-node distance matrix
* ✔ Gantt chart for delivery sequence
* ✔ Bar plots comparing algorithm performance
* ✔ Execution time plots

All visualizations are automatically generated inside the notebook.

---

## 📥 Input Format

You can supply locations in the following format:

```python
locations = {
    "Warehouse": (0, 0),
    "Client A": (2, 5),
    "Client B": (7, 3),
    "Client C": (6, 8)
}
```

Or load from JSON.

---

## 📤 Output

The system outputs:

* Optimized delivery path
* Total route cost (distance)
* Per-algorithm results
* Comparison tables
* Plot images
* Gantt chart

Example TSP output:

```
Optimized Route (Held-Karp):
Warehouse → Client A → Client C → Client B → Warehouse
Total Distance: 21.87 units
```

---

## 🏁 Final Results Summary

| Algorithm        | Best Use Case       | Pros                    | Cons                      |
| ---------------- | ------------------- | ----------------------- | ------------------------- |
| Brute Force      | Very small inputs   | Exact                   | Extremely slow            |
| Held-Karp DP     | Medium-sized inputs | Exact, faster           | Still exponential         |
| Nearest Neighbor | Real-time routing   | Fast                    | Not always optimal        |
| Dijkstra         | Shortest path       | Works with large graphs | Single-source only        |
| MST              | Network design      | Minimum linking cost    | Doesn’t solve ordering    |
| Divide & Conquer | Spatial analysis    | Fast                    | Not a full route solution |

---

## 🧑‍💻 Author

**Aaradhya** (2301201029)
---


