# Data Structures & Algorithms Cheat Sheet

This repository is a structured reference to learn and practice algorithms and data structures.

Languages covered (in order of study):

1. Python
2. Java
3. JavaScript
4. C

The goal of this project is to:

- understand each algorithm type
- know when to use it
- recognize problem patterns
- practice solutions by level: Beginner, Intermediate, Advanced

---

## 📌 Levels

### 🟢 Beginner

Focus: fundamentals, time complexity, basic data structures

Includes:

- Arrays
- Strings
- Hash Maps / Hash Sets
- Stacks and Queues
- Basic recursion
- Simple searching & sorting

### 🟡 Intermediate

Focus: problem patterns and optimization

Includes:

- Two pointers
- Sliding window
- Linked lists
- Trees (basics)
- Graphs (BFS & DFS)
- Backtracking
- Greedy algorithms

### 🔴 Advanced

Focus: high-level algorithmic thinking

Includes:

- Dynamic programming
- Advanced graph algorithms
- Tries and heaps
- Segment trees
- Union–Find (DSU)
- Complexity optimization

---

## ⏱ Time & Space Complexity Cheatsheet

| Operation    | Big-O      |
| ------------ | ---------- |
| Constant     | O(1)       |
| Logarithmic  | O(log n)   |
| Linear       | O(n)       |
| Linearithmic | O(n log n) |
| Quadratic    | O(n²)      |
| Exponential  | O(2ⁿ)      |
| Factorial    | O(n!)      |

---

# 🟢 Beginner Level

## 1. Arrays

**When to use**

- collection of ordered data
- indexing matters
- contiguous memory

**Common patterns**

- iteration
- two pointers (intro)
- prefix sum

**Example problems**

- Find max element
- Reverse array
- Remove duplicates

### Python Example

```python
def find_max(arr):
    return max(arr)

```

### Java Example

```java
intfindMax(int[] arr) {
intmax= arr[0];
for (int n : arr)if (n > max) max = n;
return max;
}

```

### JavaScript Example

```jsx
functionfindMax(arr) {
returnMath.max(...arr);
}

```

### C Example

```c
intfindMax(int arr[],int n) {
int max = arr[0];
for(int i=0;i<n;i++)
if(arr[i]>max) max = arr[i];
return max;
}

```

---

## 2. Strings

**When to use**

- text manipulation
- pattern matching

**Patterns**

- frequency counting
- two-pointer substrings
- palindrome checks

---

# 🟡 Intermediate Level

## 1. Sliding Window

**Use when**

- substring / subarray with condition
- “longest”, “shortest”, “count of”

**Idea**

- expand right pointer
- shrink left pointer

---

## 2. Linked Lists

**Use when**

- frequent insert/delete
- sequential memory not required

---

# 🔴 Advanced Level

## 1. Dynamic Programming

**Use when**

- “maximum/minimum number of ways”
- overlapping subproblems
- optimal substructure

**Techniques**

- top-down memoization
- bottom-up tabulation

---

# 🧠 Problem Bank

Track solved problems here:

| Level        | Category       | Problem           | Source     | Language |
| ------------ | -------------- | ----------------- | ---------- | -------- |
| Beginner     | Array          | Two Sum           | LeetCode   | Python   |
| Intermediate | Sliding Window | Longest Substring | LeetCode   | Java     |
| Advanced     | DP             | Coin Change       | HackerRank | C        |

---

# 🛠 Platforms Used

- HackerRank — learning tracks
- LeetCode — problem practice

---

# ✅ How I Study

1. Read concept
2. Write pseudocode
3. Implement in **Python**
4. Rewrite in **Java**
5. Rewrite in **JavaScript**
6. Rewrite in **C**
7. Add notes to cheat sheet

---

# 🚀 Goals

- Build full mapping of algorithm categories
- Solve 300+ problems across 4 languages
- Recognize patterns instantly
- Prepare for technical interviews

```

---

## Next, I can help you with any of the following

Tell me which you want next:

1. Create**repository name & description**
2. Generate**badges and table of contents**
3. Add**first filled sections** for arrays and strings
4. Provide**30-day structured practice plan**
5. Provide**list of specific LeetCode + HackerRank problems**

Just tell me:

- Do you want me to add more content into this README now?
- Or do you want help creating the GitHub repo description and tags?
```
