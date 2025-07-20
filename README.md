# Energy-Efficient Navigation Optimization of Maritime Transport

This project explores the optimization of maritime shipping routes in the Indian Subcontinent using real-time oceanographic data. The goal is to reduce navigation costs while avoiding hazardous marine conditions by applying and comparing multiple routing algorithms.

## Project Overview

We use data from the **Copernicus Marine Environment Monitoring Service (CMEMS)** to model oceanic conditions and calculate cost-effective ship routes. A bounding box is defined over the region of interest, and key variables are converted into a cost matrix that feeds routing algorithms.

## Algorithms Used

- **Dijkstra’s Algorithm** – Finds the shortest path in graphs with non-negative weights.
- **A* Search Algorithm** – Uses heuristics for faster and more informed pathfinding.
- **Bellman-Ford Algorithm** – Handles negative weights and computes shortest paths from a single source.

Each algorithm is evaluated for performance, accuracy, and suitability in dynamic maritime environments.

## Data Source

- **Copernicus Marine Environment Monitoring Service (CMEMS)**
- Key variables:
  - Significant wave height
  - Wind wave height
  - Mixed layer thickness
  - Salinity
  - Temperature

## Tech Stack

- Python
- Libraries: `ftplib`, `xarray`, `NumPy`, `Matplotlib`

## Methodology

1. Retrieve and preprocess marine data.
2. Build a cost matrix from relevant variables.
3. Run routing algorithms to generate optimal ship paths.
4. Compare algorithm outputs for efficiency and reliability.