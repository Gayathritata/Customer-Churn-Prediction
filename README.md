# Customer Churn Prediction Using Machine Learning

## 📌 Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a company or continue using its services.

The project analyzes customer behavior, usage patterns, and other relevant factors to identify customers who are at risk of leaving. Multiple Machine Learning classification algorithms are implemented and evaluated to identify effective churn prediction models.

## 🎯 Objectives

- Analyze customer data to understand churn patterns.
- Identify factors influencing customer churn.
- Apply different Machine Learning classification algorithms.
- Compare model performance using evaluation metrics.
- Help businesses improve customer retention strategies.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Environment | Jupyter Notebook, Google Colab |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn, XGBoost |
| Data Processing | Feature Engineering, SMOTE |

## 📂 Dataset Description

The dataset contains customer-related information used to predict whether a customer will leave the service.

### Important Features

| Feature | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Churn | Target variable indicating customer churn |
| Tenure | Duration of customer association |
| Preferred Login Device | Device used to access the service |
| City Tier | Customer's city classification |
| Warehouse to Home | Distance between warehouse and customer |
| Preferred Payment Mode | Customer's payment preference |
| Hours Spent on App | Time spent using the application |
| Number of Orders | Total orders placed |
| Cashback Amount | Cashback received by the customer |

**Target Variable: Churn**

- 0 – Customer continues using the service.
- 1 – Customer leaves the service.

## ⚙️ Machine Learning Algorithms

The following classification algorithms are implemented:

1. **Logistic Regression:** Predicts the probability of customer churn.
2. **Decision Tree:** Uses decision-based rules to classify customers.
3. **Random Forest:** Combines multiple decision trees to improve prediction performance.
4. **Support Vector Machine (SVM):** Classifies customers by identifying an optimal decision boundary.
5. **K-Nearest Neighbors (KNN):** Predicts churn based on the nearest data points.
6. **XGBoost:** Uses gradient boosting to improve classification performance.
7. **Stacking Classifier:** Combines multiple machine learning models to generate predictions.

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Handling Missing Values
5. Feature Engineering
6. Feature Scaling and SMOTE
7. Train-Test Splitting
8. Model Training
9. Model Evaluation
10. Customer Churn Prediction

## 📊 Model Performance and Results

The performance of different Machine Learning algorithms was evaluated using 5-Fold Stratified Cross-Validation.

### 1. Model Comparison

| Machine Learning Model | Accuracy |
|---|---:|
| Logistic Regression | 80.77% |
| Decision Tree | 92.59% |
| Random Forest | 96.64% |
| Support Vector Machine (SVM) | 92.18% |
| K-Nearest Neighbors (KNN) | 87.86% |
| XGBoost | **98.15%** |
| Stacking Classifier | 92.92% |

**Best Cross-Validation Performance:** XGBoost achieved the highest accuracy of **98.15%**.

### 2. Final Stacking Classifier Evaluation

The following classification metrics were obtained from the final Stacking Classifier evaluation.

| Evaluation Metrics | Class 0 | Class 1 |
|---|---:|---:|
| Precision | 0.99 | 0.99 |
| Recall | 0.99 | 0.99 |
| F1-Score | 0.99 | 0.99 |
| Support | 937 | 936 |

**Overall Accuracy:** 99%

**Total Test Samples:** 1,873

### 3. Confusion Matrix

The confusion matrix represents the actual and predicted customer churn classifications.

| Actual / Predicted | Predicted: 0 | Predicted: 1 |
|---|---:|---:|
| Actual: 0 | 923 | 14 |
| Actual: 1 | 11 | 925 |

### 4. Key Findings

- XGBoost achieved the highest cross-validation accuracy of 98.15%.
- Random Forest achieved 96.64% cross-validation accuracy.
- The Stacking Classifier achieved 99% accuracy in the reported final test evaluation.
- The classification results demonstrate the potential of Machine Learning in identifying customer churn patterns.

**Evaluation Note:** The reported results reflect the current notebook implementation. Since preprocessing, feature scaling, and SMOTE are applied before cross-validation and train-test splitting, data leakage may occur. For a reliable evaluation, these steps should be performed within training folds using an appropriate pipeline, followed by a fresh model evaluation.

## 💡 Applications

- Customer retention management
- Identifying customers at risk of leaving
- Understanding customer behavior
- Improving business strategies
- Supporting data-driven business decisions

## 🔮 Future Enhancements

- Develop a web application for customer churn prediction.
- Integrate a user-friendly interface using Flask or Streamlit.
- Improve model performance through hyperparameter tuning.
- Generate personalized customer retention recommendations.

## 🚀 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/Gayathritata/Customer-Churn-Prediction.git
```

**Step 2: Navigate to the project folder**

```bash
cd Customer-Churn-Prediction
```

**Step 3: Install the required libraries**

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

**Step 4: Open Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5:** Open `Customer_Churn_Prediction Code.ipynb` and execute the cells sequentially.

## 👩‍💻 Author

**Gayathri Tata**

B.Tech – Artificial Intelligence and Machine Learning

GitHub: [Gayathritata](https://github.com/Gayathritata)

---

⭐ If you find this project useful, consider giving the repository a star!
