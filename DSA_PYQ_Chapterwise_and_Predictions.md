# IT2311 – Data Structures and Algorithms (R-2022)
## Complete PYQ Question Bank (Separated Chapter-Wise) + Pattern Analysis & Exam Predictions
**Institution:** PSNA College of Engineering and Technology (Autonomous)  
**Papers Analyzed (5 Consecutive End-Semester Exams):**
1. **Apr/May 2024** (`doc (6).pdf` – Date: 11-07-2024)
2. **Nov/Dec 2024** (`doc (5).pdf` – Date: 18-12-2024)
3. **Apr/May 2025** (`doc (4).pdf` – Date: 31-05-2025)
4. **Nov/Dec 2025** (`nov-dec25.pdf` – Date: 28-11-2025)
5. **Apr/May 2026** (`doc (2).pdf` – Date: 17-06-2026)

---

## 1. Exam Paper Structure & Exact Blueprint Discovered

Every single question paper strictly follows this exact blueprint:
- **Part-A (10 × 2 = 20 Marks):**
  - Q1, Q2 → **Unit I**
  - Q3, Q4 → **Unit II**
  - Q5, Q6 → **Unit III**
  - Q7, Q8 → **Unit IV**
  - Q9, Q10 → **Unit V**
- **Part-B (5 × 13 = 65 Marks) — Either/Or per Unit:**
  - **Q11 (A or B)** → **Unit I**
  - **Q12 (A or B)** → **Unit II** *(Note: once in Apr/May 2024, Circular Linked List slipped into Q12B, otherwise 100% Stack vs Queue/Recursion)*
  - **Q13 (A or B)** → **Unit III**
  - **Q14 (A or B)** → **Unit IV**
  - **Q15 (A or B)** → **Unit V**
- **Part-C (1 × 15 = 15 Marks) — Case Study / Problem Solving (Either/Or across two different units):**
  - Almost always **problem-solving / trace-based** from **Unit III** (AVL / B-Tree / Min-Heap / Huffman), **Unit IV** (Prim's / Kruskal's / Topological Sort), **Unit V** (Quick Sort / Hashing), or **Unit I** (Polynomial Addition).

---

## 2. Chapter-Wise Separated PYQ Questions (All 5 Papers)

---

### UNIT I: INTRODUCTION – LINEAR DATA STRUCTURES & ANALYSIS OF ALGORITHMS
*Syllabus: Introduction to Algorithms - Analysis of algorithm: Efficiency of an Algorithm - frequency count and its importance - Time complexity & Space complexity. Introduction to Data Structures - Types of data structures - Abstract Data Types. Lists: Array Implementation - Dynamic Implementation - Singly Linked Lists - Doubly Linked List - Circularly Linked List - Linked list application: Polynomial Representation and Addition.*

#### Part-A (2 Marks)
1. What is an Abstract Data type? *(Apr/May 2024)*
2. Define an abstract data type (ADT). *(Apr/May 2025)*
3. Define Abstract Data Types. *(Nov/Dec 2025)*
4. Define Abstract Data Type (ADT) with an example. *(Apr/May 2026)*
5. Why we need asymptotic notation? *(Apr/May 2024)*
6. Consider the following algorithm: `S=0; For i=1 to n Do S=S+i; Return i`. What does this algorithm compute? How many times the basic operation is executed? *(Nov/Dec 2024)*
7. What is meant by analysis of algorithm? *(Nov/Dec 2025)*
8. Write the significance of frequency count in algorithm analysis. *(Apr/May 2026)*
9. What is the advantage of doubly linked list over a singly linked list? *(Nov/Dec 2024)*
10. Differentiate between array and linked list. *(Apr/May 2025)*

