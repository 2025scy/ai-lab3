# AI Lab 3: BFS and DFS Graph Traversal

This repository contains my Artificial Intelligence Lab 3 work, written in Python (Jupyter Notebook).

It implements two basic graph search algorithms:

- **BFS (Breadth-First Search):** visits nodes level by level using a queue.
- **DFS (Depth-First Search):** goes as deep as possible along each branch first, using recursion.

## File

`lab3.ipynb`

## What the Notebook Contains

| Cell | Algorithm | Graph | Start Node | Output |
|------|-----------|-------|------------|--------|
| 1 | BFS | Numbered graph (0 to 13) | 3 | `3 1 2 4 7 0 10 6 5 8 12 9 11 13` |
| 2 | BFS | Letter tree (A to G) | A | `A B C D E F G` |
| 3 | DFS | Numbered graph (0 to 13) | 3 | `3 1 0 2 10 11 6 4 5 8 12 13 7 9` |
| 4 | DFS | Letter tree (A to G) | A | `A B D E C F G` |

## How the Graph Is Stored

The graph is a Python dictionary (adjacency list). Each key is a node, and its value is the list of nodes it connects to:

```python
graph = {
    'A': ['B', 'C'],
    'B': ['D', 'E'],
    'C': ['F', 'G'],
    'D': [], 'E': [], 'F': [], 'G': []
}
```

## How to Run

1. Install Python 3 and Jupyter Notebook:
   ```
   pip install notebook
   ```
2. Open the notebook:
   ```
   jupyter notebook lab3.ipynb
   ```
   You can also open it in VS Code with the Jupyter extension.
3. Run each cell with **Shift + Enter**.

## Tools Used

- Python
- Jupyter Notebook
- VS Code
- Git and GitHub

## Author

GitHub: [2025scy](https://github.com/2025scy)
