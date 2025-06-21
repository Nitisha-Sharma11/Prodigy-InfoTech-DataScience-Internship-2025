### Task 4: Twitter Sentiment Analysis (Training Task)

This task is part of my Data Science Internship at Prodigy InfoTech (June 2025).  
In this task, I performed sentiment analysis on Twitter data to understand public opinion using text preprocessing and visualizations.

---

### Dataset

- **File Name:** `Task_4_twitter_training.xlsx`
- **Source:** Contains tweets with corresponding sentiment labels.
- **Attributes Include:**
  - `id` – Unique tweet ID  
  - `label` – Sentiment (0 = Negative, 1 = Positive)  
  - `tweet` – Tweet text content  

---

### Tools and Libraries Used

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- re (regular expressions)  
- WordCloud  
- sklearn (for model evaluation in extended tasks)

---

### Key Steps Performed

#### Data Preprocessing
- Removed special characters, links, and punctuations  
- Converted all text to lowercase  
- Removed stopwords and performed tokenization  

#### Visualization
- Word cloud for positive and negative tweets  
- Bar plot showing sentiment distribution  

---

### Insights

- Positive tweets are more frequent than negative ones in the dataset  
- Common words like “good”, “great”, and “love” appear in positive tweets  
- Words like “bad”, “not”, and “worst” appear more in negative tweets  

---

### Conclusion

This sentiment analysis task highlighted the importance of preprocessing in text data and demonstrated how visual tools can reveal public opinion trends. It serves as a foundational step for more advanced NLP tasks.

---

### Dataset Source

[Kaggle - Twitter Sentiment Dataset](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
