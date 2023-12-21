# Heart Attack Project

## Overview

The Heart Attack Project is a comprehensive study aimed at understanding and predicting the likelihood of heart attacks based on various medical and lifestyle factors. Leveraging a dataset obtained from Kaggle, the project explores the impact of features such as age, gender, chest pain types, blood pressure, cholesterol levels, and other health indicators on the probability of experiencing a heart attack. Additionally, the project includes the application of multiple classification algorithms to predict the likelihood of a heart attack.

By delving into this project, you can gain valuable insights into the relationships between different health parameters and the potential risk of a heart attack.

## Technologies Used

The project utilizes a range of technologies and libraries for data analysis, visualization, and machine learning, including:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly Express
- Statsmodels
- Scikit-learn

## Exploratory Data Analysis (EDA)

The initial steps involve loading the dataset, performing exploratory data analysis, and gaining insights into the data structure. The dataset includes information on age, sex, chest pain types, resting blood pressure, cholesterol levels, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, and various other features related to heart health.

### Data Preprocessing

The dataset is explored for missing values and duplicate entries, and appropriate steps are taken to handle them. Categorical and continuous columns are identified, and the target variable, 'output,' representing the likelihood of a heart attack, is defined.

### Descriptive Statistics

Descriptive statistics are employed to understand the central tendencies and distributions of key features, such as age, blood pressure, cholesterol, and more.

### Data Visualization

Data is visualized using various plots, including count plots, distribution plots, and pair plots. These visualizations help in understanding the relationships and distributions among different variables related to heart health.

### Correlation Analysis

A correlation matrix is generated to examine the linear relationships between variables, providing insights into feature importance.

## Classification Models

To address the classification problem of predicting the likelihood of a heart attack, multiple classification algorithms are applied and compared:

1. **Decision Tree Classifier:** Achieving an accuracy of approximately 75.4%.
2. **Random Forest Classifier:** Demonstrating improved accuracy, around 85.2%.
3. **Logistic Regression:** Emerging as the most suitable algorithm with an accuracy of 88.5%.
4. **K-Nearest Neighbors (KNN):** Yielding an accuracy of 68.9%.
5. **Support Vector Machine (SVM):** Providing an accuracy of 70.5%.

Based on the results, Logistic Regression stands out as the most effective algorithm for predicting the likelihood of a heart attack in this particular dataset.
