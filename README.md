# Elevate_Labs_Task_7

````markdown
# 🧠 Breast Cancer Classification Using SVM (Linear & RBF)

This project demonstrates the use of **Support Vector Machines (SVMs)** for binary classification using both **Linear** and **RBF** kernels. The dataset used is a Breast Cancer dataset containing features computed from digitized images of fine needle aspirates (FNA) of breast masses.

---

## 📁 Dataset
- **File**: `Breast cancer dataset.csv`
- **Source**: [Kaggle - Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
- **Classes**:
  - `M` = Malignant
  - `B` = Benign

---

## 📌 Objectives
- Train SVM models using both **Linear** and **RBF** kernels.
- Visualize decision boundaries using **PCA** (2D).
- Perform **hyperparameter tuning** using `GridSearchCV`.
- Evaluate using **confusion matrix**, **classification report**, and **cross-validation**.

---

## 🛠 Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repo or download the code.
2. Place the dataset file `Breast cancer dataset.csv` in the same directory.
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
````

4. Run the Python script:

   ```bash
   python svm_breast_cancer.py
   ```

---

## 📊 Visuals Included

* Decision boundaries for both kernels (after PCA)
* Confusion matrix heatmap
* Classification metrics

---

## 📈 Key Learnings

* **Margin maximization** using SVMs
* **Kernel trick** for handling non-linear decision boundaries
* The role of **C and gamma** in SVM performance
* Using **PCA for 2D visualization**
* Model tuning and evaluation using **cross-validation**

---

## 🔍 Best Parameters from GridSearchCV

These may vary slightly depending on the run:

```
Best Parameters: {'C': 10, 'gamma': 0.01}
Best CV Accuracy: 0.982
```

---

## 📦 Repository Structure

```
.
├── Breast cancer dataset.csv
├── svm_breast_cancer.py
├── README.md
```

---

## 📬 License

This project is intended for learning purposes as part of an internship/educational task. Attribution to the dataset provider is appreciated.

---

## ✍️ Author

**Om Borase**
Task for AI & ML Internship - Support Vector Machines

```

