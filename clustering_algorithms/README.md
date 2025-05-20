# 📂 clustering_algorithms/

This module contains custom implementations and wrappers of clustering algorithms used throughout the project.

The goal is to understand how key clustering algorithms work under the hood by implementing them from scratch, and to compare them against industry-standard libraries such as `scikit-learn`.

Each file typically includes:
- A class or function with a consistent `fit()` / `predict()` API
- Configurable parameters
- Compatibility with dataset structures used across the project
- (When relevant) comparison to its scikit-learn counterpart

### 📘 Implemented so far:

- `kmeans.py`: Custom implementation of the K-Means algorithm
- `hierarchical.py`: Simple version of agglomerative (hierarchical) clustering
- `dbscan.py`: (Optional) Basic density-based clustering with neighborhood expansion

### 🛠️ How to contribute or expand

To add a new clustering algorithm:
1. Create a new Python file using one of the existing implementations as a template.
2. Follow the same interface (`fit`, `predict`, etc.).
3. Include comments or references for educational purposes if possible.

This folder serves as the core educational engine of the project.
