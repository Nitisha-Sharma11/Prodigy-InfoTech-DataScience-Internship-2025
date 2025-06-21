# Task 3: Bank Marketing ML Model (Additional Task)

This task is part of my Data Science Internship at Prodigy InfoTech (June 2025).  
In this task, I built a machine learning model using a bank marketing dataset to predict whether a client will subscribe to a term deposit.

---
 
# Dataset

- **File Name:** `Task_3_bank-additional.xlsx`
- **Source:** [UCI Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) 
- **Attributes Include:**
  - `age` – Age of the client  
  - `job`, `marital`, `education` – Client demographic information  
  - `default`, `housing`, `loan` – Financial details  
  - `contact`, `month`, `day_of_week` – Contact communication details  
  - `duration`, `campaign`, `pdays`, `previous` – Last contact duration and campaign history  
  - `poutcome` – Outcome of previous marketing campaign  
  - `y` – Target variable (yes/no for term deposit)

---

# Tools and Libraries Used

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- scikit-learn  

---

# Key Steps Performed

## Data Preprocessing
- Handled missing values and converted categorical features using Label Encoding  
- Removed irrelevant or redundant features  

## Model Building
- Built Decision Tree Classifier using both Gini Index and Entropy  
- Evaluated model performance using accuracy and classification reports  

## Visualization
- Bar plots for class distribution  
- Confusion matrix heatmaps to visualize predictions  

---

# Insights

- The model using Gini Index performed slightly better in accuracy and recall  
- Most clients do not subscribe to a term deposit (imbalanced dataset)  
- Duration of last contact had the strongest influence on prediction  

---

# Conclusion

This task demonstrated how machine learning can help banks target the right customers for marketing campaigns. Decision tree models provided interpretable results and highlighted key features influencing customer decisions.

---

# Dataset Source

🔗 [UCI Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

---
