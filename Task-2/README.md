# Task 2: Exploratory Data Analysis – Titanic Dataset

This task is part of my Data Science Internship at Prodigy InfoTech (June 2025).  
In this task, I performed Exploratory Data Analysis (EDA) on the famous Titanic dataset to uncover patterns related to passenger survival.

---

# Dataset 

- **File Name**: titanic.csv  
- **Source**: Titanic Dataset from [Kaggle](https://www.kaggle.com/competitions/titanic/data)
- **Attributes Include**:
  - `PassengerId` – Unique ID for each passenger  
  - `Survived` – Target variable (0 = No, 1 = Yes)  
  - `Pclass` – Passenger class (1st, 2nd, 3rd)  
  - `Name` – Name of the passenger  
  - `Sex` – Gender of the passenger  
  - `Age` – Age in years


- **File Name:** `Task_3_bank-additional.xlsx`
- **Source:** Bank Marketing dataset from a Portuguese banking institution.
- **Attributes Include:**
  - `age` – Age of the client  
  - `job`, `marital`, `education` – Client demographic information  
  - `default`, `housing`, `loan` – Financial details  
  - `contact`, `month`, `day_of_week` – Contact communication details  
  - `duration`, `campaign`, `pdays`, `previous` – Last contact duration and campaign history  
  - `poutcome` – Outcome of previous marketing campaign  
  - `y` – Target variable (yes/no for term deposit)


# Tools and Libraries Used

- Python  
- Jupyter Notebook  
- Pandas  
- Matplotlib  
- Seaborn

---

# Key Steps Performed

## Data Cleaning
- Handled missing values in columns like Age, Cabin, and Embarked.
- Converted data types and dropped irrelevant columns.

## Univariate Analysis
- Count plot of survival status.
- Bar chart of passengers by class and gender.
- Histogram of age distribution.

## Multivariate Analysis
- Heatmap showing correlation between numerical variables.
- Grouped visualizations to compare survival by class, gender, and embarkation point.

---

# Insights

- Female passengers had a much higher survival rate than males.
- 1st class passengers were more likely to survive than 2nd or 3rd class.
- Most passengers embarked from Southampton.
- Younger passengers (especially children under 10) had higher chances of survival.

---

# Conclusion

This EDA revealed strong correlations between survival and features like gender, passenger class, and age. The Titanic dataset remains a great resource for practicing data analysis and understanding real-world patterns.

---

# Dataset Source

🔗 [Kaggle - Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---
