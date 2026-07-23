# 🗓️ 40-Day DSA Sprint · Jul 23 – Aug 30, 2026

**Rule:** minimum 1 problem/day (40 floor) · target **60+**. Tick the boxes as you commit.
**Order matters** — each phase builds on the previous one (recursion before trees, pointers before stacks-in-C, etc.).

**Prerequisite (Day 0–1, ~2 hrs):** Big-O notation — time & space complexity. You cannot judge your own solutions without it.
📖 [Big-O Cheat Sheet](https://www.bigocheatsheet.com/) · 🎥 Abdul Bari — "1.5 Time Complexity" (YouTube)

---

## Phase 1 · Arrays, Hashing & Sorting — Jul 23 → Jul 30 (12 problems)

Learn alongside: hashing (hash maps), prefix sums, Kadane's algorithm, and **implement Bubble, Selection, Insertion, Merge & Quick Sort by hand in C before using any library sort**.

**Easy**
- [ ] 1 · Two Sum *(hash map fundamentals)*
- [ ] 217 · Contains Duplicate
- [ ] 283 · Move Zeroes
- [ ] 121 · Best Time to Buy and Sell Stock

**Medium**
- [ ] 53 · Maximum Subarray *(Kadane's)*
- [ ] 189 · Rotate Array
- [ ] 15 · 3Sum
- [ ] 75 · Sort Colors *(Dutch National Flag)*
- [ ] 912 · Sort an Array *(write Merge Sort AND Quick Sort yourself)*

**Hard**
- [ ] 42 · Trapping Rain Water
- [ ] 41 · First Missing Positive
- [ ] 4 · Median of Two Sorted Arrays

---

## Phase 2 · Recursion & Backtracking — Jul 31 → Aug 4 (7 problems)

Learn alongside: call stack mental model, recursion trees, base cases, backtracking template. This phase unlocks Trees later — do not rush it.

- [ ] 50 · Pow(x, n) *(Medium — recursion + divide & conquer)*
- [ ] 78 · Subsets *(Medium)*
- [ ] 46 · Permutations *(Medium)*
- [ ] 39 · Combination Sum *(Medium)*
- [ ] 22 · Generate Parentheses *(Medium)*
- [ ] 79 · Word Search *(Medium)*
- [ ] 51 · N-Queens *(Hard — the classic backtracking boss fight)*

---

## Phase 3 · Pointers & Linked Lists — Aug 5 → Aug 9 (8 problems)

Learn alongside: C pointers (`*`, `&`, `malloc/free`, pointer-to-pointer), the **two-pointer technique**, and **fast & slow pointers (Floyd's cycle detection)**. As a C programmer this is your superpower phase.

- [ ] 206 · Reverse Linked List *(Easy — do it iteratively AND recursively)*
- [ ] 141 · Linked List Cycle *(Easy — fast/slow pointers)*
- [ ] 876 · Middle of the Linked List *(Easy)*
- [ ] 21 · Merge Two Sorted Lists *(Easy)*
- [ ] 11 · Container With Most Water *(Medium — two pointers on arrays)*
- [ ] 19 · Remove Nth Node From End *(Medium)*
- [ ] 2 · Add Two Numbers *(Medium)*
- [ ] 25 · Reverse Nodes in k-Group *(Hard)*

---

## Phase 4 · Stacks & Queues — Aug 10 → Aug 14 (8 problems)

Learn alongside: implement stack & queue from scratch in C (array + linked list versions), monotonic stacks, deques.

- [ ] 20 · Valid Parentheses *(Easy)*
- [ ] 232 · Implement Queue using Stacks *(Easy)*
- [ ] 225 · Implement Stack using Queues *(Easy)*
- [ ] 155 · Min Stack *(Medium)*
- [ ] 496 · Next Greater Element I *(Easy — first monotonic stack)*
- [ ] 739 · Daily Temperatures *(Medium — monotonic stack)*
- [ ] 84 · Largest Rectangle in Histogram *(Hard)*
- [ ] 239 · Sliding Window Maximum *(Hard — monotonic deque)*

---

## Phase 5 · Heaps / Priority Queues — Aug 15 → Aug 18 (6 problems)

Learn alongside: heap as an array, heapify, Heap Sort, and C++ `priority_queue` (this is where switching to C++ pays off massively).

- [ ] 703 · Kth Largest Element in a Stream *(Easy)*
- [ ] 215 · Kth Largest Element in an Array *(Medium)*
- [ ] 347 · Top K Frequent Elements *(Medium)*
- [ ] 973 · K Closest Points to Origin *(Medium)*
- [ ] 23 · Merge k Sorted Lists *(Hard)*
- [ ] 295 · Find Median from Data Stream *(Hard — two heaps pattern)*

---

## Phase 6 · Trees — Aug 19 → Aug 26 (10 problems)

Learn alongside: binary trees vs BSTs, DFS traversals (pre/in/post-order), BFS (level order), recursion on trees.

- [ ] 104 · Maximum Depth of Binary Tree *(Easy)*
- [ ] 226 · Invert Binary Tree *(Easy)*
- [ ] 100 · Same Tree *(Easy)*
- [ ] 94 · Binary Tree Inorder Traversal *(Easy — also do 144 & 145 quickly)*
- [ ] 102 · Binary Tree Level Order Traversal *(Medium — BFS)*
- [ ] 98 · Validate Binary Search Tree *(Medium)*
- [ ] 235 · Lowest Common Ancestor of a BST *(Medium)*
- [ ] 105 · Construct Binary Tree from Preorder & Inorder *(Medium)*
- [ ] 124 · Binary Tree Maximum Path Sum *(Hard)*
- [ ] 297 · Serialize and Deserialize Binary Tree *(Hard)*

---

## Phase 7 · Graphs + Revision — Aug 27 → Aug 30 (7 problems)

Learn alongside: adjacency list vs matrix, BFS/DFS on graphs, topological sort. (Graphs deserve more time — treat this as an introduction and continue after the sprint.)

- [ ] 733 · Flood Fill *(Easy)*
- [ ] 200 · Number of Islands *(Medium)*
- [ ] 547 · Number of Provinces *(Medium)*
- [ ] 994 · Rotting Oranges *(Medium — multi-source BFS)*
- [ ] 133 · Clone Graph *(Medium)*
- [ ] 207 · Course Schedule *(Medium — topological sort)*
- [ ] 127 · Word Ladder *(Hard)*

**Final day:** re-solve 3–4 problems you struggled with, from a blank editor, without notes.

---

## 📚 Core Resources (all free)

| Resource | Use it for | Link |
|----------|-----------|------|
| **Striver's A2Z DSA Sheet** (takeuforward) | Primary structured course — theory articles + video + problems per topic, C++ | [takeuforward.org](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2/) |
| **NeetCode Roadmap & 150** | Pattern-wise problem lists with the best short video explanations | [neetcode.io/roadmap](https://neetcode.io/roadmap) |
| **Abdul Bari — Algorithms** (YouTube) | Deep theory: recursion, sorting, heaps, trees, graphs | Search "Abdul Bari Algorithms playlist" |
| **mycodeschool** (YouTube) | THE pointers & linked-lists-in-C playlists — perfect for a C programmer | Search "mycodeschool pointers in C" |
| **VisuAlgo** | Animated visualizations of sorting, heaps, BSTs, graph traversals | [visualgo.net](https://visualgo.net) |
| **LeetCode Explore Cards** | Arrays 101, Queue & Stack, Binary Tree, Heap — guided mini-courses | leetcode.com/explore |
| **GeeksforGeeks** | C implementations of every data structure when you get stuck | [geeksforgeeks.org](https://www.geeksforgeeks.org/dsa-tutorial-learn-data-structures-and-algorithms/) |
| **Big-O Cheat Sheet** | Complexity reference for every structure & sort | [bigocheatsheet.com](https://www.bigocheatsheet.com/) |

## ⚔️ Daily Protocol

1. **Theory first (30–40 min):** watch/read the concept for today's topic (Striver article or Abdul Bari video), visualize it on VisuAlgo.
2. **Solve (60–90 min):** attempt for 30–40 min *before* looking at any hint. Stuck → read the approach only, close it, implement yourself.
3. **Write it up (15 min):** fill the solution README (approach, complexity, edge cases) and commit.
4. **Never copy-paste a solution.** If you saw the answer, re-code it from memory the next morning.
