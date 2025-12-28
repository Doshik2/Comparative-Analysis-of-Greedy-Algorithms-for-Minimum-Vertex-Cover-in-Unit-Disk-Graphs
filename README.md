# Comparative Analysis of Greedy Algorithms for Minimum Vertex Cover in Unit Disk Graphs

This repository contains the source code and experimental data for our research paper on the performance of greedy strategies in Unit Disk Graphs (UDGs).

## 📌 Overview
The project evaluates three main algorithms for the Minimum Vertex Cover problem:
1. **Degree-based Greedy**: Iteratively selects the highest-degree vertex.
2. **Edge-based Greedy**: Iteratively selects an edge and adds both endpoints.
3. **Matching-based 2-approximation**: Computes a maximal matching to guarantee a 2-approximation ratio.

## 📁 Repository Structure
* `main.py`: The complete Python implementation used for the simulations.
* `algorithm_comparison.csv`: Raw experimental results in CSV format.
* `results/`: Directory containing generated plots and visualizations.
* `final_results_table.tex`: LaTeX source for the results table used in the paper.

## 🚀 How to Run
To reproduce the experimental results, ensure you have Python 3.9+ installed and run:
```bash
pip install networkx numpy scipy matplotlib
python main.py
