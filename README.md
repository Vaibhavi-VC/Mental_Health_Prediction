# Early Detection of Mental Health Conditions via Machine Learning

> *Bridging the gap between technology and mental wellness through predictive machine learning.*

---

## 📌 Overview

Mental health challenges affect millions worldwide, yet early detection remains a critical hurdle. This project addresses the gap by providing an intelligent machine learning classification system designed to analyze survey responses and detect early risk markers for conditions like **depression, anxiety, and stress**.

By serving a trained classification model through an interactive **Flask web application**, users can receive real-time risk assessments to encourage timely, proactive support.

---

## ✨ Key Features

* **Smart Data Processing:** Automated cleaning pipeline for missing value imputation, outlier detection, and categorical encoding.
* **Multi-Model Evaluation:** Comparative analysis across **Decision Trees**, **Random Forests**, and **Logistic Regression**.
* **Comprehensive Metrics:** Benchmarking using Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.
* **Production-Ready & Compliant:** Architected for scalability, model explainability, and healthcare compliance considerations.

---

## 🛠️ Tech Stack

* **Backend & ML:** Python 3.x, scikit-learn, Pandas, NumPy, Pickle
* **Data Visualization:** Seaborn, Matplotlib, Jupyter Notebook
* **Frontend:** Flask, HTML, CSS
* **Dataset:** OSMI Mental Health in Tech Survey (Kaggle)

---

## 📊 Model Performance

Multiple classification algorithms were benchmarked to ensure high reliability and balance between precision and recall:

| Algorithm | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| **Random Forest** | **Best** | **Best** | **Best** | **Best** |
| **Decision Tree** | Good | Good | Good | Good |
| **Logistic Regression** | Moderate | Moderate | Moderate | Moderate |

### Why Random Forest?
* Superior handling of mixed categorical and numerical data types
* Built-in feature importance ranking for model explainability
* Robust against overfitting compared to single decision trees
* Excellent performance on imbalanced datasets