#### Part-B (13 Marks — Q11 A & B)
- **Apr/May 2024:**
  - **11 A:** Explain the steps involved in the following insertion operations in a singly linked list: (i) Insert the node in the start and End. (ii) Insert the node in the middle of the List. *(13)*
  - **11 B:** (i) Illustrate how polynomial manipulations are performed using lists. *(8)* (ii) Write an algorithm to add two polynomials using linked list. Illustrate with an example. *(5)*
  - *(Also appeared in 12 B of Apr/May 2024):* Analyze and write algorithm for Circular Linked list for the following operations using structure pointer: (i) Create & Insert (ii) Delete & Display. *(13)*
- **Nov/Dec 2024:**
  - **11 A:** Do the following in a Circular linked list and draw a neat sketch with suitable pointers: a) Create a list with elements 15, 19, 25, 86, 94; b) Insert element 75 after 25; c) Delete the element 86. *(13)*
  - **11 B:** Write an algorithm to find maximum element in an array and analyze the worst case, best case, average case time efficiency of the same. *(13)*
- **Apr/May 2025:**
  - **11 A:** Explain the concepts of time and space complexity with examples. Why are they important in algorithm analysis? *(13)*
  - **11 B:** Describe different types of linked lists with diagrams. Highlight their structure and use cases. *(13)*
- **Nov/Dec 2025:**
  - **11 A:** (i) Write an algorithm to reverse an array without using an additional array. *(8)* (ii) Analyze its time complexity. *(5)*
  - **11 B:** Discuss singly linked lists with suitable diagram, algorithm, and example for insertion and deletion operations. *(13)*
- **Apr/May 2026:**
  - **11 A:** Write an algorithm that reads a list of integers from the keyboard, creates a singly linked list from them, and performs insertion and deletion operations at the front, rear and any specified position. Print the linked list after each operation. *(13)*
  - **11 B:** Write an algorithm to represent a polynomial using singly linked lists. Then develop a procedure to add two polynomials represented in this format. Demonstrate the algorithm with the following example: Polynomial A: $5x^4 + 3x^2 + 2$, Polynomial B: $4x^3 + 2x^2 + 1$. Show the resulting polynomial after addition and explain each step involved in the merging process. *(13)*

#### Part-C (15 Marks)
- **Nov/Dec 2025 (16 B):** Evaluate and explain the representation of polynomial using linked list and write an algorithm for polynomial addition. *(15)*

---

### UNIT II: STACKS AND QUEUES
*Syllabus: Stack: Array and Linked Implementation - Application: infix to postfix conversion - Evaluation of postfix expression - Recursion: Tower of Hanoi Problem - Complexity analysis of Stack operations. Queue: Array and linked implementation of queues - Circular queues - double ended queue - Priority Queue – Complexity analysis of Queue Operations.*

#### Part-A (2 Marks)
1. Write a routine to check whether the stack is full or empty. *(Apr/May 2024)*
2. Evaluate the following postfix expression using stack: `7 6 2 + * 4 5 1 - / -` *(Nov/Dec 2024)*
3. What is a stack? *(Apr/May 2025)*
4. Write short notes on overflow and underflow conditions in a stack. *(Nov/Dec 2025)*
5. List the applications of a stack. *(Apr/May 2026)*
6. List the applications of priority queue. *(Apr/May 2024)*
7. For railway reservation the queue data structure is preferred – Justify. *(Nov/Dec 2024)*
8. Explain the concept of circular queues. *(Apr/May 2025)*
9. What is a double-ended queue (Deque)? *(Nov/Dec 2025)*
10. What is a circular queue? Mention one of its applications. *(Apr/May 2026)*

#### Part-B (13 Marks — Q12 A & B)
- **Apr/May 2024:**
  - **12 A:** Write C functions for implementing the following stack operations: i. Push, ii. Peek, iii. Pop. *(13)*
  - *(12 B was Circular Linked List from Unit I)*
- **Nov/Dec 2024:**
  - **12 A:** Convert the following infix expression to postfix expression using stack: `a+b*(c-d*f)/g-(h/i+j)` *(13)*
  - **12 B:** Discuss in detail how stack can be used to solve Tower of Hanoi problem. *(13)*
