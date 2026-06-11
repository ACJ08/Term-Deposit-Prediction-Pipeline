# 📈 BankTerm Intelligence
### Customer Term Deposit Subscription Prediction Pipeline

An end-to-end machine learning project for predicting whether banking customers will subscribe to term deposit products using structured customer and campaign data.

This project focuses on building scalable preprocessing pipelines, handling severe class imbalance, optimizing decision thresholds, and generating business-oriented model insights.

---

# 📌 Project Overview

Banks often run marketing campaigns to encourage customers to subscribe to term deposits.

This project builds a predictive classification pipeline capable of identifying likely subscribers while balancing:

- Customer acquisition cost
- Campaign efficiency
- Revenue generation
- Recall vs precision tradeoffs

The workflow emphasizes reproducibility, modular preprocessing, and operational model evaluation.

---

# 📂 Dataset

Dataset Characteristics:

- 45,000+ customer records
- Binary classification problem
- Subscription rate: **11.7%**
- Mixed numerical and categorical variables

Example Features:

- Age
- Occupation
- Education
- Campaign interactions
- Contact method
- Previous outcomes

Target:

```text
Subscribe = Yes / No
```

---

# ⚙ Technologies

## Machine Learning
- scikit-learn

## Data Processing
- Pandas
- NumPy

## Visualization
- Matplotlib

## Pipeline Engineering
- Pipeline
- ColumnTransformer

---

# 🏗 Project Workflow

```text
Raw Dataset
      ↓
EDA
      ↓
Preprocessing
      ↓
Feature Transformation
      ↓
Model Training
      ↓
Threshold Optimization
      ↓
Business Evaluation
```

---

# 🔍 Data Preparation

Implemented:

✔ Missing value imputation  
✔ Feature scaling  
✔ Categorical encoding  
✔ Automated transformation workflows  

Using:

- Pipeline
- ColumnTransformer

---

# 🤖 Models Evaluated

Compared multiple approaches:

| Model |
|-------|
| Random Forest |
| Gradient Boosting |
| Balanced Bagging |
| Class Weighting |

---

# 📊 Evaluation Metrics

Measured using:

- Accuracy
- Precision
- Recall
- F1 Score
- Threshold Analysis

Additional analysis:

- F1-optimal threshold
- 90% recall threshold
- Cost-performance tradeoff

---

# 🚀 Key Outcomes

- Built reusable ML pipelines
- Improved minority-class prediction
- Reduced imbalance impact
- Generated business-oriented threshold recommendations

---

# 📁 Repository Structure

```text
├── data/
├── notebooks/
├── src/
├── models/
├── visuals/
├── README.md
```

---

# 👩‍💻 Author

Anne Carol G. Jonson  
BS Computer Science – Data Science Specialization  
University of Santo Tomas
