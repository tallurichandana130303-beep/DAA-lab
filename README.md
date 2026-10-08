# Practical 1: Sorting Algorithms

This practical implements Selection Sort, Bubble Sort, and Merge Sort, insertion sort, quick sort 
Each algorithm includes implementation, time complexity analysis (best, worst, and average cases), and execution time measurement.

# Practical 2: Linear Search

This practical implements the Linear Search algorithm with interactive user input.
It demonstrates:
- Implementation of linear search that returns the index of the target (or -1 if not found).
- Measurement of execution time using `time.perf_counter()`.
- Time complexity analysis (Best, Average, Worst cases).

Usage:
- Interactive: run the script and follow prompts to provide the list and target value.
- Demo: run the script with a demo flag (if provided in the script).
1. linear search 
2. binary search 



# Practical 3: Max-Heap and Min-Heap Sort

Aim

To implement Min-Heap and Max-Heap Sort in Python.

Description
Min-Heap Sort: Sorts elements in ascending order.
Max-Heap Sort: Sorts elements in descending order.
Execution time is measured using time.perf_counter().
Time Complexity
Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)
Conclusion

Min-Heap and Max-Heap Sort were successfully implemented to sort elements in ascending and descending order respectively.


# Practical 4: Factorial Using Iterative and Recursive Function
Description

This Python program calculates the factorial of a non-negative integer using two methods:

Iterative method Recursive method

It also compares the execution time and complexity of both methods.

Example

Input:

Enter a non-negative integer: 5

Output:

Number: 5

Iterative Method: Factorial: 120 Execution Time: 0.0000012000 seconds Time Complexity: O(n) Space Complexity: O(1)

Recursive Method: Factorial: 120 Execution Time: 0.0000015000 seconds Time Complexity: O(n) Space Complexity: O(n)

Complexity Method Time Space Iterative O(n) O(1) Recursive O(n) O(n) Requirements Python 3.x Run python factorial.py

Conclusion

Both methods produce the same factorial result. The iterative method uses less memory, while the recursive method demonstrates the use of recursion.

# practical-5: Knapsack Problem
This project is a Python program that solves the 0/1 Knapsack Problem using Dynamic Programming. The program takes the number of items, their weights, values, and the maximum capacity of the knapsack as input. It then finds the maximum value that can be carried without exceeding the given capacity. The program also displays the selected items and the execution time. This project is simple and useful for understanding the basic concept of Dynamic Programming in Python.

How to Run

To run the program, make sure Python 3 is installed on your computer. Save the code in a file named knapsack.py and run it using the command python knapsack.py in the terminal.

Example

For 4 items with weights 2, 3, 4, 5 and values 3, 4, 5, 6, with a knapsack capacity of 5, the maximum value is 7 and items 1 and 2 are selected.

Conclusion

This project demonstrates how Dynamic Programming can be used to solve the 0/1 Knapsack Problem. It helps in finding the best combination of items while keeping the total weight within the given capacity. The project is simple and helpful for learning Python and Dynamic Programming.

# PRACTICAL-6 MATRIX CHAIN MULTIPLICATION
Matrix Chain Multiplication is a Dynamic Programming problem that finds the most efficient way to multiply a sequence of matrices.

The main objective is to determine the optimal order of matrix multiplication that minimizes the total number of scalar multiplications. The order of the matrices remains unchanged; only the placement of parentheses is optimized.

This project implements the Matrix Chain Multiplication algorithm using Python and Dynamic Programming.




# practical-7 Coin Change Problem Using Dynamic Programming

This project provides a Python solution to the Coin Change Problem using Dynamic Programming. The program determines the minimum number of coins required to make a given target amount from a set of available coin denominations.

The algorithm builds a dynamic programming table to store the minimum coins needed for every amount from `0` to the target value. By reusing previously computed results, it efficiently finds the optimal solution and avoids redundant calculations.

If the target amount can be formed, the program returns the minimum number of coins required. Otherwise, it returns `-1` to indicate that no valid combination exists.

### Features

* Efficient Dynamic Programming approach
* Finds the minimum number of coins required
* Handles impossible cases by returning `-1`
* Simple and easy-to-understand Python implementation

### Complexity

