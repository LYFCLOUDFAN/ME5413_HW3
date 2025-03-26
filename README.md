# Travelling Shopper Problem - VivoCity Level 2

## Overview

This project solves the **Travelling Shopper Problem (TSP)** for visiting key locations in VivoCity Level 2 and returning to the starting point. The goal is to find the shortest route using two methods:

1. **Brute Force** - Calculates all possible routes and selects the optimal one.
2. **Greedy Algorithm** - Iteratively chooses the nearest unvisited location until all locations are visited.

The shortest routes and their distances are compared, and the optimal route is visualized on a map.

## Requirements

- Python 3.x
- Libraries: `numpy`, `imageio`, `matplotlib`, `heapq`, `itertools`, `pandas`

You can install the required libraries with:

```bash
pip install numpy imageio matplotlib pandas
