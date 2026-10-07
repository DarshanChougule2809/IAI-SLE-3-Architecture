# SLE-3: BFS vs DFS Grid Search

## Project Title

**Performance Comparison of BFS and DFS on a 20×20 Grid**

## Course

**02AML204 – Introduction to Artificial Intelligence**
**SY B.Tech. CSE (AI & ML) – SEM-VI**

**Student:** Darshan Jivandhar Chougule
**PRN:** 25UAM077
**Division:** B

## 1. Project Description

This project implements and compares two uninformed search algorithms:

* Breadth-First Search (BFS)
* Depth-First Search (DFS)

Both algorithms are applied to the same **20×20 grid** to find a path from the fixed start position **(0,0)** to the fixed goal position **(19,19)**.

The system checks the correctness of the search results by recording the **path length** and **nodes expanded**. It also performs repeated execution-time measurements to compare the practical performance of BFS and DFS.

## 2. Objectives

* Implement BFS and DFS for grid-based path finding.
* Use the same grid and start/goal positions for both algorithms.
* Compare path length and nodes expanded.
* Measure execution time using repeated experiments.
* Understand the practical difference between queue-based BFS and stack-based DFS.
* Represent the complete system using the C4 architectural model.

## 3. System Structure

The project is organized into the following major parts:

### Grid Configuration

Stores:

* Grid dimensions
* Start position
* Goal position
* Blocked and free cells

### Neighbor Module

Checks valid neighboring cells while considering grid boundaries and blocked cells.

### BFS Search Engine

Uses:

* FIFO queue
* Visited set
* Parent map

BFS searches the grid level by level.

### DFS Search Engine

Uses:

* LIFO stack
* Visited set
* Parent map

DFS explores the grid depth-first.

### Performance Profiler

Runs correctness checks and repeated timing experiments using Python's `timeit` and `statistics` modules.

### Output Module

Displays:

* Path length
* Nodes expanded
* Execution time
* BFS vs DFS comparison

## 4. Main Functions

```text
valid_neighbors(node)
bfs_search()
dfs_search()
run_profiling()
main()
```

`valid_neighbors()` generates valid free neighboring cells.

`bfs_search()` performs Breadth-First Search.

`dfs_search()` performs Depth-First Search.

`run_profiling()` performs correctness checks and timing experiments.

`main()` provides the program menu and starts the selected operation.

## 5. Performance Profiling

The profiling process performs **5 × 5000 timing experiments** to obtain repeated execution-time measurements.

The same input grid is used for both algorithms so that the comparison is fair and consistent.

## 6. Technologies Used

* **Programming Language:** Python
* **Algorithms:** BFS and DFS
* **Profiling:** `timeit`, `statistics`
* **Architecture:** C4 Model
* **Repository:** GitHub

## 7. Expected Learning Outcome

After completing this SLE, the student understands:

* How BFS and DFS work on a grid.
* How queue and stack structures affect search behavior.
* How search results can be measured using path length and nodes expanded.
* How execution time can be experimentally compared.
* How an existing implementation can be represented using the C4 architecture.

## 8. Conclusion

The project provides a practical comparison of BFS and DFS on a fixed 20×20 grid. It connects algorithm implementation with performance profiling and software architecture, demonstrating how the same search problem can be analyzed from both an algorithmic and architectural perspective.