- **Apr/May 2025:**
  - **12 A:** Simulate the Tower of Hanoi problem for 4 disks. Show the sequence of moves and explain the recursive steps involved. *(13)*
  - **12 B:** Given the postfix expression `6 2 3 + - 3 8 2 / + *`, evaluate the result using stack operations. Show all intermediate steps. *(13)*
- **Nov/Dec 2025:**
  - **12 A:** Implement the conversion from the following infix expression to postfix form `A + B * (C + D)` and evaluate it for A = 5, B = 2, C = 3, D = 1. *(13)*
  - **12 B:** Demonstrate circular queue in detail. Explain its implementation and write algorithm for insertion and deletion operations. *(13)*
- **Apr/May 2026:**
  - **12 A:** Explain the algorithm used to implement a stack of size N using an array. Describe the operations PUSH, POP, TOP and DISPLAY, and how stack overflow and underflow conditions are handled. Illustrate the concept of converting infix expressions to postfix notation and convert: `a + b * (c ^ d - e) ^ (f + g * h) - i`. *(13)*
  - **12 B:** Define Queue and explain various operations involved in it. Diagrammatically represent queue and state few of its application. Display the queue content after executing the following sequence of operation: `add(1), del(), add(2), del(), add(3), add(4), add(5), del(), del(), add(6), del(), add(7), add(8), del(), del()`. *(13)*

---

### UNIT III: TREE STRUCTURES
*Syllabus: Binary Trees - Representation: Array and Dynamic Representation - Types - Binary Tree Traversal algorithms: Inorder – Preorder – Postorder - Threaded Binary trees - Huffman algorithm - Dictionaries. Search Trees: Binary Search Trees (BST) - Insertion and Deletion in BST - AVL trees - B Trees - Max Heap and Min Heap - Complexity analysis of tree traversal algorithms.*

#### Part-A (2 Marks)
1. Define depth and height of a tree. *(Apr/May 2024)*
2. State the degree of a node, Height and depth of a node. *(Nov/Dec 2024)*
3. What is meant by the height of a binary tree? *(Nov/Dec 2025)*
4. How to resolve the null links in a binary tree? *(Apr/May 2024)*
5. State the need for threaded binary trees. *(Apr/May 2026)*
6. Define inorder traversal. *(Apr/May 2025)*
7. Differentiate max heap and min heap? *(Nov/Dec 2024)*
8. What is the difference between a Max Heap and a Min Heap? *(Apr/May 2025)*
9. State max heap and min heap. *(Nov/Dec 2025)*
10. Differentiate between Max Heap and Min Heap. *(Apr/May 2026)*

#### Part-B (13 Marks — Q13 A & B)
- **Apr/May 2024:**
  - **13 A:** Write an algorithm for pre-order, in-order and post-order traversal of a binary tree. Explain with an Example. *(13)*
  - **13 B:** Describe the algorithms used to perform single and double rotation on AVL tree for the following inputs: `1, 2, 3, 4, 5, 6, 7, 8`. *(13)*
- **Nov/Dec 2024:**
  - **13 A:** Explain the various tree traversal algorithms and construct a binary tree for the given pre-order and in-order traversals. Pre-order: `GBQACKFPDERH`, In-order: `QBKCFAGPEDHR`. *(13)*
  - **13 B:** Draw a binary search tree for the following input list `60, 25, 75, 15, 50, 66, 33, 44`; Trace the algorithm to delete the nodes `25, 75, 44` from the tree. *(13)*
- **Apr/May 2025:**
  - **13 A:** Construct a binary search tree (BST) using the following sequence of values: `90, 40, 20, 10, 30, 60, 50, 70, 80`. Perform and display the result of inorder, preorder, and postorder traversals. *(13)*
  - **13 B:** Insert the following elements into an AVL tree: `10, 20, 30, 40, 50, 15, 25, 60, 70, 80`. Show the tree after each insertion and describe the rotations performed. *(13)*
