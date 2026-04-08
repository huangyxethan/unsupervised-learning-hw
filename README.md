# Unsupervised Learning and Data Analysis

Course assignments, implementations, and notes covering unsupervised machine learning methods — from classical dimensionality reduction and clustering to modern deep generative and self-supervised approaches.

---

## Topics Covered

| Module | Methods |
|--------|---------|
| **Dimensionality Reduction** | PCA, Kernel PCA, Autoencoders, t-SNE / UMAP |
| **Clustering** | K-Means, Hierarchical, Spectral Clustering |
| **Density Estimation** | Gaussian Mixture Models, EM Algorithm, Hidden Markov Models |
| **Topic Modeling** | Latent Dirichlet Allocation (LDA) |
| **Self-Supervised Learning** | Contrastive methods, pretext tasks |
| **Semi-Supervised Learning** | Label propagation, consistency regularization |
| **Applications** | Computer vision, speech, text |

---

## Repository Structure

```
unsupervised-learning-course/
│
├── assignments/
│   ├── hw1-dimensionality-reduction/
│   │   ├── hw1.ipynb
│   │   └── README.md
│   ├── hw2-clustering/
│   └── ...
│
├── notes/
│   └── lecture-summaries.md
│
├── utils/
│   └── plotting.py
│
└── README.md
```

---

## Tech Stack

- **Language:** Python 3.x
- **Core Libraries:** NumPy, SciPy, scikit-learn, PyTorch
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/unsupervised-learning-course.git
cd unsupervised-learning-course
```

### 2. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate      # Mac / Linux
venv\Scripts\activate         # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

---

## Assignments

| # | Topic | Key Methods | Notebook |
|---|-------|-------------|---------|
| 1 | Dimensionality Reduction | PCA, Kernel PCA | [hw1.ipynb](assignments/hw1-dimensionality-reduction/hw1.ipynb) |
| 2 | Clustering | K-Means, Spectral | [hw2.ipynb](assignments/hw2-clustering/hw2.ipynb) |
| 3 | Density Estimation | GMM, EM | [hw3.ipynb](assignments/hw3-density-estimation/hw3.ipynb) |

*Table will be updated as assignments are released.*

---

## About

This repository documents my work for the **Unsupervised Learning and Data Analysis** course. It is intended both as a learning record and as a portfolio of applied machine learning implementations.