#  Customer Churn Prediction for SyriaTel

This project aims to predict customer churn for SyriaTel using machine learning classification models. By identifying customers who are likely to leave, the company can take proactive steps to retain them and improve customer satisfaction.

---

## Problem Statement

Customer churn is a significant business challenge in the telecom industry. SyriaTel wants to understand the key drivers behind churn and use predictive analytics to:

- Predict which customers are likely to churn.
- Identify the most influential features driving churn.
- Recommend business actions based on model insights.

---

## Project Structure
 classification_notebook.ipynb # Main notebook with full workflow
 data/ # Folder for input data
 README.md # Project documentation
 requirements.txt # Dependencies for the project

 
---

## Methodology

Followed the CRISP-DM approach:
1. **Business Understanding**
2. **Data Understanding & Preparation**
3. **Modeling**
4. **Evaluation**
5. **Deployment Recommendation**

---

##  Tools & Libraries Used

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook
- Git/GitHub

---

##  Models Trained & Tuned

We built and evaluated the following models:

| Model                        | ROC AUC Score |
|-----------------------------|---------------|
| Logistic Regression (Tuned) | 0.7826        |
| Decision Tree (Tuned)       | 0.7897        |
| **Random Forest (Tuned)**   | **0.8625**    |
| Random Forest (Randomized)  | 0.8590        |

**Random Forest with GridSearchCV** was the best-performing model.

---

##  Key Insights

- High day-time charges and frequent customer service calls strongly influence churn.
- Customers with international plans are more likely to churn.
- Class imbalance was addressed using SMOTE to improve model fairness.

---

##  How to Reproduce

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/syriatel-churn-classification.git
   cd syriatel-churn-classification


2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
   ```bash
   jupyter notebook classification_notebook.ipynb

---


pip install -r requirements.txt


Contact:
Created by Lilian Wangui
For inquiries, reach out via LinkedIn or [lilianwangui266@gmail.com]