- **Nov/Dec 2025:**
  - **13 A:** Examine in detail the following tree traversal algorithms with examples: Inorder traversal (4), Preorder traversal (4), Postorder traversal (5). *(13)*
  - **13 B:** Examine the purpose of AVL trees. Also describe LL, RR, LR, RL rotations used for rebalancing the tree with neat diagrams. *(13)*
- **Apr/May 2026:**
  - **13 A:** (i) Write a routine for Pre order, in order and Post order traversal. Is it possible to find minimum and maximum value in the binary search tree using traversals? Discuss. Display the given tree using Inorder, Preorder and Postorder Traversals. (ii) Delete 11 and 10 from the above binary search tree. And display the tree after each deletion. *(13)*
  - **13 B:** Write a routine for AVL tree rotations and insertion. Insert the following elements in the empty tree and how do you balance the tree after each element insertion? Elements: `2, 5, 4, 6, 7, 9, 8, 3, 1, 10`. *(13)*

#### Part-C (15 Marks)
- **Apr/May 2024 (16 B):** Show the result of inserting `15, 17, 6, 19, 11, 10, 13, 20, 8, 14, 12` one at a time into an initially empty binary min heap. Show the result of performing three delete min operations in the final binary min heap obtained. *(15)*
- **Nov/Dec 2024 (16 B):** Identify and explain each rotation or rebalancing step required to maintain the AVL tree properties after every insertion of the elements `2, 1, 4, 5, 9, 3, 6, 7` into an empty AVL tree. *(15)*
- **Nov/Dec 2025 (16 A):** (i) Formulate the use of Huffman algorithm. *(5)* (ii) Construct a Huffman tree for the following characters and frequencies: `A:5, B:9, C:12, D:13, E:16, F:45`. *(10)*
- **Apr/May 2026 (16 B):** Construct a B-Tree of order 3 by inserting the following sequence of keys one by one: `10, 20, 5, 6, 12, 30, 7, 17`. Show all intermediate steps and clearly illustrate the structure of the B-Tree after each insertion. Explain the rules applied during node splitting and balancing. *(15)*

---

### UNIT IV: GRAPH STRUCTURES
*Syllabus: Terminology - Representations of Graphs: Adjacency Matrices - Adjacency List - Topological sort - Graph Traversal: Depth First Search - Breadth First Search - Spanning Trees - Minimum Cost Spanning Trees: Prims and Kruskal algorithm - Shortest Path algorithm: Warshal Algorithm and Dijkstra Algorithm.*

#### Part-A (2 Marks)
1. Find the topological ordering of the given graph. *(Apr/May 2024)*
2. Write about the Warshall's algorithm. *(Apr/May 2024)*
3. What is the purpose of Warshall's algorithm in graph applications? *(Apr/May 2026)*
4. What is graph traversal? Mention the different techniques used for graph traversal? *(Nov/Dec 2024)*
5. What are the applications of graph? *(Nov/Dec 2024)*
6. List any two differences between DFS and BFS. *(Apr/May 2025)*
7. Define a minimum spanning tree. *(Apr/May 2025)*
8. Explain the main goal of a minimum spanning tree (MST). *(Nov/Dec 2025)*
9. State the applications of topological sort. *(Nov/Dec 2025)*
10. Compare Prim's and Kruskal's algorithms. *(Apr/May 2026)*

#### Part-B (13 Marks — Q14 A & B)
- **Apr/May 2024:**
  - **14 A:** Define a minimum spanning tree. Explain Prim's algorithm to find the minimum spanning tree of a graph. Apply the algorithm to find the minimum spanning tree of the given graph. *(13)*
  - **14 B:** Explain the Dijkstra Algorithm to find the shortest path algorithm from a source vertex and analyse the time complexity of the approach. Apply the same on the graph given below to find the shortest path from vertex A. *(13)*
