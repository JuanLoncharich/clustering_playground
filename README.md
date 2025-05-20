# 🧠 Clustering Learning Project

This is a personal project focused on learning and comparing different clustering algorithms applied to various real-world datasets. The structure is designed to support experimentation, modularity, and reproducibility.

## 📚 Objectives

- Learn core concepts and variants of clustering algorithms such as K-Means, DBSCAN, Hierarchical Clustering, and others.
- Apply these algorithms to diverse datasets.
- Evaluate and visualize clustering performance.
- Follow good software and data science practices throughout the project.

## 🗂 Project Structure

```plaintext
clustering-project/
│
├── data/ # Raw and processed datasets
│ ├── raw/
│ └── processed/
│
├── notebooks/ # Exploratory and development notebooks
│
├── clustering_algorithms/ # Algorithm implementations and wrappers
│
├── experiments/ # Experiment scripts for each dataset
│
├── results/ # Output: plots, metrics, saved models
│
├── tests/ # Unit tests
│
├── requirements.txt # Python dependencies
└── README.md # This file
```

Each main folder also contains a local `README.md` explaining its purpose.

## 🚀 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/JuanLoncharich/clustering_playground.git
cd clustering-project
```

2. **Create and activate a virtual environment:**

```bash
python -m venv clustering-env
source clustering-env/bin/activate      # Linux/Mac
clustering-env\Scripts\activate         # Windows
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

📊 Results
Results from experiments are stored in the results/ directory:

Cluster visualizations

Evaluation metrics (e.g., Silhouette, Davies-Bouldin)

Optional saved models

🧪 Technologies
Python 3.10+

scikit-learn

pandas

matplotlib / seaborn

jupyter notebooks

✅ Project Status
🚧 In progress. This repository evolves as I continue exploring and understanding clustering techniques.