# 🤖 Support Vector Machines Project

A machine learning project implementing **Support Vector Machines (SVM)** using Python and Jupyter Notebook. This project works through the full SVM classification pipeline — from data exploration to model tuning with GridSearchCV — applied to a real-world dataset.

---

## 📌 Overview

Support Vector Machines are a powerful class of supervised learning algorithms used for both classification and regression. They work by finding the optimal **hyperplane** that maximally separates classes in high-dimensional space, making them especially effective for complex, non-linear decision boundaries when combined with kernel functions.

---

## 📁 Repository Structure

```
SVM/
│
├── Support Vector Machines Project.ipynb   # Main notebook with full analysis
└── README.md                               # Project documentation
```

---

## 🧪 What's Inside the Notebook

- **Data Loading & Exploration** — Inspecting the dataset structure, types, and summary statistics
- **Exploratory Data Analysis (EDA)** — Visualising class distributions and feature relationships
- **Data Preprocessing** — Train/test split and feature scaling where applicable
- **Model Training** — Fitting an SVM classifier using `scikit-learn`'s `SVC`
- **Hyperparameter Tuning** — Using `GridSearchCV` to optimise `C`, `gamma`, and kernel type
- **Model Evaluation** — Confusion matrix, classification report (precision, recall, F1-score)
- **Comparison** — Assessing performance before and after tuning

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/townspace/SVM.git
   cd SVM
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook "Support Vector Machines Project.ipynb"
   ```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Jupyter Notebook | Interactive development environment |
| pandas | Data manipulation and analysis |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Data visualisation |
| scikit-learn | SVM model, GridSearchCV, and evaluation |

---

## 📊 Key Concepts

**Support Vector Machines (SVM)** is a supervised learning algorithm that:
- Finds the optimal **decision boundary (hyperplane)** that maximises the margin between classes
- Uses **support vectors** — the data points closest to the boundary — to define the hyperplane
- Applies **kernel functions** (linear, RBF, polynomial) to handle non-linearly separable data
- Is controlled by two key hyperparameters:
  - `C` — regularisation parameter that controls the trade-off between a smooth boundary and classifying training points correctly
  - `gamma` — defines how far the influence of a single training example reaches (used with RBF kernel)

**GridSearchCV** is used to systematically search for the best combination of these parameters.

---

## 📬 Contact

Created by [@townspace](https://github.com/townspace) — feel free to raise an issue or get in touch!