- **Nov/Dec 2024:**
  - **14 A:** Apply and explain the graph traversal algorithms (BFS & DFS) for the given graph. *(13)*
  - **14 B:** Find the shortest path for the given graph using Dijkstra's algorithm. *(13)*
- **Apr/May 2025:**
  - **14 A:** Use Dijkstra's algorithm to find the shortest path from source vertex A to all other vertices in the graph: A-B(1), A-C(4), B-C(2), B-D(5), C-D(1), D-E(3). *(13)*
  - **14 B:** Perform a Depth First Search (DFS) and Breadth First Search (BFS) on the given graph starting from vertex A. Show the order of traversal. *(13)*
- **Nov/Dec 2025:**
  - **14 A:** Implement Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms with examples. *(13)*
  - **14 B:** Apply Dijkstra's shortest path algorithm with an example. Show how distance values are updated iteratively to find shortest paths. *(13)*
- **Apr/May 2026:**
  - **14 A:** Apply Depth-First Search (DFS) and Breadth-First Search (BFS) algorithms to a graph. Write the procedure for each and demonstrate their execution with a suitable example. Show the order of node traversal for both algorithms. *(13)*
  - **14 B:** Apply an appropriate algorithm (Dijkstra's) to find the shortest path from 'A' to every other node for the given directed weighted graph. *(13)*

#### Part-C (15 Marks)
- **Apr/May 2024 (16 A):** Consider five cities (New Delhi, Mumbai, Chennai, Bangalore, Kolkata) and a list of flights with costs. Construct a graph and draw the minimum spanning tree using Kruskal's algorithm. *(15)*
- **Apr/May 2025 (16 A):** Given a weighted graph (5x5 adjacency matrix), apply Prim's algorithm to find the Minimum Spanning Tree. *(15)*
- **Apr/May 2025 (16 B):** Construct the adjacency list and adjacency matrix representations for the given directed graph and perform a topological sort. *(15)*

---

### UNIT V: SORTING AND HASHING
*Syllabus: Sequential search - Binary Search - Comparison and Analysis of searching - Types of sorting - Insertion Sort - Selection Sort - Bubble Sort - Quick Sort - Merge Sort - Radix Sort - Complexity analysis of sorting. Hashing: Hash Function, Collision Resolution Strategies.*

#### Part-A (2 Marks)
1. Differentiate Internal and External sorting. *(Apr/May 2024)*
2. Mention some methods for choosing the pivot element in quicksort? *(Nov/Dec 2024)*
3. What is the key idea behind bubble sort? *(Apr/May 2025)*
4. State the difference between sequential and binary search. *(Nov/Dec 2025)*
5. Differentiate between Selection sort and Bubble Sort. *(Apr/May 2026)*
6. Define hashing. *(Apr/May 2024)*
7. What is meant by hashing function? *(Nov/Dec 2024)*
8. Name any two collision resolution strategies. *(Apr/May 2025)*
9. List any two collision resolution strategies. *(Nov/Dec 2025)*
10. List any two collision resolution strategies. *(Apr/May 2026)*

#### Part-B (13 Marks — Q15 A & B)
- **Apr/May 2024:**
  - **15 A:** Write an algorithm to perform quick sort and analyse the best case complexity of it. Apply it to sort `24, 56, 47, 35, 10, 90, 82, 31`. *(13)*
  - **15 B:** Let us consider a simple hash function as "key mod 7" and sequence of keys as `50, 700, 76, 85, 92, 73, 101, 43, 4, 23, 9, 49, 26, 92, 77`. Construct the hash table using open addressing method and Closed addressing method. *(13)*
- **Nov/Dec 2024:**
  - **15 A:** Trace the algorithm for binary search to find the element 36 in the given list `3, 17, 36, 45, 40, 49, 52`. *(13)*
  - **15 B:** Given input `4371, 1323, 6173, 4199, 4344, 9679, 1989` and a hash function `h(X) = X (mod 10)`. Show the resulting: a) Separate chaining table, b) Open addressing hash table using linear probing, c) Open addressing hash table using Quadratic probing. *(13)*
