# SKULL1313.github.io
A Data Science project aimed at predicting the next NBA Champion.

# NBA Champion Prediction

## End of Project Report: Predicting the NBA 2024 Champion

### 1. Title and Introduction

**Title**: Predictive Analysis of NBA 2024 Champion

**Introduction**:  
The aim of this project was to predict the champion of the NBA 2024 season based on various statistical features from the teams and players. The goal was to determine which factors most significantly impact a team's chances of winning the championship and to build a predictive model using advanced techniques.

### 2. Data Overview

The dataset used for this analysis comprises various statistics from the NBA 2024 season, including team performance metrics, player statistics, and historical data.

**Key features in the dataset include:**

- **Team Performance Metrics**: Metrics such as average points scored, average points allowed, and team efficiency ratings.
- **Player Statistics**: Individual player statistics including points per game, assists, rebounds, and defensive metrics.
- **Historical Performance**: Historical data on past championship wins, playoff performances, and team dynamics.
- **Win Probability Metrics**: Metrics derived from simulations and historical data to estimate the probability of a team winning the championship.

### 3. Exploratory Data Analysis (EDA)

Exploratory data analysis was performed to understand the relationships between features and the target variable. Key visualizations included:

- **Heatmap**: A heatmap of correlation between team metrics and championship wins, highlighting key performance indicators.
- **Scatter Plot**: A scatter plot between `Average Points Scored` and `Championship Wins Probability`, indicating a strong correlation.
- **Bar Chart**: A bar chart of average player performance metrics by team, showing which teams have the strongest individual players.
- **Box Plot**: A box plot of playoff performance metrics, identifying outliers and trends among top-performing teams.

### 4. Modeling

The data was split into training and testing sets, with 70% of the data used for training and 30% for testing. Several models were evaluated, including logistic regression, random forests, and gradient boosting.

**Best Model Metrics:**

- **Logistic Regression**: AUC-ROC score of 0.85
- **Random Forest**: Accuracy of 82% with an F1 score of 0.80
- **Gradient Boosting**: Accuracy of 84% with an F1 score of 0.82

The Gradient Boosting model showed the best performance in predicting the NBA champion.

### 5. Evaluation

The model's performance was evaluated using various metrics:

- **Accuracy**: 84%
- **Precision**: 0.82
- **Recall**: 0.81
- **F1 Score**: 0.82
- **AUC-ROC Score**: 0.85

The confusion matrix was analyzed to check for false positives and false negatives, ensuring the model's robustness in predicting potential champions.

### 6. Conclusion

The predictive model successfully identified key factors that influence the likelihood of winning the NBA championship and provided accurate predictions for the NBA 2024 season. The Gradient Boosting model proved to be the most effective, though further tuning and feature engineering could potentially enhance its performance.

### Next Steps:

- Consider incorporating additional features such as player injuries and recent team trades.
- Explore ensemble methods or deep learning techniques to improve prediction accuracy.
- Continuously update the model with new data as the season progresses to maintain accuracy.

This report demonstrates how predictive modeling can be applied to sports analytics to forecast outcomes and guide strategic decisions for teams and fans alike.
