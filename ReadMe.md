# 🎗️ Breast Cancer Data Visualization using Matplotlib

This Python project analyzes and visualizes the **Breast Cancer Wisconsin Diagnostic Dataset** using **Matplotlib**. It aims to explore feature distributions and relationships to better understand patterns in the data, which can assist in diagnosis-related insights.

---

## 📌 Project Description

The Breast Cancer dataset from **scikit-learn** is used to:
- Display summary statistics
- Visualize distributions
- Examine the relationship between features
- Understand the class balance between **Malignant** and **Benign** tumors

The visualizations are created using **Matplotlib**.

---

## 📊 Visualizations Included

| Plot Type     | Description |
|---------------|-------------|
| **Line Plot** | Mean radius values across all entries |
| **Scatter Plot** | Mean radius vs mean texture colored by class |
| **Bar Plot** | Count of Malignant vs Benign cases |
| **Histogram** | Distribution of mean area |
| **Box Plot** | Mean radius distribution grouped by class |

---

## 📁 Dataset Info

**Dataset:** Breast Cancer Wisconsin Diagnostic Dataset  
**Source:** `sklearn.datasets.load_breast_cancer()`  
**Features:** 30 numeric attributes (e.g., mean radius, mean texture)  
**Target:** 0 = Malignant, 1 = Benign  
**Samples:** 569 rows

---

## 🛠️ Technologies Used

- Python 3
- Matplotlib
- Pandas
- scikit-learn

---

## ▶️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/breast-cancer-matplotlib-visualization.git
   cd breast-cancer-matplotlib-visualization
