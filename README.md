# 🧠 Support Vector Machines (SVM) – Breast Cancer Classification

## 🎯 Objective

This project demonstrates the application of **Support Vector Machines (SVM)** for both **linear and non-linear binary classification** using the Breast Cancer Wisconsin dataset. The goal is to build effective models, tune hyperparameters, and visualize decision boundaries.

---

## 🔄 Workflow Steps

### 1. 📥 Load and Prepare Dataset
- The dataset was loaded using pandas.
- ID columns were removed.
- The `diagnosis` target was encoded (Malignant = 1, Benign = 0).

### 2. ⚖ Normalize Features
- Numerical features were scaled using `StandardScaler` to ensure fair distance calculations in SVM.

### 3. 🤖 Train SVM Models
- An SVM with a **linear kernel** and another with an **RBF (Radial Basis Function)** kernel were trained and tested.

### 4. 📈 Evaluate Models
- Models were evaluated using accuracy score and **confusion matrices**.
- Hyperparameter tuning was demonstrated by adjusting `C` and `gamma`.

### 5. 🔁 Cross-Validation
- 5-fold cross-validation was used to assess generalization performance of each kernel.

### 6. 🧭 Visualize Decision Boundaries
- Principal Component Analysis (PCA) reduced features to 2D for visualization.
- A decision boundary was plotted for the RBF kernel to illustrate class separation.

---

## 📁 Dataset

The **Breast Cancer Wisconsin dataset** contains 30 features computed from digitized images of breast mass cell nuclei and a binary diagnosis label (Malignant or Benign).

---

## ✅ Output

- Accuracy of SVM with both linear and RBF kernels
- Confusion matrices
- Cross-validation scores
- Decision boundary plot using PCA

---

## 📚 Requirements

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---
