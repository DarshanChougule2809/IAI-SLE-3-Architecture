# CONTRIBUTION LOG

## SLE-3: BFS vs DFS Grid Search – C4 Architecture

**Student:** Darshan Jivandhar Chougule
**PRN:** 25UAM077
**Course:** 02AML204 – Introduction to Artificial Intelligence
**Division:** B

## 1. Project Contribution

I worked on the SLE-3 architectural design based on my existing SLE-1 and SLE-2 work. The project focuses on comparing BFS and DFS on a 20×20 grid.

My main contribution was understanding the existing implementation and representing it using the **C4 Model**.

## 2. Work Completed

### Understanding the Existing System

* Reviewed the BFS and DFS grid-search implementation.
* Understood the fixed 20×20 grid.
* Identified the start position as `(0,0)` and goal position as `(19,19)`.
* Studied how the program searches for a path.

### BFS and DFS Analysis

* Understood BFS as a queue-based search.
* Understood DFS as a stack-based search.
* Compared the role of the visited set and parent map.
* Understood how the path can be reconstructed from the parent information.

### Performance Profiling

* Reviewed the execution-time profiling approach.
* Understood the use of `timeit` for repeated timing.
* Compared the purpose of measuring path length, nodes expanded, and execution time.

### C4 Architecture

I converted the existing system into four C4 levels:

**Level 1 – Context:**
Shows the user interacting with the grid-search system.

**Level 2 – Container:**
Shows the grid configuration, neighbor module, BFS engine, DFS engine, profiler, and output module.

**Level 3 – Component:**
Explains the internal search components such as the frontier, visited set, goal test, and parent map.

**Level 4 – Code:**
Maps the architecture to the main Python functions such as `valid_neighbors()`, `bfs_search()`, `dfs_search()`, `run_profiling()`, and `main()`.

## 3. AI Contribution

**AI Tool Used:** ChatGPT / AI assistance

AI assistance was used for:

* Understanding the C4 architectural model.
* Organizing the existing BFS/DFS implementation into C4 levels.
* Improving the explanation of system components.
* Preparing concise README and contribution documentation.
* Improving the presentation of design decisions.

The uploaded SLE-3 report also identifies AI assistance for understanding the C4 model, organizing the architecture, and preparing documentation.

## 4. My Individual Contribution

I:

* Provided and worked with my existing SLE-1/SLE-2 project.
* Studied the BFS and DFS implementation.
* Understood the grid-search workflow.
* Reviewed the profiling approach.
* Connected the implementation with the C4 architecture.
* Prepared the SLE-3 documentation.
* Checked the architecture and explanations before submission.

## 5. Learning Outcome

Through this activity, I learned how to convert an existing software implementation into a structured architectural model. I also improved my understanding of BFS, DFS, performance profiling, and the relationship between software architecture and implementation.

## 6. Final Result

The SLE-3 work successfully represents the BFS-vs-DFS grid-search system using the complete C4 architecture. The architecture connects the user interaction, grid handling, search algorithms, performance profiler, and Python implementation into one structured design.

## 7. Declaration

I confirm that I understood the project implementation and used AI assistance only as a supporting tool for architectural understanding, documentation, and explanation. I reviewed the generated content and will verify the final implementation and diagrams before submission.
