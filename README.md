📊 Student Performance Regression Model

A study on predicting student math scores using Linear Regression

📌 Overview

This project analyzes the StudentsPerformance dataset and builds a Multiple Linear Regression model to understand how various demographic and educational factors influence math scores.
The goal is to identify key predictors and create an interpretable model for academic performance insights.

📁 Dataset

Dataset Name: StudentsPerformance.csv
Rows: 1,000
Columns: 8

Features

Gender

Race/Ethnicity

Parental Level of Education

Lunch Type

Test Preparation Course

Math Score

Reading Score

Writing Score

Target Variable:
✔ Math Score

🔧 Tech Stack & Tools

Python

Pandas

NumPy

Matplotlib

Scikit-Learn

Google Colab

🛠 Data Preprocessing

Import Dataset using pandas.read_csv()

Convert Categorical Columns using LabelEncoder()

Feature Selection:

X: All features except math score

y: Math score

Train-Test Split: 80% training, 20% testing

Automatic NumPy conversion during model fitting

🧮 Model Training

The project uses Multiple Linear Regression from sklearn.linear_model.

from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)

📈 Results

The model successfully learned relationships between the student features and math scores.

Regression outputs include:

Coefficients (slopes)

Intercept

Scatter plots show a strong positive correlation between reading and math scores.

🧐 Interpretation

Reading score is the strongest positive predictor of math score.

Higher reading and writing scores consistently indicate higher math performance.

The intercept (-11.39) acts as the baseline score when all predictors are zero.

✅ Conclusion

A strong positive relationship exists between reading and math scores.

Regression coefficients help explain how demographic and academic factors influence performance.

The model can support educators and researchers in predicting and improving student outcomes.

📚 References

Dataset: Kaggle — StudentsPerformance

Tools: Google Colab

Libraries: Pandas, NumPy, Matplotlib, Scikit-Learn

🙋‍♂️ Author

Sourav Paul(ADTU/0/2024-26/MCAM/006)
MCA (2024–2026), Assam Downtown University
