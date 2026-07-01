# Rosalind – Eulerian Path (BA3G)

Python solution to the **BA3G: Eulerian Path** problem from the Rosalind Bioinformatics Textbook Track.

## Problem Description

Given the adjacency list of a directed graph that contains an Eulerian path, determine and output one valid Eulerian path.

This problem is part of the **Genome Assembly** chapter, where Eulerian paths are used to reconstruct sequences from graph representations such as de Bruijn graphs.

## Algorithm

The solution implements **Hierholzer's Algorithm** to efficiently construct an Eulerian path by:

1. Computing the in-degree and out-degree of every node.
2. Identifying the correct start and end nodes.
3. Traversing the graph while removing edges.
4. Constructing the Eulerian path in reverse order.
5. Outputting the final path in the required format.

## Technologies

- Python
- Graph Algorithms
- Eulerian Path
- Genome Assembly
- Bioinformatics


## How to Run

```bash
python solution.py
```

## Input Format

The input consists of a directed graph represented as an adjacency list:

```
0 -> 2
1 -> 3
2 -> 1
3 -> 0,4
...
```

## Output Format

A valid Eulerian path represented as:

```
6->7->8->9->...
```

## Concepts Covered

- Directed Graphs
- Eulerian Path
- Hierholzer's Algorithm
- Graph Traversal
- Genome Assembly

## Source

- Rosalind Textbook Track – BA3G: Eulerian Path
- https://rosalind.info/problems/ba3g/

## License

This repository is intended for educational purposes.
