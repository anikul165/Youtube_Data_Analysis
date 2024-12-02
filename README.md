# YouTube Data Analysis

## Overview

This project analyzes YouTube data to derive insights related to user engagement, comment trends, and sentiment analysis.

## Libraries Used

- **NumPy**: For numerical computations.
- **Pandas**: To manipulate and analyze data.
- **Matplotlib & Seaborn**: For visualizing trends and relationships in the data.
- **Warnings**: To suppress unwanted warnings during execution.

## Steps of Analysis

### 1. Data Loading

- **Dataset**: The dataset `UScomments.csv` was loaded.
- **Handling Bad Data**: Rows causing errors were skipped using `on_bad_lines='skip'`.

### 2. Data Cleaning

- Removed null values and duplicates to ensure data integrity.
- **Conclusion**: Missing or duplicate data can skew results, hence must be cleaned.

### 3. Exploratory Data Analysis (EDA)

- Visualized distribution and patterns in the data:
  - Analyzed the frequency of comments over time.
  - Identified trends in user engagement.

### 4. Sentiment Analysis

- **Objective**: To classify comments as positive, negative, or neutral.
- Steps:
  - Preprocessing text by removing stop words, punctuation, and converting to lowercase.
  - Visualized the distribution of sentiments using a bar chart.
- **Conclusion**: Most comments were positive, indicating overall user satisfaction.

### 5. Insights

- Comments with the highest likes and replies were identified, showing patterns of viral engagement.
- **Visualizations**:
  - Bar charts: Displaying top contributors.
  - Word clouds: Highlighting frequently used keywords in comments.

## Conclusion

The analysis successfully derived insights into YouTube user engagement patterns and comment sentiments. Future work can include deeper analysis of user demographics and video content correlations.
"""
