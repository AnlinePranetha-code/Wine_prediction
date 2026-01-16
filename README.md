# 🍷 Wine Quality Prediction | End-to-End Machine Learning System

An end-to-end **Machine Learning classification system** designed to predict wine quality (**Good vs Bad**) using physicochemical attributes. This project follows **industry-standard ML practices**, including data preprocessing, model benchmarking, pipeline automation, and hyperparameter optimization.

---

## 🚀 Project Objective
To design, train, evaluate, and optimize a **binary classification model** that accurately predicts wine quality while demonstrating the **complete Machine Learning lifecycle** used in production-grade systems.

---

## 🧠 Problem Formulation
- **Type:** Supervised Learning  
- **Task:** Binary Classification  
- **Target Variable:** `quality_label`  
- **Classes:**
  - `1` → Good Wine (quality ≥ 7)
  - `0` → Bad Wine (quality < 7)

---

## 📊 Dataset Description
- Numerical physicochemical features (acidity, pH, alcohol, etc.)
- No missing values
- Imbalanced class distribution
- Clean dataset suitable for statistical modeling and ML algorithms

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution analysis of wine quality scores
- Class imbalance identification
- Feature scale inspection
- Visualization using Matplotlib and Seaborn
- Insights used to guide preprocessing and modeling decisions

---

## ⚙️ Data Preprocessing Pipeline
- Feature–target separation
- Train–test split (80/20)
- Feature scaling using `StandardScaler`
- Pipeline-based preprocessing to prevent data leakage

---

## 🤖 Machine Learning Models Implemented
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)

Each model was trained, tested, and evaluated using **consistent metrics**.

---

## 📈 Model Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross-validation scores

---

## 🧪 Hyperparameter Optimization
- Implemented `Pipeline` + `GridSearchCV`
- 5-fold cross-validation
- Optimized model parameters for better generalization
- Reduced overfitting and improved test performance

---

## 🏆 Results & Performance
- Best-performing model selected based on validation accuracy
- Tuned model showed improved performance on unseen data
- Final model ready for deployment or integration

---

## 🛠️ Tech Stack / Libraries Used
- **Programming:** Python  
- **Data Analysis:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Optimization:** GridSearchCV, Pipelines  

## 📁 Project Structure
```text
├── wine.py
├── winequality.csv
├── model_comparison.png
├── quality_distribution.png
├── binary_classification.png
└── README.md
