# Must Know

A collection of Must Know Topics.

## Index
* [Data Structures](#data-structures)
* [Algorithms](#algorithms)
* [Patterns](#patterns)

## Data Structures
Here’s a comprehensive list of common data structures, organized into categories:

### Linear Data Structures
1. **Array**
   - Fixed-size, contiguous memory allocation.
2. **Linked List**
   - **Singly Linked List**
   - **Doubly Linked List**
   - **Circular Linked List**
3. **Stack**
   - Last-In-First-Out (LIFO) principle.
4. **Queue**
   - First-In-First-Out (FIFO) principle.
   - **Circular Queue**
   - **Priority Queue**
   - **Deque (Double-ended Queue)**

### Non-linear Data Structures
1. **Tree**
   - **Binary Tree**
   - **Binary Search Tree (BST)**
   - **Balanced Trees** (e.g., AVL Tree, Red-Black Tree)
   - **B-Tree**
   - **B+ Tree**
   - **Segment Tree**
   - **Fenwick Tree (Binary Indexed Tree)**
   - **Trie (Prefix Tree)**
   - **N-ary Tree**
   - **Heap**
     - **Min-Heap**
     - **Max-Heap**

2. **Graph**
   - **Directed Graph**
   - **Undirected Graph**
   - **Weighted Graph**
   - **Unweighted Graph**
   - **Adjacency Matrix**
   - **Adjacency List**
   - **Edge List**

### Hash-Based Structures
1. **Hash Table (Hash Map)**
   - Key-value pairs with efficient access.
2. **Hash Set**
   - Unordered collection of unique elements.

### Specialized Data Structures
1. **Matrix**
   - 2D array representation.
2. **Bit Array (Bit Vector)**
   - Compact representation of boolean values.
3. **Skip List**
   - A probabilistic alternative to balanced trees.
4. **Disjoint Set (Union-Find)**
   - Efficiently handles dynamic connectivity.

### Miscellaneous Structures
1. **Bloom Filter**
   - Probabilistic data structure for membership testing.
2. **Suffix Tree**
   - String data structure for substring search.
3. **Trie (Prefix Tree)**
   - Used for efficient retrieval of strings.

Sure! Here are additional data structures, along with some variations and specialized forms:

### Advanced Data Structures
1. **Augmented Data Structures**
   - Structures enhanced with additional information for improved operations.
   - **Segment Tree with Lazy Propagation**: For range queries and updates.
   - **Interval Tree**: For storing intervals and efficiently querying overlapping intervals.

2. **K-D Tree**
   - A space-partitioning data structure for organizing points in a k-dimensional space, useful in multidimensional search.

3. **R-Tree**
   - A tree data structure for spatial access methods, used in databases for spatial data indexing.

4. **Quad Tree**
   - A tree data structure in which each internal node has four children, used for partitioning a two-dimensional space.

5. **Octree**
   - Similar to a quad tree, but for three-dimensional space, useful in 3D graphics and spatial indexing.

### Graph Variants
1. **Directed Acyclic Graph (DAG)**
   - A directed graph with no cycles, often used for scheduling and dependency resolution.

2. **Planar Graph**
   - A graph that can be drawn on a plane without edges crossing.

3. **Weighted Directed Graph**
   - A graph where edges have weights, often used in shortest path algorithms.

4. **Network Flow Graph**
   - A directed graph used for flow problems, where each edge has a capacity.

### Search Structures
1. **Self-balancing Binary Search Trees**
   - **Splay Tree**: Self-adjusting binary search tree.
   - **Treap**: Combines binary search tree and heap properties.
   - **AA Tree**: A form of balanced binary tree with a simplified balancing mechanism.

2. **Skip Graph**
   - A probabilistic data structure for maintaining a sorted list of elements that allows fast search and insertion.

### Miscellaneous Data Structures
1. **Sparse Table**
   - A data structure that allows answering range queries in constant time after preprocessing.

2. **Fibonacci Heap**
   - A data structure for priority queue operations with better amortized time complexity for certain operations.

3. **Van Emde Boas Tree**
   - A tree structure that provides fast operations for integer keys, particularly useful for a bounded universe.

4. **Count-Min Sketch**
   - A probabilistic data structure for estimating the frequency of events in a data stream.

5. **DataFrame**
   - A tabular data structure used primarily in data analysis and manipulation (e.g., in Pandas for Python).

6. **Suffix Array**
   - An array of the starting indices of suffixes of a string, useful for efficient string processing.

7. **Ternary Search Tree**
   - A trie-like data structure that can efficiently store strings and supports prefix-based searching.

### Geometric Data Structures
1. **Spatial Hashing**
   - A technique for efficiently storing and querying spatial data by mapping coordinates to hash values.

2. **Bounding Volume Hierarchies (BVH)**
   - A tree structure used in computer graphics for ray tracing and collision detection.

3. **Point Quadtree**
   - A variant of quad tree used for efficiently storing points in a 2D space.

### Specialized Trees
1. **Binary Indexed Tree (Fenwick Tree)**
   - A tree structure that provides efficient methods for cumulative frequency tables.

2. **Patricia Trie**
   - A space-optimized trie for storing a dynamic set or associative array where the keys are usually strings.

3. **Segment Tree with Dynamic Size**
   - A segment tree that can adapt its size based on the input.


## Algorithms
Here’s a comprehensive combined list of common algorithms organized into various categories, including both basic and advanced algorithms:

### 1. **Sorting Algorithms**
- **Comparison-Based Sorting**
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Heap Sort
  - Shell Sort
  - Tim Sort
- **Non-Comparison-Based Sorting**
  - Counting Sort
  - Radix Sort
  - Bucket Sort
- **Adaptive Sorting Algorithms**
  - Smoothsort
  - Bead Sort
  - Gnome Sort
  - Comb Sort
- **Distribution Sort**
  - Flashsort
  - Pigeonhole Sort
  - Stooge Sort

### 2. **Search Algorithms**
- **Linear Search**
- **Binary Search**
- **Ternary Search**
- **Exponential Search**
- **Interpolation Search**
- **Jump Search**
- **Fibonacci Search**
- **Graph Search Variants**
  - Depth-First Search (DFS)
  - Breadth-First Search (BFS)
  - Uniform Cost Search
  - Bidirectional Search
- **Heuristic Search**
  - Best-First Search
  - Hill Climbing Search
  - Simulated Annealing

### 3. **Graph Algorithms**
- **Traversal Algorithms**
  - Depth-First Search (DFS)
  - Breadth-First Search (BFS)
- **Shortest Path Algorithms**
  - Dijkstra's Algorithm
  - Bellman-Ford Algorithm
  - Floyd-Warshall Algorithm
  - A* Search Algorithm
- **Minimum Spanning Tree Algorithms**
  - Prim's Algorithm
  - Kruskal's Algorithm
  - Reverse-Delete Algorithm
- **Flow Algorithms**
  - Ford-Fulkerson Method
  - Edmonds-Karp Algorithm
  - Dinic's Algorithm
- **Cycle Detection Algorithms**
  - Floyd-Warshall Cycle Detection
  - Union-Find Algorithm (Disjoint Set)
- **Topological Sorting**
- **Graph Coloring**
- **Connected Components**

### 4. **Dynamic Programming Algorithms**
- **Knapsack Problem**
- **Longest Common Subsequence**
- **Longest Increasing Subsequence**
- **Fibonacci Sequence**
- **Matrix Chain Multiplication**
- **Coin Change Problem**
- **Edit Distance**
- **Traveling Salesman Problem (TSP)**
- **Job Scheduling Problem**
- **Bin Packing Problem**
- **Palindrome Partitioning**

### 5. **Greedy Algorithms**
- **Activity Selection Problem**
- **Huffman Coding**
- **Minimum Spanning Tree**
  - Prim's Algorithm
  - Kruskal's Algorithm
- **Job Sequencing Problem**
- **Fractional Knapsack Problem**
- **Coin Change (Greedy vs. Dynamic Programming)**

### 6. **Backtracking Algorithms**
- **N-Queens Problem**
- **Sudoku Solver**
- **Rat in a Maze**
- **Hamiltonian Cycle**
- **Subset Sum Problem**
- **Generating Permutations**
- **Generating Combinations**
- **Graph Coloring Problems**
- **Word Search Problems**

### 7. **Divide and Conquer Algorithms**
- **Merge Sort**
- **Quick Sort**
- **Binary Search**
- **Strassen's Algorithm for Matrix Multiplication**
- **Convex Hull Algorithms**
  - Graham's Scan
  - Jarvis March
- **Fast Fourier Transform (FFT)**
- **Karatsuba Algorithm for Fast Multiplication**

### 8. **Mathematical Algorithms**
- **Greatest Common Divisor (GCD)**
- **Least Common Multiple (LCM)**
- **Sieve of Eratosthenes (Prime Number Generation)**
- **Fermat's Little Theorem**
- **Fast Exponentiation**
- **Monte Carlo Method**
- **Number Theory Algorithms**
  - Pollard's Rho Algorithm (for Factorization)
  - Miller-Rabin Primality Test
  - Chinese Remainder Theorem
  - Lucas Sequence

### 9. **String Algorithms**
- **Knuth-Morris-Pratt (KMP) Algorithm**
- **Rabin-Karp Algorithm**
- **Boyer-Moore Algorithm**
- **Longest Common Substring**
- **Suffix Array and Suffix Tree**
- **Trie Data Structure**
- **Pattern Matching Algorithms**
  - Aho-Corasick Algorithm
  - Z Algorithm
- **String Distance Algorithms**
  - Levenshtein Distance
  - Jaro-Winkler Distance

### 10. **Data Structure Algorithms**
- **Binary Tree Traversals**
- **Balanced Tree Operations (AVL, Red-Black Tree)**
- **Hashing Techniques**
- **Heap Operations (Min-Heap, Max-Heap)**
- **Segment Trees**
  - Range Queries
  - Lazy Propagation
- **Fenwick Tree (Binary Indexed Tree)**
- **Splay Trees**
- **Skip Lists**
- **K-D Trees (for multidimensional data)**

### 11. **Machine Learning Algorithms**
- **Linear Regression**
- **Logistic Regression**
- **Decision Trees**
- **Random Forests**
- **Support Vector Machines (SVM)**
- **K-Means Clustering**
- **Neural Networks**
- **Gradient Descent Algorithms**
- **Ensemble Methods**
  - Bagging (e.g., Bootstrap Aggregating)
  - Boosting (e.g., AdaBoost, XGBoost)
- **Clustering Algorithms**
  - Hierarchical Clustering
  - DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- **Dimensionality Reduction Algorithms**
  - Principal Component Analysis (PCA)
  - t-Distributed Stochastic Neighbor Embedding (t-SNE)

### 12. **Miscellaneous Algorithms**
- **Flood Fill Algorithm**
- **Cache Algorithms**
  - Least Recently Used (LRU)
  - Least Frequently Used (LFU)
- **Networking Algorithms**
  - Dijkstra's Algorithm (for routing)
  - Bellman-Ford Algorithm (for routing)
- **Simulation Algorithms**
  - Discrete Event Simulation
  - Markov Chain Monte Carlo (MCMC)

### 13. **Cryptographic Algorithms**
- **Symmetric Key Algorithms**
  - AES (Advanced Encryption Standard)
  - DES (Data Encryption Standard)
- **Asymmetric Key Algorithms**
  - RSA (Rivest-Shamir-Adleman)
  - Diffie-Hellman Key Exchange
- **Hash Functions**
  - SHA (Secure Hash Algorithms)
  - MD5 (Message-Digest Algorithm 5)

### 14. **Computer Vision Algorithms**
- **Image Processing Algorithms**
  - Canny Edge Detection
  - Hough Transform
- **Feature Detection Algorithms**
  - SIFT (Scale-Invariant Feature Transform)
  - SURF (Speeded Up Robust Features)

### 15. **Game Algorithms**
- **Pathfinding Algorithms**
  - A* Algorithm
  - Dijkstra’s Algorithm
- **AI Algorithms**
  - Minimax Algorithm
  - Alpha-Beta Pruning

### 16. **Approximation Algorithms**
- **Vertex Cover Problem**
- **Set Cover Problem**
- **Traveling Salesman Problem (TSP) Approximation**

### 17. **Distributed Algorithms**
- **Leader Election Algorithms**
- **Consensus Algorithms**
  - Paxos
  - Raft
- **MapReduce Framework Algorithms**


## Patterns

### 1. **Array Patterns**
- Two Pointer
- Sliding Window
- Prefix Sum
- Kadane’s Algorithm
- Dutch National Flag
- XOR Patterns
- Combination Sum

### 2. **String Patterns**
- Pattern Matching
- Two Pointer for Strings
- Sliding Window for Strings
- Longest Palindromic Substring
- String Compression
- Anagram Checking

### 3. **Linked List Patterns**
- Fast and Slow Pointers
- Reversal of a Linked List
- Merge Two Sorted Lists
- Cycle Detection
- Remove N-th Node from End
- Intersection of Two Linked Lists

### 4. **Tree Patterns**
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Level Order Traversal
- Lowest Common Ancestor
- Tree Traversal Patterns (Inorder, Preorder, Postorder)
- Serialize and Deserialize a Binary Tree
- Binary Tree Maximum Path Sum

### 5. **Graph Patterns**
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Topological Sort
- Dijkstra’s Algorithm
- Floyd-Warshall Algorithm
- Kruskal’s Algorithm
- Prim’s Algorithm
- Connected Components
- Cycle Detection in Graphs

### 6. **Dynamic Programming Patterns**
- 1D DP (Fibonacci, Climbing Stairs)
- 2D DP (Knapsack, Longest Common Subsequence)
- Memoization
- Tabulation
- Optimal Substructure
- Coin Change Problem
- Palindrome Partitioning

### 7. **Backtracking Patterns**
- N-Queens Problem
- Permutations and Combinations
- Subset Sum Problem
- Sudoku Solver
- Word Search
- Generate Parentheses

### 8. **Greedy Patterns**
- Activity Selection
- Huffman Coding
- Fractional Knapsack Problem
- Job Sequencing Problem
- Minimum Spanning Tree (Prim’s and Kruskal’s)
- Coin Change (Greedy vs. Dynamic Programming)

### 9. **Divide and Conquer Patterns**
- Merge Sort
- Quick Sort
- Binary Search
- Matrix Multiplication
- Closest Pair of Points
- Finding K-th Largest Element

### 10. **Concurrency Patterns**
- Producer-Consumer
- Observer
- Active Object
- Thread Pool
- Read-Write Lock
- Barrier
- Fork-Join

### 11. **Architectural Patterns**
- Model-View-Controller (MVC)
- Microservices
- Event-Driven Architecture
- Service-Oriented Architecture (SOA)
- Layered Architecture
- Client-Server Architecture
- Publish-Subscribe

### 12. **Miscellaneous Patterns**
- Caching
- Rate Limiting
- Throttling
- Event Sourcing
- Command Query Responsibility Segregation (CQRS)
- Repository Pattern
- Dependency Injection

### 13. **Mathematical Patterns**
- Sieve of Eratosthenes
- Euclidean Algorithm
- Fast Exponentiation
- Monte Carlo Method
- Combinatorial Patterns

### 14. **Networking Patterns**
- Client-Server Model
- Load Balancing
- Circuit Breaker
- API Gateway





