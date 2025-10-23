# Employee Sentiment Analysis Project

## Project Summary

This project focuses on analyzing employee sentiment using Natural Language Processing (NLP) techniques on a dataset of employee messages. The main objective was to identify sentiment trends, rank employees based on their communication tone, and flag potential flight risks.

### Top Employees by Sentiment

- **Top 3 Positive Employees:**  
  *(Based on monthly cumulative sentiment scores)*  
  1. Employee ID: 116 
  2. Employee ID: 162
  3. Employee ID: 211 

- **Top 3 Negative Employees:**  
  *(Based on monthly cumulative sentiment scores)*  
  1. Employee ID: 80  
  2. Employee ID: 1136  
  3. Employee ID: 1324  

### Flight Risk Identification

No employees were flagged as flight risks. This is because each employee in the dataset sent only one message, and the flight risk criterion required at least four negative messages within a 30-day period.

### Key Insights

1. **Sentiment Distribution:** Positive messages slightly dominated, followed by neutral and negative messages. Overall sentiment levels remained consistent over time.
2. **Message Frequency:** Uniform across employees, as each employee sent only one message.
3. **Predictive Modeling:** Linear regression analysis using message count, word count, and message length as predictors showed minimal correlation with sentiment scores. This indicates that sentiment variation is independent of message length or frequency in this dataset.

### Recommendations

- **Employee Engagement:** Encourage continuous feedback to improve sentiment tracking over time. A larger dataset with multiple messages per employee will provide more actionable insights.
- **Flight Risk Monitoring:** Maintain a rolling window approach for future datasets with multiple messages per employee to identify potential attrition risks.
- **Feature Enhancement:** Consider additional behavioral or engagement features (e.g., response time, interaction type) for better predictive modeling of sentiment trends.

---

**Technologies Used:**  
- Python  
- NLP with NLTK (VADER Sentiment Analyzer)  
- Pandas for data manipulation  
- Matplotlib & Seaborn for visualization  
- Scikit-learn for predictive modeling