- **Apr/May 2025:**
  - **15 A:** Explain and simulate one pass of quick sort on the array `[33, 15, 10, 99, 78, 65, 27, 5, 12, 45]` using the first element as the pivot. *(13)*
  - **15 B:** Explain hashing and demonstrate how collisions are handled using linear probing. Insert the keys `22, 42, 32, 52, 72, 62` into a hash table of size 5 using `h(k) = k mod 5`. *(13)*
- **Nov/Dec 2025:**
  - **15 A:** Explain quick sort algorithm with an example. Derive its best, average, and worst-case complexities. *(13)*
  - **15 B:** Explain in detail the following: a) Hash function design techniques (7), b) Collision handling methods (6). *(13)*
- **Apr/May 2026:**
  - **15 A:** Apply linear and binary search algorithms to a list of integers. Write the pseudocode for each algorithm and demonstrate their execution with sample input. Present the time complexity for best, average, and worst cases. *(13)*
  - **15 B:** Demonstrate Quick sort algorithm to sort the following set of numbers `42, 47, 52, 57, 62, 37, 27, 22`. List the time complexities, merits and demerits of the algorithm. *(13)*

#### Part-C (15 Marks)
- **Nov/Dec 2024 (16 A):** Explain the Quick sort algorithm and apply it to sort `42, 12, 8, 98, 67, 83, 104, 07`. Analyze the time efficiency of the same. *(15)*
- **Apr/May 2026 (16 A):** Given a hash table of size 10, insert keys `25, 35, 15, 20, 30, 45, 55` using division method (`mod 10`) and linear probing. Show final hash table, explain each step, and demonstrate how key 45 is searched. *(15)*

---

## 3. Shockingly Consistent Patterns Across All 5 Papers!

Look at how repetitive the paper setter's pattern is across every unit:

| Unit | Part-A Super-Repeats (2M) | Part-B Option A vs Option B Pattern (13M) |
| :--- | :--- | :--- |
| **Unit I** | **ADT definition** (4/5 papers!) + **Frequency count / Complexity** (4/5 papers!) | **Linked List Operations (SLL / CLL / Types)** is ALWAYS at least ONE option (5/5 papers!). The other option is either **Algorithm/Array Complexity** (3/5) or **Polynomial Addition** (2/5). |
| **Unit II** | **Stack basics/overflow/apps** (5/5) + **Circular Queue / Deque / Priority Queue** (5/5) | **Stack + Infix-to-Postfix / Postfix Evaluation** (5/5 papers!) vs **Queue / Circular Queue OR Tower of Hanoi**. |
| **Unit III** | **Max Heap vs Min Heap** (4/5 papers!) + **Height/Depth or Threaded BT** (5/5) | **Tree Traversals (In/Pre/Post) + BST Insertion/Deletion** (5/5 papers!) vs **AVL Tree Rotations & Insertion** (4/5 papers in Part-B, 1/5 in Part-C!). |
| **Unit IV** | **MST / Prim vs Kruskal** + **Warshall / Topological Sort / BFS vs DFS** | **BFS & DFS Graph Traversal** (4/5 papers!) vs **Dijkstra's Shortest Path Algorithm** (5/5 papers!! Dijkstra appeared in EVERY single paper!). |
| **Unit V** | **Collision resolution / Hashing** (5/5 papers!) + **Search/Sort comparison** | **Quick Sort / Binary Search** (5/5 papers! Quick Sort in 4/5 Part-B + 1/5 Part-C!) vs **Hashing & Collision Resolution (Linear/Quadratic/Chaining)** (4/5 in Part-B, 1/5 in Part-C!). |

