# 💰 Cash Flow Simplification - 4 Algorithm Comparison

## 📋 Project Overview

This is a **4-person team project** demonstrating how different data structures and algorithms can solve the same problem: **simplifying cash flows in a group of people**.

Given a list of transactions between people, this web application shows how to minimize the number of settlements needed using 4 different algorithms:

1. **Algorithm 1: Greedy Two-Pointer** (Person A)
2. **Algorithm 2: DFS Graph Traversal** (Person B)
3. **Algorithm 3: Union-Find (Disjoint Sets)** (Person C)
4. **Algorithm 4: Min-Heap Priority Queue** (Person D)

Each algorithm uses different data structures learned in a **Data Structures & Algorithms** course.

---

## 🎯 The Problem

Imagine 5 friends go on a trip where everyone pays for different things. At the end, there are many mutual debts. Instead of asking everyone to pay everyone else, how can we **minimize the number of settlements**?

### Example:
```
Original Transactions:
Alice → Bob: $50
Bob → Charlie: $30
Charlie → Alice: $20

Simplified Settlements:
Alice → Bob: $20
Bob → Charlie: $30
Total: 2 settlements (instead of 3)
```

---

## 🏗️ Architecture

```
Frontend (HTML/CSS/JS) 
    ↓ HTTP/JSON
Node.js/Express Backend
    ↓ child_process
C++ Algorithm Programs (4 executables)
```

---

## 📁 Project Structure

```
ds-cp/
├── cpp/                        # C++ Algorithm Implementations
│   ├── algorithm1-greedy.cpp   # (Person A)
│   ├── algorithm2-dfs.cpp      # (Person B)
│   ├── algorithm3-unionfind.cpp # (Person C)
│   ├── algorithm4-heap.cpp     # (Person D)
│   ├── Makefile
│   └── bin/                    # Compiled executables
│
├── public/                     # Frontend Files
│   ├── index.html
│   ├── styles.css
│   └── js/
│       ├── main.js
│       └── visualization.js
│
├── server.js                   # Express backend
├── package.json
└── README.md
```

---

## 🚀 Quick Start

1. **Compile C++ programs:**
   ```bash
   cd cpp && make all && cd ..
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start server:**
   ```bash
   npm start
   ```

4. **Open in browser:**
   ```
   http://localhost:3000
   ```

---

## 🧮 The 4 Algorithms

| Algorithm | Person | DS Used | Complexity | Best For |
|-----------|--------|---------|-----------|----------|
| Greedy Two-Pointer | A | Vector, Map, Sort | O(n log n) | Quick solutions |
| DFS Graph Traversal | B | Graph, Map, Stack | O(V+E) | Understanding paths |
| Union-Find | C | Union-Find, Map | O(n α(n)) | Connected components |
| Min-Heap Priority Queue | D | Heap, Map | O(n log n) | Streaming data |

---

## 📚 Learning Outcomes

- Hash Maps & Hashing
- Vectors & Arrays
- Graphs & DFS
- Union-Find Data Structure
- Heaps & Priority Queues
- Algorithm Complexity Analysis
- Backend-Frontend Integration

---

## 👥 Team Members

- **Person A:** Greedy Two-Pointer Algorithm
- **Person B:** DFS Graph Traversal Algorithm
- **Person C:** Union-Find Algorithm
- **Person D:** Min-Heap Priority Queue Algorithm

**Course:** Data Structures & Algorithms

---

## 🤝 Contributing

We welcome contributions that improve this project!

### How to Contribute
1. **Fork** this repository
2. **Create** a new branch (`git checkout -b feature/your-feature`)
3. **Commit** your changes (`git commit -m 'Add some feature'`)
4. **Push** to your fork (`git push origin feature/your-feature`)
5. **Open a Pull Request** and describe your changes

### Guidelines
- Keep code clean and well-commented
- Respect existing architecture and naming conventions
- Make sure your code passes all tests (if applicable)
- Update documentation as needed

Thank you for your interest in contributing!
