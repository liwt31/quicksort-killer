# quicksort-killer
Exploration of quicksort and its killer in jupyter-notebook

The notebook is inspired by [*A Killer Adversary for Quicksort*](https://www.cs.dartmouth.edu/~doug/mdmspe.pdf), which introduces a simple yet very efficient algorithm for compare function to make almost any pure quicksort implementation under their worst case O(N^2).

The notebook can be separated into several parts:
1. A simple quicksort implementation, which works as O(N^2) at sorted data, to warm up.
2. Implement the widely used median of 3 quicksort which performs well at sorted data. The algorithm still have weaknesses, so an artificial killer for the implementation is devised.
3. Introduce the automatic quicksort killer which can beat not only median of 3 pivot but also median of random 3 pivot.
