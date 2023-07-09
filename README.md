# Bank Marketing Machine Learning Predictive Analysis

This project aims to predict whether a customer will subscribe to a term deposit based on various customer information. The dataset used in this project is related to direct marketing campaigns of a bank.

## Dataset Description

The dataset contains the following attributes:

1. Age: The age of the customer (numeric).
2. Job: The type of job the customer has (categorical: 'admin.', 'blue-collar', 'entrepreneur', 'housemaid', 'management', 'retired', 'self-employed', 'services', 'student', 'technician', 'unemployed', 'unknown').
3. Marital: The marital status of the customer (categorical: 'divorced', 'married', 'single', 'unknown'; note: 'divorced' means divorced or widowed).
4. Education: The education level of the customer (categorical: 'basic.4y', 'basic.6y', 'basic.9y', 'high.school', 'illiterate', 'professional.course', 'university.degree', 'unknown').
5. Default: Whether the customer has a credit in default (categorical: 'no', 'yes', 'unknown').
6. Housing: Whether the customer has a housing loan (categorical: 'no', 'yes', 'unknown').
7. Loan: Whether the customer has a personal loan (categorical: 'no', 'yes', 'unknown').
8. Contact: The type of contact communication (categorical: 'cellular', 'telephone').
9. Month: The last contact month of the year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec').
10. Day_of_week: The last contact day of the week (categorical: 'mon', 'tue', 'wed', 'thu', 'fri').
11. Duration: The last contact duration in seconds (numeric).
12. Campaign: The number of contacts performed during this campaign and for this client (numeric, includes last contact).
13. Pdays: The number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means the client was not previously contacted).
14. Previous: The number of contacts performed before this campaign and for this client (numeric).
15. Poutcome: The outcome of the previous marketing campaign (categorical: 'failure', 'nonexistent', 'success').
16. Emp.var.rate: The employment variation rate - quarterly indicator (numeric).
17. Cons.price.idx: The consumer price index - monthly indicator (numeric).
18. Cons.conf.idx: The consumer confidence index - monthly indicator (numeric).
19. Euribor3m: The Euribor 3-month rate - daily indicator (numeric).
20. Nr.employed: The number of employees - quarterly indicator (numeric).

## Project Steps

1. Exploratory Data Analysis (EDA): Conducted an analysis of the categorical variables to identify their categories and determine if any of them have missing values. Plotted bar graphs to visualize the distribution of each category.

2. Target Variable Correlation: Analyzed the correlation between categorical variables and the target variable (subscription to term deposit) to identify categories that are more favorable towards subscribers.

3. Missing Values: Addressed missing values in the dataset by imputing values based on known correlations and logical assumptions. Created new variables to capture the information if the missing values are at random or if there is a pattern in the missing values.

4. Feature Scaling: Performed feature scaling on numerical variables to ensure that all variables are on the same scale.

5. Principal Component Analysis (PCA): Applied PCA to reduce the dimensionality of the data and visualize the data in a lower-dimensional space.

6. Feature Selection: Conducted feature selection using various techniques such as correlation analysis, chi-square test, and recursive feature elimination to identify the most important features for predicting the target variable.

7. Model Selection: Compared and evaluated different classification models such as logistic regression, decision tree, random forest, and gradient boosting to determine the best-performing model for the given dataset.

8. Model Evaluation: Evaluated the selected model using performance metrics such as accuracy, precision, recall, and F1-score. Utilized techniques like cross-validation and hyperparameter tuning to improve the model's performance.

9. Model Interpretation: Interpreted the selected model to understand the significant features and their impact on the prediction of the target variable.

## Conclusion

This project demonstrates the predictive analysis of a bank marketing dataset to determine whether a customer will subscribe to a term deposit. By applying various data preprocessing, feature selection, and model evaluation techniques, we have built a predictive model that can assist the bank in targeting potential customers who are more likely to subscribe to the term deposit. The insights gained from this project can help optimize marketing strategies and improve the success rate of the bank's campaigns.