---

## 4. Upcoming Exam Predictions (Nov/Dec 2026)

### Predicted Part-A (Top 10 Most Likely 2-Mark Questions)
1. **Unit I:** Define Abstract Data Type (ADT) with an example. / Differentiate between singly and doubly linked lists (or Array vs Linked List).
2. **Unit I:** Define Time Complexity and Space Complexity / Asymptotic notations ($O, \Omega, \Theta$) or Frequency count of a loop.
3. **Unit II:** Overflow & Underflow conditions in Stack / Applications of Stack.
4. **Unit II:** Define Circular Queue / Priority Queue / Double-Ended Queue (Deque) and its applications.
5. **Unit III:** Differentiate between Max Heap and Min Heap *(appeared 4 times in a row!)*.
6. **Unit III:** Threaded Binary Tree (need/advantages) OR Height & Depth of a Binary Tree.
7. **Unit IV:** Purpose of Warshall's Algorithm / Applications of Topological Sort.
8. **Unit IV:** Define Minimum Spanning Tree (MST) / Differences between BFS and DFS.
9. **Unit V:** List any two Collision Resolution Strategies in Hashing *(appeared 3 times in a row!)*.
10. **Unit V:** Sequential Search vs Binary Search / Pivot selection in Quick Sort / Merge vs Quick Sort.

### Predicted Part-B (5 × 13 Marks — Most Likely Pairs)
- **Q11 (Unit I):**
  - **Choice 1:** Linked List Operations — **Doubly Linked List** (overdue!) or **Singly / Circular Linked List** (Create, Insert at front/middle/end, Delete, Display).
  - **Choice 2:** **Time & Space Complexity / Frequency Count Analysis** (with array algorithm) OR **Polynomial Representation & Addition using Linked List**.
- **Q12 (Unit II):**
  - **Choice 1:** **Infix to Postfix Conversion + Postfix Evaluation** using Stack (with trace).
  - **Choice 2:** **Circular Queue / Deque / Priority Queue** implementation (Insert/Delete) OR **Tower of Hanoi** recursion trace.
- **Q13 (Unit III):**
  - **Choice 1:** **Binary Tree Traversals (Inorder, Preorder, Postorder)** + **BST Construction & Deletion**.
  - **Choice 2:** **AVL Tree Insertion & Rotations (LL, RR, LR, RL)** step-by-step problem.
- **Q14 (Unit IV):**
  - **Choice 1:** **BFS and DFS Graph Traversal** (algorithm + trace on given graph).
  - **Choice 2:** **Dijkstra's Shortest Path Algorithm** (or **Prim's/Kruskal's MST**).
- **Q15 (Unit V):**
  - **Choice 1:** **Quick Sort** (or Merge Sort) trace + Best/Average/Worst case complexity.
  - **Choice 2:** **Hashing & Collision Resolution** (Separate Chaining, Linear Probing, Quadratic Probing problem with `h(k) = k mod m`).

### Predicted Part-C (1 × 15 Marks — Top Candidates)
- **Prim's or Kruskal's MST** problem on a weighted graph / city matrix (since Apr/May 2026 had Hashing & B-Tree, MST is due back in Part-C!).
- **Huffman Coding Tree** construction OR **Min/Max Heap** insertion & delete-min OR **AVL / B-Tree** construction.
- **Hashing Collision Resolution** (Linear + Quadratic + Separate Chaining) or **Polynomial Addition**.

---

## 5. Deep-Dive Strategy for UNIT I (Q11): Minimum Study to GUARANTEE Attending 1 Choice in Part-B

Let's look at the exact **Q11 (A vs B)** pairing across all 5 past papers:

