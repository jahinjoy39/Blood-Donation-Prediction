# 🩸 Blood Donation Prediction using Machine Learning

This repository contains a machine learning project focused on predicting whether a blood donor will donate in a given period, using logistic regression and classification techniques.

## 📂 Files Included

- `BloodDonation.ipynb`: Jupyter notebook containing the full data analysis, model training, and evaluation process.
- `transfusion.data`: Dataset from the UCI Machine Learning Repository — Blood Transfusion Service Center.
- `README.md`: This documentation file.

---

## 📊 Project Description

The objective of this project is to predict blood donation behavior using historical data of blood donors. It helps in identifying individuals likely to donate blood again, which is valuable for planning blood drives and managing donor outreach efficiently.

---

## 🧠 Dataset Information

The dataset has the following columns:

1. **Recency (months)** – months since last donation  
2. **Frequency (times)** – total number of donations  
3. **Monetary (cc blood)** – total blood donated  
4. **Time (months)** – months since first donation  
5. **Target (whether they donated in March 2007)** – 1 (Yes), 0 (No)

---

## 🧪 Project Workflow and Code Description

The notebook follows these major steps:

### 1. **Data Loading**
- Load the dataset `transfusion.data` using `pandas`.
- Rename the columns for better readability.

### 2. **Exploratory Data Analysis (EDA)**
- Visualize the data using histograms and correlation plots.
- Analyze class distribution to understand the balance between donors and non-donors.

### 3. **Data Preprocessing**
- Normalize or scale features if required.
- Split the dataset into training and testing sets using `train_test_split`.

### 4. **Model Building**
- Train a **Logistic Regression** model as a baseline.
- Optionally test other models like **Random Forest**, **SVM**, or **KNN** for comparison.

### 5. **Model Evaluation**
- Use evaluation metrics such as:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
- Display results using a confusion matrix and classification report.

### 6. **Visualization**
- Plot ROC Curve and learning curves.
- Use feature importance plots if applicable (e.g., for tree-based models).

### 7. **Conclusion**
- Summarize the best-performing model.
- Discuss future steps like hyperparameter tuning or deep learning approaches.

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/blood-donation-prediction.git
   cd blood-donation-prediction
