# Delivery Route Optimization for E-commerce
**Course:** ENCA351 — Design and Analysis of Algorithms Lab  
**Author:** <Your Name>  
**Faculty:** Dr. Aarti

## Overview
This project demonstrates multiple algorithmic strategies (recurrence, greedy, dynamic programming, graph algorithms, TSP) to model and solve a delivery route optimization problem for an e-commerce setting.

## Files
- `delivery_route_optimization.ipynb` — Jupyter notebook with code, plots and analysis
- `src/algorithms.py` — reusable algorithm functions
- `requirements.txt` — Python dependencies
- `images/` — plots and exported images

## How to run
1. Create and activate virtual environment.
2. `pip install -r requirements.txt`
3. Launch Jupyter and open `delivery_route_optimization.ipynb`

## Problem setup (sample)
- Locations: Warehouse, C1, C2, C3
- Distance matrix: provided in notebook
- Parcels: `C1`, `C2`, `C3` with value, time window, weight
- Vehicle capacity: 30

## Notes
- TSP is solved by brute force (small n) and Held-Karp DP for demonstration.
- Greedy knapsack used for value/weight selection; DP used for time-window constraints.