| Exam | Q11 (A) | Q11 (B) |
| :--- | :--- | :--- |
| **Apr/May 2024** | **Singly Linked List** (Insertion at start, middle, end) | **Polynomial Representation & Addition** using Linked List |
| **Nov/Dec 2024** | **Circular Linked List** (Create, Insert, Delete with pointers) | Algorithm for Max in Array + Time Efficiency Analysis |
| **Apr/May 2025** | Time & Space Complexity with examples | **Types of Linked Lists** (SLL, DLL, CLL) with diagrams & structure |
| **Nov/Dec 2025** | Algorithm to Reverse an Array + Time Complexity | **Singly Linked List** (Diagram, Algorithm & Example for Insertion & Deletion) |
| **Apr/May 2026** | **Singly Linked List** (Create, Insert & Delete at front, rear, position) | **Polynomial Representation & Addition** using Singly Linked List |

### Key Proof from the Table:
Notice that **100% of the time (5 out of 5 papers)**, **AT LEAST ONE** (and sometimes BOTH!) of Q11A and Q11B comes from the **Linked Lists half** of Unit 1!
- Specifically, **Algorithm Analysis + Arrays** was NEVER asked in both A and B together. Whenever an Array/Complexity question appeared (Nov/Dec 24, Apr/May 25, Nov/Dec 25), the other choice was **always a Linked List question**.
- And when Linked Lists appeared in BOTH choices (Apr/May 24 & Apr/May 26), Choice A was **Linked List Operations (Insert/Delete)** and Choice B was **Polynomial Addition using Linked List**.

### Therefore: What You MUST Study in Chapter 1 to 100% Guarantee 1 Part-B Question (Without Studying the Whole Unit)

Skip studying complex random array-manipulation algorithms if you want to save time! Instead, master **ONLY the Linked List cluster** (which is essentially one connected concept). Specifically, study these **4 closely connected sub-topics**:

1. **Singly Linked List (SLL) – Complete Operations [HIGHEST PRIORITY – Asked 4/5 times]**
   - Node structure (`data`, `next`), diagram with `head` pointer.
   - Algorithm / C routine for:
     - Creation & Display (`traverse`)
     - **Insertion** at Beginning (Front), End (Rear), and Given Position (Middle).
     - **Deletion** at Beginning, End, and Given Position/Element.
2. **Doubly Linked List (DLL) & Circular Linked List (CLL) – Operations & Diagrams [HIGH PRIORITY]**
   - Node structure (`prev`, `data`, `next` for DLL; `last->next = head` for CLL).
   - How Insertion and Deletion pointers change in **Circular Linked List** (asked in Nov/Dec 2024 & Apr/May 2024) and **Doubly Linked List** *(DLL hasn't been asked as a full 13-mark yet, making it a prime target for the upcoming exam!)*.
   - Note: Once you know SLL insert/delete, CLL and DLL are just 2 extra pointer updates — and this also covers the *"Describe different types of linked lists with diagrams"* question (Apr/May 2025)!
3. **Linked List Application: Polynomial Representation & Addition [SAFETY NET + PART-C BONUS]**
   - Node structure (`coeff`, `exp`, `next`).
   - Algorithm for adding two polynomials `P1` and `P2` (comparing exponents: `p1->exp == p2->exp`, `>`, `<`).
   - Practice 1 numerical trace (e.g., $(5x^4 + 3x^2 + 2) + (4x^3 + 2x^2 + 1)$).
   - *Why include this?* Even if Q11A asks Doubly Linked List and Q11B asks Polynomial Addition, you can pick whichever is easier — PLUS Polynomial Addition also appears as a **15-mark Part-C question** (like in Nov/Dec 2025)!

*(Optional 10-minute read for Part-A 2 Marks only)*: Just memorize the 3-line definitions of **ADT (Abstract Data Type)**, **Frequency Count**, and **Time vs Space Complexity** so you don't lose the 4 marks in Part-A (Q1 & Q2). You do **not** need to prepare long 13-mark derivations on Algorithm Analysis / Array programs if you thoroughly master **Linked Lists (SLL, DLL, CLL) + Polynomial Addition**.
