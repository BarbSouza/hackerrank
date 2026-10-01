# 🧩 HackerRank Practice

My solutions to HackerRank coding challenges, written in Python in Jupyter notebooks. I use this repository to practise problem solving and to show how I improve a solution step by step, not just the final answer.

## How each notebook is organised

Each notebook keeps my attempts in order, so you can see the thinking:

1. A first working solution
2. A more efficient version
3. Edge cases handled
4. A cleaner, more idiomatic version

## Solutions

| Problem | Notebook | Approach |
|---|---|---|
| Count Elements Greater Than Previous Average | [Notebook](Count%20Elements%20Greater%20Than%20Previous%20Average.ipynb) | Started with recalculating the average of all previous elements for every item (O(n²)). Improved to a single pass with a running sum (O(n)), comparing `value × count` with the sum to avoid division, then handled the empty-list case and simplified the loop with `enumerate()`. |

## Tech

Python 3 · Jupyter Notebook

## How to run

Open a notebook in Jupyter (or view it directly on GitHub) and run the cells. Each solution reads its input the same way HackerRank does: the number of items first, then one value per line.
