# CMPS 2200 Recitation 09

## Answers

**Name:**Viraj Choksi
**Name:**_________________________


Place all written answers from `recitation-09.md` here for easier grading.



- **2)** Worst-case work:
Each component runs Prim’s algorithm once. Prim’s algorithm using a heap (priority queue) runs in O(E log V) time.
If the full graph has V nodes, E edges, and k components, total work across all components: O(E log V)

- **4)** There are n points → O(n^2) pairs → O(n^2) edges.
Prim's algorithm on complete graph:
V = n, E = n(n-1)/2 = O(n^2)
So work is O(n^2 log n).
