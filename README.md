# 📘 Data Structures and Algorithms - Algorithms Guide

A categorized overview of essential algorithms used in Data Structures and Algorithms (DSA), suitable for coding interviews, competitive programming, and real-world applications.

---

## 📂 Table of Contents

1. [Sorting Algorithms](#sorting-algorithms)
2. [Searching Algorithms](#searching-algorithms)
3. [Divide and Conquer](#divide-and-conquer)
4. [Dynamic Programming](#dynamic-programming)
5. [Greedy Algorithms](#greedy-algorithms)
6. [Recursion and Backtracking](#recursion-and-backtracking)
7. [Graph Algorithms](#graph-algorithms)
8. [Tree Algorithms](#tree-algorithms)
9. [String Algorithms](#string-algorithms)
10. [Bit Manipulation](#bit-manipulation)

---

## 1. 🔁 Sorting Algorithms

```
| Algorithm       | Time Complexity | Description                          |
|----------------|------------------|--------------------------------------|
| Bubble Sort     | O(n²)            | Repeatedly swaps adjacent elements.  |
| Selection Sort  | O(n²)            | Selects the minimum element.         |
| Insertion Sort  | O(n²)            | Inserts elements into the sorted part. |
| Merge Sort      | O(n log n)       | Divide and conquer sorting.          |
| Quick Sort      | O(n log n) avg   | Partition-based sorting.             |
| Heap Sort       | O(n log n)       | Uses a binary heap.                  |
| Counting Sort   | O(n + k)         | Counts occurrences, non-comparison sort. |
| Radix Sort      | O(nk)            | Sorts digit by digit.                |
| Bucket Sort     | O(n + k)         | Divides into buckets, then sorts.    |
```

---

## 2. 🔍 Searching Algorithms

```
| Algorithm       | Time Complexity | Description                           |
|----------------|------------------|----------------------------------------|
| Linear Search   | O(n)             | Checks each element one by one.        |
| Binary Search   | O(log n)         | Searches in a sorted array.            |
| Jump Search     | O(√n)            | Jumps ahead by fixed steps.            |
| Interpolation   | O(log log n)     | Improved binary search on uniform data |
| Exponential      | O(log i)        | Useful for unbounded binary search.    |
```

---

## 3. 📐 Divide and Conquer

```
| Algorithm                   | Description                                |
|----------------------------|--------------------------------------------|
| Merge Sort                 | Divide array, sort halves, then merge.     |
| Quick Sort                 | Partition and sort sub-arrays.             |
| Binary Search              | Recursively divide search space.           |
| Closest Pair of Points     | Efficient 2D point distance finding.       |
| Strassen’s Matrix Mult.    | Faster matrix multiplication.              |
```

---

## 4. 📊 Dynamic Programming (DP)

```
| Problem                            | Description                             |
|-----------------------------------|-----------------------------------------|
| Fibonacci Number                  | Avoids recomputation using memoization. |
| 0/1 Knapsack                      | Maximize value within weight limit.     |
| Longest Common Subsequence (LCS) | Finds common sequence in two strings.   |
| Longest Increasing Subsequence   | Finds longest ordered subsequence.      |
| Matrix Chain Multiplication       | Optimal order of matrix multiplication. |
| Edit Distance                     | Converts one string to another.         |
| Coin Change Problem               | Fewest coins to make a given sum.       |
```

---

## 5. 🧭 Greedy Algorithms

```
| Algorithm             | Description                                       |
|----------------------|---------------------------------------------------|
| Activity Selection    | Selects maximum non-overlapping intervals.       |
| Huffman Encoding      | Prefix-free code generation.                     |
| Kruskal’s Algorithm   | Minimum spanning tree using edges.               |
| Prim’s Algorithm      | Minimum spanning tree using vertices.            |
| Dijkstra’s Algorithm  | Shortest path from a source node.                |
```

---

## 6. 🔄 Recursion and Backtracking

```
| Problem              | Description                                    |
|---------------------|------------------------------------------------|
| N-Queens             | Place queens on a board without attacking.    |
| Sudoku Solver        | Fills valid numbers recursively.              |
| Rat in a Maze        | Find path from start to end.                  |
| Subset Sum Problem   | Checks if subset adds to target.              |
| Permutations         | Generates all arrangements of elements.       |
```

---

## 7. 🕸️ Graph Algorithms

```
| Algorithm             | Description                                 |
|----------------------|---------------------------------------------|
| BFS (Breadth-First)  | Explores nodes level by level.              |
| DFS (Depth-First)    | Explores as deep as possible.               |
| Topological Sort     | Orders DAG nodes respecting dependencies.   |
| Dijkstra’s Algorithm | Shortest path (non-negative weights).       |
| Bellman-Ford         | Handles negative weights.                   |
| Floyd-Warshall       | All-pairs shortest paths.                   |
| Kruskal’s Algorithm  | MST using disjoint sets.                    |
| Prim’s Algorithm     | MST with priority queue.                    |
| Tarjan’s Algorithm   | Finds Strongly Connected Components (SCCs). |
| Kosaraju’s Algorithm | Another SCC detection method.               |
```

---

## 8. 🌲 Tree Algorithms

```
| Algorithm              | Description                                  |
|-----------------------|----------------------------------------------|
| Inorder Traversal      | Left - Root - Right                         |
| Preorder Traversal     | Root - Left - Right                         |
| Postorder Traversal    | Left - Right - Root                         |
| Lowest Common Ancestor | Finds shared ancestor of two nodes.         |
| Balanced Tree Check    | Checks if tree is height-balanced.          |
| Diameter of Tree       | Longest path between any two nodes.         |
| BST Operations         | Insert, Search, Delete in a BST.            |
```

---

## 9. 🧵 String Algorithms

```
| Algorithm             | Description                                     |
|----------------------|-------------------------------------------------|
| Naive Pattern Search  | Checks all positions.                          |
| KMP Algorithm         | Efficient prefix-based search.                 |
| Rabin-Karp Algorithm  | Hash-based string matching.                    |
| Z Algorithm           | Computes longest substring match at each index|
| Trie                  | Prefix tree for word storage/search.           |
| Suffix Array/Tree     | Fast substring search and matching.            |
| Aho-Corasick          | Multi-pattern matching.                        |
```

---

## 10. 🧠 Bit Manipulation

```
| Operation/Algorithm     | Description                                 |
|------------------------|---------------------------------------------|
| Check Power of 2        | `(n & (n-1)) == 0` for powers of 2.         |
| Count Set Bits          | Count `1`s in binary representation.        |
| XOR Swap                | Swapping values using XOR.                  |
| Missing Number          | XOR all numbers to find the missing one.   |
| Bitmasking Subsets      | Generate all subsets using binary masks.    |
```

---

## 📌 Notes

- Mastering these algorithms will give you an edge in technical interviews and algorithmic problem solving.
- Start with easier ones (e.g. sorting/searching), then move to advanced ones (e.g. DP, graph algorithms).


---
Happy coding! 🚀
