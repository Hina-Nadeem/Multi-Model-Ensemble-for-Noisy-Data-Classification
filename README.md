# Multi-Model Ensemble for Noisy Data Classification

## 📌 Project Overview
This project addresses a real-world noisy data classification problem using multiple
machine learning models and ensemble learning techniques. The dataset contains missing
values and noise, which are handled through appropriate preprocessing steps. The goal is
to compare individual models and demonstrate how ensemble learning improves performance
and generalization.

---

## 🎯 Learning Objectives
- Handle noisy real-world datasets effectively
- Apply data preprocessing techniques such as imputation and feature scaling
- Train and evaluate multiple supervised learning models
- Implement ensemble learning to reduce overfitting
- Analyze model performance using standard classification metrics

---

## 📂 Dataset
A real-world dataset (Breast Cancer dataset from `scikit-learn`) is used in this project.
To simulate real-world conditions, artificial noise and missing values are introduced.

- **Type:** Binary Classification  
- **Target Variable:** Class label (Malignant / Benign)

---

## ⚙️ Data Preprocessing
The following preprocessing steps are applied:
- **Missing Value Handling:** Mean Imputation
- **Feature Scaling:** Standardization using `StandardScaler`
- **Noise Simulation:** Randomly introduced missing values

These steps ensure fair model comparison and improved learning performance.

---

## 🤖 Machine Learning Models
Three supervised learning models are implemented:

1. **Decision Tree**
   - Pruning applied using maximum depth to reduce overfitting
2. **Naive Bayes**
   - Probabilistic classifier assuming feature independence
3. **Support Vector Machine (SVM)**
   - Uses regularization to improve generalization

All models are evaluated using **5-fold cross-validation**.

---

## 🔁 Ensemble Learning
To enhance performance on noisy data, **Bagging (Bootstrap Aggregating)** is applied using
Decision Trees as base learners.

### Why Bagging?
- Reduces variance
- Improves stability
- Handles noisy data more effectively

---

## 📊 Evaluation Metrics
Model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a comprehensive evaluation of classification performance.

---

## 📈 Results & Observations
- Decision Trees tend to overfit noisy data without pruning
- SVM performs well due to regularization and margin maximization
- Ensemble learning outperforms individual models by reducing variance
- Proper preprocessing significantly improves overall results

---

## 🧠 Conclusion
This project demonstrates that ensemble learning methods, combined with proper data
preprocessing and regularization, provide robust and reliable performance on noisy
real-world datasets. Such approaches are highly suitable for practical machine learning
applications.

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 👩‍💻 Author
**Hina Nadeem**  
Bachelor of Artificial Intelligence  
Machine Learning Assignment Project

---

## 📄 License
This project is for academic and educational purposes only.