* **Time Complexity:** O(n × amount)
* **Space Complexity:** O(amount)

This project is useful for learning Dynamic Programming concepts, practicing algorithm design, and preparing for coding interviews.

# PRACT8-(DAA)
SUMMARY :

Graph traversal is an important technique used to visit all the vertices of a graph systematically. DFS explores a graph deeply by visiting a vertex and then recursively visiting its unvisited neighbors. BFS explores the graph level by level using a queue data structure. Both DFS and BFS have a time complexity of O(V + E), where V is the number of vertices and E is the number of edges. These searching techniques are widely used in path finding, network analysis, and many other computer science applications.

CONCLUSION :

The graph traversal program successfully implements both DFS and BFS searching techniques using Python. DFS uses a depth-based approach, while BFS visits vertices level by level. Both methods efficiently traverse the vertices and edges of a graph. The program accepts user input, making it flexible for different graph structures and starting vertices. Thus, DFS and BFS are useful and fundamental techniques for solving various graph-based problems.
# PRACTICAL 8 implementation of graph and searching (DFS and BFS)
# Graph Traversal – DFS and BFS

This project implements a **Graph** using an adjacency matrix and performs two graph traversal techniques:

- **DFS (Depth First Search)**
- **BFS (Breadth First Search)**

### Features
- Creates a graph using vertices and edges.
- Traverses the graph using DFS.
- Traverses the graph using BFS.
- Written in **C**.

### Complexity
- DFS: **O(V²)**
- BFS: **O(V²)**
- Space: **O(V²)**

### Example Output
```text
DFS: 0 1 3 4 2
BFS: 0 1 2 3 4
```
# PRACTICAL 9 Implement prim 's alogiratham
# Prim's Algorithm

This project implements **Prim's Algorithm** in Python to find the **Minimum Spanning Tree (MST)** of a weighted graph.

### Features
- Uses a cost/adjacency matrix.
- Finds the Minimum Spanning Tree.
- Displays selected edges and minimum total cost.
- Written in **Python**.

### Complexity
- Time Complexity: **O(V²)**
- Space Complexity: **O(V²)**

### Example Output
```text
Edges in Minimum Spanning Tree:
0 - 1 : 2
1 - 2 : 1
1 - 3 : 4
Minimum cost = 7
```
# implement kruskail's algoritham
# Kruskal's Algorithm

## Description
This project implements **Kruskal's Algorithm** in Python to find the **Minimum Spanning Tree (MST)** of a weighted, undirected graph.

## Features
- Sorts edges by weight.
- Uses **Union-Find (Disjoint Set)** to detect cycles.
- Constructs the Minimum Spanning Tree.
- Calculates the total weight of the MST.

## Algorithm
1. Sort all edges by increasing weight.
2. Select the smallest edge.
3. Check for a cycle using Union-Find.
4. Add the edge if it does not create a cycle.
5. Continue until the MST contains `V-1` edges.

## Complexity
- Time: `O(E log E)`
- Space: `O(V + E)`

## Language
- Python 3
# write a program for Floyd - Warshal algoritham
# Floyd–Warshall Algorithm

## Description
This project implements the Floyd–Warshall algorithm in Python to find the shortest distances between all pairs of vertices in a weighted graph.

## Algorithm
1. Initialize the distance matrix.
2. Consider each vertex as an intermediate vertex.
3. Update the shortest distances between all pairs of vertices.
4. Display the final shortest distance matrix.

## Time Complexity
`O(V³)`

## Space Complexity
`O(V²)`

## Language
Python 3

## Applications
- Network routing
- Shortest path problems
- Graph analysis
# write a program for traveling salesman
# Traveling Salesman Problem (TSP)

## Description
This project implements the Traveling Salesman Problem in Python using the brute-force approach to find the minimum-cost route that visits every city exactly once and returns to the starting city.

## Algorithm
1. Select the starting city.
2. Generate all possible routes.
3. Calculate the total cost of each route.
4. Find and display the route with the minimum cost.

## Time Complexity
`O(n!)`

## Space Complexity
`O(n)`, excluding the input graph.

## Language
Python 3

## Applications
- Route optimization
- Delivery planning
- Transportation and logistics
