# Task 2: Exploratory Data Analysis – Titanic Dataset

This task is part of my Data Science Internship at Prodigy InfoTech (June 2025).  
In this task, I performed Exploratory Data Analysis (EDA) on the Titanic dataset to uncover survival patterns based on passenger demographics and ticket details.

---

# Dataset

- **File Name**: titanic.csv  
- **Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/competitions/titanic/data) 
- **Attributes Include**:
  - `PassengerId` – Unique ID for each passenger  
  - `Survived` – Target variable (0 = No, 1 = Yes)  
  - `Pclass` – Passenger class (1st, 2nd, 3rd)  
  - `Name` – Name of the passenger  
  - `Sex` – Gender of the passenger  
  - `Age` – Age in years  

---

# Tools and Libraries Used

- Python  
- Jupyter Notebook  
- Pandas  
- Matplotlib  
- Seaborn

---

# Key Steps Performed

## Data Cleaning
- Handled missing values in `Age`, `Cabin`, and `Embarked`  
- Converted data types and dropped irrelevant columns like `Cabin` and `Ticket`

## Univariate Analysis
- Count plot of survival status  
- Bar charts for `Pclass`, `Sex`, and `Embarked`  
- Histogram of age distribution

## Multivariate Analysis
- Heatmap to analyze correlations between numerical variables  
- Grouped bar plots showing survival by `Sex`, `Pclass`, and `Embarked`

---

# Insights

- Female passengers had a significantly higher survival rate than males  
- 1st class passengers had better chances of survival  
- Most passengers embarked from Southampton  
- Younger passengers (especially children under 10) showed higher survival rates

---

# Conclusion

This analysis revealed meaningful survival patterns on the Titanic, influenced by gender, class, and age.  
It demonstrates how EDA can highlight key factors from historical data and support data-driven storytelling.

---

# Dataset Source

🔗 [Kaggle – Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---
### 🔗 Dataset Source  
[Kaggle – Twitter Sentiment Dataset](https://www.kaggle.com/datasets/cosmos98/twitter-sentiment-analysis)
