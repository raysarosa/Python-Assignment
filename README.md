# 🧠 Programming for Data Science 2024 — Midterm Assignment

This repository contains my submission for the **midterm assignment** of the *Programming for Data Science 2024* course. It is divided into two main parts:

1. **Part I – Python Basics**
2. **Part II – K-Means Clustering (from scratch)**

---

## 📘 Part I – Python Basics

This section includes 14 programming tasks designed to assess understanding of:

- Variables and expressions
- Data structures (lists, tuples)
- Control flow (loops, conditionals)
- Functions
- Working with strings and dates
- Basic statistics (mean, standard deviation)
- File reading (without external libraries)

Each function is written using only the **Python Standard Library**, as per assignment rules.

---

## 🤖 Part II – K-Means Clustering from Scratch

This section contains a complete implementation of the **K-Means Clustering algorithm** without using libraries like NumPy, Pandas, or Scikit-learn.

### Core components:
- Random centroid initialization
- Euclidean distance computation
- Data point assignment to clusters
- Centroid recalculation
- Iterative refinement until convergence
- Encapsulated in a custom `KMeans` class

### Optional Visualization:
A final step includes visualizing the clustering result using `matplotlib`.

---

## 📁 Project Structure

```bash
📦 your_repo/
├── python_assignment.ipynb     # Jupyter notebook with all solutions
└── README.md                   # This file

## 🧪 How to Run

- Open `python_assignment.ipynb` in Jupyter Notebook.
- Execute each cell to test the code.

### For K-Means testing:

```python
kmeans = KMeans(k=2, max_iters=100)
kmeans.fit(test_data)
print(kmeans.get_labels(test_data))
