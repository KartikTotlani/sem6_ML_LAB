# 🧠 Machine Learning Lab – Semester 6

This repository contains six foundational machine learning assignments completed as part of the Semester 6 ML Lab. Each assignment introduces a core ML technique with practical implementation in Python using real-world datasets.

---

## 📁 Assignments Overview

### 1. `ML_1.ipynb` – Data Preprocessing
- Loaded a dataset (`train1.csv`)
- Performed cleaning: handling missing values
- Feature encoding using Label Encoding and One-Hot Encoding
- Normalization and scaling
- Train-test split
- Useful as a base for preparing data before model training

---

### 2. `ML2.ipynb` – Linear Regression
- Applied Linear Regression on `Housing.csv` dataset
- Visualized the relationship between features and target
- Evaluated performance using R² and Mean Squared Error
- Demonstrated use of `sklearn.linear_model.LinearRegression`

---

### 3. `ML3.ipynb` – Logistic Regression
- Binary classification using Logistic Regression
- Worked on the `adult (1).csv` dataset
- Evaluated with accuracy, confusion matrix, and classification report
- Used `train_test_split` and `StandardScaler` for preprocessing

---

### 4. `ML4.ipynb` – Decision Tree Classifier
- Implemented Decision Tree model on preprocessed dataset
- Visualized the tree using `plot_tree`
- Compared accuracy and overfitting with varying depths
- Good for understanding decision boundaries and feature importance

---

### 5. `ML_5.ipynb` – Random Forest Classifier
- Ensemble technique: Random Forest applied to the same dataset
- Compared with Decision Tree performance
- Evaluated using accuracy and confusion matrix
- Emphasized robustness over single decision tree

---

### 6. `ML6.ipynb` – Support Vector Machine (SVM)
- Implemented SVM using `sklearn.svm.SVC`
- Used kernels like linear and RBF
- Preprocessed features with scaling
- Evaluated using accuracy and visualization of decision boundaries

---

## 📊 Datasets Used
- `train1.csv`
- `Housing.csv`
- `adult (1).csv`
- `Salaries_pd.csv`

---

## 🚀 How to Run

```bash
git clone https://github.com/KartikTotlani/sem6_ML_LAB.git
cd sem6_ML_LAB
pip install -r requirements.txt  # or install manually: pandas, sklearn, matplotlib, seaborn, jupyter
jupyter notebook
