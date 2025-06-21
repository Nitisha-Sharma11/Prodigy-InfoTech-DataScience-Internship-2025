# Task 5: U.S. Accidents – ML Model (March 2023)

This task is part of my Data Science Internship at Prodigy InfoTech (June 2025).  
In this task, I built a Machine Learning model using a U.S. accidents dataset to predict accident severity levels and gain insights into the contributing factors.

---

# Dataset

The dataset used is from [Kaggle - U.S. Accidents (March 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents).  
It contains detailed records of traffic accidents, including date/time, location, weather, road conditions, and severity.

---

# Tools and Libraries Used

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

# Key Steps Performed

## Data Preprocessing
- Handled missing values in key columns like `Weather_Condition`, `Visibility`, and `Wind_Speed`.
- Selected important features for the ML model (e.g., `Temperature(F)`, `Humidity(%)`, `Visibility(mi)`, `Weather_Condition`, `Start_Time`, etc.).
- Converted categorical columns using label encoding or one-hot encoding.

## Model Building
- Chose `Severity` as the target variable.
- Split the data into training and testing sets (80-20 ratio).
- Trained a **Decision Tree Classifier**.
- Evaluated the model using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## Visualization
- Plotted feature distributions and model performance metrics.
- Used bar plots and heatmaps to interpret results.

---

# Insights

- The model was able to classify accident severity with reasonable accuracy.
- Certain weather and visibility conditions had a stronger impact on accident severity.
- Time of the accident (e.g., peak hours) influenced the likelihood of severe cases.

---

# Conclusion

This task demonstrated how machine learning can be applied to real-world accident data to predict severity levels.  
Such insights can assist in planning better traffic safety strategies and reducing accident impacts.

---

# Dataset Source

🔗 [Kaggle - U.S. Accidents (March 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

---
