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

- The dataset `UScomments.csv` was loaded.
- Handled problematic rows using `on_bad_lines='skip'`.

**Key Insight**: Skipping bad lines ensures smooth loading of large datasets with potential inconsistencies.

---

### 2. Data Cleaning

- Removed null values and duplicate records to maintain data quality.

**Conclusion**: Cleaning ensures accurate analysis by eliminating redundant and missing data points.

---

### 3. Exploratory Data Analysis (EDA)

- Analyzed key metrics like the number of comments, likes, and replies.
- Visualized trends in user engagement over time using line charts and bar graphs.

**Visualizations**:

1. Line chart: Frequency of comments by date.
2. Bar chart: Top 10 videos with the most user engagement.

**Key Insight**: A few videos garnered significant attention, contributing to most likes and replies.

---

### 4. Sentiment Analysis

- **Objective**: Classify comments into positive, negative, or neutral categories.
- Preprocessing steps:
  - Removed punctuation and stop words.
  - Converted text to lowercase for uniformity.
- Sentiments were visualized using bar charts.

**Conclusion**: The majority of comments were positive, indicating user satisfaction and appreciation for content.

---

### 5. Keyword Analysis

- Generated word clouds to visualize the most frequently used keywords in comments.

**Key Insight**: Frequently used words reflect common user opinions, recurring topics, or feedback themes.

---

## Visualizations

This project includes the following visual aids:

1. Distribution of sentiments across comments.
2. Word cloud showcasing dominant keywords.
3. Engagement metrics visualized via bar charts.

---

## Conclusion

The project highlights:

1. The importance of data cleaning in maintaining analysis quality.
2. How sentiment analysis and keyword trends provide actionable feedback.
3. Insights into engagement trends for video content.

## Future Scope

1. Correlate video content types with engagement levels.
2. Analyze demographic patterns in comment trends.
3. Extend sentiment analysis with advanced NLP techniques.
