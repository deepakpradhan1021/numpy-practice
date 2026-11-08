# NumPy Practice & Data Analysis Notebooks

A structured repository containing Jupyter notebooks developed while learning foundational array computing and numerical operations using Python and **NumPy**.

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/Library-NumPy-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Jupyter](https://img.shields.io/badge/Environment-Jupyter%20Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)

---

## 📂 Notebooks in This Repository

### 1. `1.ipynb` — NumPy Core Fundamentals
A comprehensive practice notebook (47 cells) covering core NumPy operations:
- **Array Creation:** Initializing 1D, 2D, and multi-dimensional arrays using `np.array`, `np.zeros`, `np.ones`, `np.arange`, and `np.linspace`.
- **Indexing & Slicing:** Multi-dimensional row/column slicing, negative indexing, and boolean filtering.
- **Mathematical Operations:** Element-wise arithmetic, matrix multiplications, exponential and trigonometric functions.
- **Reshaping & Manipulation:** `reshape`, `flatten`, `ravel`, transposing, and array concatenation.
- **Broadcasting Rules:** Understanding how arrays of different shapes interact during vector operations.

### 2. `capstone_project.ipynb` — Simulated Dataset Statistical Analysis
A practical mini-project (13 cells) applying NumPy statistical routines on a simulated dataset of 200 student records:
- **Dataset Generation:** Using `np.random.seed(42)` to generate reproducible student IDs, exam scores, and attendance rates.
- **Statistical Aggregations:** Computing `mean`, `median`, `min`, `max`, standard deviation, and variance.
- **Distribution Analysis:** Identifying top performers and attendance thresholds using boolean indexing.

---

## 💻 How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/deepakpradhan1021/numpy-practice.git
cd numpy-practice
```

### 2. Set up environment and install dependencies

```bash
# Create virtual environment
python -m venv .venv

# Windows
.\.venv\Scripts\activate

# Linux / macOS
source .venv/bin/activate

# Install NumPy and Jupyter
pip install numpy jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```
Or open the `.ipynb` files directly inside **VS Code** with the Jupyter extension.

---

## 📜 Educational Context

This repository is part of my 2nd-year B.Tech learning journey in Artificial Intelligence & Machine Learning, establishing solid fundamentals in vector computing before moving to higher-level frameworks.
